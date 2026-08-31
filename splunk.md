# Splunk

# Assets & Identity
El marco de Activos e Identidades en Splunk Enterprise Security mejora los resultados de búsqueda correlacionando campos en conjuntos de eventos con datos contextuales enriquecidos. 

Por ejemplo, si una búsqueda devuelve registros de un dispositivo específico en un entorno, este marco utiliza consultas y configuraciones para añadir detalles valiosos. Los activos pueden incluir atributos como direcciones IP, nombres de dominio, nombres NetBIOS y direcciones MAC. 

Las identidades, por otro lado, pueden incluir atributos como nombre de usuario, información de contacto o categoría, por ejemplo. Este tipo de información es excelente para proporcionar un contexto más profundo a los hallazgos. Este enriquecimiento permite una lógica de alertas más eficaz basada en el riesgo.

## Metricas Comunes 

- ***Mean Time to Detect (MTTD)***: El MTTD mide el tiempo medio que tarda un equipo SOC en detectar un incidente o una brecha de seguridad. Un valor de Tiempo Medio de Detección (MTTD) más corto suele ser mejor. Indica la capacidad del equipo SOC para detectar y responder rápidamente a incidentes. Además, el MTTD ayuda a evaluar la eficiencia de las capacidades de detección.

- ***Mean Time to Investiguate (MTTI)***: MTTI es el tiempo medio desde la detección de fallos hasta que se inicia una investigación. Sirve de puente entre MTTD (Tiempo Medio de Detección) y el inicio de MTTR (Tiempo Medio hasta Resolución), describiendo la fase inicial de respuesta.

- ***Mean Time to Resolution (MTTR)***: MTTR es la métrica utilizada para evaluar el tiempo medio que tarda un equipo SOC en resolver completamente un incidente una vez detectado. Un valor MTTR más bajo indica que su proceso de respuesta a incidentes es rápido y altamente eficaz.

- ***False Positives Rates(FPR) & False negative Rates (FNR)**: FPR, o tasa de falsos positivos, mide el porcentaje de incidentes que se clasifican incorrectamente como incidentes de ciberseguridad pero que no son amenazas reales.

    La tasa de falsos negativos (FNR) es el porcentaje de incidentes que se categorizan erróneamente como amenazas no cibernéticas pero que en realidad lo son. Una alta tasa de falsos negativos indica que el sistema tiene muchas probabilidades de pasar por alto las verdaderas amenazas de seguridad.

### Codigo Abierto (Open Source) & Splunk
Código abierto y Splunk Aunque los productos principales de Splunk son propietarios, Splunk apoya a la comunidad de código abierto a través de proyectos como Splunk Attack Range y ContentCtl en GitHub. 
El software de código abierto es gratuito, lo que lo hace accesible para que cualquiera experimente, aprenda o personalize.

Important Open Source Projects:

- ***Splunk Attack Range***: Una herramienta que permite crear entornos locales o en la nube instrumentados vulnerables para simular ataques y recopilar datos en Splunk. [GitHub - splunk/attack_range](github.com/splunk/attack_range).

- ***Attack Data***: es un repositorio de código abierto que alberga toda la telemetría generada a partir de la simulación de técnicas de adversarios realizada por el Equipo de Investigación de Amenazas Splunk. Estos conjuntos de datos pueden utilizarse para:
    - **Desarrolla detecciones fácilmente** sin tener que construir un entorno desde cero ni simular un ataque. 
    
    - **Detección de pruebas**, específicamente contenido de seguridad de Splunk. 
    
    - **Reproduce eventos (se abre en una pestaña nueva)** en pipelines de streaming para validar tus detecciones en tu SIEM de producción.

    > GITHUB: [Attack Data: splunk/attack_data](github.com/splunk/attack_data)

- ***Splunk Security Content***: Splunk Security Content es contenido preempaquetado, proporcionado por la aplicación Splunk ES Content Update (ESCU). 

    Consiste en tácticas, técnicas y metodologías que ayudan a los equipos de seguridad en la detección, investigación y respuesta. 
    
    El contenido apoya la operacionalización de las detecciones y respuestas, e incluye información de fondo fácil de leer con orientación sobre técnicas de ataque y cómo combatirlas. Puedes explorar detecciones, historias analíticas y manuales en el enlace de abajo:
    > Mas informacion: [Splunk Security Content: research.splunk.com](research.splunk.com)