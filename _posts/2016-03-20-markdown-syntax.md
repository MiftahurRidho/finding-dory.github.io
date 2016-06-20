---
layout: post
title:  "Update seputar finding dory"
date:   2016-03-15
excerpt: "informasi umum finding dory."
tag:
- markdown 
- syntax
- sample
- test
- jekyll
comments: true
---

#### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

And you'll get something that looks like this:

<figure class="half">
	<a href="https://raw.githubusercontent.com/fheo18/finding-dory.github.io/gh-pages/a.png"><img src="https://raw.githubusercontent.com/fheo18/finding-dory.github.io/gh-pages/a.png"></a>
	<a href="https://raw.githubusercontent.com/fheo18/finding-dory.github.io/gh-pages/b.jpg"><img src="https://raw.githubusercontent.com/fheo18/finding-dory.github.io/gh-pages/b.jpg"></a>
	<figcaption>Two images.</figcaption>
</figure>

#### Three Up

Apply the `third` class like so to display three images side by side that share the same caption.

{% highlight html %}
<figure class="third">
	<img src="/images/image-filename-1.jpg">
	<img src="/images/image-filename-2.jpg">
	<img src="/images/image-filename-3.jpg">
	<figcaption>Caption describing these three images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="third">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<figcaption>Three images.</figcaption>
</figure>

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}
