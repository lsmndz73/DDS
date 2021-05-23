# DDS
# Trabajo práctico del curso de Data Science
# Trabajo aplicado 

Trabajo Práctico Data Science - Grupo 6

Puesto:	Integrante
Líder/Programador: Flavio Chaffo
Analista/Programador:	Luis Mendoza
Analista: Marco Carrasco
Programador/Tester: César Ortiz
Programador/Tester: Edwin León

# Funciones del Equipo de Trabajo
Líder: Coordina y define las actividades. Interlocutor
Analista: ¿Qué hacer? Define el lineamiento del trabajo a ejecutar
Programador: El que desarrolla el programa: dice lo que se puede hacer y plantea opciones
Tester: Evaluador de código

# Objetivos a desarrollar
Objetivo General
Análisis de amenazas asociados a sistemas de control industrial que ayuden en la toma de decisiones acerca de gestión de riesgos en una empresa que gestiona infraestructuras críticas.

Objetivos Secundarios
Análisis estadístico de vulnerabilidades, controles, etc.

https://miro.com/app/board/o9J_lGjMu8w=/?fromRedirect=1

# Identificación del problema
1.	Definir el problema
Falta de visualización del impacto de las amenazas a las que estamos expuestos en la red de operaciones (OT) respecto de los métodos de ataque predominantes sobre sistemas OT a nivel mundial tomando como referencia a MITRE ATTACK y otras fuentes de información similares.

2.	Revertir el problema
Identificar el nivel de exposición que se tiene ante atacantes de alto perfil como APTs.

3.	Colección de ideas
3.1. Público objetivo
- IT Operation
- SOC
- CxOs

3.2. Caso de uso
- SOC. Análisis de datos de escaneos (Port scanning, cross site scriptings, entre otros) para decidir si la alarma es un falso positivo o no.
- CxO. Cruzar la información externa con la interna para analizar el nivel de riesgo al que estamos expuestos en la industria.

3.3. Preguntas
- ¿Qué tan eficiente y eficaz es el sensor de vulnerabilidades?
- ¿Cuál es el nivel de riesgo de la empresa?

3.4. Métricas
- % de equipos vulnerables
- % de falsos positivos levantados
- % de confiabilidad de la herramienta
- Probabilidad de ser atacados
- % de riesgos controlados
- % de riesgos inherentes controlados
- Amenazas por año.
- % Sistemas con capacidad de detención del proceso.
- Distribución de amenazas por nivel de criticidad.
- Amenazas IT vs OT.
- Vulnerabilidades por sistema.
- Riesgo basado en Vulnerabilidad vs Amenazas vs Activos

3.5. Acciones
- Cambiar la herramienta de detección de vulnerabilidades
- Creación de tickets automáticos con las vulnerabilidades detectadas
- Eliminar las vulnerabilidades en los equipos detectados
- Revisar los sistemas de parchado automático
- Informar a las áreas que tienen riesgos no controlados para que apliquen medidas correctivas

4.	Revertir las ideas
Validar las fuentes de datos de vulnerabilidades, amenazas, mitigaciones, APTs, etc
Validar las fuentes de datos de CVE Details.
Validar los enfoques y esfuerzo requerido: objetivos vs información recopilada.

5.	Identificar soluciones
Efectuar consultas básicas que asegure la lectura de las bases de datos y verifique su estructura.
Efectuar consultas que permita concatenar las bases de datos y verificar que se ejecuten las relaciones.
Verificar la coherencia de los resultados obtenidos.

# Tipos de fuentes de información para el trabajo
Bases de datos de vulnerabilidades de fabricantes de sistemas OT.
Bases de datos de vulnerabilidades de fabricantes de equipos IT que son utilizados en redes OT.
Componentes de tecnología de operaciones.
CVE Details: https://cvedetails.com

Amenazas de alto perfil, métodos de mitigación, de bases de datos oficiales.

# Fuentes de información, bases de datos, código R utilizados para el desarrollo del trabajo.

# Trabajo destacado de semestre anterior del curso
https://datadrivensecurity-project.web.app/

# CVE de Fabricantes
https://nvd.nist.gov/vuln/data-feeds

# Archivos descargados de las bases de datos de Mitre
cwes.rda
apnic.rds
attck.groups.rda
attck.mitigations.rda
attck.relations.rda
attck.software.rda
attck.tactics.rda
attck.techniques.rda
capec.categories.rda
capec.patterns.rda
capec.relations.rda
capec.views.rda
cwes.rda
mitre-attck.rda
mitre-shield.rda
shield.opportunities.rda
shield.procedures.rda
shield.relations.rda
shield.tactics.rda
shield.techniques.rda
shield.use_cases.rda

# Resultados de análisis de vulnerabilidades de sistema de detección de intrusos de Claroty
Rockwell.Results.Clarority.xlsx

# Fuente de datos europea
https://data.europa.eu/

# Fuente de datos de vulnerabilidades reportadas por Rockwell

# Descripción de bases de datos usadas
Common Platform Enumeration (CPE)
Common Platform Enumeration (CPE) is a standardized method of describing and identifying classes of applications, operating systems, and hardware devices present among an enterprise's computing assets. CPE does not identify unique instantiations of products on systems, such as the installation of XYZ Visualizer Enterprise Suite 4.2.3 with serial number Q472B987P113. Rather, CPE identifies abstract classes of products, such as XYZ Visualizer Enterprise Suite 4.2.3, XYZ Visualizer Enterprise Suite (all versions), or XYZ Visualizer (all variations).

IT management tools can collect information about installed products, identifying these products using their CPE names, and then use this standardized information to help make fully or partially automated decisions regarding the assets. For example, identifying the presence of XYZ Visualizer Enterprise Suite could trigger a vulnerability management tool to check the system for known vulnerabilities in the software, and also trigger a configuration management tool to verify that the software is configured securely in accordance with the organization's policies. This example illustrates how CPE names can be used as a standardized source of information for enforcing and verifying IT management policies across tools.

CVEDetails
www.cvedetails.com provides an easy to use web interface to CVE vulnerability data. You can browse for vendors, products and versions and view cve entries, vulnerabilities, related to them. You can view statistics about vendors, products and versions of products. CVE details are displayed in a single, easy to use page, see a sample here.

CVE vulnerability data are taken from National Vulnerability Database (NVD) xml feeds provided by National Institue of Standards and Technology. Additional data from several sources like exploits from www.exploit-db.com, vendor statements and additional vendor supplied data, Metasploit modules are also published in addition to NVD CVE data.

Vulnerabilities are classified by cvedetails.com using keyword matching and cwe numbers if possible, but they are mostly based on keywords.

Unless otherwise stated CVSS scores listed on this site are "CVSS Base Scores" provided in NVD feeds. Vulnerability data are updated daily using NVD feeds.Please visit nvd.nist.gov for more details.



