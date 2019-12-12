---
layout: post
title: Behavior-Settings | WindowsForms | Syncfusion
description: behavior settings
platform: WindowsForms
control: EditorsPackage
documentation: ug
---

# Behavior Settings

The behavior settings of the TextBoxExt control are discussed below.

## MaxLength

The maximum length of the text can be set using the property given below.

Property Table

<table>
<tr>
<th>
TextBoxExt Property</th><th>
Description</th></tr>
<tr>
<td>
MaxLength</td><td>
Specifies the maximum number of characters that can be entered into the edit control. The default value is set to '32767'.</td></tr>
</table>

{% tabs %}
{% highlight c# %}

this.textBoxExt1.MaxLength = 32800;               

{% endhighlight %}

{% highlight vb %}

Me.textBoxExt1.MaxLength = 32800

{% endhighlight %}
{% endtabs %}

### ReadOnly

The ReadOnly mode can be enabled for the TextBoxExt control using the below given property.

Property Table

<table>
<tr>
<th>
TextBoxExt Property</th><th>
Description</th></tr>
<tr>
<td>
ReadOnly</td><td>
Specifies whether the text in the edit control can be changed or not.</td></tr>
</table>

{% tabs %}
{% highlight c# %}

this.textBoxExt1.ReadOnly = true;

{% endhighlight %}

{% highlight vb %}

Me.textBoxExt1.ReadOnly = True

{% endhighlight %}
{% endtabs %}

A sample which demonstrates the ReadOnly mode of TextBoxExt control is available in the below sample installation path.

…\_My Documents\Syncfusion\EssentialStudio\Version Number\Windows\Tools.Windows\Samples\Advanced Editor Functions\ActionGroupingDemo_