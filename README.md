# Prism

A stylish faux-3D effect in pure CSS.

[**Demo**](https://garcia.sh/prism/)

## Usage

Prism is a Sass project. Compile or include [`prism.scss`](prism.scss) as you would any other Sass file. If you need help, [the Sass guide](http://sass-lang.com/guide) is a great resource.

Apply the class `prism-base` to the outermost container (e.g. your `<body>` tag) to begin using Prism.

The file [`_prism-config.scss`](_prism-config.scss) contains everything you would want to customize.

Every available class fits one of the following forms:

* `prism-{type}-{size}`
* `prism-{selector}-{type}-{size}`
* `prism-blank`
* `prism-{selector}-blank`

Substitute the curly-braced words as needed:

* `{type}`: box or notch
* `{size}`: sm or lg
* `{selector}`: active, focus, or hover

## License

Prism is licensed under the [MIT License](LICENSE.md).
