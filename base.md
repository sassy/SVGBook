# SVGの基本

SVGはXMLで書かれます。

以下は矩形を描画するSVGの例です。

{% code-tabs %}
{% code-tabs-item title="rest.svg" %}
```markup
<svg xmlns="http://www.w3.org/2000/svg"> 
　　　　　<rect x="0" y="0" width="100" height="100" />
</svg>
```
{% endcode-tabs-item %}
{% endcode-tabs %}

SVGはルート要素は**`<svg>`**になります。名前空間は **"http://www.w3.org/2000/svg"**です。

