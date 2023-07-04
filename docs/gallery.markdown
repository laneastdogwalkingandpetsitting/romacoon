---
layout: page
title: Gallery
permalink: /gallery/
gallery_images:
 - name: Blue savannah
   filename: blue_savannah.jpg
 - name: Cranberry isle
   filename: cranberry_isle.jpg
 - name: Ellie
   filename: ellie.jpg
 - name: Jakatta Charlie Brown
   filename: Jakatta.jpg
 - name: Luna moon
   filename: luna_moon.jpg
 - name: Magazia
   filename: magazia.jpg
 - name: Mrs Shimbles
   filename: mrs_shimbles.jpg
 - name: Red adair
   filename: red_adair.jpg
 - name: Scarlet Ohara
   filename: scarlet_ohara.jpg

---
This is a gallery of my cats and kittens:
 <div style="display:flex; flex-wrap: wrap;">
  {% for img in page.gallery_images %}
    <div style="padding:10px; text-align: center">
    
      <a href="/assets/images/gallery/{{ img.filename }}">
          <img src="/assets/images/gallery/tn_{{ img.filename }}" style="box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);"/>
      </a>
      <br/>
      {{ img.name }}
    </div>
  {% endfor %}
  </div>

<script type="text/javascript" src="/assets/js/lightbox.js"></script>
<link rel="stylesheet" href="/assets/css/lightbox.css">

