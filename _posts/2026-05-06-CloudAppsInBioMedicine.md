---
layout: post
title: NarxCare- A Harmful Cloud Application in Biomedicine
subtitle: When clinical prediction models go unchecked
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: Bill Smith
---

{: .box-success}
Note: This blog post does not speak highly of a particular cloud application in Biomedicine. 

**If we don't critique harmful applications in biomedicine, how can we say we are promoting health?**

## A BIG problem doesn't have an easy solution

The United States has the highest overdose and drug related death rate in the world by a significant margin. The US overdose epidemic is a complex issue for which many mistakes have been made due to oversimplification. Complex issues can have seemingly viable solutions for which tech companies are often happy to quickly provide / roll out solutions for in the form of cloud-based applications. One noteworthy example of a seemingly viable solution is Bamboo Health’s Narxcare – a prescription drug monitoring program-based analytics platform marketed as a clinic al support tool. 

Narxcare belongs to a class of monitoring and surveillance programs called prescription drug monitoring programs or PDMPs
[which have been the subject of much public scrutiny by numerous clinicians](https://journals.lww.com/journaladdictionmedicine/abstract/2022/05000/_nobody_knows_how_you_re_supposed_to_interpret.26.aspx). Narxcore claims to  impact over one billion patient encounters annually across the US and has been used across 45 states in the US while its platform still lacks sufficient evidence for its wide clinical implementation. 

Here's a Map from Narxcare on PDMP Coverage of the US from their 2025 Impact Report: 

![Map of Narxcore US Coverage]("/images/Narxcoremap.png)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
