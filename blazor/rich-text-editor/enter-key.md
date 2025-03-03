---
layout: post
title: Enter key customization in Blazor RichTextEditor | Syncfusion
description: Checkout and learn here all about the Enter key and Shift + Enter key customization feature in Syncfusion Blazor RichTextEditor component and more.
platform: Blazor
control: RichTextEditor
documentation: ug
---

# Enter and Shift-Enter Key Configuration

The Rich Text Editor allows to customize the tag that is inserted when pressing the <kbd>Enter</kbd> key and <kbd>Shift</kbd> + <kbd>Enter</kbd> key in the Rich Text Editor.

## Enter key customization 

By default, the `<p>` tag is created while pressing the <kbd>Enter</kbd> key. The tag created while pressing the <kbd>Enter</kbd> key can be customized by using the [EnterKey](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.RichTextEditor.SfRichTextEditor.html#Syncfusion_Blazor_RichTextEditor_SfRichTextEditor_EnterKey) property. The [possible tags](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.RichTextEditor.EnterKeyTag.html) that can be used to customize the <kbd>Enter</kbd> key are `<p>`, `<div>`, and `<br>`.

When the <kbd>Enter</kbd> key is customized with any of the above possible values, pressing the <kbd>Enter</kbd> key in the editor will create a new tag that is configured.


> The `pre` tag will be inserted when code format is applied, enter key press will created only `<br>` tag if the editor content is inside the `pre` tag. Need to press enter key twice to come out of the `pre` tag.

{% tabs %}
{% highlight razor %}

{% include_relative code-snippet/enter-key-customization.razor %}

{% endhighlight %}
{% endtabs %}

![Enter key confuguration in Blazor RichTextEditor](./images/blazor-richtexteditor-enter-key.png)

> [View Sample](https://blazor.syncfusion.com/demos/rich-text-editor/enterkeyconfiguration)

## Shift-Enter key customization

By default, the `<br>` tag is created while pressing the <kbd>Shift</kbd> + <kbd>Enter</kbd> key. The tag created while pressing the <kbd>Shift</kbd> + <kbd>Enter</kbd> key can be customized by using the [ShiftEnterKey](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.RichTextEditor.SfRichTextEditor.html#Syncfusion_Blazor_RichTextEditor_SfRichTextEditor_ShiftEnterKey) property. The [possible tags](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.RichTextEditor.ShiftEnterKeyTag.html) that can be used to customize the <kbd>Shift</kbd> + <kbd>Enter</kbd> key are `<br>`, `<p>`, and `<div>`.

When the <kbd>Shift</kbd> + <kbd>Enter</kbd> key is customized with any of the possible values, pressing the <kbd>Shift</kbd> + <kbd>Enter</kbd> key in the editor will create a new tag that is configured.

{% tabs %}
{% highlight razor %}

{% include_relative code-snippet/shift-enter-key-customization.razor %}

{% endhighlight %}
{% endtabs %}

![Shift + Enter key confuguration in Blazor RichTextEditor](./images/blazor-richtexteditor-shift-enter-key.png)

