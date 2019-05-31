---
layout: page
title: Introduction
---

<head>
 
<link rel="stylesheet" href="path/to/balloon.css">
 
  <style>
    .flex-container {
      display: flex;
      justify-content: center;
    }

    .flex-container > div {
      background-color: #f1f1f1;
      width: 100%;
      margin: 10px;
      text-align: center;
      line-height: 75px;
      font-size: 30px;
    }
  </style>
</head>

This is an example of how the final website would look.



<div class="introduction">
  <div class="flex-container">
    <div class="overlay">
     <a href="{{ site.baseurl }}/storiesIndex.html"><span class="caption" style="display:block">Short stories</span></a>
    </div>
    <div class="overlay">
      <a href="{{ site.baseurl }}/imagesIndex.html"><span class="caption" style="display:block">Short story images</span></a>
    </div>
  </div>
</div>
<hr />
<p>This site will display a list of shortstories and their associated images.</p>

 
<span data-balloon="I'm a tooltip." data-balloon-pos="up">Blablabla</span>