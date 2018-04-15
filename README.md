[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/htmlelements/smart-button)

# &lt;smart-button&gt;

[Live Demo ↗](http://htmlelements.com/demos/button/)
|
[Documentation ↗](http://www.htmlelements.com/docs/)
|
[Installation ↗](https://www.npmjs.com/package/@smarthtmlelements/smart-html-elements-core)

[&lt;smart-accordion&gt;](http://htmlelements.com/demos/accordion/) is a Custom HTML Element with expandable panels, part of the [Smart HTML Elements](http://htmlelements.com/). Each panel has header and content. 

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="../smarthtmlelements-core/source-minified/native-shim.js"></script>
    <script src="../smarthtmlelements-core/source-minified/smart.element-polyfills.js"></script>
    <script src="../smarthtmlelements-core/source-minified/smart.element.js"></script>
    <script src="../smarthtmlelements-core/source-minified/smart.accordion.js"></script>
    <link rel="stylesheet" href="../smarthtmlelements-core/source-minified/styles/smart.base.css" type="text/css" />
    <link rel="stylesheet" href="../smarthtmlelements-core/source-minified/styles/smart.material.css" type="text/css" />
     <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
 <smart-accordion>
  <smart-accordion-item label="Item 1" content="Content 1" expanded></smart-accordion-item>
  <smart-accordion-item label="Item 2" content="Content 2"></smart-accordion-item>
  <smart-accordion-item label="Item 3" content="Content 3"></smart-accordion-item>  
 </smart-accordion>
```

[<img src="https://raw.githubusercontent.com/htmlelements/smart-accordion/master/smart-accordion.gif" alt="Screenshot of smart-accordion, using the Material theme">](http://htmlelements.com/demos/accordion)

## Getting Started

Smart HTML Elements components documentation includes getting started, customization and api documentation topics.

[Getting Started Documentation](http://www.htmlelements.com/docs/accordion/)
|
[CSS Documentation](http://www.htmlelements.com/docs/accordion-css/)
|
[API Documentation](http://www.htmlelements.com/docs/accordion-api/)


## The file structure for Smart HTML Elements

- `source-minified/`

  Javascript files.

- `source-minified/styles/`

  Component CSS Files.

- `demos/`

  Demo files

## Running demos in browser

1. Fork the `Smart-HTML-Elements-Core` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `Smart-HTML-Elements-Core` directory, run `npm install` and then `bower install` to install dependencies.

1. Run a localhost or upload the demo on a web server. Then run:

  - /demos/smart-accordion/smart-accordion-overview.htm


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. 

## Creating a pull request

  - Make sure your code is compliant with ESLint
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of our team members


## License

Apache License 2.0

