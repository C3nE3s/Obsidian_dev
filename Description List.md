---
author: Ben Myers
date: 2021-08-06
tags: ['HTML', 'symantic']
aliases: ['dl', 'symantic html with <dl>']
createdAt: 2021-11-01
---
# Description List
[Source Blog Post Here](https://benmyers.dev/blog/on-the-dl/)

``` html
<dl>
	<dt>Description Term</dt>
	<dd>Description Detail</dd>
</dl>
```

>For what it's worth, these screenreader experiences _aren't_ hypothetical — they're benefits that screenreader users really get from using `<dl>` [in most browser/screenreader combinations](https://a11ysupport.io/tech/html/dl_element). Admittedly, however, support for the `<dl>` element is not yet universal. You may decide that screenreaders' fallback experience — treating the list as standalone text nodes — isn't sufficient for your use case, and instead opt for something like a `<ul>` until support improves.