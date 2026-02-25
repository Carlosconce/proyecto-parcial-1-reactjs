# Historial de Prompts Prototipado de Componente UI

## Prompt 1 Estructura Semántica HTML

Necesito generar la estructura HTML semántica para un componente de interfaz que contiene 5 elementos visuales decorativos con forma de cápsula. 

y para ello necesito que sigas los siguientes requisitos:
- Usa las etiquetas semánticas como `<main>` y `<section>`.
- Evitar el uso innecesario de `<div>` si no es requerido para el resultado.
- Preparar la estructura pensando en aplicar posteriormente un layout con CSS Grid o Flexbox el que mejor consideres.
- No incluir estilos todavia.
- Mantener buenas prácticas de accesibilidad y estructura jerárquica del DOM.


## Prompt 2 Estilos Base (Modelo de Caja y Colores)

Ahora necesito agregar unos estilos base en CSS:

y para lograrlo necesito que sigas estos requisitos:
- Aplicar un reset básico usando el selector universal `*`.
- Usa el `box-sizing: border-box`.
- Aplicar colores exactos similares al:
  - Fondo morado oscuro.
  - Elementos color beige claro.
- Definir tamaños usando unidades relativas como `rem`.
- Aplicar `border-radius` alto para lograr forma tipo "pill".
- Centrar el contenedor vertical y horizontalmente usando Flexbox.
- Evitar problemas de especificidad innecesaria.


## Prompt 3 Layout y Refinamiento con Grid

Ahora necesito que el layout coincida exactamente con la imagen.

asi que porfavor sigue estos siguientes requisitos:
- Usar `display: grid`.
- Definir `grid-template-columns: repeat(3, 1fr)`.
- Usar `gap` para espaciamiento uniforme.
- Centrar elementos con `justify-items`.
- Mantener 3 elementos en la primera fila y 2 en la segunda.
- Ajustar proporciones para que las cápsulas tengan forma vertical.
- Asegurar que el diseño sea responsive usando `max-width`.


##  Análisis Técnico Final

Se uso en este proyecto:

- Modelo de caja con `box-sizing`.
- Unidades relativas `rem`.
- Layout moderno con CSS Grid.
- Flexbox para centrado global.
- Baja especificidad (uso de clases).
- Diseño modular y escalable.

El resultado replica fielmente la distribución visual del componente proporcionado.