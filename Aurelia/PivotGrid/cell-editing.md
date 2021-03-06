---
layout: post
title: Cell-Editing
description: cell editing
platform: js
control: PivotGrid
documentation: ug
api: /api/js/ejpivotgrid
---

# Cell Editing

I> This feature is applicable only for the relational data source.

Cell editing allows you to edit and alter the values in the PivotGrid. The summary values will be recreated based on edited values. By selecting multiple cells (like in cell selection feature), you can edit multiple cells at the same time.

You can enable the cell editing option in the PivotGrid by setting the [`enableCellEditing`](/api/js/ejpivotgrid#members:enablecellediting) property to true.

{% highlight html %}

<template>
  <div>
    <ej-pivot-grid e-enable-cell-editing="true">
    </ej-pivot-grid>
  </div>
</template>

{% endhighlight %}

![](Cell-Editing_images/celleditingclient.png)
