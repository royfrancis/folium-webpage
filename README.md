# folium-webpage <span><a href="https://github.com/royfrancis/folium-webpage"><img src="folium.png" style="height:40px;vertical-align:middle;"></a></span> 

[![ci_badge](https://github.com/royfrancis/folium-webpage/workflows/deploy/badge.svg)](https://github.com/royfrancis/folium-webpage/actions?workflow=deploy)    [![lifecycle_badge](https://lifecycle.r-lib.org/articles/figures/lifecycle-experimental.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)

This is a single page quarto html template for project reports. For a multi-page website template, see [folium](https://github.com/royfrancis/folium).

![](preview.jpg)

For a demo page, see [here](http://royfrancis.github.io/folium-webpage).

## Usage

- Required quarto 1.3.4 or higher
- To download a starter template, run in terminal:

```
quarto use template royfrancis/folium-webpage
```

- Launch preview in the browser

```
quarto preview index.qmd
```

- Render

```
quarto render index.qmd
```

## Tips

- Template directory structure

```
.
├── assets
├── _extensions
└── index.qmd
```

- Update `nbis` meta variables
- Use `##` as the highest level heading.
- The output html is intended to be standalone with no child assets. To disable this set:

```
standalone: false
embed-resources: false
```

## Acknowledgements

- Built using [Quarto](https://quarto.org/)
- Uses the [lightbox extension](https://github.com/quarto-ext/lightbox) for viewing images
- Uses the [fontawesome extension](https://github.com/quarto-ext/fontawesome) to include fontawesome icons

---

2024 • Roy Francis
