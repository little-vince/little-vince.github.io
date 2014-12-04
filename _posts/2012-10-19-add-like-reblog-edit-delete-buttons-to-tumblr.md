---
layout: post
title: "[Tutorial] How to add Like, Reblog, Edit and Delete buttons under every Tumblr post"
tags: tutorial tumblr lred
---

It’s an absolute pain always having to go to the permalink page to like, edit or delete a post.
Whether you’re doing some mass post editing or simply don’t like the fact that an extra click is extra effort for your visitors, then this is what this post aims to address.

Here are some screenshots to show you what the final product looks like. Click for full sized image.

To others:
[![Visitor Screenshot](https://github.com/little-vince/lred/raw/master/screenshots/visitor.png?raw=true "What visitors see.")](https://github.com/little-vince/lred/raw/master/screenshots/visitor.png?raw=true)

To you:
[![Visitor Screenshot](https://github.com/little-vince/lred/raw/master/screenshots/owner.png?raw=true?raw=true "What you see.")](https://github.com/little-vince/lred/raw/master/screenshots/owner.png?raw=true?raw=true)

To some, the multitude of ‘Dashboard’ and ‘Follow’ links may be a little bit daunting. If you don’t like the look of it or if you don’t think that it will work with your theme then now is the time to leave.
Everyone else, follow carefully. :)

**Disclaimer: This tutorial assumes you have basic HTML knowledge and that you know how to edit your Tumblr theme.**

## Step 1 
Add the following code to your Tumblr theme, right before the `</head>` tag.
{% highlight html %}
<script type="text/javascript" src="http://little-vince.tumblr.com/lred.js"></script>
{% endhighlight %}

## Step 2
Place the following code somewhere between the `{block:Date}` and `{/block:Date}` tags. If you have more than one set of those tags then you will need to work out which one is best to put it in.
{% highlight html %}
<div class="reblogframe">
  <iframe class="lred" scrolling="no" width="100%" height="26px" frameborder="0" data-plink="{Permalink}" data-reblog="{ReblogURL}" data-user="{Name}" data-pic="{URLEncodedPortraitURL-64}"></iframe>
</div>
{% endhighlight %}

### Step 3
That's it! You might need to edit your theme a bit to make it fit in a little more but assuming all things went well, it should look vaguely similar to the screenshots up there.

Now you can enjoy editing and deleting your posts, and your visitors can enjoy liking and rebloging your posts, without having to through the permalink page. :) If you have any questions or need help, feel free to [send me a message](http://little-vince.tumblr.com/ask).
