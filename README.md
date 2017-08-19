# Prism

A stylish faux-3D effect in pure CSS.  [Demo](https://garcia.sh/prism/)

* Prism is built on two complementary structures: boxes, which extrude out of the page, and notches, which sink into the page. Box shadows are special – look at the corners!
* The virtual “depth” of nested boxes and notches is tracked up to a customizable recursion limit.
* Built-in `-active-`, `-focus-`, and `-hover-` variants of classes can dynamically change the depth of elements. Still no JavaScript in sight!

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
