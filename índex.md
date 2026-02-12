Vídeo explicativo: https://youtu.be/jbVBU_uOZvM 

Introducción
¿Tu sitio es inclusivo? Por qué seguir las reglas de accesibilidad no es suficiente.
Como estrategas digitales, debemos saber que una "luz verde" en un validador automático no es sinónimo de un sitio inclusivo, en realidad esto es apenas el punto de partida. Para un usuario con ceguera total, un sitio que aprueba dichos tests puede seguir siendo un "laberinto" indescifrable si los contenidos no textuales carecen de alternativas reales (Acosta et al., 2016). La accesibilidad no es un checklist de código; es la garantía de que cualquier persona, sin importar su condición, pueda percibir, comprender e interactuar con la web de manera efectiva y digna.

1. Más allá del checklist: Por qué las pautas WCAG no son suficiente.
Las guías del W3C (World Wide Web Consortium) proporciona cuatro pilares fundamentales: las WCAG (para contenidos), las ATAG (para herramientas de autor), las UAAG (para navegadores) y, crucialmente, las especificaciones ARIA (Accessible Rich Internet Applications), que permiten dotar de semántica a los elementos HTML.
Sin embargo, estas normas no garantizan una experiencia de usuario óptima. Investigaciones de Engel et al. (2019) advierten que a menudo son demasiado generales y fallan al abordar elementos complejos como gráficos de dispersión o barras. Los algoritmos pueden detectar la falta de una etiqueta, pero no pueden juzgar si la información es comprensible para un ser humano.
Saqr y Bhattacherjee (2012) describen las directrices de la W3C como "insuficientes para satisfacer las necesidades de las personas con discapacidad visual" específica.

2. La accesibilidad es, en realidad, usabilidad para todos.
Como señalan Shera et al. y Mazalu & Cechich, la accesibilidad debe ser agnóstica a factores como la edad, el género, el contexto cultural, la ubicación geográfica o la alfabetización informática. Tampoco es un diseño "especial" para una minoría, sino que ayuda a elevar la calidad del producto para todos.
Un diseño accesible es, por lo tanto, un diseño más usable. Los beneficios se extienden a una persona mayor con visión disminuida, a un usuario en un entorno con exceso de iluminación que afecta su pantalla, o a alguien que intenta navegar en un dispositivo móvil bajo condiciones de red limitadas. La accesibilidad elimina barreras situacionales y técnicas para el 100% de la audiencia.

3. El dilema de la arquitectura: No basta con que el código sea correcto.
Existe una conexión entre la Arquitectura de la Información y la usabilidad. Un código HTML puede ser semánticamente perfecto, pero tener una estructura de la información caótica, volviéndolo inutilizable.
Debemos entender que, para un usuario con ceguera total, la Arquitectura de la Información es la interfaz. Si la jerarquía de los datos no es lógica, el contenido se vuelve inaccesible. La presentación y organización de la información son tan críticas como el código mismo; sin una estructura coherente, la tecnología asistiva solo servirá para leer un caos.

4. El poder de la refactorización: Reestructurando desde la raíz.
Cuando un sistema existente presenta barreras, la solución no es un parche superficial, sino una refactorización de raíz. Según Garrido et al. (2014), refactorizar implica reestructurar el código fuente para mejorar su calidad interna sin alterar su comportamiento externo. El objetivo es permitir el acceso a información antes bloqueada y eliminar obstáculos en la interacción con contenidos ya existentes.
Existen dos formas de abordar el problema: crear una aplicación separada o integrar la accesibilidad en la arquitectura actual. Mientras que la primera opción suele sacrificar funcionalidad, la segunda es el estándar de oro, aunque exige un equilibrio técnico para no comprometer la usabilidad de los usuarios sin discapacidad.
Para terminar de explicar este punto, se puede citar a Harold (2018) quien define la refactorización como un proceso orientado a "reestructurar el código fuente... para ampliar sus artefactos de software o para cambiar y mejorar su estructura interna".

5. El camino a la inclusión: Un proceso de rediseño de 5 etapas.
En el trabajo de tesis de la Licneciatura en TEcnologías Computacionales de la Universidad Veracruzana (Xalapa, Veracruz, México) se propuso un marco de trabajo lineal capaz de guíar al desarrollador en el resideseño de sistemas inaccesibles, enfocado en usuarios con discapcidad visua total:
1. Capacitación del equipo de desarrollo para conocer los estándares (WCAG, ARIA) y sensibilización sobre las necesidades reales del usuario.
2. Exploración inicial: Diagnóstico del estado actual del sistema y su contexto de uso con herramientas automáticas.
3. Evaluación: Identificación de barreras mediante la evaluación con usuarios reales y heurísticas especializadas con ayuda de expertos.
4. Análisis: Determinación de soluciones técnicas y arquitectónicas basadas en los hallazgos.
5. Recodificación: Implementación de cambios en el código y la arquitectura para asegurar una navegación fluida.

6. ¿Por qué es importante proponer mejoras?
La inclusión digital no es una opción técnica, es un imperativo de derechos humanos y dignidad. Los Objetivos de Desarrollo Sostenible de la ONU (ODS 4.5) son claros: para 2030 debemos eliminar las disparidades y asegurar el acceso igualitario en todos los niveles de enseñanza y formación profesional para las personas con discapacidad.
Como líderes en tecnología, cada línea de código que escribimos es una decisión que afecta a los demás: podemos construir puentes o levantar muros. Al iniciar tu próximo proyecto, la pregunta no es si cumple con las reglas, sino: ¿estás abriendo las puertas de la sociedad del conocimiento o estás dejando a alguien afuera?

Marco teórico
Vídeo explicativo: https://youtu.be/avg1NJLb4Xs 

Como se mencionó en la introducción, la usabilidad es un atributo de calidad esencial que coexiste con la accesibilidad y la ingeniería de software para lograr sitios web inclusivos.
A continuación, se presnetna algunos términos importantes:

1. Accesibilidad
Se puede entender como “el grado en el que todas las personas pueden utilizar un objeto, visitar un lugar o acceder a un servicio, independientemente de sus capacidades técnicas, cognitivas o físicas” (Graue, 2022).
Para Lawton (2019), en el ámbito web la accesibilidad significa que personas con discapacidades pueden percibir, comprender, navegar e interactuar con la Web, incluyendo discapacidades auditivas, cognitivas, neurológicas, físicas, del habla y visuales. Sin embargo, es importante aclarar que el término accesibilidad *no se limita a las discapacidades*, por lo contrario, tiene impacto en usuarios de dispositivos con pantallas pequeñas, diferentes modos de entrada, personas mayores cuyas habilidades cambian con la edad, personas con “discapacidades temporales” o con “limitaciones por su ubicación” y personas con conexión lenta a Internet o que tienen ancho de banda limitado o costoso.
 
2. Usabilidad
Allanwood y Beare (2021) indican que es una medida de la facilidad con la que un usuario puede, o no, lograr un objetivo. Es subjetiva (al depender del usuario), sin embargo, la definición anterior se puede complementar con la de Nielsen (2012) quien indica que es un atributo de calidad que evalúa la facilidad de uso de las interfaces de usuario y la divide en cinco componentes los cuales se enlistan a continuación:
1. Capacidad de aprendizaje (facilidad con la cual los usuarios pueden realizar tareas básicas desde el primer uso). 
2. Eficacia (rapidez con la que se pueden realizar las tareas). 
3. Memorización (capacidad de dominio que tiene un usuario al hacer uso repetido de una interfaz). 
4. Errores (la facilidad con la cual un usuario puede recuperarse de los mismos durante la interacción). 
5. Satisfacción (evalúa qué tan agradable es utilizar una interfaz).
 
3. Sitios web
Según la Real Academia Española, (RAE, 2022) un sitio web es un “Conjunto de páginas web agrupadas bajo un mismo dominio de internet”. 
Berners-Lee (s.f.), define que una página web está compuesta de tres tecnologías: 
Un lenguaje de marcado de hipertexto el cual le da formato a la información presentada (HMTL), para Carles (1994) este lenguaje incluye la estructura, el formato de representación, el origen y el destino de saltos hipertextuales. 
La segunda tecnología es un Identificador Uniforme de Recursos (URI) el cual representa una dirección única que identifica a cada recurso en la web; en la definición de la RAE (2022) este identificador es manejado como “dominio de internet”. 
Finalmente, también hace uso de HTTP el cual sirve para recuperar y transportar los datos en la red del internet.
 
4. Internet
Internet es considerado la red de redes debido a que es la conexión de diversos servidores. Internet es un grupo de ordenadores los cuales transfieren datos entre sí. También se pueden resaltar algunos datos que proporciona Millán (2015) tales como la denominación ARPANET que en un principio recibió el proyecto de internet, iniciando operaciones en 1969 con el apoyo del Pentágono de Estados Unidos de Norteamérica y la Universidad de California; finalmente, en 1989, desapareció ARPANET, sin embargo, ya había diferentes redes creadas a lo largo del mundo. Es importante mencionar que en ese mismo año Tim Berners-Lee presenta el sistema de hipertexto compartido y da un primer acercamiento a la WWW, la cual según Malkin (1993) como se citó en Carles (1994) sigue el modelo cliente-servidor, un paradigma donde los clientes realizan peticiones de servicios de acuerdo y los servidores las atienden. Estos datos se representan en forma de hipertexto y desde 1989 se transmiten mediante el protocolo HTTP viajando a través de Internet. En estos hipertextos se pueden compartir textos, imágenes, sonidos, vídeos y una gran variedad de tipos MIME.
 
5. Normas de accesibilidad en sitios web
Como se indicó previamente, uno de los elementos fundamentales de la arquitectura web, es el lenguaje de marcas HTML, y a su vez es el factor más importante para proveer accesibilidad a los sitios web, debido a que contiene la estructura y la información que se presenta en los sitios web. En este sentido, el W3C, organismo creado por Tim Berners-Lee y encargado de “desarrollar normas de alta calidad a partir de las contribuciones de los miembros del W3C, el personal y la comunidad en general” (W3C, 2023) tiene un grupo encargado de estudiar la accesibilidad en sitios web y proponer normativas para el desarrollo de sistemas web accesibles. Este grupo se denomina WAI, mencionado en el apartado “antecedentes” de este documento, el cual propone las siguientes normativas: las Pautas de Accesibilidad para el Contenido Web (WCAG), las Pautas de Accesibilidad para las Herramientas de Creación de Contenidos (ATAG), las Pautas de Accesibilidad para el Agente de Usuario (UAAG) y las especificaciones WAI-ARIA. A continuación, se describen cada una de ellas.
 
5.1 WCAG
Las Pautas de Accesibilidad para el Contenido Web (WCAG) “ofrecen un estándar para satisfacer las necesidades de personas, organizaciones y empresas a nivel internacional en cuanto a contenido web accesible para personas con discapacidad” (Lawton, 2018). Según Lawton (2018) son aplicables tanto a información natural (textos, imágenes y sonidos) como código o marcado (estructura o presentación de la información).
Si bien existen diferentes versiones de las pautas WCAG, esta investigación se concentra en la versión 2.1 publicada en junio del 2018. De acuerdo con Lawton (2018) esta versión extendida comparte los criterios de conformidad que tiene la versión 2.0 publicada en 2008. Además, ambas versiones están compuestas de entre 12 y 13 pautas agrupadas bajo cuatro principios: perceptible, operable, comprensible y robusto, cada pauta incluye criterios de conformidad comprobables y clasificados en tres niveles: A, AA y AAA. Finalmente, Lawton (2018) también afirma que las WCAG 2.0 están aprobadas como un estándar ISO: ISO/IEC 40500:2012. A continuación, se enlistan las pautas y su descripción:
1.1. Alternativas textuales: Se deben proporcionar alternativas textuales para cualquier contenido que no sea texto, de modo que pueda cambiarse a otras formas que la gente necesite, como letra grande, braille, voz, símbolos o un lenguaje más sencillo.
1.2. Medios basados en el tiempo: Se deben proporcionar alternativas para los medios basados en el tiempo. 
1.3. Adaptables: Se deben crear contenidos que puedan presentarse de diferentes maneras (por ejemplo, con una maquetación más sencilla) sin perder información ni estructura. 
1.4. Distinguibles: Se debe facilitar a los usuarios la visualización y audición de los contenidos, por ejemplo, separando el primer plano del fondo. 
2.1. Accesible desde el teclado: Se debe hacer que toda la funcionalidad esté disponible desde un teclado. 
2.2. Tiempo suficiente: Se debe proporcionar a los usuarios tiempo suficiente para leer y utilizar los contenidos. 
2.3. Convulsiones y reacciones físicas: No se deben diseñar contenidos que pueden provocar convulsiones o reacciones físicas. 
2.4. Navegable: Se deben proporcionar formas de ayudar a los usuarios a navegar, encontrar contenidos y determinar dónde se encuentran. 
2.5. Modalidades de entrada: Se debe facilitar a los usuarios el manejo de las funcionalidades a través de diversas entradas más allá del teclado. 
3.1. Legible: Se debe hacer que el contenido del texto sea legible y comprensible. 
3.2. Predecible: Se debe hacer que las páginas Web aparezcan y funcionen de manera predecible. 
3.3. Ayuda a la introducción de datos: Se debe ayudar a los usuarios a evitar y corregir errores. 
4.1. Compatibilidad: Se debe maximizar la compatibilidad con los agentes de usuario actuales y futuros, incluidas las tecnologías de asistencia.
 
2.5.2 ATAG
Las pautas ATAG “explican cómo hacer accesibles las herramientas de creación de contenido web para que las personas con discapacidad y cómo crear contenidos web más accesibles ... que se ajusten a las Pautas de Accesibilidad al Contenido en la Web (WCAG)” (Lawton, 2020). Lawton (2020) también describe dichas pautas como agnósticas a la tecnología y fueron publicadas en el año 2015, haciendo referencia a la versión 2.0 de las WCAG, por otro lado, son dirigidas a desarrolladores de herramientas de autor (editores HTML del tipo WYSIWYG, sistemas CMS y LMS, creadores de sitios web sin código, software que convierte documentos a tecnologías de contenido web, herramientas de creación multimedia o sitios web que permiten a los usuarios añadir contenidos (blogs, foros en línea y redes sociales). Finalmente, según Lawton (2020) las pautas ATAG son una norma técnica y explican cómo hacer accesible la propia herramienta de autor y cómo dicha herramienta de autor ayuda a los autores a producir contenidos accesibles. En ese sentido, están organizadas por niveles: Los principios (organización de alto nivel para las pautas), las pautas (el marco y los objetivos para los criterios de éxito) y los criterios de éxito (requisitos de accesibilidad comprobables en tres niveles: A, AA, AAA). En ese sentido, las pautas ATAG contienen ocho principios, cuatro están dirigidos a cómo hacer accesibles las herramientas de autor y cuatro están dirigidas a cómo ayudar a producir contenidos accesibles, y un total de veinticuatro pautas. 
 
2.5.3 UAAG
Según Spellman et al (2016) las Directrices UAAG son una especificación para crear agentes de usuario accesibles para las personas con discapacidad, se pueden clasificar como agentes de usuario a los navegadores, extensiones de navegadores, reproductores multimedia, lectores y otras aplicaciones que reproducen contenidos web.
Citando nuevamente a Spellman et al (2016) estas pautas se enfocan en cubrir las necesidades de accesibilidad que es mejor satisfacer en el agente de usuario que en el contenido web, esto también beneficia a la comunicación entre el agente de usuario y las tecnologías de apoyo (software que algunas personas con discapacidad utilizan para satisfacer sus necesidades). UAAG 2.0 se desarrolló para ayudar a que las futuras generaciones de navegadores web sean más accesibles, para proporcionar información alternativa basada en la tecnología y la plataforma del usuario, y para alinearse con WCAG 2.0 y ATAG 2.0. Estas pautas están compuestas en cinco principios (perceptible, operable, comprensible, acceso programático y especificaciones y convenciones) entre las cuales se dividen veintiséis pautas.
 
2.5.4 ARIA
Las pautas ARIA definen, según Nurthen et al (2022), cómo hacer contenidos y aplicaciones web más accesibles para las personas con discapacidad y se especializa en contenidos dinámicos y controles avanzados de interfaz de usuario desarrollados con HTML, JavaScript y tecnologías afines. Específicamente proporciona un marco para añadir atributos que identifiquen las características de interacción con el usuario, cómo se relacionan entre sí y su estado actual.
La versión 1.2 de las pautas WAI-ARIA agrega características que completan el modelo de accesibilidad HTML + ARIA. En este sentido es conveniente resaltar que la versión 1.0 de estas pautas fue lanzada el 20 de marzo de 2014, la versión 1.1 el 14 de diciembre de 2017 y la versión 1.2 está en desarrollo actualmente.
 
2.6 Usuarios con discapacidad visual
Los usuarios con discapacidad visual se definen y caracterizan a través de su perfil médico, sus capacidades de interacción técnica y las barreras que enfrentan en el entorno digital.
• Baja Visión: Se define por una agudeza visual inferior a 6/18 pero igual o mejor que 3/60, o una pérdida del campo visual correspondiente inferior a 20°.
• Ceguera: Se define por una agudeza visual inferior a 3/60, o una pérdida del campo visual inferior a 10°.
Para superar estas barreras, los usuarios utilizan diferentes tecnologías de asistencia según su clasificación:
• Usuarios con ceguera (discapacidad visual total): Utilizan principalmente lectores de pantalla, un software que les permite interactuar con el ordenador mediante audio o braille. Esto requiere que los sitios web implementen técnicas modernas de usabilidad y accesibilidad en su código.
• Usuarios con baja visión: Requieren ayudas visuales, específicamente la ampliación de la interfaz gráfica mediante el uso de magnificadores.
 
2.7 Procesos de desarrollo de software
El desarrollo de una guía de rediseño implica la definición de las etapas que componen este proceso a partir del análisis de metodologías o ciclos de desarrollo de software más comunes en la actualidad. Lo anterior con el objetivo de apegar las etapas de la guía propuesta a las etapas de los procesos más conocidos hasta el momento.
Los Procesos de desarrollo de software se definen no como una simple ejecución técnica, sino como un conjunto estructurado de actividades intelectuales y creativas.
El proceso de software se entiende como un conjunto de actividades orientadas al desarrollo de un producto de software. 
Para Sommerville (2005) un proceso de software es un conjunto de actividades que buscan desarrollar un producto de software, esto implica la ampliación y modificación de los sistemas existentes, dichos procesos de desarrollo de software son complejos, intelectuales y creativos, a su vez, dependen de las decisiones y juicios de las personas. Según Sommerville (2005) estos procesos han mejorado con el fin de explotar las capacidades del personal y las características específicas de los sistemas. En ese sentido, el uso de los procesos depende del sistema, para los sistemas críticos se recomienda un proceso muy estructurado mientras para aquellos que cambian rápidamente se recomienda un proceso flexible, ágil y eficaz. Sin importar el proceso de software, Sommerville (2005) indica que existen algunas actividades fundamentales y comunes en todos los procesos de software: especificación del software, diseño e implementación del software, validación del software y evolución del software.
Existen representaciones abstractas de estos procesos (modelos) que proporcionan información parcial y pueden adaptarse. Se destacan tres paradigmas principales: el modelo de cascada, el desarrollo evolutivo y la ingeniería de software basada en componentes.
La definición de estos procesos tiene un objetivo práctico: establecer las etapas para una guía de rediseño. El análisis de estos ciclos de vida busca alinear las etapas de la refactorización propuesta con los procesos de ingeniería más conocidos, asegurando que la integración de la accesibilidad y usabilidad siga un flujo profesional y validado.

Estado del Arte
Vídeo explicativo: https://youtu.be/eDde-cfE1LU

Aquí se ve una revisión sistemática de la literatura científica de los últimos diez años (2012-2022), centrada en la accesibilidad web, la refactorización y el rediseño de sitios para usuarios con discapacidad.  
Para lo anterior se utilizó la siguiente cadena de búsqueda en Scopus: (*desing OR *factoring OR *recoding OR *engineering) AND (accessib* OR Usab*) AND (disab* or impair* OR discapa*).

De una búsqueda inicial de 5,483 artículos, se seleccionaron y analizaron 51 documentos clave. A continuación, se presenta un resumen estructurado por los tópicos principales identificados en la investigación:
1. Evaluación de la Accesibilidad
La evaluación se divide en dos frentes complementarios:
• Herramientas Automáticas: Se analizaron herramientas como WAVE, TAW y MAUVE++. Mientras WAVE es popular, TAW tiene mejor desempeño evaluando JavaScript y MAUVE++ sobresale en páginas dinámicas. Otras herramientas mencionadas incluyen AChecker (que permite ver el código HTML del error) y extensiones como Axe y Hera.
    ◦ Limitación crítica: Las herramientas automáticas son de bajo costo pero no inteligentes; requieren supervisión experta y no sustituyen el juicio humano.
• Evaluación con Usuarios: Se considera fundamental para garantizar el acceso real. Se destacan métodos como ACCESSA (enfoque centrado en usuario y expertos), el protocolo Thinking Aloud (pensar en voz alta), estudios etnográficos y el uso de cuestionarios estandarizados como SUS (Escala de Usabilidad del Sistema) y UEQ (Cuestionario de Experiencia de Usuario) para medir la satisfacción y eficacia.

2. Normativas y Directrices
El marco normativo sigue regido por el consorcio W3C. Se identifican cuatro estándares principales: WCAG (contenido), ATAG (herramientas de autor), UAAG (navegadores) y WAI-ARIA (semántica para contenido dinámico).
Dichas pautas suelen ser difíciles de integrar en el flujo de trabajo diario. Por ello, surgen propuestas para crear listas de comprobación específicas para desarrolladores y "prototipos de pautas" con ejemplos de código y buenas prácticas.

3. Tecnologías de Asistencia: Lectores de Pantalla
Los lectores de pantalla (screen readers) son esenciales para usuarios con ceguera, traduciendo lo visual a audio.
• Clasificación: Se dividen en integrados (VoiceOver, TalkBack) y externos (JAWS, NVDA).
• Requisitos técnicos: Para que funcionen, los sitios deben usar correctamente HTML5 semántico y etiquetas WAI-ARIA, además de garantizar la navegación completa por teclado.

4. Metodologías de Diseño y Desarrollo
La investigación muestra cómo la accesibilidad se integra en el ciclo de vida del software:
• Enfoques de Diseño: Se contrastan el Diseño Universal (diseño único apto para todos bajo 7 principios) y el Diseño Centrado en el Usuario (DCU), que involucra al usuario final en todas las etapas.
• Ciclos de Desarrollo: Se observa una integración de la accesibilidad tanto en metodologías tradicionales (Cascada, V-Model) pero se presta mayor enfoque a las metodologías Ágiles (Scrum, RAD) porque favorecen la refactorización incremental y la adaptación rápida ante barreras detectadas.
• Elicitación de Requisitos: Se proponen técnicas para capturar requisitos de accesibilidad desde el inicio, como el uso de UserX Stories (historias de usuario extendidas), catálogos de requisitos no funcionales y listas de comprobación de conflictos.

5. Recodificación y Refactorización (Tecnologías)
Esta sección aborda cómo implementar técnicamente la accesibilidad mediante la recodificación, ya sea manual o asistida:
• Frameworks de JavaScript: Se analizan tecnologías modernas como React, Angular y Vue. Se destacan librerías específicas que facilitan la accesibilidad, como React ARIA, Chakra UI, Material UI y Headless UI, las cuales ofrecen componentes pre-construidos que cumplen con WAI-ARIA.
• Frameworks CSS: Se evalúan Tailwind CSS y Bootstrap. Ambos incluyen clases utilitarias para ocultar contenido visualmente pero mantenerlo accesible para lectores de pantalla (clases visually-hidden o sr-only).
• Linters (Análisis estático): Herramientas cruciales para detectar errores de accesibilidad en el código mientras se escribe, antes de compilar. Se destacan ESLint, Axe Accessibility Linter (para VS Code) y Webhint. Estas herramientas educan al desarrollador y previenen errores comunes desde etapas tempranas.
En conclusión, el estado del arte revela una transición desde la simple evaluación post-desarrollo hacia una integración proactiva de la accesibilidad mediante el uso de frameworks modernos, herramientas de análisis de código (linters) y metodologías de diseño centrado en el usuario.
