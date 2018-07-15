# Contributing

The file list may look intimidating at first, but this is actually a very simple Jekyll website.

Here's a run through by the important files:

- [`_data/abnd.yml`](_data/abnd.yml) and [`_data/abnd.yml`](_data/and.yml) Project entries are defined here. We'll be able to access data from files under `_data` directory in templates.

- [`index.md`](index.md), [`and.html`](and.html), [`abnd.html`](abnd.html) Page files which will correspond to urls `/`, `/and`, `/abnd` respectively.

- [`_layouts/default.html`](_layouts/default.html), [`_layouts/home.html`](_layouts/home.html), [`_layouts/page.html`](_layouts/page.html) Page files may specify which layouts to render them from.

- [`_includes/`](_includes/) Various reusable pieces of layout, which can be included in pages, layouts, and other includes via `{% include %}` tag. You can pass parameters to included files which will be exposed as `include.*` variables.

- [`assets/`](assets/) Images go here. You can also put `.scss` files here which will be transpiled into normal css before being returned to the browser.

- [`_config.yml`](_config.yml) Jekyll configuration file: https://jekyllrb.com/docs/configuration/
