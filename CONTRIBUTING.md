# 🤝 Contribuciones — Pull Request Guidelines — "Excel vs Python"

Este repositorio celebra los 40 años de Excel mostrando sus funciones más populares y cómo se traducen a Python. Queremos que sea colaborativo, limpio, útil y profesional para toda la comunidad. 

Te pedimos seguir estas reglas al contribuir:

## ✅ ¿Qué puedes aportar?

> - Nuevas funciones de Excel con su equivalente en Python
> - Correcciones o mejoras a funciones existentes
> - Ejemplos más claros, edge cases o alternativas más eficientes
> - Traducciones, explicaciones didácticas o mejoras en documentación
> - Mejoras en documentación o estructura del repositorio


## 📁 Estructura de contribuciones

> - Cada función debe incluir:
>   - Nombre de la función en Excel
>   - Equivalente en Python
>   - Librería usada
>   - Ejemplo mínimo funcional
>   - Usuario de GitHub

---
## 🧾 Reglas para Pull Requests

- Puedes proponer Pull Requests con funciones nuevas o correcciones a funciones existentes.
- Si corriges una función de otro usuario, hazlo con respeto y claridad. El _objetivo es mejorar el repositorio, **no competir**_.
- Si se solicita un cambio/corrección en tu Pull Request y no hay actividad en 1 semana, se cerrará para mantener el repositorio limpio. Puedes volver a enviarla cuando quieras.
- No se aceptarán PRs con código duplicado, sin ejemplos funcionales o sin descripción clara.
- Usa Markdown limpio, sin estilos innecesarios. El foco es la claridad didáctica.
- Si propones una función avanzada, incluye un ejemplo mínimo reproducible.
- Si tienes dudas, abre un Issue antes de hacer el PR. Así podemos discutirlo en comunidad.

---
## 📄 Ejemplo de aporte: contribuciones/functions.md

- ` 📦 Funciones aportadas`

| Excel Function | Python Equivalent | Library | Example | GitHub user |
|----------------|-------------------|---------|---------|-------------|
| SUM            | `df['col'].sum()` | pandas  | `df['Ventas'].sum()` | tu_usuario_github |
| IF             | `np.where()`      | numpy   | `np.where(df['x'] > 0, 'Sí', 'No')` | tu_usuario_github |
| VLOOKUP        | `merge()`         | pandas  | `df1.merge(df2, on='ID')` | tu_usuario_github |
| INDEX          | `iloc[]`          | pandas  | `df.iloc[3, 2]` | tu_usuario_github |
| MATCH          | `.index`          | pandas  | `df[df['Nombre'] == 'Ana'].index[0]` | tu_usuario_github |

---

## 🧠 Filosofía

Este repositorio celebra la colaboración, la claridad y el aprendizaje. Cada función es una oportunidad para enseñar, migrar y conectar mundos: Excel y Python. Tu contribución puede ayudar a miles de analistas a dar el salto técnico con confianza.

¡Gracias por ser parte de esta comunidad!
