# Instrucciones para estudiantes

## Fase 1 — Descarga e interpretación (15 minutos)

Descarga el ZIP del repositorio del docente. Lee `CASO_CLINICO.md` e identifica qué campos necesitas para representar cada paciente en una fila. Propón tus propios nombres de columnas antes de comenzar Excel.

## Fase 2 — Construcción de Excel (50 minutos)

Crea `Base_Datos_Hospital.xlsx` con una hoja **Pacientes** y otra **Análisis**.

En **Pacientes**:
- Registra los 20 pacientes ficticios, una fila por paciente.
- Utiliza columnas para código, edad, sexo, fecha de consulta, motivo, temperatura (°C), frecuencia cardíaca (lpm), saturación de oxígeno (%), diagnóstico simulado y estado de atención.
- Normaliza fechas al formato AAAA-MM-DD, sexos a F/M y estados a Pendiente/En atención/Finalizada.
- Guarda los números como valores numéricos y activa filtros.
- **No inventes información faltante.** Deja la celda vacía y explica la ausencia en el análisis.

## Fase 3 — Análisis (35 minutos)

En **Análisis**, calcula con fórmulas:
1. Total de pacientes.
2. Edad promedio.
3. Temperatura promedio.
4. Cantidad de pacientes por sexo.
5. Cantidad por estado de atención.
6. Saturación mínima registrada (ignorando celdas vacías).
7. Cantidad de registros incompletos.

Agrega **dos gráficos** (por ejemplo, distribución por sexo y estado de atención).

## Fase 4 — Documentación (20 minutos)

Crea `analisis.md` con respuestas interpretadas a los siete indicadores anteriores, descripción de las inconsistencias y una reflexión de 100–150 palabras sobre privacidad clínica.

En el `README.md` de tu repositorio explica el objetivo, el diccionario de datos, el proceso de limpieza, los archivos entregados y la declaración de datos ficticios.

## Fase 5 — Publicación (25 minutos)

1. Exporta la hoja **Pacientes** como `pacientes.csv` (CSV UTF-8).
2. Entra a https://github.com y crea tu cuenta si todavía no tienes una.
3. Crea un repositorio **público** llamado `hospital-san-gabriel-solucion`.
4. Selecciona **Add file → Upload files** y sube `Base_Datos_Hospital.xlsx`, `pacientes.csv`, `analisis.md` y `README.md`.
5. Confirma con **Commit changes**.
6. Comprueba que todos los archivos estén disponibles y que `pacientes.csv` se vea como texto tabular.
7. Copia la URL de tu repositorio y entrégala en la plataforma institucional.

## Cierre (5 minutos)

Verifica que los 20 registros estén completos salvo los datos ausentes en el caso original, que las fechas sean consistentes y que no haya datos personales reales.

**Prohibido:** publicar datos reales, inventar saturaciones u otras mediciones faltantes, copiar una base resuelta de otra persona.
