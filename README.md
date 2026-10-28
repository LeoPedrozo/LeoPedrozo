<!-- Profile README (default, English). Spanish version: README.es.md. Public repo github.com/LeoPedrozo/LeoPedrozo. -->

<p align="right"><b>English</b> · <a href="README.es.md">Español</a></p>

<p align="center"><img src="assets/banner-en.svg" width="100%" alt="Software Engineer: Oracle APEX, Salesforce and AI"/></p>

# Oscar Leonardo Pedrozo

**Software Engineer**: Oracle APEX · Salesforce · Data & Integrations<br>
Asunción, Paraguay · [LinkedIn](https://www.linkedin.com/in/oscar-leonardo-pedrozo) · [GitHub](https://github.com/LeoPedrozo)

---

### Summary

Computer Engineer, graduated with distinction from FP-UNA, with over 4 years of experience in enterprise development on **Oracle APEX** and **Salesforce**. I took part in migrating a healthcare system from Oracle Forms 6i to APEX, integrated Salesforce with core systems and SAP, and built a fleet telemetry solution with Platform Events, REST APIs and MQTT. I am currently developing AI projects with Oracle APEX and the new AI features in version 26.2. I complement my work with research in medical image processing, with papers presented in Brazil and Colombia.

---

### Experience

**Salesforce Developer**, Freelance<br>
*January 2026 – Present*
- Built a second-generation Salesforce package (2GP) for telemetry and tracking of a logistics vehicle fleet, on Sales Cloud.
  - Real-time position and work-route tracking, idle-time monitoring, and multi-sensor logging per vehicle.
  - Pub/sub architecture with Platform Events to process telemetry events.
  - Apex REST API with GET, POST and PUT operations, consumed by an external platform that integrates the leading fleet-telemetry APIs.
  - Lightning Web Components (LWC) interface with interactive Leaflet maps.
  - Configured permissions for access to the system and its classes.
- Extended an open-source Kotlin Android app for field staff tracking, adding MQTT over TLS support and sensor readings.

**Oracle APEX Developer**, Excelsis S.A.<br>
*June 2024 – Present*
- Develop and optimize medical systems applications with PL/SQL and Oracle APEX.
- Design complex database triggers, procedures and functions to improve system logic.
- Implement reporting solutions with Jasper Reports.
- Deliver software modules on schedule using Agile methodologies.
- **AI customer-service assistant for a medical ERP** (2026, in production): chatbot built on Oracle APEX 26.2 for an ERP used by hospitals, clinics and prepaid healthcare providers in Paraguay.
  - Integrated OCI Generative AI with a recent xAI Grok model as the assistant's engine.
  - Centralized customer information retrieved through PL/SQL to provide context-aware answers.
  - Protected sensitive patient information through data encryption.
- **On-site consulting for a prepaid healthcare provider** (May – August 2026): successfully completed the migration of its system from Oracle Forms 6i to Oracle APEX 22.1.
  - Analyzed and built Oracle APEX pages to migrate Forms 6i screens and business logic.
  - Served as liaison between the client and the development team, gathering and translating requirements.
  - Improved PL/SQL triggers and procedures.
  - Supported report development with Jasper Reports.
  - Advised the client on planning future migrations to newer Oracle APEX versions.

**Salesforce Developer**, Excelsis S.A.<br>
*April 2023 – June 2024*
- **Brokerage firm:** integrated leads and accounts from its core system into Salesforce Sales Cloud, end to end, using Apex and the Salesforce SOAP and REST APIs.
- **Machinery sales:** built custom Salesforce forms for the sales process and integrated Salesforce with SAP through its SOAP API.
- **Automotive company:** cleaned up and merged duplicate records with Pentaho ETL processes and the Salesforce Bulk API, automated with Python (Pandas) in Jupyter Notebook.
- Supported and maintained system integrations with Salesforce.

**Support & Development Intern**, National Securities Commission (CNV), Paraguay<br>
*August 2022 – March 2023*
- Gathered requirements to implement a document management system on Salesforce Sales Cloud for CNV.
- Developed data-availability APIs with Django and Python.
- Maintained the institutional WordPress site and built new PHP pages listing bond issuers.
- Administered Windows and Ubuntu servers and monitored backup systems (Veeam).

---

### Education

- **B.Sc. in Computer Engineering**, Facultad Politécnica, UNA. *Graduated with distinction, November 2025*
- **Specialization in Higher Education Teaching**, Facultad Politécnica, UNA. *July 2026 – April 2027 (in progress)*
- **Postgraduate Diploma in IoT and Embedded Systems**, FP-UNA. *May 2025*
- **Summer School on Medical Informatics with AI**, UNAM (Mexico). *August 2025*
- **Macro-Training in Artificial Intelligence (MeIA)**, UNAM and the Latin American and Caribbean Macro Universities Network. *June 2023*. **2nd place** award for the solution "Artificial Intelligence for species classification from DNA sequences".
- **Linux Administration (Linux SysAdmin I)**, 30-hour course, FP-UNA.
- **English**, Centro Cultural Paraguayo Americano (CCPA), completed up to the "Avanzado Superior 2" (Upper Advanced 2) course. *2015 – 2018*

---

### Certifications

- Google Cloud Digital Leader. *Google, 2026*
- Oracle APEX Cloud Developer Certified Professional. *Oracle, 2025*
- Salesforce Certified AI Associate. *Salesforce, 2024*
- Salesforce Certified Platform Foundations. *Salesforce, 2023*

---

### Research

**Registration of CT and MR medical images with the Contour-Point Signature (CPS) descriptor**<br>
*Research Group on Scientific Computing and Applied Mathematics, FP-UNA · September 2024 – November 2025*
- Developed a medical image registration method based on CPS, a mathematical method from the shape descriptor family: CPS represents each image's contour, and a cost matrix finds the optimal rotation and point correspondences for landmark-based registration.
- Evaluated the method on CT and MR images from the public RIRE dataset (Vanderbilt University): on a test patient's slices it reached 72.80% accuracy for 10 extracted points, with a 1% error threshold (≈ 5.12 pixels).
- Implemented the processing pipeline in Python with SimpleITK.
- Funded by FP-UNA through its Program for Strengthening Science, Technology and Innovation (2025), and sponsored by Excelsis S.A.
- Worked alongside leading researchers from FP-UNA and FIUNA in a multidisciplinary group.

### Publications & Presentations

- **"Contour-Point Signature in Registration of Tomography and Magnetic Resonance Images"**: poster and oral presentation at the XLIV National Congress of Applied and Computational Mathematics (CNMAC 2025), organized by SBMAC, Brazil, September 2025. Published in [*Proceeding Series of the Brazilian Society of Computational and Applied Mathematics*, v. 12 n. 1 (2026)](https://proceedings.sbmac.org.br/sbmac).
- **"Eficiencia del uso del CPS en Registro de imágenes médicas"** (Efficiency of CPS in Medical Image Registration): remote talk at the V Meeting on Mathematics and Statistics Applied to the Social and Economic Sciences, Colombia, May 2025. Published in the meeting's proceedings (2026), [DOI: 10.18359/litgris.8305](https://doi.org/10.18359/litgris.8305).
- **"Uso del descriptor firma punto-contorno en el registro de imágenes de tomografía y resonancia magnética"** (Contour-point signature descriptor for CT and MR image registration): poster at the 4th AMARU-CYTED International Specialization Courses Conference 2024, UNA, August 2024.

---

### Technical Skills

| Area | Skills |
|---|---|
| Salesforce | Apex, LWC, Platform Events, Flows, Dashboards, SOAP/REST APIs, Bulk API, 2GP packages, Sales Cloud |
| Oracle | Oracle APEX (including its AI features), PL/SQL, SQL, Oracle Forms migration, Jasper Reports |
| Integrations | SAP (SOAP), REST APIs, MQTT/TLS, Pentaho ETL |
| Programming | Python (Pandas, NumPy), Django, Java, Kotlin (Android), JavaScript, PHP, WordPress, Leaflet |
| Data & AI | Medical image processing (SimpleITK), Machine Learning, data cleansing and migration |
| Infrastructure & Management | Linux, Google Cloud, IoT with ESP32, Git, Jira (Scrum/Kanban) |

---

### Languages

Spanish (native) · Guarani (native) · English (advanced reading and writing, intermediate speaking)

---

### Selected Repositories

| Repository | Description |
|---|---|
| [envio_masivo_sms_vox](https://github.com/LeoPedrozo/envio_masivo_sms_vox) | PL/SQL procedure for bulk SMS sending through the Vox Paraguay API. |
| [simpleITKnotebooks](https://github.com/LeoPedrozo/simpleITKnotebooks) | Medical image processing notebooks with SimpleITK. |
| [MEIA](https://github.com/LeoPedrozo/MEIA) | Exercises from an AI training workshop. |
| [laberinto-caminocorto](https://github.com/LeoPedrozo/laberinto-caminocorto) | Shortest path through a maze, in C. |

---

### Appendix

#### Photos

<p align="center">
  <img src="assets/foto-graduado-distinguido.jpg" height="160" alt="Graduated with distinction, FP-UNA 2025"/>
  <img src="assets/foto-graduacion.jpg" height="160" alt="Computer Engineering graduation"/>
  <img src="assets/foto-defensa-tesis.jpg" height="160" alt="Thesis defense"/>
</p>
<p align="center"><sub>Graduated with distinction, FP-UNA 2025 · Computer Engineering graduation · Thesis defense</sub></p>

<p align="center">
  <img src="assets/foto-poster-cnmac2025.jpg" height="160" alt="Poster at CNMAC 2025, Brazil"/>
  <img src="assets/foto-poster-cyted-2024.jpg" height="160" alt="Poster at the AMARU-CYTED 2024 conference"/>
  <img src="assets/foto-presentacion-cps.jpg" height="160" alt="Presenting the CPS method"/>
</p>
<p align="center"><sub>Poster at CNMAC 2025, Brazil · Poster at the AMARU-CYTED 2024 conference · Presenting the CPS method</sub></p>

<p align="center">
  <img src="assets/foto-workshop-presentacion.jpg" height="160" alt="Talk at the research group workshop"/>
  <img src="assets/foto-workshop-grupo.jpg" height="160" alt="Research Group on Scientific Computing and Applied Mathematics"/>
  <img src="assets/foto-diplomado-iot.jpg" height="160" alt="Embedded Systems and IoT Diploma"/>
</p>
<p align="center"><sub>Talk at the research group workshop · Research Group on Scientific Computing and Applied Mathematics · Embedded Systems and IoT Diploma</sub></p>

<p align="center">
  <img src="assets/foto-excelsis-oracle.jpg" height="160" alt="Oracle and Excelsis event"/>
  <img src="assets/foto-salesforce-friends.jpg" height="160" alt="Salesforce community meetup"/>
</p>
<p align="center"><sub>Oracle and Excelsis event · Salesforce community meetup</sub></p>

#### Certificates and awards

<p align="center">
  <img src="assets/cert-oracle-apex-cloud-developer.jpg" height="160" alt="Oracle APEX Cloud Developer Certified Professional"/>
  <img src="assets/cert-salesforce-ai-associate.jpg" height="160" alt="Salesforce Certified AI Associate"/>
  <img src="assets/cert-salesforce-platform-foundations.jpg" height="160" alt="Salesforce Certified Platform Foundations"/>
</p>
<p align="center"><sub>Oracle APEX Cloud Developer Certified Professional · Salesforce Certified AI Associate · Salesforce Certified Platform Foundations</sub></p>

<p align="center">
  <img src="assets/cert-cnmac-2025.jpg" height="160" alt="Presentation certificate, CNMAC 2025"/>
  <img src="assets/cert-linux-sysadmin.jpg" height="160" alt="Linux Administration course (SysAdmin I), FP-UNA"/>
  <img src="assets/cert-ccpa-ingles.jpg" height="160" alt="English program, CCPA"/>
</p>
<p align="center"><sub>Presentation certificate, CNMAC 2025 · Linux Administration course (SysAdmin I), FP-UNA · English program, CCPA</sub></p>

<p align="center">
  <img src="assets/cert-google-cloud-digital-leader.jpg" height="160" alt="Google Cloud Digital Leader"/>
  <img src="assets/cert-diplomado-iot.jpg" height="160" alt="Embedded Systems and IoT Diploma, FP-UNA"/>
  <img src="assets/cert-cyted-amaru-2024.jpg" height="160" alt="Poster certificate, AMARU-CYTED 2024"/>
</p>
<p align="center"><sub>Google Cloud Digital Leader · Embedded Systems and IoT Diploma, FP-UNA · Poster certificate, AMARU-CYTED 2024</sub></p>

<p align="center">
  <img src="assets/reconocimiento-unam-meia-2023.jpg" height="160" alt="2nd place award, MeIA 2023 (UNAM)"/>
  <img src="assets/cert-unam-meia-2023.jpg" height="160" alt="MeIA 2023 workshop certificate (UNAM)"/>
  <img src="assets/cert-cnv-pasantia.jpg" height="160" alt="Internship certificate, CNV"/>
</p>
<p align="center"><sub>2nd place award, MeIA 2023 (UNAM) · MeIA 2023 workshop certificate (UNAM) · Internship certificate, CNV</sub></p>
