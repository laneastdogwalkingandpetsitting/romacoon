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
 - name: Luna moon
   filename: luna_moon.jpg
 - name: Magazia
   filename: magazia.jpg
 - name: Mrs Shimbles
   filename: mrs_shimbles.jpg
 - name: Red adair
   filename: red_adair.jpg
 - name: Scarlet O'hara
   filename: scarlet_ohara.jpg
 - name: All about Steve
   filename: Romacoon_All_about_Steve.jpg
 - name: Autumn Gold
   filename: Romacoon_Autumn_Gold.jpg
 - name: Baby Bear
   filename: Romacoon_Baby_Bear.jpg
 - name: Black Sambuca
   filename: Romacoon_Black_Sambuca.jpg
 - name: Blinky Bill
   filename: Romacoon_Blinky_Bill.jpg
 - name: Jack Sparrow
   filename: Romacoon_Jack_Sparrow.jpg
 - name: Kenzo
   filename: Romacoon_Kenzo.jpg
 - name: Magic
   filename: Romacoon_Magic.jpg
 - name: Micky Finn
   filename: Romacoon_Micky_Finn.jpg
 - name: Poseidon
   filename: Romacoon_poseidon.jpg
 - name: Premonition
   filename: Romacoon_Premonition.jpg
 - name: Raksha
   filename: Romacoon_Raksha.jpg
 - name: Reckless
   filename: Romacoon_Reckless.jpg
 - name: Rufus
   filename: Romacoon_Rufus.jpg
 - name: Rumour
   filename: Romacoon_Rumour.jpg
 - name: Saburou and Kenzo
   filename: Romacoon_Saburou_and_Kenzo.jpg
 - name: Somersby
   filename: Romacoon_Somersby.jpg
 - name: Sorceress Spangle
   filename: Romacoon_Sorceress_Spangle.jpg
 - name: The Joshua Tree
   filename: Romacoon_The_Joshua_Tree.jpg
 - name: Tilly Bearkins
   filename: Romacoon_Tilly_Bearkins.jpg
 - name: Walter Wombat
   filename: Romacoon_Walter_Wombat.jpg
 - name: Tigg
   filename: Tigg.jpg 

---
This is a gallery of some of my cats and kittens (past and present):
 <div style="display:flex; flex-wrap: wrap;">
  {% for img in page.gallery_images %}
    <div style="padding:10px; text-align: center">
    
      <a href="/assets/images/gallery/{{ img.filename }}">
          <img src="/assets/images/gallery/thumbnails/tn_{{ img.filename }}" style="box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);"/>
      </a>
      <br/> 
      {{ img.name }}
    </div>
  {% endfor %}
  </div>

<script type="text/javascript" src="/assets/js/lightbox.js"></script>
<link rel="stylesheet" href="/assets/css/lightbox.css">

