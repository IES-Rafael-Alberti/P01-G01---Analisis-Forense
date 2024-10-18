# Development of a Forensic Analysis Methodology
![Portada](/Assets/portada.png)

<br>

# ÍNDICE
- Introducción
- Investigación de normas y estándares forenses.
- Comparativa de normas y estándares
  - Análisis Comparativo
    - Objetivo
    - Alcance
    - Contenido
    - Aplicación
- Desarrollo de metodología propia
  - Adquisición de evidencia digital. (ISO/IEC 27037)
  - Preservación y almacenamiento de la evidencia  (RFC 3227).
  - Análisis de las evidencias (UNE 71506:2013).
  - Documentación de hallazgos (UNE 71506:2013).
  - Presentación de resultados (UNE 71506:2013).
- Resumen
- Fuentes

<br>

# Introducción
Hemos asumido el compromiso de desarrollar una metodología de análisis forense propia que refuerce la calidad y precisión de nuestros servicios de análisis de incidentes.

Nuestro objetivo es crear un proceso robusto y metódico que abarque desde la adquisición hasta la presentación de evidencias digitales, garantizando que cada paso cumpla con los más altos estándares de integridad y credibilidad.

Para ello, investigaremos y adaptamos normas y estándares forenses reconocidos, asegurando que nuestra metodología se alinee con las mejores prácticas internacionales y ofrezca a nuestros clientes resultados fiables y consistentes.

<br>

# Investigación de normas y estándares forenses.

En el ámbito de la seguridad de la información y el análisis forense digital, existen diversas normas y estándares que proporcionan directrices fundamentales para la recopilación, manejo y análisis de evidencias digitales. Entre estas, destacan tres normas de particular relevancia:

## ISO/IEC 27037

La ISO/IEC 27037 es una norma internacional que proporciona directrices para la identificación, recolección, adquisición y preservación de evidencias digitales potenciales. Esta norma está diseñada para optimizar el valor probatorio de las evidencias digitales en investigaciones forenses.

**Objetivo.**

El propósito principal de esta norma es establecer un marco estandarizado para el manejo de evidencias digitales, asegurando su validez y admisibilidad en procesos judiciales. Busca facilitar el intercambio de evidencias digitales entre diferentes jurisdicciones y proporcionar orientación sobre mejores prácticas en el tratamiento de estas evidencias.

**Estructura**.

- Identificación de evidencias digitales potenciales
    
- Recolección de dispositivos físicos que pueden contener evidencias
    
- Adquisición de datos digitales
    
- Preservación de la integridad de las evidencias
    

Además, se definen dos **roles** especializados:

- Digital Evidence First Responders (DEFR)
    
- Digital Evidence Specialists (DES)
    

**Aplicabilidad.**

La ISO/IEC 27037 es aplicable a una amplia gama de dispositivos y escenarios, incluyendo medios de almacenamiento digitales, dispositivos móviles y personales, sistemas de navegación, cámaras digitales y de video, ordenadores conectados a redes, así como redes basadas en protocolos TCP/IP. Su enfoque integral permite su utilización en diversas situaciones donde se requiera la gestión adecuada de evidencias digitales.

**Importancia**.

Esta norma es fundamental porque asegura que la evidencia digital se recopila de manera válida para su uso legal. Proporciona un estándar internacional que mejora la credibilidad y admisibilidad de las evidencias en procesos judiciales. Además, facilita la colaboración entre diferentes jurisdicciones en casos que involucran evidencias digitales y establece buenas prácticas para profesionales en el campo de la informática forense.

En resumen, la ISO/IEC 27037 es una herramienta esencial para garantizar la integridad y validez de las evidencias digitales en investigaciones forenses, proporcionando un marco estandarizado que puede ser utilizado internacionalmente en contextos legales y de seguridad informática.

## ISO/IEC 27042

La ISO/IEC 27042 es una norma que proporciona un marco para las directrices y posterior interpretación de las evidencias electrónicas. Establece cómo un perito debe abordar el análisis y la interpretación de evidencias digitales en investigaciones forenses.

**Objetivo**. El objetivo principal de esta norma es proporcionar orientación sobre cómo realizar el análisis e interpretación de evidencias digitales potenciales en incidentes de seguridad. Busca identificar y evaluar aquellas evidencias que pueden ayudar a comprender el incidente, asegurando que el proceso sea válido, reproducible y repetible.

**Estructura**. La norma se estructura en torno a varios elementos clave:
- Selección y justificación de métodos de análisis
    
- Relación entre la evidencia y el método utilizado
    
- Competencia y proficiencia del equipo investigador
    
- Documentación y registro del proceso de análisis
    
- Marco común para el manejo de incidentes de seguridad
    

**Aplicabilidad**. La ISO/IEC 27042 es aplicable en:

- Investigaciones forenses digitales
    
- Análisis de incidentes de seguridad informática
    
- Procesos judiciales que involucren evidencias digitales
    
- Desarrollo de nuevos métodos de análisis forense digital
    

**Importancia**. La importancia de esta norma radica en varios aspectos:

- Establece un estándar común para el análisis e interpretación de evidencias digitales
    
- Mejora la credibilidad y admisibilidad de las evidencias en procesos legales
    
- Proporciona una base para la implementación de nuevos métodos de análisis
    
- Asegura que las opiniones de los investigadores estén claramente separadas de los hechos
    
- Enfatiza la importancia de la competencia y formación continua de los analistas forenses
    

En resumen, la ISO/IEC 27042 es fundamental para garantizar la calidad, fiabilidad y validez de los análisis forenses digitales, proporcionando un marco estandarizado que puede ser utilizado tanto en contextos legales como en investigaciones de seguridad informática.

## RFC 3227

La RFC 3227 es una guía de alto nivel que establece directrices para la recolección y archivo de datos relacionados con intrusiones y evidencias digitales en incidentes de seguridad. Esta norma está diseñada principalmente para administradores de sistemas e investigadores de incidentes.

**Objetivo.** Proporcionar orientación sobre cómo recopilar y archivar evidencias relevantes ante un incidente de seguridad, de manera que puedan ser admisibles en procesos judiciales.

**Estructura.** La norma aborda:

*   Principios fundamentales durante la recolección de evidencia, incluyendo consideraciones de privacidad y legales.
    
*   El proceso de recolección, enfatizando la transparencia y proporcionando pasos detallados.
    
*   El proceso de archivo, incluyendo la cadena de custodia y las mejores prácticas para el almacenamiento de evidencias.
    

**Aplicabilidad.** La RFC 3227 es útil para:

*   Administradores de sistemas e investigadores de incidentes de seguridad.
    
*   Formulación de procedimientos de recopilación de evidencias en organizaciones.
    
*   Preparación para posibles procesos judiciales relacionados con incidentes de seguridad.
    

**Importancia.** La norma es fundamental porque:

*   Facilita la trazabilidad del atacante al proporcionar métodos correctos de recopilación de evidencias.
    
*   Aumenta la probabilidad de que las evidencias sean admitidas en procesos judiciales.
    
*   Ayuda a mantener la integridad de las evidencias durante todo el proceso de investigación.
    
*   Proporciona una base sólida para que las organizaciones desarrollen sus propios procedimientos detallados y específicos.
    

En resumen, la RFC 3227 es crucial para asegurar que la recopilación y manejo de evidencias digitales se realice de manera sistemática, transparente y legalmente admisible, lo cual es esencial en la investigación de incidentes de seguridad y en posibles procesos legales subsecuentes.

## UNE 71506:2013

La norma UNE 71506:2013 establece la metodología para el análisis forense de evidencias electrónicas. Esta norma complementa a la serie UNE 71505 y se enfoca específicamente en el proceso de análisis forense dentro del ciclo de gestión de evidencias electrónicas. Algunos aspectos clave de la norma son:

**Objetivo.** Define el proceso de análisis forense de evidencias electrónicas, proporcionando una metodología estandarizada para su preservación, adquisición, documentación, análisis y presentación.

**Estructura.** La norma se divide en varias fases principales:

1.  **Preservación.** Enfocada en mantener la validez y confiabilidad de las evidencias originales. Incluye procedimientos para el almacenamiento seguro y manejo adecuado de las evidencias.
    
2.  **Adquisición.** Detalla el proceso de clonado a bajo nivel de los datos originales, considerando diferentes escenarios (sistemas encendidos o apagados).
    
3.  **Documentación.** Establece la necesidad de documentar todo el procedimiento desde el inicio del análisis hasta la entrega del informe pericial. Incluye la documentación de procesos, herramientas utilizadas y la cadena de custodia.
    
4.  **Análisis.** Describe las tareas y procesos para analizar las evidencias, incluyendo:
    
    *   Recuperación de ficheros borrados
        
    *   Estudio de particiones y sistemas de archivos
        
    *   Análisis del sistema operativo
        
    *   Estudio de la seguridad implementada
        
    *   Análisis detallado de los datos obtenidos
        
5.  **Presentación.** Guía la elaboración del informe pericial, enfatizando la necesidad de usar un lenguaje comprensible para un público no técnico.
    

**Aplicabilidad.** La norma es aplicable a cualquier organización, independientemente de su tamaño o actividad, así como a profesionales competentes en el ámbito del análisis forense digital.

**Importancia.** Contribuye a la estandarización y sistematización de la metodología de análisis forense, especialmente en países de habla hispana. Aumenta la probabilidad de que las evidencias electrónicas sean admitidas en procedimientos legales al seguir un proceso riguroso y estandarizado.

Esta norma es fundamental para garantizar la calidad, fiabilidad y admisibilidad legal de las evidencias electrónicas en investigaciones forenses digitales.

<br>

# Comparativa de normas y estándares

Para realizar una selección de las normas que usaremos en nuestra metodología, es conveniente comparar las normas anteriormente para ver cuales nos pueden ser más útiles. En esta comparativa es importante tener en cuenta el objetivo, el alcance el contenido y la aplicación de cada norma.

## Análisis Comparativo

**Objetivo**

*   **ISO/IEC 27037 y RFC 3227**.Ambas normas se enfocan en la recolección y preservación de evidencia digital, asegurando su integridad y admisibilidad en investigaciones legales. ISO/IEC 27037 ofrece un marco amplio, mientras que RFC 3227 brinda recomendaciones prácticas para incidentes de seguridad.
    
*   **UNE 71506.** Se especializa en procedimientos técnicos para el análisis forense de sistemas de información, aplicando herramientas avanzadas para extraer información relevante.
    
*   **ISO/IEC 27042.** Complementa a la ISO/IEC 27037 al centrarse en el análisis e interpretación de la evidencia digital, proporcionando pautas sobre cómo evaluar datos, reconstruir eventos y presentar información de manera clara y objetiva.
    
**Alcance**

*   **ISO/IEC 27037.** Se centra en la recolección y manejo de evidencia digital en diversos entornos. Cubre exhaustivamente desde la identificación hasta la preservación de evidencia en múltiples plataformas, asegurando la integridad y admisibilidad de la evidencia en procesos legales.
    
*   **RFC 3227.** Enfocada en respuestas a incidentes críticos, prioriza la captura de datos volátiles y minimiza la alteración de evidencia. Proporciona guías prácticas para la recolección rápida y efectiva de evidencia digital en situaciones de emergencia.
    
*   **UNE 71506.** Especializada en el análisis forense de sistemas de información complejos en entornos empresariales. Va más allá de la preservación, ofreciendo técnicas específicas para analizar, interpretar y documentar pruebas admisibles en tribunales o investigaciones corporativas.
    

*   **ISO/IEC 27042.** Se enfoca en el análisis y evaluación de evidencia digital ya recolectada. Proporciona directrices para interpretar evidencia, aplicar métodos de análisis según el tipo de incidente y generar informes para investigaciones o litigios.


**Contenido**

*   **ISO/IEC 27037.** Ofrece directrices sobre identificación, recolección y preservación de evidencia digital, asegurando su admisibilidad legal. Incluye métodos para mantener la cadena de custodia, recomendaciones sobre herramientas forenses y gestión de equipos multidisciplinarios.
    
*   **RFC 3227.** Proporciona un enfoque práctico con listas de verificación para la recolección en emergencias. Prioriza tipos de evidencia y detalla cómo preservar datos en sistemas comprometidos, enfatizando la documentación para garantizar la validez.
    
*   **UNE 71506.** Presenta procedimientos técnicos exhaustivos para el análisis forense, incluyendo recuperación de datos borrados y análisis de tráfico de red. Se centra en la integridad de la evidencia y la preparación de información para auditorías o tribunales.
    

*   **ISO/IEC 27042.** Se centra en el análisis e interpretación de evidencia digital, ofreciendo un marco para evaluar la validez de los datos y reconstruir incidentes. Incluye pautas para generar informes claros y objetivos para audiencias técnicas y legales.
