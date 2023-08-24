---
title: Examples of supported markup features
language: en
---

## Headers

{% highlight markdown %}
## Example header, level 2
### Example header, level 3
#### Example header, level 4
{% endhighlight %}

## Example header, level 2
### Example header, level 3
#### Example header, level 4

## Text styling

{% highlight markdown %}
*Italic text*

**Bold text**
{% endhighlight %}

*Italic text*

**Bold text**

## Paragraphs
{% highlight markdown %}
Separate paragraphs with blank lines.

This is a new paragraph.

Another one
{% endhighlight %}

Separate paragraphs with blank lines.

This is a new paragraph.

Another one

## Text decoration — note

{% highlight markdown %}
**Note.** This is an important note
{: .note}
{% endhighlight %}

**Note.** This is an important note
{: .note}

## Text decoration — alert

{% highlight markdown %}
**Warning.** This is a alert
{: .alert}
{% endhighlight %}

**Warning.** This is a alert
{: .alert}

## Text decoration — multiline alert

{% highlight html %}
<div class="alert" markdown="1">
**Warning**

Lorem ipsum dolor set amet.

Take care of yourself!
</div>
{% endhighlight %}

<div class="alert" markdown="1">
**Warning**

Lorem ipsum dolor set amet.

Take care of yourself!
</div>

## Unordered list

{% highlight markdown %}
* Lorem
* Ipsum
  * Dolor
  * Set
* Amet
{% endhighlight %}

* Lorem
* Ipsum
  * Dolor
  * Set
* Amet

## Ordered list

{% highlight markdown %}
1. Lorem
2. Ipsum
3. Dolor
{% endhighlight %}

1. Lorem
2. Ipsum
3. Dolor


## Links

{% highlight markdown %}
* Here is a [link](https://lessy.app)
* A mailto link: [feedback@lessy.app](mailto:feedback@lessy.app)
{% endhighlight %}

* Here is a [link](https://lessy.app)
* A mailto link: [feedback@lessy.app](mailto:feedback@lessy.app)


<br />**A URL in text does not become a link automatically:**
{% highlight markdown %}
* https://this.is.not.a.link.com/
* [this.is.a.link.com](https://this.is.a.link.com/)
{% endhighlight %}

* https://this.is.not.a.link.com/
* [this.is.a.link.com](https://this.is.a.link.com/)


## Buttons

{% highlight markdown %}
Here's a button:

[Click me](https://lessy.app){: .button}

Here's a button with additional top margin:

[Click me too](https://lessy.app){: .button .button_top-margin}
{% endhighlight %}

Here's a button:

[Click me](https://lessy.app){: .button}

Here's a button with additional top margin:

[Click me too](https://lessy.app){: .button .button_top-margin}


## Images

{% highlight markdown %}
![A food basket](https://yastatic.net/s3/edadeal-public-static/corecase/images-for-desktop-segments/food-rec.png)
{% endhighlight %}

![A food basket](https://yastatic.net/s3/edadeal-public-static/corecase/images-for-desktop-segments/food-rec.png)

Text in square brackets is an Alt-text that is shown when the image hasn't loaded.


## Tables

{% highlight markdown %}
| Here | are | some | table | headers |
| -------- | ------- | -------- | ------- |  ------- |
| Table cell 1 | Table cell 2 | Table cell 3 | Table cell 4 |  Table cell<br /><br />With 2 paragraphs |
| Table cell 1 | Table cell 2 | Table cell 3 | Table cell 4 |  Table cell 5 |
{% endhighlight %}

| Here | are | some | table | headers |
| -------- | ------- | -------- | ------- |  ------- |
| Table cell 1 | Table cell 2 | Table cell 3 | Table cell 4 |  Table cell<br /><br />With 2 paragraphs |
| Table cell 1 | Table cell 2 | Table cell 3 | Table cell 4 |  Table cell 5 |


## Inline code

{% highlight markdown %}
To be happy use the following function: `doNotWorry()` and `becomeHappy(now)`.
{% endhighlight %}

To be happy use the following function: `doNotWorry()` and `becomeHappy(now)`.

## Block code

{% highlight markdown %}
{% raw  %}
{% highlight json %}
{
  "conditions": "A promoção é válida nas lojas da rede comercial, desde que o produto esteja disponível na loja. Quantidade limitada",
  "date_end": "2020-06-12",
  "date_start": "2020-06-05",
  "id": "1234",
  "image": "https://retailer1234.com/catalogs/1234.jpg",
  "is_main": true,
  "offers": [
    "11111",
    "22222",
    "33333"
  ],
  "target_regions": [
    "Brasil, São Paulo",
    "Brasil, São Paulo Butantã"
  ]
}
{% endhighlight %}
{% endraw %}
{% endhighlight %}

{% highlight json %}
{
  "conditions": "A promoção é válida nas lojas da rede comercial, desde que o produto esteja disponível na loja. Quantidade limitada",
  "date_end": "2020-06-12",
  "date_start": "2020-06-05",
  "id": "1234",
  "image": "https://retailer1234.com/catalogs/1234.jpg",
  "is_main": true,
  "offers": [
    "11111",
    "22222",
    "33333"
  ],
  "target_regions": [
    "Brasil, São Paulo",
    "Brasil, São Paulo Butantã"
  ]
}
{% endhighlight %}

 **Replace `json` in {% raw  %}`{% highlight json %}`{% endraw  %} with the name of the language in the snippet. Here is the [list of supported languages](https://github.com/rouge-ruby/rouge/wiki/List-of-supported-languages-and-lexers).**
