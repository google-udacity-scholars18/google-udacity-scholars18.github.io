# Contributing

If you have an idea and don't know where to start, [create an issue](https://github.com/AndroidDevScholarship/ud851-emea/issues/new) and we'll point you in the right direction.

## Project Structure

The file list may look intimidating at first, but this is actually a very simple Jekyll website.

Here's a run through by the important files:

- [`_data/abnd.yml`](_data/abnd.yml) and [`_data/abnd.yml`](_data/and.yml) Project entries are defined here. We'll be able to access data from files under `_data` directory in templates.

- [`index.md`](index.md), [`and.html`](and.html), [`abnd.html`](abnd.html) Page files which will correspond to urls `/`, `/and`, `/abnd` respectively.

- [`_layouts/default.html`](_layouts/default.html), [`_layouts/home.html`](_layouts/home.html), [`_layouts/page.html`](_layouts/page.html) Page files may specify which layouts to render them from.

- [`_includes/`](_includes/) Various reusable pieces of layout, which can be included in pages, layouts, and other includes via `{% include %}` tag. You can pass parameters to included files which will be exposed as `include.*` variables.

- [`assets/`](assets/) Images go here. You can also put `.scss` files here which will be transpiled into normal css before being returned to the browser.

- [`_config.yml`](_config.yml) Jekyll configuration file: https://jekyllrb.com/docs/configuration/

For more detailed explanation, see [Jekyll Docs](https://jekyllrb.com). 

## How to run this project locally

You need to have Ruby environment setup. See [Jekyll requirements](https://jekyllrb.com/docs/installation/#requirements).

Clone this project and run `bundle install` followed by `bundle exec jekyll serve`.

Server URL will be printed to the console. Open it in the browser.

Any changes you make to the files will be reflected on the website after refresh, with the exception of `_config.yml` file.

If you make changes to `_config.yml` then you need to stop the server and run `bundle exec jekyll serve` again.

