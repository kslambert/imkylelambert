---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Blogging Like a Hacker
---

<article class="post-wrap home-wrap">
  <h1>Hey, I&rsquo;m Kyle Lambert</h1>
  <h2>Simply put, I build things.</h2>
  <p>I research, design, draw, write, and code. I live in "sunny" Portland, OR with <a href="https://thefittutor.com/" target="_blank">my wife Allison</a> and two pups Chainsaw and Samurai Warrior Princess. Currently I spend my days helping change the way people rent at <a href="https://cozy.co/">Cozy.co</a>.</p>

  <h2>Around the web</h2>
  <p>See my <a href="https://dribbble.com/calloutcreative" target="_blank">Dribbble portfolio</a></p>
  <p>Buy a logo at my <a href="https://bootstraplogos.com" target="_blank">logo store here</a></p>
  <p>Follow me on twitter <a href="https://twitter.com/imkylelambert" target="_blank">@imkylelambert</a></p>
  <p>Email me at <a href="mailto:imkylelambert@gmail.com">imkylelambert [at] gmail.com</a></p>
  <h2>Here are some recent thoughts</h2>
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}"><h3>{{ post.title }}</h3></a>
      </li>
    {% endfor %}
  </ul>
</article>
