##############################
# PROMPT 1: Generación de User Stories
##############################

### Contexto:
Como paso 0, he copy/paste el contenido de `LTI-FCV.md`

---

Eres un Product Manager y Business Analyst con amplia experiencia en metodologías ágiles. Utilizando toda la documentación previamente generada para el sistema LTI (incluyendo el PRD, funcionalidades clave, casos de uso, modelo de datos y diseño de alto nivel) y el contexto de "Gestión de Producto y User Stories" (donde se explica la importancia del Product Roadmap, épicas, historias de usuario y tickets de trabajo), genera al menos 2 User Stories completas. Cada historia debe cumplir con los siguientes requisitos:

1. **Título de la Historia de Usuario:**  
   - Utiliza el formato clásico: "Como [rol del usuario], quiero [acción] para [beneficio]".  
   - Ejemplo sugerido: "Como Reclutador, quiero gestionar la lista de candidatos para filtrar y priorizar perfiles relevantes".

2. **Descripción:**  
   - Redacta una explicación narrativa, en lenguaje natural, que detalle la funcionalidad desde la perspectiva del usuario final.  
   - Conecta la historia con las necesidades identificadas en el PRD y los casos de uso ya definidos, enfatizando el valor que aporta al usuario y cómo se alinea con el Product Roadmap.

3. **Criterios de Aceptación:**  
   - Define las condiciones de éxito utilizando el formato "Dado que [contexto inicial], cuando [acción realizada], entonces [resultado esperado]".  
   - Incluye al menos tres criterios que contemplen tanto requisitos funcionales como no funcionales (por ejemplo, tiempos de respuesta, usabilidad, etc.).

4. **Notas Adicionales:**  
   - Añade cualquier consideración extra relevante (restricciones técnicas, dependencias con otros módulos, integraciones con sistemas externos o referencias específicas del modelo de datos).
   - Menciona cómo esta historia se relaciona con la épica correspondiente en el Product Roadmap, si aplica.

5. **Tareas/Subtareas:**  
   - Desglosa la historia en tareas específicas y manejables que permitan implementarla de manera incremental.  
   - Ejemplos: "Diseñar la interfaz", "Implementar el filtro de candidatos", "Realizar pruebas de integración", etc.

Presenta toda la salida en un único bloque de código Markdown para facilitar su copia.  
Asegúrate de que toda la información esté profundamente conectada con la documentación y el contexto del producto LTI.

##############################
# PROMPT 2: Creación y Priorización del Backlog de Producto
##############################
Eres un Product Manager y Business Analyst. Utilizando las User Stories generadas en el PROMPT 1 y la información del PRD, funcionalidades clave, casos de uso, modelo de datos y diseño de alto nivel del sistema LTI, crea el Backlog de Producto. Tu respuesta debe incluir:

1. **Listado de Historias de Usuario:**  
   - Muestra todas las User Stories generadas previamente.

2. **Priorización del Backlog:**  
   - Prioriza las historias usando una metodología ágil (por ejemplo, MoSCoW, WSJF o similar), considerando criterios como impacto en el negocio, valor para el usuario y complejidad técnica.
   - Para cada historia, añade una breve justificación que explique por qué se asignó esa prioridad, haciendo referencia a aspectos del PRD y a las necesidades identificadas en el Product Roadmap.

3. **Formato de Presentación:**  
   - Organiza la información de forma clara (por ejemplo, en una tabla o lista numerada) y preséntala en un único bloque de código Markdown.

Asegúrate de que la solución se base explícitamente en la documentación y User Stories previas, demostrando un análisis crítico y estratégico del producto LTI.

##############################
# PROMPT 3: Desglose en Tickets de Trabajo con Estimación
##############################
Eres un Product Manager y Business Analyst. Selecciona una de las User Stories generadas en el PROMPT 1 (por ejemplo, la historia relacionada con la gestión de candidatos) y desglósala en Tickets de Trabajo. Para cada ticket, debes incluir:

1. **Descripción Técnica del Ticket:**  
   - Proporciona una descripción breve y concreta de la tarea técnica necesaria para implementar la funcionalidad.  
   - Haz referencia a aspectos técnicos específicos derivados de la documentación previa (por ejemplo, integración con la base de datos, implementación de filtros, etc.).

2. **Criterios de Aceptación Técnicos:**  
   - Define condiciones claras y medibles que deben cumplirse para que la tarea se considere terminada (incluye validaciones, pruebas unitarias o de integración, etc.).

3. **Tareas/Subtareas Detalladas:**  
   - Desglosa la tarea principal en subtareas específicas y manejables (por ejemplo, "Desarrollar endpoint API para recuperar candidatos", "Implementar validaciones en el formulario de filtrado", "Realizar pruebas de usabilidad").

4. **Estimación del Esfuerzo:**  
   - Estima el esfuerzo utilizando una metodología ágil (por ejemplo, Fibonacci, planning poker o tallas de camiseta) e indica la unidad de medida (puntos de historia o horas).
   - Incluye una breve justificación de la estimación basada en la complejidad y alcance de la tarea.

Presenta toda la información en un único bloque de código Markdown, asegurándote de que la solución se base en la User Story seleccionada y en toda la documentación previa del sistema LTI.
