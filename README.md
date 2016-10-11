# slider-pro
In this article [Solodev](https://www.solodev.com/) teaches you how to build a hero slider using a responsive jQuery slider called sliderPro that features touch-swipe, text thumbnails, slide loops, animated layers, and JavaScript breakpoints. sliderPro has emerged as one of the go-to jQuery sliders on the web and this article will get you started working with it.

## Tutorials

For detailed instructions, view Solodev's [Crafting a Hero Slider with sliderPro.js]() article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/m5svs63m/).

## HTML

The slider contains the following basic HTML markup.

```
<div id="example1" class="slider-pro">
   <div class="sp-slides">
      <div class="sp-slide">
         <img class="sp-image" src="../src/css/images/blank.gif"
            data-src="images/slide1.jpg"
            data-retina="images/slide1.jpg"/>
         <p class="sp-layer sp-white sp-padding"
            data-horizontal="50" data-vertical="50"
            data-show-transition="left" data-hide-transition="up" data-show-delay="400" data-hide-delay="200">
            Lorem ipsum
         </p>
         <p class="sp-layer sp-black sp-padding hide-small-screen"
            data-horizontal="180" data-vertical="50"
            data-show-transition="left" data-hide-transition="up" data-show-delay="600" data-hide-delay="100">
            dolor sit amet
         </p>
         <p class="sp-layer sp-white sp-padding hide-medium-screen"
            data-horizontal="315" data-vertical="50"
            data-show-transition="left" data-hide-transition="up" data-show-delay="800">
            consectetur adipisicing elit.
         </p>
      </div>
      <div class="sp-slide">
         <img class="sp-image" src="../src/css/images/blank.gif"
            data-src="images/slide2.jpg"
            data-retina="images/slide2.jpg"/>
         <h3 class="sp-layer sp-black sp-padding" 
            data-horizontal="40" data-vertical="10%" 
            data-show-transition="left" data-hide-transition="left">
            Lorem ipsum dolor sit amet
         </h3>
         <p class="sp-layer sp-white sp-padding hide-medium-screen" 
            data-horizontal="40" data-vertical="22%" 
            data-show-transition="left" data-show-delay="200" data-hide-transition="left" data-hide-delay="200">
            consectetur adipisicing elit
         </p>
         <p class="sp-layer sp-black sp-padding hide-small-screen" 
            data-horizontal="40" data-vertical="34%" data-width="350" 
            data-show-transition="left" data-show-delay="400" data-hide-transition="left" data-hide-delay="500">
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
         </p>
      </div>
      <div class="sp-slide">
         <img class="sp-image" src="../src/css/images/blank.gif"
            data-src="images/slide3.jpg"
            data-retina="images/slide3.jpg"/>
         <p class="sp-layer sp-white sp-padding" 
            data-position="centerCenter" data-vertical="-50" 
            data-show-transition="right" data-hide-transition="left" data-show-delay="500" >
            Lorem ipsum dolor sit amet
         </p>
         <p class="sp-layer sp-black sp-padding hide-small-screen" 
            data-position="centerCenter" data-vertical="50" 
            data-show-transition="left" data-show-delay="700" data-hide-transition="right" data-hide-delay="200">
            consectetur adipisicing elit
         </p>
      </div>
      <div class="sp-slide">
         <img class="sp-image" src="../src/css/images/blank.gif"
            data-src="images/slide4.jpg"
            data-retina="images/slide4.jpg"/>
         <p class="sp-layer sp-black sp-padding" 
            data-position="bottomLeft"
            data-show-transition="up" data-hide-transition="down">
            Lorem ipsum dolor sit amet <span class="hide-small-screen">, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</span> <span class="hide-medium-screen">Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</span>
         </p>
      </div>
      <div class="sp-slide">
         <img class="sp-image" src="../src/css/images/blank.gif"
            data-src="images/slide5.jpg"
            data-retina="images/slide5.jpg"/>
         <p class="sp-layer sp-black sp-padding" 
            data-position="bottomLeft"
            data-show-transition="up" data-hide-transition="down">
            Lorem ipsum dolor sit amet <span class="hide-small-screen">, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</span> <span class="hide-medium-screen">Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</span>
         </p>
      </div>
   </div>
   <div class="sp-thumbnails">
      <div class="sp-thumbnail">
         <div class="sp-thumbnail-title">Lorem ipsum</div>
         <div class="sp-thumbnail-description">Dolor sit amet, consectetur adipiscing elit sed</div>
      </div>
      <div class="sp-thumbnail">
         <div class="sp-thumbnail-title">Do eiusmod</div>
         <div class="sp-thumbnail-description">Tempor incididunt ut labore et dolore magna aliqua</div>
      </div>
      <div class="sp-thumbnail">
         <div class="sp-thumbnail-title">Ut enim</div>
         <div class="sp-thumbnail-description">Ad minim veniam, quis nostrud exercitation</div>
      </div>
      <div class="sp-thumbnail">
         <div class="sp-thumbnail-title">Ullamco oris</div>
         <div class="sp-thumbnail-description">Nisi ut aliquip ex ea commodo consequat</div>
      </div>
      <div class="sp-thumbnail">
         <div class="sp-thumbnail-title">Duis aute</div>
         <div class="sp-thumbnail-description">Irure dolor in reprehenderit in voluptate velit</div>
      </div>
   </div>
</div>

```
## CSS

All required CSS is in sliderPro.css

## External Includes

This tutorial includes the following third party resources.
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://www.solodev.com/assets/slider-pro/jquery.sliderPro.min.js"></script>
<script src="https://www.solodev.com/assets/slider-pro/sliderPro.js"></script>
```
