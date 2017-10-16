vega-collection
==========

<!---
```
<custom-element-demo>
  <template is="dom-bind">
    <link rel="import" href="../vega-element/vega.html">
    <link rel="import" href="../vega-element/vega-tooltip.html">
    <link rel="import" href="../vega-element/vega-signal.html">
    <link rel="import" href="../vega-element/vega-element.html">
    <link rel="import" href="../marked-vega/marked-vega.html">
    <link href="http://polygit.org/components/marked-element/marked-element.html" rel="import">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<h4>Embedding Vega/Vega-Lite charts with <i>vega-element</i></h4>
<vega-element tooltip hover
  vega-spec-url="https://rawgit.com/PolymerVis/marked-vega/master/demo/barchart-vg.json"></vega-element>

<h4>Embedding Vega/Vega-Lite charts in markdown with <i>marked-vega</i> and <i>marked-element</i></h4>
<marked-element>
  <marked-vega slot="markdown-html"></marked-vega>
  <script type="text/markdown" src="https://rawgit.com/PolymerVis/marked-vega/master/demo/readme.md"></script>
</marked-element>
```

`vega-collection` is a collection of Polymer elements for [Vega](https://vega.github.io/vega/) and [Vega-Lite](https://vega.github.io/vega-lite/):
- [`vega-element`](https://www.webcomponents.org/element/PolymerVis/vega-element) is a Polymer (1.X, 2.X) element for rendering interactive data visualization with Vega and Vega-Lite.
- [`marked-vega`](https://www.webcomponents.org/element/PolymerVis/marked-vega) is a Polymer 2.0 add-on element for [`marked-element`](https://www.webcomponents.org/element/PolymerElements/marked-element) to render Vega and Vega-Lite charts from markdown.

**Vega** is a visualization grammar, a declarative language for creating, saving, and sharing interactive visualization designs. With Vega, you can describe the visual appearance and interactive behavior of a visualization in a JSON format, and generate web-based views using Canvas or SVG.

**Vega-Lite** is a high-level grammar of interactive graphics. It provides a concise JSON syntax for rapidly generating visualizations to support analysis. Vega-Lite specifications can be compiled to Vega specifications.
