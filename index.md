---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: I'm Kyle Lambert | Designer, Developer, Business Builder
---

<article class="post-wrap home-wrap">
  <h1>Hey, I&rsquo;m Kyle Lambert</h1>
  <h2>Simply put, I make things and help people.</h2>
  <p>I research, design, draw, write, and code. I live in "sunny" Portland, OR with <a href="https://thefittutor.com/" target="_blank">my wife Allison</a> and two pups Chainsaw and Samurai Warrior Princess. Currently I spend my days helping change the way people rent at <a href="https://cozy.co/">Cozy.co</a>.</p>

  <h2>Around the web</h2>
  <ul>
    <li>See my <a href="https://dribbble.com/calloutcreative" target="_blank">Dribbble portfolio</a></li>
    <li>Buy a logo at my <a href="https://bootstraplogos.com" target="_blank">logo store</a></li>
    <li>Follow me on twitter <a href="https://twitter.com/imkylelambert" target="_blank">@imkylelambert</a></li>
    <li>Email me at <a href="mailto:imkylelambert@gmail.com">imkylelambert [at] gmail.com</a></li>
  </ul>
  <h2>Some recent articles</h2>

  {% for post in site.posts %}
    <a href="{{ post.url }}"><h3>{{ post.title }}</h3></a>
  {% endfor %}

</article>
