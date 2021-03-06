# 基本画像

SVGは以下の基本画像で描画できます。



## rect要素

矩形の描画です。

右上の座標\(x, y\)と幅\(width\)と高さ\(height\)を指定することによって描画できます。

{% code-tabs %}
{% code-tabs-item title="rect.svg" %}
```markup
<svg xmlns="http://www.w3.org/2000/svg>
  <rect x="10" y="10" width="100" height="100" fill="red" stroke="blue" />
</svg>

```
{% endcode-tabs-item %}
{% endcode-tabs %}

![&#x56F3; &#x77E9;&#x5F62;&#x306E;&#x63CF;&#x753B;&#x7D50;&#x679C;](https://lh6.googleusercontent.com/j0_p7gzg51PiI7eDJdcKT_X6sSx2H_U0iZRHXyFDm7XzExQSJ9N0Q8Ac65C5XTwhhqD7c1LqU-GEFPRlptUNlyUNtlwNkF4buHybA9MRA2QQ2eB4goObhRgycTRW7SZ_BttdyVGN)



SVGには独自のスタイルがあります。代表的なのがfill と strokeで上記でも使っています。**fill**は内部の色情報を表していて、上記の矩形では赤です。**strokeは**外枠の色情報で、上記だと青を使用しています。また、外枠の幅\(太さ\)は**stroke-width** で指定できます。

## Circle要素

円を中心座標\(cx, cy\)と半径 \(r\)を指定して描画します。

{% code-tabs %}
{% code-tabs-item title="circle.svg" %}
```markup
<svg xmlns="http://www.w3.org/2000/svg">
  <circle cx="60" cy="60" r="50" fill="red" stroke="blue" />
</svg>

```
{% endcode-tabs-item %}
{% endcode-tabs %}

![&#x5186;&#x306E;&#x63CF;&#x753B;&#x7D50;&#x679C;](https://lh6.googleusercontent.com/Qm11EbS3phHxtCyjeMMRT9aqpp6WMgdRlcTFja3gx5s7VElnH1dwn8dhADO4iV9TNgaTHoElfJyMenumH65a5oRevxoM643jzg1U7nX1NqIB2ch5fITEsoeFj76610nbNiJhy0SG)









