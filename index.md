---
layout: base
title: Kushi's Homepage 
description: Home Page
---

˗ˏˋ ♡ ˎˊ˗

Kushi's fantastic blog 

‧₊˚ ☁️⋅♡🪐༘⋆


![computer]({{site.baseurl}}/images/notebooks/foundation/compsci.jpeg)

<head>
  <style>
    .grid-container {
      display: grid;
      grid-template-columns: repeat(3, 1fr); /* make 3 columns */
      gap: 10px; /* put gap between grid items */
      text-align: center; /* center text & images */
    }
    .grid-item img {
      width: 100%; /* Make image full width */
      height: auto; /* keep aspect ratio */
    }
    p {text-align: center;}
    .column {
    float: right;
    width: 100%;
    padding: 2px;
    }
    .row {
    display: flex;
    }
    .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); /* Dynamic columns */
            gap: 10px;
        }
        .grid-item {
            text-align: center;
        }
        .grid-item img {
            width: 100%;
            height: 200px;
            max-height: 200px;
            object-fit: contain; /* make image fit with fixed height */
        }
        .grid-item p {
            margin: 5px 0;
        }
        .center {
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;
}
  </style>
</head>
<body>
<h2 style="text-align:center;"> Welcome to Kushi Gade's blog!!  °˖✧</h2>
<br>
<strong><p> Computer Science Principles is awesome! </p></strong>
<div class="grid-container" id="grid_container">
</div>
  <div class="grid-container">
    <div class="grid-item">
      <img src="{{site.baseurl}}/images/comp sci.jpeg"> 
    </div>
    <div class="grid-item">
      <img src="images/grape.png" 
    </div>
    <div class="grid-item">
      <img src="images/orange.png">
      <p>Wow an orange</p>
    </div>
    <div class="grid-item">
      <img src="images/cherrys.png" alt="cherry">
      <p>Cherry!</p>
    </div>
    <div class="grid-item">
      <img src="images/pear.png" alt="pear">
    
    </div>
  </div>
<br>
<br>
<br>
<h2 style="text-align:center;"> Thanks for visiting my page </h2>

</body>









