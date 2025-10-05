# 📊 Excel vs Python — Equivalencias de funciones

Este archivo contiene las funciones más populares de Excel y su equivalente en Python, con ejemplos mínimos y claros.

|Number| Excel Function | Python Equivalent | Library | Example | GitHub user |
|-|----------------|-------------------|---------|---------|--------|
|1|SUM            | `df['col'].sum()` | pandas  | `df['Ventas'].sum()` | vegacastilloe |
|2|IF             | `np.where()`      | numpy   | `np.where(df['x'] > 0, 'Sí', 'No')` | vegacastilloe |
|3|VLOOKUP        | `merge()`         | pandas  | `df1.merge(df2, on='ID')` | vegacastillo |
|4|INDEX          | `iloc[]`          | pandas  | `df.iloc[3, 2]` | vegacastillo |
|5|MATCH          | `.index`          | pandas  | `df[df['Nombre'] == 'Ana'].index[0]` | vegacastillo |
|6|