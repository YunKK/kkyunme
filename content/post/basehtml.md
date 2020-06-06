---
title: "Base Html"
description: "learning note"
date: "2020-06-06T17:01:40+08:00"
thumbnail: ""
categories:
  - "Coding"
tags:
  - "Html"

## Base Html

{{< highlight html >}}
<section id="main">
  <div>
   <!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        2020-6-4
    </head>
    <title>Base Html</title>
    <body>
        <h1>Base Html</h1> 

        <p>There are H1 to H6 for different size</p>

        <p><b>Bold the text with  b tags</b></p>

        <p><i>Italic the txet with the i tags</i></p>

        <p>EM=MC<sup>2</sup> and CO<sub>2</sub></p>

        <p>The write the poem<br />can use the br / tags<br />like this.</p>

        <p>To draw a line between<hr />use the hr / tags,like this.</p>

        <p><strong>To bold the text, use strong tags</strong></p>

        <p><em>Emphasis the text by using the em tags</em></p>

        <address><p><a href="mail@sample.com">mail@sample.com</a></p><p>address and email in the website</p></address>

        <p><s>was 100</s></p> <p>now only 70</p>
    
    </body>
    
</html>

    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}