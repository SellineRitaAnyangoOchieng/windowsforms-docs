---
layout: post
title: Layout-Settings | WindowsForms | Syncfusion
description: layout settings
platform: WindowsForms
control: EditorsPackage
documentation: ug
---

# Layout Settings

The layout settings of the TextBoxExt control are discussed in this section.

The size of the TextBoxExt control can be set according to the needs of the user using the properties discussed below.

Property Table

<table>
<tr>
<th>
TextBoxExt Properties</th><th>
Description</th></tr>
<tr>
<td>
MaximumSize</td><td>
Gets / sets the maximum size for the control.</td></tr>
<tr>
<td>
MinimumSize</td><td>
Gets / sets the minimum size for the control.</td></tr>
</table>

{% tabs %}
{% highlight c# %}

this.textBoxExt1.MaximumSize = new System.Drawing.Size(150, 20);
this.textBoxExt1.MinimumSize = new System.Drawing.Size(150, 20);

{% endhighlight %}

{% highlight vb %}

Me.textBoxExt1.MaximumSize = New System.Drawing.Size(150, 20)
Me.textBoxExt1.MinimumSize = New System.Drawing.Size(150, 20)

{% endhighlight %}
{% endtabs %}

![](Layout-Settings_images/Layout-Settings_img1.png)