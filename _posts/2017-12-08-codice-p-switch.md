---
title: "Codice P-Switch"
date: 2017-12-08 13:30:00 +0100
mathjax: false
categories: codice
layout: post
---
{% highlight html %}
<div>
  <style>
    #mmb_pswitch,
    #mmb_pswitch_gfx,
    .mmb_coin,
    .mmb_block {
        user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        -o-user-select: none;
        -webkit-user-select: none;
    }
    #mmb_pswitch {
        display: none;
    }
    #mmb_pswitch_gfx {
        vertical-align: middle;
        cursor: pointer;
        display: inline-block;
        width: 16px;
        height: 18px;
    }
    #mmb_pswitch + #mmb_pswitch_gfx {
        background: url('http://i.imgur.com/40nmlmK.png') no-repeat;
        background-position: -16px -14px;
    }
    #mmb_pswitch:checked + #mmb_pswitch_gfx {
        background: url('http://i.imgur.com/40nmlmK.png') no-repeat;
        background-position: -16px 4px;
    }
    .mmb_block,
    .mmb_coin {
        vertical-align: middle;
        display: inline-block;
        width: 16px;
        height: 16px;
    }
    #mmb_pswitch ~ .mmb_block,
    #mmb_pswitch:checked ~ .mmb_coin {
        background: url('http://i.imgur.com/40nmlmK.png') no-repeat;
        background-position: 0px 0px;
    }
    #mmb_pswitch:checked ~ .mmb_block,
    #mmb_pswitch ~ .mmb_coin {
        background: url('http://i.imgur.com/40nmlmK.png') no-repeat;
        background-position: 0px -16px;
    }
  </style>A P-Switch effect can be achieved without Javascript, as demonstrated below.
  <br />
  <input type="checkbox" id="mmb_pswitch"><label for="mmb_pswitch" id="mmb_pswitch_gfx"></label><br />
  <br />
  <span class="mmb_block"></span><span class="mmb_block"></span><span class="mmb_coin"></span><span class="mmb_coin"></span><span class="mmb_block"></span><span class="mmb_block"></span><br />
  <br />
  <span class="mmb_coin"></span> View the page's source to find out how this is done. <span class="mmb_coin"></span><br />
  <br />
  It is limited, though. The P-Switch has to be placed before the blocks and coins in HTML, and all have to be in the same container.
</div>
{% endhighlight %}
<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;div&gt;</span><br data-jekyll-commonmark-ghpages="">  <span class="nt">&lt;style&gt;</span><br data-jekyll-commonmark-ghpages="">... <br data-jekyll-commonmark-ghpages="">
   &lt;/style&gt;</span>
<br data-jekyll-commonmark-ghpages=""><span class="nt">&lt;/div&gt;</span></code></pre></figure>
