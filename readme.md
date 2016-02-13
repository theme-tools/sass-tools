# Evan's Sass Tools

A personal collection of mixins and other handy tools.

## Installation & Setup

Works via `npm` or `bower`. First, **pick one** install method:

	npm install evans-sass-tools
	bower install evans-sass-tools

Then, include the main file in your sass; so if you had `scss/style.css`, you'd include this in it:

	@import "../node_modules/evans-sass-tools/all.scss";

If you're using bower, just replace `node_modules/` for `bower_components/`.

### Installing just what you need

Feel free to not grab the whole thing and just pick a single mixin:

	@import "../node_modules/evans-sass-tools/lib/_arrow-btn.scss";

If a mixin has dependencies on other mixins, it'll import them; so just grab what you need.

## Examples

See the `examples/` directory for the Sass and HTML used to demo the different tools. You'll need to build the tools to see them in a browser though (see below; it's easy).

## More Info

### Docs

After building the tools, you can see the [SassDocs](http://sassdoc.com) at `docs/`.

### Building the Tools

Not needed to use the tools; just to compile the example Sass to CSS and build the Docs. Simply run:

	npm install
	npm run build

### Contributing

To fire up BrowserSync and all the watches; just run:

	npm install
	npm start

Please ensure:

- Items have [SassDocs Annotations](http://sassdoc.com/annotations) (the triple slash `///` comments)
- Examples have been provided
- `npm test` executes successfully
