---
layout: docs
title: Icons
description: Guidance and suggestions for using icon libraries with Arizona Bootstrap.
group: extend
---

These icons have been approved to use within Arizona web assets like Arizona
Quickstart, and Arizona Bootstrap.

- [Arizona Icons](https://github.com/az-digital/az-icons) (Arizona branded icons)
- [Google Material icons (Sharp)](https://material.io/resources/icons/?style=sharp)

## Material Icons Implementation

Include a the Material Icons' stylesheet to your project in order to use the font icons. [Refer to Material Icons docs](https://google.github.io/material-design-icons/#icon-font-for-the-web) for more information.

{% highlight html %}
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
{% endhighlight %}


Google's Material font icons can be implemented just like text, in that they can combined with any utility class available to text. 

Your `span` should include the `.material-icons` class along with any utility classes you want to include. The text inside the `span` should be the ID/name of the icon you want to use. [Browse the font icon library (sharp style)](https://material.io/resources/icons/?style=sharp) to find the ID of your desired icon.

{% capture example %}
<span class="material-icons text-sky display-4">accessible_forward</span>
<span class="material-icons text-azurite display-3">accessible_forward</span>
<span class="material-icons text-blue display-1">accessible_forward</span>
{% endcapture %}
{% include example.html content=example %}
