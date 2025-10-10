# MAC – Motor de Análisis de Correlación (Artritis Reumatoide)

Aplicación de escritorio en **Python + Tkinter** para registrar **síntomas diarios** de Artritis Reumatoide (AR) y descubrir **relaciones** con factores de **estilo de vida** y **ambiente** (sueño, dieta, clima, actividad física).  
Cada usuario tiene **su perfil** y **su propio CSV** con registros. Incluye **simulación de datos** realistas para aprender el flujo desde el primer uso.

>  Esta app **no diagnostica ni receta**. Solo muestra **asociaciones** (correlación) para apoyar el autocuidado y la conversación con el equipo de salud. **Correlación ≠ causalidad.**

---

## Planteamiento 

- La AR puede aparecer a **cualquier edad** y sus síntomas (dolor, rigidez, inflamación, fatiga) **varían entre personas**.  
- Los médicos piden llevar un **diario** (qué duele, cuánto, clima, sueño, dieta, actividad), pero:
  - Es **difícil** mantenerlo a diario.
  - Casi nunca se **analiza** para encontrar **patrones personales**.
- **Necesidad:** una herramienta **simple** que permita **registrar** rápido y **visualizar** cómo los factores cotidianos se **relacionan** con los síntomas, * y con **explicaciones claras**.

---

## Objetivos

**Objetivo general**  
Facilitar el **registro diario** y la **interpretación** de los síntomas y factores personales en AR para apoyar el **autocuidado** y la **conversación** con el equipo de salud.

**Objetivos específicos**
1. Permitir un **registro simple** (0–5) de dolor, rigidez, inflamación y fatiga, junto con **sueño**, **dieta**, **clima**, **temperatura**, **actividad** y **ánimo**.
2. Guardar la **información por usuario** (perfil en `data/usuarios.json` y registros en `data/{usuario}_registros.csv`).
- **Enfoque cuantitativo + visual** con **retroalimentación personalizada** basada en tu **registro diario**, y **gráficas clínicas interpretables** para paciente y reumatólogo.

3. Calcular y mostrar **correlaciones** (Pearson), **prueba t** (clima adverso vs dolor) y un índice **ISA** (promedio de síntomas).
4. **Visualizar** resultados con gráficos y **mensajes interpretables**
5. Incluir **simulación de datos** realistas para aprender el uso desde el primer día.

---

##Herramientas utilizadas

- **Python 3**
- **Tkinter** (interfaz de escritorio)
- **Pandas** (carga, limpieza, análisis)
- **NumPy** (simulación y operaciones numéricas)
- **Matplotlib** y **Seaborn** (gráficos)
- **SciPy** (prueba t)
- **CSV/JSON** para persistencia por usuario (simple y entendible)

---

