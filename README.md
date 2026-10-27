<!-- README de perfil, estilo CV: va en el repo público github.com/LeoPedrozo/LeoPedrozo. -->

<p align="right"><b>Español</b> · <a href="README.en.md">English</a></p>

<p align="center"><img src="assets/banner-es.svg" width="100%" alt="Ingeniero de Software: Oracle APEX, Salesforce e IA"/></p>

# Oscar Leonardo Pedrozo

**Ingeniero de Software**: Oracle APEX · Salesforce · Datos e Integraciones<br>
Asunción, Paraguay · [LinkedIn](https://www.linkedin.com/in/oscar-leonardo-pedrozo) · [GitHub](https://github.com/LeoPedrozo)

---

### Perfil profesional

Ingeniero en Informática, graduado distinguido de la FP-UNA, con más de 4 años de experiencia en desarrollo empresarial sobre **Oracle APEX** y **Salesforce**. Participé en la migración de un sistema del sector salud de Oracle Forms 6i a APEX, integré Salesforce con sistemas core y SAP, y desarrollé una solución de telemetría de flotas con Platform Events, REST API y MQTT. Actualmente desarrollo proyectos de IA con Oracle APEX y sus nuevas funcionalidades de IA de la versión 26.2. Complemento mi trabajo con investigación en procesamiento de imágenes médicas, con trabajos presentados en Brasil y Colombia.

---

### Experiencia

**Desarrollador Salesforce**, Freelance<br>
*Enero 2026 – Presente*
- Desarrollé un paquete Salesforce de segunda generación (2GP) de telemetría y seguimiento para una flota de vehículos de logística, sobre Sales Cloud.
  - Seguimiento de posición actual y rutas de trabajo, control de tiempo en ralentí y registro de múltiples sensores por vehículo.
  - Arquitectura pub/sub con Platform Events para procesar los eventos de telemetría.
  - REST API en Apex con operaciones GET, POST y PUT, consumida por una plataforma externa que integra las principales APIs de telemetría para control de flotas.
  - Interfaz en Lightning Web Components (LWC) con mapas interactivos en Leaflet.
  - Configuración de permisos de acceso al sistema y a sus clases.
- Extendí una app Android de código abierto en Kotlin para el seguimiento del personal en campo, agregando soporte para el protocolo MQTT sobre TLS y lectura de sensores.

**Desarrollador Oracle APEX**, Excelsis S.A.<br>
*Junio 2024 – Presente*
- Desarrollo y optimizo aplicaciones de sistemas médicos con PL/SQL y Oracle APEX.
- Diseño triggers, procedimientos y funciones de base de datos complejos para mejorar la lógica del sistema.
- Implemento soluciones de reportes con Jasper Reports.
- Entrego módulos de software en plazo con metodologías ágiles.
- **Asistente de IA para atención al cliente de un ERP médico** (2026, en producción): chatbot en Oracle APEX 26.2 para un ERP utilizado en hospitales, sanatorios y prepagas de Paraguay.
  - Integré OCI Generative AI con un modelo reciente de Grok (xAI) como motor del asistente.
  - Centralicé la información del cliente obtenida mediante PL/SQL para dar respuestas contextualizadas.
  - Protegí la información sensible de los pacientes con datos encriptados.
- **Consultoría on-site para un sanatorio de medicina prepaga** (mayo – agosto 2026): migración de su sistema de Oracle Forms 6i a Oracle APEX 22.1, completada con éxito.
  - Analicé y desarrollé páginas en Oracle APEX para migrar formularios y lógica de negocio de Forms 6i.
  - Fui el nexo entre el cliente y el equipo de desarrollo, relevando y traduciendo requerimientos.
  - Implementé mejoras en triggers y procedimientos PL/SQL.
  - Apoyé el desarrollo de reportes con Jasper Reports.
  - Asesoré al cliente en la planificación de futuras migraciones a versiones más recientes de Oracle APEX.

**Desarrollador Salesforce**, Excelsis S.A.<br>
*Abril 2023 – Junio 2024*
- **Casa de bolsa:** integré los leads y cuentas de su sistema core con Salesforce Sales Cloud, de inicio a fin del proyecto, usando Apex y las APIs SOAP y REST de Salesforce.
- **Venta de maquinarias:** desarrollé formularios personalizados en Salesforce para el proceso de venta e integré Salesforce con SAP mediante la API SOAP.
- **Empresa del rubro automotor:** depuré y unifiqué registros duplicados con procesos ETL en Pentaho y la Bulk API de Salesforce, automatizados con Python (Pandas) en Jupyter Notebook.
- Di soporte y mantenimiento a integraciones de sistemas con Salesforce.

**Soporte y Desarrollo**, Comisión Nacional de Valores (CNV), Paraguay<br>
*Agosto 2022 – Marzo 2023*
- Relevé requerimientos para implementar en Salesforce Sales Cloud un sistema de gestión de documentos para la CNV.
- Desarrollé APIs de disponibilidad de datos con Django y Python.
- Mantuve el sitio WordPress institucional y desarrollé en PHP nuevas páginas para listar las emisoras de bonos.
- Administré servidores Windows y Ubuntu y monitoreé los sistemas de respaldo (Veeam).

---

### Educación

- **Ingeniería en Informática**, Facultad Politécnica, UNA. *Graduado distinguido en noviembre de 2025*
- **Especialización en Didáctica de la Educación Superior**, Facultad Politécnica, UNA. *Julio 2026 – Abril 2027 (en curso)*
- **Diplomado de Posgrado en IoT y Sistemas Embebidos**, FP-UNA. *Mayo 2025*
- **Escuela de Verano de Informática Médica con IA**, UNAM (México). *Agosto 2025*
- **Macroentrenamiento en Inteligencia Artificial (MeIA)**, UNAM y Red de Macro Universidades de América Latina y el Caribe. *Junio 2023*. Reconocimiento al **2.º lugar** por la solución "Inteligencia Artificial para clasificación de especies a partir de secuencias de ADN".
- **Inglés**, Centro Cultural Paraguayo Americano (CCPA), hasta el curso "Avanzado Superior 2". *2015 – 2018*

---

### Certificaciones

- Google Cloud Digital Leader. *Google, 2026*
- Oracle Certified Professional (OCP). *Oracle, 2025*
- Salesforce Certified AI Associate. *Salesforce, 2024*
- Salesforce Certified Platform Foundations. *Salesforce, 2023*

---

### Investigación

**Registro de imágenes médicas de tomografía y resonancia magnética con el descriptor Firma Punto-Contorno (CPS)**<br>
*Grupo de Investigación en Computación Científica y Matemática Aplicada, FP-UNA · Septiembre 2024 – Noviembre 2025*
- Desarrollé un método de registro de imágenes médicas basado en el CPS, un método matemático de la familia de los descriptores de forma (*shape descriptors*): el CPS representa el contorno de cada imagen y una matriz de costos determina la rotación óptima y los puntos correspondientes para un registro por puntos de referencia.
- Evalué el método con imágenes de CT y RM de la base pública RIRE (Universidad de Vanderbilt): en los cortes de un paciente de prueba alcanzó una precisión del 72,80 % para 10 puntos extraídos, con un umbral de error del 1 % (≈ 5,12 píxeles).
- Implementé el procesamiento en Python con SimpleITK.
- Proyecto financiado con fondos de la FP-UNA, a través de su Programa de Fortalecimiento para el Desarrollo de la Ciencia, Tecnología e Innovación (2025), y patrocinado por Excelsis S.A.
- Trabajé junto a investigadores destacados de la FP-UNA y la FIUNA, en un grupo multidisciplinario.

### Publicaciones y presentaciones

- **"Contour-Point Signature in Registration of Tomography and Magnetic Resonance Images"**: póster en el XLIV Congreso Nacional de Matemática Aplicada y Computacional (CNMAC 2025), organizado por la SBMAC, Brasil, septiembre de 2025. Publicado en [*Proceeding Series of the Brazilian Society of Computational and Applied Mathematics*, v. 12 n. 1 (2026)](https://proceedings.sbmac.org.br/sbmac).
- **"Eficiencia del uso del CPS en Registro de imágenes médicas"**: ponencia remota en el V Encuentro de Matemáticas y Estadística Aplicadas a las Ciencias Sociales y Económicas, Colombia, mayo de 2025. Publicado en las *Memorias* del encuentro (2026), [DOI: 10.18359/litgris.8305](https://doi.org/10.18359/litgris.8305).
- **"Uso del descriptor firma punto-contorno en el registro de imágenes de tomografía y resonancia magnética"**: póster en la 4.ª Jornada Internacional de Cursos de Especialización AMARU-CYTED 2024, UNA, agosto de 2024.

---

### Habilidades técnicas

| Área | Habilidades |
|---|---|
| Salesforce | Apex, LWC, Platform Events, Flows, Dashboards, APIs SOAP/REST, Bulk API, paquetes 2GP, Sales Cloud |
| Oracle | Oracle APEX (incluidas sus funcionalidades de IA), PL/SQL, SQL, migración desde Oracle Forms, Jasper Reports |
| Integraciones | SAP (SOAP), APIs REST, MQTT/TLS, ETL con Pentaho |
| Programación | Python (Pandas, NumPy), Django, Kotlin (Android), JavaScript, PHP, WordPress, Leaflet |
| Datos e IA | Procesamiento de imágenes médicas (SimpleITK), Machine Learning, limpieza y migración de datos |
| Infraestructura y gestión | Linux, Google Cloud, IoT con ESP32, Git, Jira (Scrum/Kanban) |

---

### Idiomas

Español (nativo) · Guaraní (nativo) · Inglés (avanzado en lectura y escritura, intermedio en conversación)

---

### Repositorios destacados

| Repositorio | Descripción |
|---|---|
| [envio_masivo_sms_vox](https://github.com/LeoPedrozo/envio_masivo_sms_vox) | Procedimiento PL/SQL para envío masivo de SMS con la API de Vox Paraguay. |
| [simpleITKnotebooks](https://github.com/LeoPedrozo/simpleITKnotebooks) | Notebooks de procesamiento de imágenes médicas con SimpleITK. |
| [MEIA](https://github.com/LeoPedrozo/MEIA) | Ejercicios de un taller de entrenamiento en IA. |
| [laberinto-caminocorto](https://github.com/LeoPedrozo/laberinto-caminocorto) | Camino más corto en un laberinto, en C. |

---

### Anexo

#### Fotos

<p align="center">
  <img src="assets/foto-graduado-distinguido.jpg" height="160" alt="Graduado distinguido, FP-UNA 2025"/>
  <img src="assets/foto-graduacion.jpg" height="160" alt="Graduación en Ingeniería en Informática"/>
  <img src="assets/foto-defensa-tesis.jpg" height="160" alt="Defensa de tesis"/>
</p>
<p align="center"><sub>Graduado distinguido, FP-UNA 2025 · Graduación en Ingeniería en Informática · Defensa de tesis</sub></p>

<p align="center">
  <img src="assets/foto-poster-cnmac2025.jpg" height="160" alt="Póster en el CNMAC 2025, Brasil"/>
  <img src="assets/foto-poster-cyted-2024.jpg" height="160" alt="Póster en la Jornada AMARU-CYTED 2024"/>
  <img src="assets/foto-presentacion-cps.jpg" height="160" alt="Presentación del método CPS"/>
</p>
<p align="center"><sub>Póster en el CNMAC 2025, Brasil · Póster en la Jornada AMARU-CYTED 2024 · Presentación del método CPS</sub></p>

<p align="center">
  <img src="assets/foto-workshop-presentacion.jpg" height="160" alt="Presentación en el workshop del grupo de investigación"/>
  <img src="assets/foto-workshop-grupo.jpg" height="160" alt="Grupo de Investigación en Computación Científica y Matemática Aplicada"/>
  <img src="assets/foto-diplomado-iot.jpg" height="160" alt="Diplomado en Sistemas Embebidos e IoT"/>
</p>
<p align="center"><sub>Presentación en el workshop del grupo de investigación · Grupo de Investigación en Computación Científica y Matemática Aplicada · Diplomado en Sistemas Embebidos e IoT</sub></p>

<p align="center">
  <img src="assets/foto-excelsis-oracle.jpg" height="160" alt="Evento Oracle y Excelsis"/>
  <img src="assets/foto-salesforce-friends.jpg" height="160" alt="Encuentro de la comunidad Salesforce"/>
</p>
<p align="center"><sub>Evento Oracle y Excelsis · Encuentro de la comunidad Salesforce</sub></p>

#### Certificados y reconocimientos

<p align="center">
  <img src="assets/cert-google-cloud-digital-leader.jpg" height="160" alt="Google Cloud Digital Leader"/>
  <img src="assets/cert-diplomado-iot.jpg" height="160" alt="Diplomado en Sistemas Embebidos e IoT, FP-UNA"/>
  <img src="assets/cert-cyted-amaru-2024.jpg" height="160" alt="Certificado de póster, AMARU-CYTED 2024"/>
</p>
<p align="center"><sub>Google Cloud Digital Leader · Diplomado en Sistemas Embebidos e IoT, FP-UNA · Certificado de póster, AMARU-CYTED 2024</sub></p>

<p align="center">
  <img src="assets/reconocimiento-unam-meia-2023.jpg" height="160" alt="Reconocimiento 2.º lugar, MeIA 2023 (UNAM)"/>
  <img src="assets/cert-unam-meia-2023.jpg" height="160" alt="Constancia del taller MeIA 2023 (UNAM)"/>
  <img src="assets/cert-cnv-pasantia.jpg" height="160" alt="Certificado de pasantía, CNV"/>
</p>
<p align="center"><sub>Reconocimiento 2.º lugar, MeIA 2023 (UNAM) · Constancia del taller MeIA 2023 (UNAM) · Certificado de pasantía, CNV</sub></p>
