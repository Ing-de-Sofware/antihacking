INGENIERÍA DE SISTEMAS DE SOFTWARE
CURSO: 1ASI0665 Anti-Hacking y Nuevas Tendencias de Seguridad
ENUNCIADO DEL TRABAJO FINAL
PROFESORES: Vera Olivera, David Carlos
SECCIONES: Todas
FECHA DE EVALUACIÓN: Semana 15
CICLO ACADEMICO: 2025-20
1. OBJETIVO
El presente documento define el trabajo final y la rúbrica que permite evaluar el logro del curso
1ASI0665 Anti-Hacking y Nuevas Tendencias de Seguridad. Los objetivos de este trabajo son:
a. Aplicar de manera práctica los conocimientos adquiridos en el curso de Anti-Hacking y
Nuevas Tendencias de Seguridad en un entorno real.
b. Ejecutar todas las fases de un proyecto de hacking ético y pentesting (planificación,
reconocimiento, escaneo, explotación, post-explotación, reporte y mitigación).
c. Emular el rol de una consultora de ciberseguridad para una empresa real (cliente PyME)
con la que se establezca contacto directo.
d. Entregar un informe técnico y ejecutivo con evidencias, hallazgos, riesgos priorizados
(CVSS) y plan de mitigación.
e. Desarrollar habilidades de trabajo en equipo, gestión de proyectos, responsabilidad ética y
comunicación efectiva.
2. LOGRO DEL CURSO
Al finalizar el curso, el estudiante será capaz de aplicar los conocimientos y habilidades del
hacking ético para evaluar la seguridad de sistemas informáticos y proponer contramedidas
efectivas. Asimismo, podrá identificar y analizar las nuevas tendencias en ciberseguridad para
desarrollar estrategias de defensa proactivas en un entorno tecnológico en constante evolución.
3. ABET – EAC - STUDENT OUTCOME 2
La capacidad de aplicar el diseño de ingeniería para producir soluciones que satisfagan
necesidades específicas con consideración de salud pública, seguridad y bienestar, así como
factores globales, culturales, sociales, ambientales y económicos.
4. ENUNCIADO
El curso de Anti-Hacking y Nuevas Tendencias de Seguridad tiene una naturaleza teórico-práctica,
por lo que es necesario evidenciar la capacidad para aplicar los conocimientos y habilidades del
hacking ético para evaluar la seguridad de sistemas informáticos y proponer contramedidas
efectivas aplicando los conceptos, técnicas y buenas prácticas impartidos en el curso.
1/19
Los equipos de estudiantes se organizarán como consultoras de ciberseguridad y deberán ejecutar
un servicio completo de Ethical Hacking y Pentesting. El cliente será una empresa real de
pequeña o mediana escala que provea autorización para realizar pruebas (firma de Reglas de
Compromiso).
El alcance incluye:
• Aplicaciones Web y Portales (formularios, login, sesiones, OWASP Top 10).
• APIs REST/SOAP (pruebas de seguridad de endpoints, fuzzing, tokens).
• Aplicaciones móviles (análisis estático/dinámico de APK o IPA, API calls).
• Redes y servidores (esquema básico de reconocimiento, escaneo y pruebas controladas).
El proyecto se desarrollará en 15 semanas, siguiendo entregables TP1 y TF1
Uso obligatorio de herramientas: Kali Linux, Metasploit, Burp Suite/ZAP, Nmap, sqlmap,
Wireshark. Se recomienda además Nessus/OpenVAS y MobSF.
5. EXPOSICIÓN
Cada equipo deberá grabar un video de exposición (15 min) donde se muestre:
• La empresa cliente y el alcance aprobado.
• Metodología seguida.
• Evidencias de vulnerabilidades críticas explotadas.
• Recomendaciones de mitigación.
• Conclusiones y aprendizajes.
La sustentación será síncrona (en clase o vía Class For Teams), con preguntas del docente.
Nota: La exposición forma parte de la nota. Si al momento de la exposición el profesor
determina que el alumno no ha hecho parte o la totalidad del trabajo debido a que el alumno no
supo responder correctamente a las preguntas realizadas el profesor podrá considerar
descontar puntos en funcionalidades ya implementadas del trabajo. La frase “En esa parte me
ayudaron” no será considerada como válida por lo que el alumno deberá realizar el trabajo de
forma total.
6. INSTRUCCIONES PARA LA ENTREGA DEL TRABAJO
Un representante del grupo subirá los archivos en la actividad indicada por el docente, los
siguientes archivos:
6.1. Informe de proyecto
• Final Project Document Report (docx y pdf).
• Estructura detallada en la sección 7.
Nota: El informe de proyecto se elaborará de forma colaborativa durante todo el ciclo de
vida del proyecto, en el formato Markdown (organizado en uno o mas archivos con extensión
.md, siendo el archivo principal README.md) en un repositorio de control de versiones que
forme parte de una organización pública de GitHub. Dicho repositorio debe evidenciar
2/19 V1.0
mediante commits los aportes de los miembros del equipo. Debe aplicar GitFlow y
conventional commits para su creación y evolución. A partir de dicho repositorio se generan
las exportaciones en formato .pdf para las entregas (TP1 y TF1). Tomar las consideraciones
del caso en caso se deba subir información relacionada al cliente (confidencialidad).
6.2. Videos de exposición
• Formato: mp4 + enlace en Stream/YouTube privado.
• Duración: 15 min.
Todo video de exposición debe mostrar a cada uno de los integrantes ante cámara
explicando la construcción de los artefactos del trabajo, centrándose en mostrar los
artefactos según la rubrica correspondiente al hito, apoyándose en una presentación de
PowerPoint y demostrando los artefactos en las herramientas indicadas. La duración máxima
del video es de 30 minutos.
6.3. Horarios de entrega
• TP1 – Semana 9: Documento de Alcance + primer reporte de reconocimiento y escaneo +
Reporte preliminar de vulnerabilidades + PoC de explotación inicial.
• TF1 – Semana 15: Evidencias de explotación avanzada + borrador del informe + Informe
final, presentación ejecutiva y video.
Nota:
Para TP1, la entrega se realiza hasta 24 horas después del horario programado regular de la
sesión síncrona de la semana (en caso de dos sesiones síncronas semanales, se considera la
segunda sesión síncrona).
Para TF1, la entrega se realiza 24 horas antes de la hora programada de la primera sesión
síncrona semanal.
6.4. Nomenclatura de Archivos
• Informe: upc-pre-202520-1asi0665-<NRC>-<consultora>-report-<tp1/tf1>.pdf
• Presentación: upc-pre-202520-1asi0665-<NRC>-<consultora>-keynote-<tp1/tf1> (.pptx y
.pdf)
• Informe de participación: upc-pre-202520-1asi0665-<NRC>-<consultora>-performance-
<tp1/tf1> (.docx y .pdf)
• Video: upc-pre-202520-1asi0665-<NRC>-<consultora>-expo-<tp1/tf1> (.mp4)
• Evidencias: upc-pre-202520-1asi0665-<NRC>-<consultora>-evidence.zip
6.5. Recomendaciones generales
• Respetar ética profesional y reglas de compromiso.
• Entregar todos los archivos con hash SHA256.
• Validar ortografía, citación y formato APA en bibliografía.
Nota: Revisar con detenimiento los documentos Final Project Statement (este documento), así
3/19
como las rúbricas.
6.6. Exposición
Para cada entrega, el equipo grabará en video su exposición con anticipación. El video
contará de una edición que muestre la presentación de PowerPoint junto con la muestra en
pantalla de artefactos como diagramas u otros que lo requieran, sincronizado con la
explicación ante cámara de los participantes. En la primera parte de la exposición, debe
incluirse tomas de cada participante hablando a la cámara y presentándose. Debe editarse
para que sólo sea un video cuidando que el contenido no exceda el límite impuesto por
Microsoft Stream/Clipchamp.
El enlace del video debe incluirse en el Document Report, dentro de un anexo titulado
“Videos de Exposiciones” y especificando la entrega a la que corresponde la Exposición. Debe
entregarse además el archivo de video (ver anexos).
6.7. Sustentación síncrona
Para TP1 y TF1, la sesión de clase en la que esté programada la entrega se enfocará en la
sustentación de los proyectos. Cada equipo iniciará con una exposición planificada para una
duración máxima de 15 minutos. Luego se realizará la sustentación con preguntas a los
participantes de forma indistinta, sobre diversos aspectos del proyecto previamente
entregado y expuesto (vía video pre-grabado).
6.8. Participant Performance Report
El Participant Performance Report es un documento en Word que elabora el Team Leader, en
el cual explica y califica el desempeño de cada uno de los miembros de su equipo (ver
anexos). En este Documento el coordinador resume la participación de cada integrante y la
asigna a cada uno una calificación entre 0 y 20 (siendo las alternativas de calificación 20, 16,
13, 07 o 00). Cada entrega debe incluir un Participant Performance Report sobre el
desempeño de cada participante en relación con dicha entrega.
6.9. Final Project Keynote
Cada entrega incluye una presentación de PowerPoint cuyo contenido se relaciona con el
ciclo de vida del proyecto, priorizando contenido relacionado con la entrega en cuestión.
Entre las diapositivas deben incluir una de presentación del equipo con las fotos de los
miembros del startup/consultora, identificados por nombre, apellido y carrera.
6.10. Final Project Document Report
Tener cuidado con el respeto del Template en caso aplique.
7. ESTRUCTURA DEL INFORME
Cada grupo debe entregar un informe detallando cada una de las secciones que se muestran a
continuación:
Carátula
• Logo de la UPC.
• Nombre de la universidad, carrera, ciclo, código y nombre del curso, NRC.
• Nombre del profesor.
4/19 V1.0
• Título: “Informe de Trabajo Final – Anti-Hacking y Nuevas Tendencias de Seguridad”.
• Nombre de la consultora.
• Relación de integrantes (código, apellidos y nombres).
• Mes y año.
Registro de Versiones del Informe
• Tabla con número de versión, fecha, cambios realizados, responsable.
Project Report Collaboration Insights
• Roles Scrum: Product Owner (líder de consultora), Scrum Master (coordinador de
procesos), Development Team (pentesters, documentadores, analistas).
• Herramientas de colaboración usadas (Trello, Jira, GitHub, etc.).
Tabla de Contenidos
Student Outcome
• Explicación de cómo el proyecto contribuye al Outcome 2 (Diseño de ingeniería con
impacto en seguridad, bienestar, aspectos sociales y culturales).
Capítulo I: Introducción
1.1. Startup Profile (Cliente)
• Descripción de la empresa PyME.
• Expectativas del cliente.
1.2. Consultora de Ciberseguridad (Equipo)
• Descripción de la consultora
• Perfiles de los integrantes y roles Scrum.
1.3. Solution Profile
• Antecedentes y problemática.
• Objetivos del pentesting (General y específicos).
1.4. Aceptación del Servicio de Pentesting (Rules of Engagement)
Capítulo II: Metodología Ágil y de Pentesting
2.1. Marco de referencia: Scrum aplicado a pentesting + PTES + OWASP+Otros.
2.2. Backlog inicial: User Stories de seguridad (ej. “Como atacante externo quiero identificar
vulnerabilidades en el login web…”).
2.3. Planificación de sprints (Sprint Planning):
• Sprint 1: Reconocimiento & Escaneo inicial.
• Sprint 2: Enumeración y vulnerabilidades preliminares.
• Sprint 3: Explotación controlada (web, APIs).
• Sprint 4: Post-explotación y persistencia.
• Sprint 5: Informe final y recomendaciones.
2.4. Definición de Done (DoD): Evidencia clara, reproducible y con PoC.
2.5. Herramientas: Kali Linux, Metasploit, Burp Suite, Nmap, sqlmap, Wireshark, etc.
Capítulo III: Desarrollo del Proyecto por Sprints
Sprint 1 – Reconocimiento y Escaneo
• Objetivos del sprint.
5/19
• Historias de usuario atendidas.
• Actividades realizadas.
• Resultados y evidencias.
• Retrospectiva del sprint.
Sprint 2 – Enumeración y Vulnerabilidades
• Historias de usuario atendidas.
• Actividades (Nessus, Nikto, análisis de endpoints API).
• Resultados y evidencias.
• Retrospectiva.
Sprint 3 – Explotación
• Historias de usuario atendidas.
• Actividades (Metasploit, Burp, sqlmap).
• Resultados y PoC.
• Retrospectiva.
Sprint 4 – Post-explotación y Persistencia
• Historias de usuario atendidas.
• Actividades (escalamiento, extracción de credenciales, movimiento lateral).
• Evidencias.
• Retrospectiva.
Sprint 5 – Informe Final y Recomendaciones
• Historias de usuario atendidas.
• Consolidación de hallazgos y plan de mitigación.
• Preparación de la presentación ejecutiva.
• Retrospectiva global.
Capítulo IV: Resultados Consolidados
4.1. Matriz de vulnerabilidades (ID, descripción, CVSS, impacto).
4.2. Evidencias técnicas (pantallazos, logs, outputs).
4.3. Impacto en el negocio.
Capítulo V: Recomendaciones y Plan de Mitigación
5.1. Recomendaciones técnicas (patching, WAF, hardening).
5.2. Recomendaciones organizacionales (capacitación, políticas).
5.3. Priorización por impacto/urgencia.
Capítulo VI: Conclusiones y Recomendaciones
• Conclusiones y recomendaciones del equipo.
• Lecciones aprendidas en metodología ágil.
• Relación con Student Outcome 2.
• Video “About-the-Team”.
Bibliografía
Formato APA.
Anexos
• Registro de User Stories.
• Product Backlog y Sprint Backlogs.
6/19 V1.0
8. • Evidencias de cada sprint (capturas, reportes de herramientas).
• Scripts y código.
• Registro de retrospectivas.
CONSIDERACIONES SOBRE LOS COMPONENTES Y ENTREGABLES
8.1. Registro de Versiones del Informe
El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe
durante el ciclo de vida del proyecto.
Esta sección inicia en una página nueva y se incluye un cuadro con la siguiente estructura:
Versión Fecha Autor Descripción de modificación
Como primera línea de la tabla se incluye la primera versión del informe. A partir de ello, se
considera modificaciones relevantes la adición de secciones, eliminación de secciones,
correcciones o mejoras producto de retroalimentación recibida del docente o producto de la
autocrítica del equipo. Cada línea de versión debe incluir solo un autor. Esto quiere decir que,
entre una entrega y otra, pueden irse generando varias versiones del informe. Todo ello debe
quedar reflejado en este cuadro de Registro.
8.2. Project Report Collaboration Insights
En esta sección el equipo indica el URL del repositorio para el Project Report en la organización
de GitHub del equipo. Adicionalmente, para cada entrega explica cómo se han desarrollado las
actividades de elaboración del informe y se presenta capturas en imagen de los analíticos de
colaboración y commits en GitHub para el repositorio del informe, realizados por los miembros
del equipo. Todos los miembros del equipo deben tener participación en la elaboración del
informe. Esta sección debe ir expandiéndose con descripciones y evidencias en cada entrega. Lo
descrito y evidenciado debe tener coherencia con el Registro de Versiones del Informe.
8.3. Contenido
La sección inicia en una nueva página. Para esta sección utilice hipervínculos de Markdown
para construir la tabla de contenido. Considere en la elaboración 4 niveles de esquema.
Recuerde actualizar y verificar la tabla de contenidos antes de cada entrega.
8.4. Student Outcome
Cada participante del equipo debe colaborar a fin de que se redacte como grupo los
sustentos y evidencias de las actividades realizadas en el trabajo final han ayudado a
desarrollar cómo las dimensiones del student outcome. Por ello en esta sección debe quedar
descrito por escrito, la relación entre el outcome, sus dimensiones y el trabajo que han
realizado. Esto se complementa con lo reflejado en los testimonios expuestos que forman
parte del video About The Team.
La sección inicia en una nueva página. Debe incluir el párrafo introductorio y el cuadro de
Student Outcome tal como se indica en la sección de Anexos de este documento. En las
celdas Acciones realizadas, debe especificarse cada participante: Apellidos, Nombres y a
continuación, cada entrega (TP1, TF1, etc.) con las acciones específicas realizadas que se
7/19
relacionen con el criterio del Outcome al que corresponda la celda. Esta celda se irá
expandiendo en cada entrega. Las celdas Conclusiones se llenan de forma grupal y son
acumulables, es decir se van expandiendo en cada entrega. Vea especificaciones sobre cómo
estructurar esta sección en el Anexo A. Estructura para la sección Objetivo del Estudiante
(Student Outcome). El párrafo introductorio antes del cuadro que se aprecia en el anexo
referido debe colocarse también de forma idéntica en su informe.
8.5. Startup Profile
Incluye la descripción de startup1 o consultora de ciberseguridad, perfiles de los miembros
del equipo, incluyendo foto de participante, nombres y apellidos, código de estudiante y
descripción de carrera, junto con párrafo de resumen indicando principales conocimientos
técnicos y habilidades que puede aportar en el equipo.
8.6. Solution Profile
Esta sección incluye dos secciones internas. La primera parte, Antecedentes y Problemática,
consta del enunciado de problema, y una descripción de los puntos más importante que debe
resolver la solución propuesta, así como objetivos y restricciones que delimiten el alcance del
proyecto.
8.7. Aceptación del Servicio de Pentesting (Rules of Engagement)
En esta sección se debe incluir un documento formal de aceptación de los servicios de
pentesting por parte de la empresa cliente. Dicho documento constituye las Reglas de
Compromiso (Ver Anexo) y garantiza que el cliente autoriza la realización de pruebas de
seguridad ofensivas en los sistemas previamente acordados.
El documento debe estar firmado por un representante autorizado del cliente (ej. gerente,
jefe de TI o responsable designado), debidamente escaneado e incorporado en esta sección
como evidencia.
Contenido mínimo del documento de aceptación:
1. Datos de la empresa cliente: Razón social, RUC, dirección y representante autorizado.
2. Datos de la consultora (equipo de estudiantes): Nombre del equipo, integrantes y
roles.
3. Objetivo del servicio: Realizar pruebas de penetración controladas para identificar
vulnerabilidades en sistemas, aplicaciones y servicios digitales del cliente.
4. Alcance autorizado: Listado de dominios, sistemas, aplicaciones y APIs que pueden
ser evaluados.
5. Limitaciones y exclusiones: Ej. no ejecutar ataques de Denegación de Servicio (DoS),
no realizar explotación en sistemas fuera del alcance.
6. Periodo de ejecución: Fechas de inicio y fin de las pruebas.
7. Responsabilidades:
o Del cliente: proveer accesos, contactos y autorizaciones necesarias.
o De la consultora: realizar pruebas éticas, seguras, documentadas y no
destructivas.
8. Confidencialidad: Compromiso de no divulgar la información obtenida sin
autorización.
1 Un startup es una pequeña empresa de reciente creación, con alto potencial innovador y tecnológico, donde su modelo es escalable y su
crecimiento puede ser exponencial. En su traducción del inglés, el término start-up significa “puesta en marcha”. Y, efectivamente, podemos
definirlo como el periodo inicial de una empresa, el comienzo o arranque de un nuevo negocio.
8/19 V1.0
9. Firma y sello: Representante del cliente y líder del equipo consultor.
8.8. Antecedentes y Problemática
Aquí se incluye una aproximación preliminar a la descripción de los antecedentes y la
descripción de la problemática. Para la elaboración de esta descripción, el equipo debe
aplicar previamente la técnica de The 5 ‘W’s y 2 ‘H’s - Who, What, Where, When, Why, How
& How Much.
8.9. Estructura Contenido Informe
Sección / Sub-sección Descripción (50–100 palabras)
Este apartado muestra la evolución del documento. Contiene número de versión,
fecha, cambios realizados y responsable. Permite mantener trazabilidad y control
Registro de Versiones
de calidad sobre las entregas, asegurando que el proyecto refleje prácticas de
del Informe
documentación profesional y simulando procesos usados en consultoras de
ciberseguridad reales.
Se documenta cómo trabajó el equipo bajo metodología ágil. Incluye roles (Scrum
Máster, Product Owner, Pentesters, Documentadores), responsabilidades de
Project Report
cada miembro y herramientas colaborativas usadas (Trello, Jira, GitHub, Teams).
Collaboration Insights
Su objetivo es demostrar la capacidad de organización, colaboración y gestión
efectiva en un proyecto de seguridad ofensiva.
Explica cómo el proyecto contribuye al Student Outcome 2 (ABET–EAC). Se
detalla cómo el diseño y ejecución del pentesting permitió proponer soluciones
Student Outcome
de seguridad considerando factores técnicos y sociales, salud pública, bienestar y
aspectos culturales y económicos. Esta sección vincula el trabajo académico con
la formación integral del ingeniero de software.
Presenta el contexto general del proyecto y justifica su relevancia. Incluye la
descripción de la empresa cliente (perfil, sector, servicios digitales), la consultora
Capítulo I: Introducción
de ciberseguridad (equipo de estudiantes) y los objetivos principales. Se exponen
antecedentes y la problemática de seguridad a resolver, enmarcando la
importancia del pentesting dentro de la realidad empresarial.
En esta sección se documenta el perfil de la empresa cliente seleccionada. Debe
incluir: rubro o sector de actividad, tamaño de la organización, número de
empleados, servicios digitales ofrecidos (ej. portal web, sistemas internos,
aplicaciones móviles, APIs expuestas), así como sus principales necesidades de
1.1 Client Profile
seguridad. Se debe explicar el contexto de negocio de la empresa y su motivación
para aceptar la consultoría de pentesting. También es relevante describir la
infraestructura tecnológica básica y las expectativas de resultados (ej. identificar
vulnerabilidades críticas, contar con un informe técnico y un plan de
remediación).
Describe a la empresa cliente con datos generales: misión, visión, mercado
1.1.1 Descripción de la
objetivo, servicios digitales ofrecidos y nivel de madurez tecnológica. Sirve como
PYME
punto de partida para comprender los activos de información críticos que serán
evaluados.
Esta sección presenta el perfil del equipo de estudiantes que asume el rol de
1.2 Startup/Consultora
consultora de ciberseguridad. Se debe incluir el nombre de la consultora (marca
Profile
ficticia creada por el grupo) y una breve misión orientada a la seguridad ofensiva.
9/19
Sección / Sub-sección Descripción (50–100 palabras)
Cada integrante debe describir su perfil técnico y rol dentro del marco Scrum
(Scrum Master, Product Owner, Pentester Web, Pentester de APIs/móvil,
Documentador/Analista). Se espera detallar competencias, experiencia
académica previa (ej. en desarrollo, redes o bases de datos) y el valor que aporta
cada rol a la ejecución del pentesting.
Se describen los perfiles de los estudiantes que forman la consultora. Incluye su
1.1.2 Perfiles de
rol dentro del marco Scrum (ej. Scrum Master, Product Owner, especialista web,
integrantes del equipo
especialista APIs, documentador) y sus competencias técnicas, reforzando el
aprendizaje colaborativo y multidisciplinario.
Expone el enfoque de solución del proyecto: el servicio de pentesting ofrecido.
Describe la propuesta de valor de la consultora hacia el cliente, las fases
1.3 Solution Profile
metodológicas que se aplicarán y las expectativas de seguridad que se busca
alcanzar.
Identifica las principales vulnerabilidades y riesgos que motivan el proyecto.
1.3.1 Antecedentes y
Incluye ejemplos de incidentes pasados, deficiencias en el desarrollo seguro o
problemática
configuraciones inseguras. Esto ayuda a justificar la necesidad del servicio de
Ethical Hacking.
Define quiénes se benefician de la solución: directivos (con un informe ejecutivo),
1.4 Segmentos objetivo
área TI (con informe técnico), y usuarios finales (mediante mayor seguridad en
sistemas). Relaciona hallazgos con su impacto real en las partes interesadas.
Se describe el marco metodológico. Se explica cómo se combinan Scrum y los
estándares de pentesting (PTES, OWASP, NIST SP 800-115). Incluye backlog inicial,
Capítulo II: Metodología
definición de sprints, DoD (Definition of Done) y herramientas utilizadas. El
Ágil y de Pentesting
objetivo es demostrar un proceso iterativo y controlado que asegure calidad en
los entregables.
Explica los marcos usados: PTES, OWASP Testing Guide y NIST SP 800-115,
2.1 Marco de referencia
adaptados a Scrum. Muestra cómo estos estándares guían las fases del proyecto
desde reconocimiento hasta reporte final.
Presenta el Product Backlog con historias de usuario enfocadas en pentesting (ej.
2.2 Backlog inicial
pruebas de SQL Injection, escaneo de vulnerabilidades en APIs, explotación de
credenciales débiles). Define prioridades y criterios de aceptación.
Explica cómo se planifican 5 sprints: Reconocimiento & Escaneo, Enumeración &
2.3 Planificación de
Vulnerabilidades, Explotación, Post-explotación, Informe Final. Cada sprint tiene
sprints
objetivos, actividades técnicas y entregables.
Explica la definición de completitud para cada historia de usuario. Incluye:
2.4 Definición de Done
evidencia clara (pantallazos, reportes), reproducibilidad, documentación de PoC y
(DoD)
análisis de impacto.
Enumera las herramientas obligatorias (Kali Linux, Metasploit, Burp Suite, Nmap,
2.5 Herramientas
sqlmap, Wireshark). Además, recomienda Nessus/OpenVAS y MobSF. Explica
utilizadas
cómo cada una contribuye a las fases del proyecto.
Documenta las actividades ejecutadas en cada sprint. Cada subcapítulo incluye
Capítulo III: Desarrollo
objetivos, historias de usuario trabajadas, actividades realizadas, resultados,
del Proyecto por Sprints
evidencias y retrospectiva. Refleja un avance incremental y controlado.
Sprint 1 –
Se detallan las actividades de OSINT, recolección de información pública,
Reconocimiento y
descubrimiento de hosts y puertos con Nmap/Masscan. Se documentan
Escaneo
resultados, evidencias y retrospectiva del sprint.
10/19 V1.0
Sección / Sub-sección Descripción (50–100 palabras)
Se presenta la identificación de servicios, enumeración de versiones, y análisis
Sprint 2 – Enumeración
preliminar de vulnerabilidades con Nessus, Nikto y Burp. Se incluyen hallazgos
y Vulnerabilidades
priorizados.
Muestra la ejecución de pruebas controladas con Metasploit, sqlmap y Burp
Sprint 3 – Explotación
Suite. Incluye PoC de vulnerabilidades críticas, pantallazos y explicación de
impacto.
Sprint 4 – Post-
Se documentan técnicas de escalamiento de privilegios, movimiento lateral y
explotación y
acceso a información sensible. Incluye evidencia y análisis de impacto.
Persistencia
Consolida resultados, valida hallazgos y desarrolla el informe técnico y ejecutivo.
Sprint 5 – Informe Final
Incluye la preparación de la presentación final y la retrospectiva global del
y Recomendaciones
equipo.
Resume los hallazgos en una matriz de vulnerabilidades con ID, descripción, CVSS,
Capítulo IV: Resultados
impacto y recomendaciones preliminares. Incluye capturas, logs y outputs como
Consolidados
evidencias técnicas. También analiza riesgos para el negocio.
Capítulo V:
Presenta recomendaciones clasificadas en técnicas, organizacionales y de gestión.
Recomendaciones y
Incluye un plan priorizado a corto, mediano y largo plazo, enfocado en mejorar la
Plan de Mitigación
seguridad de la empresa cliente.
Resume los aprendizajes, hallazgos principales y el cumplimiento de objetivos.
Capítulo VI:
Relaciona el proyecto con el Student Outcome 2 y con la ética en la práctica
Conclusiones
profesional. Incluye video “About-the-Team” como evidencia de la experiencia.
Incluye todas las referencias bibliográficas en formato APA. Se consideran
Bibliografía
manuales técnicos, OWASP, PTES, NIST, libros de hacking ético y papers
académicos. Garantiza el rigor académico del proyecto.
Incluyen materiales complementarios: Product Backlog, Sprint Backlogs, reportes
Anexos
de herramientas, scripts, capturas, registros de retrospectivas. Respaldan la
reproducibilidad y trazabilidad del trabajo final.
8.10. Video About-The-Team
En esta sección el equipo redacta un resumen de los aspectos más relevantes del video About-
The-Team, la pauta de secuencias de contenido (secciones con el timing de inicio de cada una,
es decir hh:mm:ss de cada sección dentro del video) incluyendo además un cuadro de video
representativo del mismo, junto con el URL de la versión publicada en Microsoft
Stream/Clipchamp (y además, el URL de la versión publicada en YouTube utilizada para
incrustarse en el Landing Page).Este video resume el proceso de trabajo realizado, incluyendo
escenas con imágenes o video de sesiones de trabajo real del equipo, complementando con
narración (voz en off) del proceso. Incluye además el testimonio ante cámara de cada
participante describiendo actividades realizadas, logro de outcomes y desarrollo de
competencias alcanzados. Ver otras indicaciones importantes en el Anexo C. Indicaciones para
secciones que incluyen Videos.
8.11. Bibliografía
En esta sección el equipo especifica todas las referencias bibliográficas en formato APA 7ma
edición (https://normas-apa.org/), utilizadas como base para el desarrollo del trabajo o
referenciadas en secciones del informe.
11/19
8.12. Anexos
En esta sección, el equipo incluye como anexos tablas, documentos, gráficos, u otros elementos
que por su extensión o grado de importancia ameriten aparecer en esta sección. Cada sección
de anexo debe iniciar en una nueva página diferenciando el título con una letra mayúscula
(Ejemplo: Anexo A, Anexo B, etc.)
Considere un Anexo con el nombre Videos de Exposiciones, donde se incluya de forma
progresiva el título e hipervínculo al video de Exposición en Microsoft Stream/Clipchamp para
cada entrega del proyecto. La relación de títulos y videos se va expandiendo con cada entrega.
9. ÉTICA Y RESPONSABILIDAD
El equipo de consultoría de ciberseguridad debe redactar y publicar los términos y condiciones del
servicio de pentesting, garantizando transparencia y responsabilidad profesional. Estos deberán
incluirse como documento anexo y, opcionalmente, en un enlace dentro del footer de la Landing
Page de la consultora. Se debe evidenciar el cumplimiento de los principios del código de ética de la
ACM/IEEE y del Colegio de Ingenieros del Perú (CIP). Además, el equipo debe documentar, con
capturas y evidencias, la práctica de hacking ético, asegurando consentimiento del cliente y
demostrando profesionalismo en la recolección, tratamiento y resguardo de la información
obtenida.
10. TECNOLOGÍA
El desarrollo del proyecto de pentesting requiere utilizar un conjunto de herramientas de seguridad y
entornos especializados. De manera obligatoria, se debe emplear Kali Linux como sistema base y
herramientas como Metasploit, Burp Suite, Nmap, sqlmap y Wireshark para reconocimiento,
explotación y análisis de tráfico. Adicionalmente, se puede utilizar OpenVAS/Nessus para escaneo de
vulnerabilidades, MobSF para análisis de aplicaciones móviles y OWASP ZAP para pruebas web. Para la
documentación y reportes, se recomienda el uso de Markdown, LaTeX o Microsoft Word. Para la gestión
ágil de tareas, se permite Trello, Jira o GitHub Projects.
12/19 V1.0
11. EVALUACIÓN DEL TRABAJO FINAL
El trabajo se ha dividido en 2 entregables.
TP1 – Sprint Review – Semana 9 Final Project
Documentation Report Final Project Keynote
Final Project Individual Member Performance Report (by Team Leader)
Archivo .zip con archivos complementarios según corresponda (videos, proyectos de software,
documentos complementarios).
Video de Exposición
Consideraciones.
Incluir avance de Conclusiones, Bibliografía y Anexos.
Aspectos a incluir:
Carátula
Registro de Versiones del Informe Project Report
Collaboration Insights Contenido
Student Outcome
Capítulo I: Introducción
Capítulo II: Requirements Elicitation & Analysis.
Capítulo III: Requirements Specification.
Capítulo IV: Solution Software Design.
Conclusiones
Bibliografía Anexos.
TF1 – Release Review – Semana 15
Final Project Final Documentation Report Final Project
Final Keynote
Final Project Final Individual Member Performance Report (by Team Leader)
Archivo .zip con archivos complementarios según corresponda (videos, proyectos de software,
documentos complementarios).
Consideraciones
Debe incluir versión actualizada de Registro de Versiones del Informe, Project Report Collaboration
Insights y Sección Student Outcome.
Debe incluir versión corregida y mejorada de artefactos previamente presentados.
Debe incluir en el informe versión final y evidencias de la conclusión del ciclo de vida y el proyecto con
todos los Capítulos.
Conclusiones
Bibliografía
Anexos.
13/19
12. REFERENCIAS
• The Markdown Guide https://www.markdownguide.org/
• How to use Acceptance Criteria in Scrum: Explanation, Examples, and Template
https://dzone.com/articles/acceptance-criteria-in-software-explanation-example
• A Beginner’s Guide to finding User Needs:
https://jdittrich.github.io/userNeedResearchBook/
• The Four Dimensions of Tone of Voice: https://www.nngroup.com/articles/tone-of-voice-
dimensions/
• A successful Git branching model: https://nvie.com/posts/a-successful-git-branching-model/
• Semantic Versioning 2.0.0: https://semver.org/
• Conventional Commits: https://www.conventionalcommits.org/
• Google Conventions for Readable Specifications: https://specflow.org/gherkin/gherkin-
conventions-for-readable-specifications/
• Domain-Driven Architecture Diagrams: https://medium.com/nick-tune-tech-strategy-
blog/domain-driven-architecture- diagrams-139a75acb578
• Domain Storytelling and Requirement: https://domainstorytelling.org/#dst-requirements
• Domain Driven Design: Tackling Complexity in the Heart of Software
https://openpracticelibrary.com/perspective/domain-driven-design/
• Must-know HTML Tags for SEO and Digital Marketing: https://seranking.com/blog/html-
tags-in-seo/
• How to Write a User Story for an API Product: https://sameera17w.medium.com/how-to-
write-a-user-story-for-an-api-product- 7af6abd4ad2e
• Firebase App Distribution: https://firebase.google.com/docs/app-distribution
• Using PlantUML for Creating Clear and Concise Diagrams:
https://connect2grp.medium.com/using-plantuml-for-creating-clear-and-concise- diagrams-
2fc621529560
• Big Picture EventStorming: https://github.com/ddd-by-
examples/library/blob/master/docs/big-picture.md
• Design Level EventStorming: https://github.com/ddd-by-
examples/library/blob/master/docs/design-level.md
14/19 V1.0
13. ANEXOS
13.1. Anexo A. Estructura para la sección Objetivo del Estudiante (Student Outcome)
El curso contribuye al cumplimiento del Student Outcome ABET:
ABET – EAC - Student Outcome 2
Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos
proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos,
planifican tareas y cumplen objetivos.
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por
parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student
Outcome 2.
Criterio específico Acciones realizadas Conclusiones
Diseña soluciones en ingeniería
Jiménez Rosas, Arturo Eduardo
Fusce cursus dolor et nulla suscipit,
de software (productos,
TB1
sit amet ullamcorper nibh
procesos y/o servicios) que
Morbi vel tortor id eros dictum
vestibulum.
venenatis id ut dui.
Nam ornare massa eu lobortis
satisfagan necesidades
Mauris quis tellus sed nunc
porttitor.
específicas considerando el
hendrerit vehicula ac id mauris.
Nam ut erat feugiat libero pretium
impacto en salud pública,
Pellentesque volutpat tellus
semper at ac metus.
seguridad, bienestar, así como
non ligula blandit ullamcorper
Sed at eros dapibus, fermentum
factores globales, culturales,
quis sodales erat.
quam ut, bibendum lacus.
sociales, ambientales y
TB2
Curabitur eget orci eget urna varius
económicos
…
commodo.
Rodríguez Peña, Jorge Andrés
…
TB1
…..
Valida que el diseño de la
solución de software considere
aspectos en salud pública,
seguridad, bienestar, así como
factores globales, culturales,
sociales, ambientales y
económicos
Jiménez Rosas, Arturo Eduardo
TB1
Cras sed diam suscipit,
malesuada ex rutrum, fringilla
orci.
Vestibulum in nunc quis elit
suscipit sollicitudin.
TB2
…
TB1
Rodríguez Peña, Jorge Andrés
…..
Fusce mattis augue a nisl
bibendum, quis fringilla neque
scelerisque.
Vivamus commodo libero eget
venenatis imperdiet.
Etiam imperdiet quam
condimentum velit tempor
porttitor.
Suspendisse blandit nisl quis mauris
vehicula faucibus.
…
15/19
13.2. Anexo B. Estructura para el Informe de participación
El Final Project Participant Performance Report es un documento en word donde el Team Leader
resume la participación de cada integrante y la asigna a cada uno, una calificación entre 0 y 20
(según las alternativas especificadas: 20, 16, 13, 07 o 00).
Estructura del nombre de archivo: upc-pre-202520-1asi0665-<NRC>-<consultora>-
performance-<tp1/tf1> (.docx y .pdf)
Adjuntar el archivo en todas las entregas programadas junto al final Project.
Participant Performance Report
Nombre de Consultora Solvers Squad Nombre de Producto Health Advisor
Entrega TP1 Team Leader Jiménez Rosas, Arturo Eduardo
Ítem Estudiante Responsabilidades Cumplió
a tiempo
cumplió a
destiempo
cumplió
parcialmente
no
cumplió
(Cero)
Calificación
asignada
(20 / 16 /
13 / 07 / 0)
1 Jiménez
Rosas,
Arturo
Eduardo
Vivamus commodo
libero eget venenatis
imperdiet.
X 13
Etiam imperdiet
quam condimentum
velit tempor porttitor.
X
… …
Suspendisse blandit
nisl quis mauris
vehicula faucibus.
X
2 Rodríguez
Peña, Jorge
Andrés
Duis lacinia purus eu
urna euismod, at
auctor felis
pellentesque.
X 20
Duis porta lectus sit
amet tortor aliquam,
in dictum magna
ullamcorper.
X
… …
Praesent mattis arcu
ut nunc tempus
facilisis.
X
…
n Barrera
Robles, Luis
Miguel
No participó X 0
16/19 V1.0
13.3. Anexo C. Indicaciones para secciones que incluyen Videos
Sección Características del video Sobre el contenido Integración y entrega
About the
Team
Cantidad de videos: 1
Nomenclatura:
upc-pre-202520-1asi0572-<NRC>-<startup>-about-
the-team-sprint-<n>
Formato: .mp4
Duración: En función al contenido (considerar 5
minutos para la sección de retrospectiva del grupo
y 1 minuto por cada testimonio de miembro del
equipo).
Video que resume el proceso
de trabajo realizado,
incluyendo escenas de
sesiones de trabajo real del
equipo, complementando con
narración (voz en off) del
proceso. Incluye además el
testimonio ante cámara de
cada participante
describiendo actividades
realizadas, logro de outcomes
y desarrollo de competencias
alcanzados.
Subir el video en Microsoft
Stream/Clipchamp y en
YouTube.
Incluir redacción de
introducción a la sección,
resumiendo el proceso de
trabajo y los logros
alcanzados por los
miembros del requipo.
Adicionalmente, incrustar
el video en una sección
adecuada del Landing
Page. Seguir
especificaciones del
enunciado.
17/19
13.4. Anexo D. Errores típicos en la traducción y uso de términos para Ingeniería de Software
La competencia de comunicación efectiva juega un rol fundamental en los procesos de
Ingeniería de Software. El ingeniero de software debe comunicarse empleando códigos
apropiados de acuerdo con la audiencia a la que se dirige, sea a través de la preparación de
informes técnicos, presentaciones en proyectos colaborativos, demostraciones, entre otras
actividades. En todos los casos, debe validar los atributos de calidad antes de la entrega o
presentación, así como validar que el mensaje llegue satisfactoriamente.
La tabla a continuación resume los errores más comunes en la traducción de términos en el
área de ingeniería de software. En general, los errores de traducción se consideran errores de
comunicación y son objeto de penalización.
Término original Traducción
correcta
Traducción
incorrecta
Explicación
Library5 Biblioteca Librería Error común producto de
la semejanza fonética,
pero biblioteca (library) y
librería (bookstore)
tienen significados
diferentes.
Requirement6 Requisito Requerimiento Error común debido a la
semejanza fonética, sin
embargo, requisito
(requirement) y
requerimiento (request)
tienen diferente
significado.
Request7 Solicitud /
Petición /
Requerimiento
Requisito Consecuencia de la
traducción incorrecta de
requirement.
Application8 Aplicación Aplicativo Aplicativo en español no
existe como sustantivo.
Aplicativo es un
sustantivo solo en
portugués.
Elicit9 Obtener Elicitar Elicitar no existe en
español.
5 Vea la traducción de library en https://www.collinsdictionary.com/dictionary/english-spanish/library.
6 Vea la traducción de requirement en https://www.collinsdictionary.com/dictionary/english-spanish/requirement.
7 Vea la traducción de request en https://www.collinsdictionary.com/dictionary/english-spanish/request.
8 Vea la traducción de application en https://www.collinsdictionary.com/dictionary/english-spanish/application.
9 Vea la traducción de elicit en https://www.collinsdictionary.com/dictionary/english-spanish/elicit.
18/19 V1.0
También se considera un error el uso de forma oral o escrita de traducciones incorrectas
resultado de la mutación de términos originales en inglés, de uso típico en ingeniería de
software. Términos como deploy (desplegar), deployment (despliegue), test (probar/prueba,
según el contexto de uso), testing (pruebas) por ejemplo, son de uso típico en ingeniería de
software.
En la comunicación oral o escrita, en cualquier medio, solo se permite el uso de términos en
idioma original o la traducción correcta de los mismos. Al igual que el caso de traducción con el
término erróneo, no se admite el uso de mutaciones como por ejemplo deployar, testear,
comitear/commitear, entre otras. Dichos errores se consideran errores de comunicación son
objeto de penalización.
También se considera un error de comunicación el uso indiscriminado de términos como
apartado10 para evitar referirse a elementos identificables con un término más adecuado, tanto
en descripción de la interfaz de usuario (en reemplazo de elementos reconocibles como view,
section, dialog, toolbar, sidebar entre otros), como componentes de artefactos elaborados (p.ej.
en reemplazo de términos como capítulo, anexo, sección, cuadro, tabla).
Igualmente se considera un error de comunicación, el uso del término metodología11 para referirse
a métodos, marcos de trabajo, técnicas, aproximaciones u otros conceptos similares (p.ej. Scrum
no es una metodología, es un marco de trabajo ágil. Referirse a Scrum como metodología es un
error).
