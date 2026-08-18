# Examples

Examples from real datasets you'd actually analyse.

<!-- gallery-cards-start -->
::::{grid} 1 2 2 2
:gutter: 3

:::{grid-item-card} Visium mouse brain
:link: /notebooks/examples/visium_mouse_brain
:link-type: doc
:img-top: /notebooks/_static/img/visium_mouse_brain.png

Render H&E tissue, overlay spots, color by gene expression and by cluster,
and finish with a publication-style figure.
:::

:::{grid-item-card} Interactive region annotation
:link: /notebooks/examples/interactive_annotate
:link-type: doc
:img-top: /notebooks/_static/img/interactive_annotate.png

Draw regions of interest directly on a `spatialdata-plot` canvas with
`sdata.pl.annotate(...)` and persist them as a `ShapesModel` element.
:::

:::{grid-item-card} Point density maps
:link: /notebooks/examples/point_density
:link-type: doc
:img-top: /notebooks/_static/img/point_density.png

Turn tens of millions of Xenium transcripts into a readable density
heatmap with `render_points(density=True)`, reshape it with `density_how`,
and draw a separate density per gene.
:::

::::
<!-- gallery-cards-end -->

```{toctree}
:hidden:
:maxdepth: 1

visium_mouse_brain
interactive_annotate
point_density
```
