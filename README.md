# Radar de Morosidad · MVP

MVP académico de un tablero de **scoring preventivo de morosidad** desarrollado con enfoque ágil Scrum + IA (proyecto final de Business Analytics e Inteligencia Artificial).

> **Aviso:** todos los datos son **100 % ficticios**. El score es una herramienta de apoyo; **la decisión final siempre corresponde al gestor humano autorizado**.

## Qué incluye

- **Radar:** vista general animada con clientes por nivel de riesgo.
- **Cartera:** lista priorizada con filtros, factores explicativos, historial y acciones recomendadas.
- **Modelo:** AUC, KS, precisión, recall, F1, matriz de confusión y curva ROC con umbral ajustable.
- **Equidad:** tasa de falsos positivos y recall por género, edad y zona (criterio: diferencia < 5 pp).
- **Registro:** decisiones confirmadas o descartadas por el gestor, con exportación a CSV.

## Cómo verlo

Es una página estática de un solo archivo (`index.html`), sin dependencias ni instalación.

- En local: abre `index.html` en tu navegador.
- En línea: activa GitHub Pages (Settings → Pages → Deploy from a branch → `main` / `(root)`).

## Nota técnica

El score del MVP proviene de un modelo logístico simulado con contribuciones aditivas por cliente (tipo SHAP). En el piloto real se sustituiría por XGBoost + SHAP sin cambiar la interfaz.
