---
layout: post
title:  "Create query string without a loop"
date:   2016-10-20 20:08:54 +0200
categories: php
---
Create a query string without a loop.

{% highlight php %}
$query_string .= '?' . implode('&', $array);
{% endhighlight %}
