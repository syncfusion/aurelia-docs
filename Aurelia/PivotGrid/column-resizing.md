---
layout: post
title:  Column Resizing
description: column resizing
platform: js
control: PivotGrid
documentation: ug
api: /api/js/ejpivotgrid
---

# Resizing Column

Allows you to change the column width by holding and dragging the column border using the mouse pointer.

## Column width based on size

The [`enableColumnResizing`](/api/js/ejpivotgrid#members:enablecolumnresizing) property adjusts the width of each column based on size of the widget.

{% highlight html %}

<template>
  <div>
    <ej-pivot-grid e-enable-column-resizing="true">
    </ej-pivot-grid>
  </div>
</template>

{% endhighlight %}

## Column width based on text

The [`resizeColumnsToFit`](/api/js/ejpivotgrid#members:resizecolumnstofit) property automatically adjusts the width of each column based on the maximum content length available in the respective column.

{% highlight html %}

<template>
  <div>
    <ej-pivot-grid e-resize-columns-to-fit="true">
    </ej-pivot-grid>
  </div>
</template>

{% endhighlight %}

![](Column-Resizing_images/columnresizing.png)
