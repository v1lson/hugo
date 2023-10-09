+++
title = 'Shortcode'
date = 2023-09-26T08:49:10+02:00
draft = false
weight = 15
categories = ["Test"]
tags = ["Tag"]
+++

## Highlight

{{< highlight lineNos="true" type="py" wrap="true" title="python" >}}
print("Hello World!")
{{< /highlight >}}

## Botton
{{% button href="https://gohugo.io/" style="warning" icon="dragon" %}}Get Hugo{{% /button %}}
{{% button href="https://gohugo.io/" style="info" %}}Get Hugo{{% /button %}}
{{% button href="https://gohugo.io/" style="note" %}}Get Hugo{{% /button %}}
{{% button href="https://gohugo.io/" style="tip" %}}Get Hugo{{% /button %}}
{{% button href="https://gohugo.io/" style="warning" %}}Get Hugo{{% /button %}}

## Attachments
{{% attachments style="info" sort="desc" /%}}

## Badge
{{% badge %}}Important{{% /badge %}}
{{% badge style="primary" title="Version" %}}7.1{{% /badge %}}
{{% badge style="blue" icon="bomb" %}}Bombo clack{{% /badge %}}
{{% badge style="info" %}}New{{% /badge %}}
{{% badge color="fuchsia" icon="fab fa-hackerrank" %}}Awesome{{% /badge %}}

{{% children sort="weight" %}}

## Expand
{{% expand title="Expand me..." %}}```Hola```{{% /expand %}}

## Iconos
{{% icon icon="exclamation-triangle" %}}
{{% icon icon="puzzle-piece" %}}
{{% icon icon="skull-crossbones" %}}

## Notice

{{% notice default "Pay Attention to this Note!" "skull-crossbones" %}}
Some serious information.
{{% /notice %}}

{{% notice style="orange" title="Orange" icon="bug" %}}
A **orange** disclaimer
{{% /notice %}}

## Site Param

`editURL` value: {{% siteparam name="weight" %}} https://fontawesome.com/docs/web/

## Tablas
{{< tabs groupid="a" >}}
{{% tab title="js" %}}
```js
hola
```
{{% /tab %}}
{{% tab title="_**XML**_ stuff" %}}
```xml
<Hello>World</Hello>
```
{{% /tab %}}
{{% tab title="text" %}}
    Hello World
{{% /tab %}}
{{< /tabs >}}

{{< color >}} hola {{< /color >}} 