# Examples

Examples from real datasets you'd actually analyse.

::::{grid} 1 2 2 2
:gutter: 3

:::{grid-item-card} Visium mouse brain
:link: visium_mouse_brain
:link-type: doc
:img-top: ../_static/img/visium_mouse_brain.png

Render H&E tissue, overlay spots, color by gene expression and by cluster,
and finish with a publication-style figure.
:::

:::{grid-item-card} Interactive region annotation
:link: interactive_annotate
:link-type: doc
:img-top: ../_static/img/interactive_annotate.png

Draw regions of interest directly on a `spatialdata-plot` canvas with
`sdata.pl.annotate(...)` and persist them as a `ShapesModel` element.
:::

:::{grid-item-card} Speeding up rendering
:link: performance
:link-type: doc
:img-top: ../_static/img/performance.png

Keep rendering fast on large data: automatic rasterization and scale
selection for images, and the `datashader` backend for large collections
of shapes and points.
:::

::::

```{toctree}
:hidden:
:maxdepth: 1

visium_mouse_brain
interactive_annotate
performance
```
