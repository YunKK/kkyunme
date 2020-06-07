---
title: "Html Lists"
description: ""
date: "2020-06-07T20:29:29+08:00"
draft: false
thumbnail: ""
categories:
  - "Coding"
tags:
  - "Html"
---

## Html Lists

Learing everyday, html lists

{{< highlight html >}}
<!DOCTYPE html>
<html>    
    <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    2020-6-5
</head>
<title>Html List</title>
<body>
    <h1>Html  Lists</h1><br>

    <ol>
        <li>Number 1</li>
        <li>Number 2</li>
        <li>SO ON...</li>
    </ol>

    <ul>
        <li>Number 1</li>
        <li>Number 2</li>
        <li>SO ON...</li>
    </ul>

    <ul>
        <li>Number 1</li>
        <ul>
            <li>S Number 1</li>
        </ul>
    </ul>

    <dl>
        <dt>First</dt>
        <dd>Belongs to first.</dd>
        <dt>Second</dt>
        <dd>Belongs to second.</dd>
        <dd>Also belongs to second.</dd>
    </dl>

    <ol>
        <dt>Note 1</dt>
        <dd>about note 1</dd>
        <dd><li>belongs to note 1</li></dd>
    </ol>

</body>


</html>
{{< /highlight >}}