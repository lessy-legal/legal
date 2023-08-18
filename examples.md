---
title: Examples of supported markup features
language: en
---

## Text styling

## Header 2
### Header 3
#### Header 4

Normal text

*Italic text*

**Bold text**

**Note.** This is an important note
{: .note}

**Warning.** This is a alert
{: .alert}

Here is a multiline alert
<div class="alert" markdown="1">
**Warning**

Lorem ipsum dolor set amet.

Take care of yourself!
</div>

## Lists
### Unordered list
* Lorem
* Ipsum
  * Dolor
  * Set
* Amet

### Ordered list
1. Lorem
2. Ipsum
3. Dolor


## Links

* Here is a [link](https://lessy.app)
* A mailto link: [feedback@lessy.app](mailto:feedback@lessy.app)

A URL in text does not become a link automatically.
* https://this.is.not.a.link.com/
* [this.is.a.link.com](https://this.is.a.link.com/)


## Buttons

[A link that looks like a button](https://lessy.app){: .button}

[A button with extra top margin](https://lessy.app){: .button .button_top-margin}


## Images

![A food basket](https://yastatic.net/s3/edadeal-public-static/corecase/images-for-desktop-segments/food-rec.png)

Alt text is shown when the image hasn't loaded.


## Tables

| Here | are | some | table | headers |
| -------- | ------- | -------- | ------- |  ------- |
| Table cell 1 | Table cell 2 | Table cell 3 | Table cell 4 |  Table cell<br /><br />With 2 paragraphs |
| Table cell 1 | Table cell 2 | Table cell 3 | Table cell 4 |  Table cell 5 |


## Code snippets

### Inline code
Wrap inlide code snippets in ticks: `becomeHappy(now)`.

### Block code
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

[List of languages](https://github.com/rouge-ruby/rouge/wiki/List-of-supported-languages-and-lexers) supported by syntax highlighter.
