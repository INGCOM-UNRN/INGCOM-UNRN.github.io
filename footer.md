% This defines the footer of the site, and is not parsed as a regular "page"
% We point to it with the following in `myst.yml`:
% site:
% parts:
% footer: footer.md

% Here we use `grid` to add a basic grid structure to the HTML,
% but the formatting column sizes are defined manually in css/footer.css
% see the `grid-template-columns` line.
:::::{grid} 1 1 2 3
:class: outer-grid col-screen

<!-- Project description -->

::::{div}

# Universidad Nacional de Río Negro - Sede Andina

```{image} ./img/footer_logo_unrn.svg
:width: 200px
:align: left
```
::::

<!-- Spacer between project description and links columns -->

::::{div}
::::

<!-- Link columns -->

% This a _second_ grid embedded within the first one, to create nicer
% responsive design experience. This grid will have a single column on narrow screens,
% and fan out into three columns on wide screens. However, it always remains within
% its parent grid column.

::::{div} 
- [Sitio oficial](https://www.unrn.edu.ar).
- [Acerca de](https://mystmd.org/overview/ecosystem)
- [Github](hhttps://github.com/INGCOM-UNRN/)

::::

:::::

