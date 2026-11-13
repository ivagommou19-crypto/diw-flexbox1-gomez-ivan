# diw-flexbox1-gomez-ivan

## Comprobación de Contraste (Parte C)

- **Elemento**: Texto blanco (`#ffffff` / `var(--color-texto-inverso)`) en la cabecera y pie de página sobre el degradado horizontal.
- **Fondo evaluado (extremo más claro)**: `#1f5088` (`var(--color-primario-claro)`).
- **Ratio de contraste obtenido**: **8,35:1**.
- **Cumplimiento WCAG 2.1**:
  - Nivel AA (mínimo 4,5:1): **Cumple** ampliamente.
  - Nivel AAA (mínimo 7,0:1): **Cumple**.
- **Cómo se midió**:
  1. Utilizando las **Herramientas de desarrollo del navegador (DevTools)**: inspeccionando el elemento de texto (`.cabecera__marca`, `.menu__enlace`, `.pie__texto`) y abriendo el selector de color de la propiedad de color/fondo en la pestaña *Estilos / Inspeccionar*, donde el evaluador de accesibilidad integrado muestra el ratio de contraste frente al fondo `#1f5088`.
  2. Verificación matemática mediante la fórmula oficial de luminancia relativa de la especificación WCAG 2.1:
     $$\text{Ratio} = \frac{L_1 + 0.05}{L_2 + 0.05} = \frac{1.0 + 0.05}{0.0758 + 0.05} \approx 8{,}35:1$$
