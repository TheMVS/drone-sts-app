# Simulador examen drones STS

Simulador local (sin servidor, sin internet salvo para cargar la página) para practicar de cara al **certificado de conocimientos teóricos de piloto a distancia UAS en categoría específica (escenarios estándar STS-01 / STS-02)**, con contenido adicional de categoría abierta (A1/A2/A3), PDRA, LUC, Reglamento (UE) 2019/945 y factores humanos/meteorología/rendimiento.

## 🔗 Accede aquí

**https://themvs.github.io/drone-sts-app/**

Funciona en cualquier dispositivo con navegador (móvil, tablet, ordenador) y conexión a internet para cargar la página. Una vez cargada, no necesita conexión para funcionar (todo el banco de preguntas va incluido en el propio archivo).

## Qué contiene

- **1495 preguntas tipo test**, cada una con 4 opciones, respuesta correcta, explicación y fuente citada.
- **610+ conceptos únicos** — muchas preguntas son variantes parafraseadas de un mismo concepto, para practicar reconociéndolo con distintas redacciones (como en el examen real).
- Cobertura completa de las **8 materias del temario oficial de AESA** para el examen de categoría específica (Ed. 2, 17/04/2023):
  1. Reglamentación de la aviación (categoría específica, SORA/PDRA, escenarios estándar, espacio aéreo, información aeronáutica)
  2. Limitaciones del rendimiento humano
  3. Procedimientos operacionales
  4. Mitigación técnica y operacional del riesgo en aire
  5. Conocimientos generales del UAS (clases C0-C6, FTS, geocaging, baterías, sensores)
  6. Meteorología
  7. Rendimiento de vuelo del UAS
  8. Mitigaciones técnicas y operacionales del riesgo en tierra
- Contenido adicional de **categoría abierta (A1/A2/A3)**, **PDRA** (S01, S02, G01, G02), **LUC y clubes de aeromodelismo**, **Reglamento (UE) 2019/945** (marcado CE, evaluación de conformidad) y glosario de definiciones EASA.
- **Preguntas de meteorología sobre rangos de visibilidad y humedad** de niebla, neblina, calima, bruma, lluvia y llovizna, basadas en la tabla oficial del temario AESA (FOR-UAS-P01-DT04).
- **Preguntas sobre las clases de espacio aéreo (A-G)**: vuelos permitidos, separación entre aeronaves, servicios proporcionados, requisitos de comunicación, limitaciones de velocidad y necesidad de autorización ATC, además del esquema general de distribución vertical del espacio aéreo.
- **Preguntas sobre la secuencia de los 10 pasos de la metodología SORA** (ConOps, GRC intrínseco/final, ARC inicial/residual, TMPR, SAIL, requisitos de contención, OSO y cumplimiento en Fase 2), basadas en el proceso oficial de EASA Easy Access Rules for UAS.
- Pregunta aclaratoria sobre la diferencia entre **humedad del aire** (afecta a la densidad y sustentación) y **nubosidad** (puede afectar a la recepción de la señal GNSS).
- Tres **sets de examen fijos**, seleccionables aparte para hacer un simulacro cerrado idéntico a esos bancos:
  - **Banco UAS 1-52**: 52 preguntas transcritas de un banco de preguntas de estudio.
  - **Banco Droniteca 1-89**: 89 preguntas transcritas del banco de preguntas STS de Droniteca.com, con las respuestas correctas señaladas en su documento de soluciones.
  - **Banco Examen STS 1-70**: 70 preguntas transcritas de un examen tipo test (Google Forms) ya corregido, verificando cada respuesta correcta contra el documento de resultados.

### Preguntas por tema

| Tema | Preguntas |
|---|---|
| STS-01 | 122 |
| Meteorología | 120 |
| Espacio aéreo | 105 |
| Rendimiento y técnica | 91 |
| Banco Droniteca 1-89 (set de examen) | 89 |
| Emergencias y seguridad | 84 |
| Factores humanos | 79 |
| Banco Examen STS 1-70 (set de examen) | 70 |
| STS (general) | 66 |
| Formación y responsabilidades | 64 |
| Normativa y conceptos | 60 |
| SORA y PDRA | 67 |
| STS-02 | 59 |
| Banco UAS 1-52 (set de examen) | 52 |
| Mitigaciones de riesgo | 46 |
| Categoría abierta - general | 46 |
| Comunicaciones y observadores | 42 |
| Electricidad y sistemas | 41 |
| Información aeronáutica | 35 |
| Procedimientos operacionales | 34 |
| Categoría abierta | 31 |
| Categorías de operación | 24 |
| Categoría abierta A1 | 21 |
| Categoría abierta A3 | 19 |
| Categoría abierta A2 | 18 |
| Declaración operacional y SORA | 7 |
| AIP / NOTAM | 3 |

**STS + STS-01 + STS-02 (etiquetado directo): 247 preguntas.**

### Preguntas por dificultad

| Dificultad | Preguntas |
|---|---|
| Fácil | 202 |
| Media | 811 |
| Difícil | 403 |
| Muy difícil | 79 |

## Cómo usarlo

1. Entra en el enlace de arriba.
2. En "Configurar cuestionario" elige:
   - **Número de preguntas**
   - **Tema** (o "Todos")
   - **Dificultad** (o "Todas")
   - **Modo**: Normal / Repetir más falladas / No vistas
   - **Set de examen**: "Mezcla general" (por defecto, usa todo el banco con los filtros anteriores), "Banco UAS 1-52", "Banco Droniteca 1-89" o "Banco Examen STS 1-70" (cada uno ignora Tema/Dificultad y te examina con ese banco fijo, barajado)
   - Casillas de "Evitar repetidas recientes" y "Barajar respuestas"
3. Pulsa **Generar cuestionario**, responde, y al entregar verás el porcentaje de acierto y la explicación de cada pregunta.
4. Tras corregir, puedes pulsar **Descargar preguntas (TXT)** para guardar un archivo de texto con la pregunta, la respuesta correcta y la explicación de cada una de las preguntas de ese cuestionario (sin las opciones de respuesta), ideal para repasar offline.
5. **Ver estadísticas** te muestra tu progreso acumulado por tema y las preguntas que más fallas.
6. **Reiniciar estadísticas** borra tu historial local si quieres empezar de cero.

### Sobre las estadísticas y el progreso

Las estadísticas se guardan en el **almacenamiento local del navegador** (`localStorage`), no en un servidor. Esto significa:
- Tu progreso persiste entre sesiones en el mismo navegador/dispositivo.
- Si usas la app desde el móvil y luego desde el ordenador, **las estadísticas no se sincronizan** — cada dispositivo/navegador lleva su propio historial independiente.
- Borrar los datos de navegación del navegador (caché, cookies, etc.) puede borrar también tus estadísticas guardadas.

## Estructura del proyecto

```
drone-sts-app/
├── index.html       # La app completa (HTML+CSS+JS), con las 1495 preguntas embebidas
├── questions.json   # Copia del banco de preguntas en formato JSON (referencia/backup)
└── README.md        # Este archivo
```

`index.html` es autocontenido: no necesita `questions.json` para funcionar, ya que las preguntas están embebidas directamente en el propio HTML (variable `QUESTIONS`). El `.json` se incluye como copia de referencia/backup del banco, por si en el futuro se quiere reconstruir la app o extraer las preguntas por separado.

## Cómo actualizar el banco de preguntas

Si en el futuro se añaden más preguntas:

1. Sustituye `index.html` (y opcionalmente `questions.json`) por la nueva versión en tu carpeta local.
2. En terminal, dentro de la carpeta del repositorio:
   ```bash
   git add .
   git commit -m "Actualizo banco de preguntas"
   git push
   ```
3. GitHub Pages se actualiza automáticamente unos minutos después de cada `push`, sin tocar nada en la configuración.

## Notas sobre las fuentes

Cada pregunta incluye una explicación con la fuente normativa o técnica en la que se basa (Reglamento (UE) 2019/945 y 2019/947, EASA Easy Access Rules for UAS, temario/Syllabus oficial de AESA, entre otras). El contenido ha sido redactado y verificado contrastando la normativa vigente; en algún caso puntual donde un banco de preguntas de terceros contenía una respuesta discutible, se ha señalado la discrepancia en la propia explicación de la pregunta, priorizando siempre la normativa oficial vigente sobre la fuente secundaria.

Este simulador es una herramienta de estudio personal y no sustituye al temario oficial de AESA ni garantiza la superación del examen real. Ante cualquier duda normativa, consulta siempre las fuentes oficiales: [AESA](https://www.seguridadaerea.gob.es) y [EASA Easy Access Rules for UAS](https://www.easa.europa.eu/en/document-library/easy-access-rules/easy-access-rules-unmanned-aircraft-systems).
