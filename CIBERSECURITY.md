# Que es Ciberseguridad
Ciberseguridad es la practica de proteger alas personas, los sisteas y los datos de ciberataques mediante el uso de diversas tecnologias(Software & Hardware), procesos(Roles o pasos a comletar en una tarea) y politicas(CIA).

## Que es NIST (National Institute of Standards and Technology)
Es una agencia de la administracion de tecnologia del departamento de comercio de ls EE.UU.
Prioriza 4 cosas (CIA + no Repudio)
- ***Confidenciality***
- ***Integrati***
- ***Availability***
- ***No repudio***

## Integridad de los Datos
Que tipos de datos pueden ser visibles:
- ***Restricted***: Propiedad intelectual o otra informacion de propiedad
- ***Confidential***: 
    * Datos personales de clientes (Customer personal) & payment information
    * Informaion personal de empleados
    * Company financial Information

- ***Private or Internal-Only***: 
    * Comunicaciones Internas
    * Team Meeting recording (Grabaciones de las reuniones de equipo)
    * Algunos planes estrategicos

- ***Public***
    * Modelos de Camisetas (T-shirt Models), costs & sizes

* *Ejemplo*
    - Persona: datos personales y el Rol
    - EMpleado: UserName, Ip address, Device Name

## Equipos de Ciberseguridad
Unidades focalizadas en diferentes aspectos de las Operaciones de Seguridad.
Los mas comunmente conocidos:

- ***Red Team***: "Breakers, Disyuntores" porque usan tacticas ofensivas y tecnicas de test en Ciber defense, Offensive Security.
- ***Blue Team*** "Defenders" porque usan tacticas defensivas y procedimientos para cazar amenazas y defender operaciones, Defensive Security.
- ***Purple Team***: Integran tacticas defensivas con resultados ofensivos.

> Aqui algunos mas
- ***Green Team***: ""Collaboration" Mejorar la automatizacion de la seguridad con diseño y codigo
- ***Yellow Team*** "The Builders" Software Coders and Architects
- ***Orange Team*** "Collaboration" Facilitan colaboracion y educacion

### Cumplimento y Normativas
Existen leyes y regulaciones que regulan los derechos y responsabilidades que tienen organizaciones, profesionales e incluso ciudadanos no técnicos respecto a sus datos personales y su huella cibernética. 

Algunas de estas leyes y las culturas que las rodean cambian geográficamente, de país en país, de estado en estado y, en algunos casos, incluso de comunidad en comunidad.

Las organizaciones que gestionan datos deben identificar y cumplir con las leyes y regulaciones que les corresponden, de lo contrario pueden enfrentarse a consecuencias legales y/o financieras.

Algunos ejemplos de datos que pueden estar sujetos a regulaciones son:

- ***Personal Identifiable Information (PI or PII)***: Es la informacion que identifica a una persona(phone, full name, email, etc).

- ***Protected Health Information(PHI), Informacion de Salud Protegida***: Cualquier información en el historial médico o conjunto de registros designados de una persona que pueda utilizarse para identificarla y que haya sido creada, utilizada o divulgada en el curso de la prestación de un servicio sanitario como diagnóstico o tratamiento.

-***Payment Card Industry (PCI), Industria de las tarjetas de pago***: Incluyen "datos del titular" como el nombre del titular, número de cuenta, fecha de caducidad y código de servicio de tarjeta. Otros datos relacionados con PCI incluyen los datos completos de banda magnética de una tarjeta, así como PINs o códigos de seguridad (CVV).

> Algunas Regulaciones a estos tipos de datos:
- ***The European Union General Data Protection Regulation (GDPR), El Reglamento General de Protección de Datos de la Unión Europea***: Regula el uso de los datos inseparables de una persona y los derechos que esta tiene sobre ellos, incluso bajo la custodia de una organización. [Saber mas acerca de los datos personales] (https://gdpr-info.eu/issues/personal-data/#:~:text=In%20practice%2C%20these%20also%20include,address%20are%20all%20personal%20data.)

- ***The Health Insurance Portability and Accountability Act (HIPAA) La Ley de Portabilidad y Responsabilidad del Seguro de Salud***: Fue promulgada en Estados Unidos para regular la protección de la privacidad y la seguridad de cierta información sanitaria, como resultados diagnósticos, registros de seguros, estado del seguro y más.

- ***The Payment Card Industry Data Security Standard (PCI-DSS), El Estándar de Seguridad de Datos de la Industria de Tarjetas de Pago***: Es un estándar de importancia global que constituye un acuerdo contractual entre comerciantes, procesadores de tarjetas y la propia industria de tarjetas de pago.

## Riesgo y Administracion del Riesgo
Riesgo es = probabilidad * impacto.
Mitigar: sgnifica minimizar el riesgo

### Frameworks & Controls
Organizaciones que deberías conocer como profesional de seguridad:

- ***CIS 18***: El Instituto SANS comenzó como una cooperativa para el liderazgo de pensamiento en seguridad de la información y se ha convertido en un recurso fundamental para la comunidad de ciberseguridad, proporcionando formación, certificaciones, investigación y otros recursos. [SANS](https://www.sans.org/blog/cis-controls-v8/).

- ***ISO(International organization Standars)/IEC 27000***: La serie ISO/IEC 27000 (se abre en una nueva pestaña) es la serie de normas para la Seguridad de la Información. Este conjunto de controles, a menudo más relacionado con la colocación y aplicación de políticas y procedimientos que sobre controles técnicos directos, es utilizado por las organizaciones para demostrar que disponen de un buen Sistema de Gestión de Seguridad de la Información (a menudo denominado ISMS).

- ***NIST(United States National Institute of Standards and Technology) Framework***: Debemos conocer :
    - ***[The CiberSecurity Framework(CSF)](https://www.nist.gov/cyberframework/online-learning/five-functions)***: un meta-marco que reúne muchas Publicaciones Especiales del NIST en un único marco digerible y consultivo. Dentro del CSF existe el Núcleo NIST, que es un conjunto de actividades y resultados deseados organizados en Funciones y Categorías que cubren la amplitud de los objetivos de ciberseguridad de una organización, incluyendo temas cibernéticos, físicos y de personal, con un enfoque en los resultados empresariales.

    - ***[The Risk Management Framework(RMF)](https://csrc.nist.gov/projects/risk-management/about-rmf)***: ampliamente utilizado como estándar para la gestión de riesgos, especialmente para empresas con sede en Estados Unidos; Su objetivo es fortalecer los procesos de gestión de riesgos y fomentar la colaboración y la reciprocidad entre las organizaciones. Este marco también se basa en múltiples publicaciones especiales que cubren diferentes pasos dentro del proceso propuesto de Gestión de Riesgos.

### Frase
"""
Existe el Riesgo si hay vulnerabilidades o amenazas
"""

## Comprension de Amenazas y Ataques (Understanding Threats & Attacks)
- ***Common Atacks & Terms***: 
    * **Phishing**: Es La práctica fraudulenta de enviar correos electrónicos u otros mensajes que supuestamente provienen de empresas de confianza para inducir a las personas a revelar información personal, como contraseñas y números de tarjetas de crédito. 
    
    Las técnicas de phishing no son exclusivas de las comunicaciones por correo electrónico, pueden ser por voz(Vishing), smishing.

    * **Credential Access**: Esto puede ser una de las principales tácticas o objetivos de los actores de amenaza; Al acceder a credenciales comprometidas, se abre una nueva puerta para vectores de ataque adicionales y opciones de explotación. 
    Pero, ¿cómo se comprometen las credenciales? 
    
    * **Ingeneria Social**: Las técnicas de ingeniería social pueden usarse para que los usuarios revelen sus credenciales o suficiente información para que los atacantes las adivinen o las respuestas a sus preguntas de seguridad
    
    * **Los ataques de fuerza bruta o de diccionario** son aquellos en los que intentan varias veces hasta tener éxito, ya sea adivinando posibles contraseñas o usando una "lista de diccionario" de palabras y frases comunes. 
    
    * **El spray de contraseñas** es otro ataque de fuerza bruta en el que intentan usar las mismas contraseñas comunes en varias cuentas.

    * **Man-in-the-Middle**: un atacante esta husmeando en la red.

    * **La ofuscación** es el proceso de ocultar algo importante, valioso o crítico. Los ciberdelincuentes utilizan la ofuscación para ocultar información como archivos a descargar, sitios a visitar, etc.


# Common Vulnerabilities and Exposures (CVE)
El programa CVE es un esfuerzo internacional basado en la comunidad que mantiene un registro de datos abiertos impulsado por la comunidad de vulnerabilidades de ciberseguridad públicamente conocidas: la lista CVE. Aunque el programa está financiado por el Departamento de Seguridad Nacional de EE. UU. (DHS) y el Componente de Gestión de Vulnerabilidades (VMC) de la Agencia de Ciberseguridad e Seguridad de Infraestructuras (CISA), es gestionado de forma independiente por la corporación [MITRE](https://www.cve.org/)

