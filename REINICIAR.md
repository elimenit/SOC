# Demonio en Linux
Alguna vez inteststes que tu PC al reiniciar ejecute comandos por defecto?

Por sugerencia de la IA es crear un servicio con *systemd*:
* **Ejemplo**:
Crearemos un servicio que cambie nuestra MAC Automaticamente
```bash
    # Crear el archivo del servicio
    sudo nano /etc/systemd/system/change_mac.service
```


```bash
[Unit]
Description=Ejecutar mi comando al iniciar
After=network-online.target
Wants=network-online.target

[Service]
Type=oneshot
ExecStart=macchanger -r wlan0
RemainAfterExit=yes

[Install]
WantedBy=multi-user.target
```
Recarga de Systemd y activar el servicio
```bash
sudo systemctl daemon-reload
sudo systemctl enable change_mac.service
```
```bash
sudo systemctl start change_mac.service
```