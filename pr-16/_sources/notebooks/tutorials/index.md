# Tutorials

Entry-point material for learning the API on synthetic data.

<!-- gallery-cards-start -->
::::{grid} 1 2 2 2
:gutter: 3

:::{grid-item-card} Getting started
:link: /notebooks/tutorials/getting_started
:link-type: doc
:img-top: /notebooks/_static/img/getting_started.png

The fluent `.pl` API, layering, and styling on the in-memory `blobs`
dataset. Ideal first read.
:::

:::{grid-item-card} Colour and palettes
:link: /notebooks/tutorials/color_and_palette
:link-type: doc
:img-top: /notebooks/_static/img/color_and_palette.png

How `color=` resolves, the v0.3.0 `groups` behaviour, and building
perceptually well-spaced or colourblind-safe palettes with
`make_palette` and `make_palette_from_data`.
:::

:::{grid-item-card} Multi-panel colouring
:link: /notebooks/tutorials/multi_panel_color
:link-type: doc
:img-top: /notebooks/_static/img/multi_panel_color.png

Render several colourings at once by passing a list to `color=`,
scanpy-style, with per-panel legends/colourbars, shared `palette`/`cmap`,
and `ncols` grid control.
:::

:::{grid-item-card} Speeding up rendering
:link: /notebooks/tutorials/performance
:link-type: doc
:img-top: /notebooks/_static/img/performance.png

Keep rendering fast on large data: automatic rasterization and scale
selection for images, and the `datashader` backend for large collections
of shapes and points.
:::

:::{grid-item-card} Scalebars
:link: /notebooks/tutorials/scalebars
:link-type: doc
:img-top: /notebooks/_static/img/scalebars.png

Add a physical scalebar with `scalebar_dx`, choose units, and style
placement, colour, length and fonts through `scalebar_params`.
:::

:::{grid-item-card} Styling shapes and labels
:link: /notebooks/tutorials/styling_shapes_and_labels
:link-type: doc
:img-top: /notebooks/_static/img/styling_shapes_and_labels.png

Control how shapes and labels are drawn: `fill_alpha`, the `outline`
toggle with `outline_width`/`outline_color`/`outline_alpha`, hollow
shapes, `scale`, and segmentation boundaries via `contour_px`.
:::

::::
<!-- gallery-cards-end -->

```{toctree}
:hidden:
:maxdepth: 1

getting_started
color_and_palette
multi_panel_color
performance
scalebars
styling_shapes_and_labels
```
