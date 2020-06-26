# NOTAS

## Definición de propiedades

Se pueden definir columnas y filas por separado o directamente en una sola:

Ejemplo separado:

```css
.container {
  display: grid;
  grid-template-columns: 25% 200px 25%;
  grid-template-rows: 300px 150px;
}
```

Ejemplo en una unica propiedad:

```css
.container {
  display: grid;
  /** filas y columnas se delimitan por "/" */
  /** filas / columnas */
  grid-template: 300px 150px / 25% 200px 25%;
}
```

