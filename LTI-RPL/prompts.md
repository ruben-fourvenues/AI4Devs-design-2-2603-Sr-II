# Prompts — proyecto LTI

Registro de prompts enviados para trazabilidad y reutilización.

---

## Prompt 1

```
Actúa como Product Manager senior y Business Analyst con experiencia en ATS y SaaS B2B.

A partir del PRD @LTI-RPL/LTI-RPL.md, que ya define funciones, casos de uso (CU-01 publicar vacante, CU-02 evaluación colaborativa, CU-03 programar entrevista), modelo de datos y arquitectura del producto LTI, genera entre 6 y 10 User Stories que cumplan INVEST y cubran las 12 funciones del punto 1.7 y los 3 casos de uso del punto 2.

Para cada historia incluye:
- Título descriptivo orientado a valor.
- Historia en formato "Como [rol], quiero [acción], para [beneficio]".
- Entre 3 y 5 criterios de aceptación en Gherkin (Dado que/Cuando/Entonces), testables.
- Notas técnicas breves (contratos de API, eventos de dominio, validaciones).
- Dependencias con otras historias.
- Prioridad MoSCoW (Must/Should/Could/Won't v1).
- Score RICE con la fórmula (Reach × Impact × Confidence) / Effort.
- Estimación en story points Fibonacci (1, 2, 3, 5, 8, 13) y en días de trabajo.
- Métrica de éxito observable.

Después de generar las historias, construye el backlog priorizado del MVP combinando MoSCoW y RICE, justifica por qué esa combinación y no Kano o WSJF, y reparte las historias en sprints de 2 semanas asumiendo un equipo de 4 personas con capacidad de 25 SP por sprint. Comenta explícitamente cualquier caso en el que el orden RICE difiera del orden de ejecución real por dependencias técnicas.

A continuación, documenta como sección "meta" tres prompts alternativos de calidad creciente que se podrían haber usado para generar este backlog (uno naïve, uno con contexto pero sin metodología, y el ganador con rol + metodología + formato + ejemplo). Califica cada uno y cierra con 5 o 6 razones de por qué el ganador funciona mejor.

Después, elige la historia más rica técnicamente y desglósala en tickets de trabajo como se haría en un planning. Incluye diagrama Mermaid de descomposición, tabla de tickets con tipo, capa, story points, horas ideales, talla y dependencias, y detalla uno de los tickets entero a modo de ejemplo (objetivo, alcance, fuera de alcance, criterios técnicos de aceptación, riesgos, estimación). Comenta por qué la suma de SP de tickets puede superar el SP de la historia.

Cierra con un resumen de estimación (SP totales, horas ideales y sprints por bloque) y unos próximos pasos operativos.

Restricciones:
- No inventes funciones que no estén en el PRD @LTI-RPL/LTI-RPL.md.
- Justifica cada decisión opinable en una sola línea.
- Haz diagramas en Mermaid si es necesario.
- Salida en español, en un único archivo Markdown llamado UserStories-RPL.md.
- Empieza directamente por el título del documento, sin preámbulos.
```


