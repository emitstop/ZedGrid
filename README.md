ZedGrid
=======

An intuitive, fluid grid with flexible gutters.

###Semantic Edition
ZedGrid 1.1 adds support for semantically creating css grids through a SASS mixin.


*Semantic Usage*

  Include the zedGrid mixin and specify a *fraction numerator*, a *fraction denominator* and a *gutter width*. Gutter width values can be specified in any of the browser-supported CSS units.

  ```scss
  .my-column {
    @include zedGrid(1, 4, 20px);
  }
 ```

###Usage

To get started all you need to do is include the ZedGrid CSS in your project.

 ```html
 <link rel="stylesheet" href="zedgrid.min.css"/>
 ```
 
#####Basic Markup Structure
  ```html
  <div class="grid">

        <div class="column-1-3">
            1 / 3
        </div>
        
        <div class="column-1-6">
            1 / 6
        </div>

        <div class="column-1-6">
            1 / 6
        </div>

        <div class="column-1-3">
            1 / 3
        </div>

    </div>
 ```
 
#####Modifying Gutter Width
 
Gutter width is controlled by the $gutter variable in the SCSS file. You can also do this by modifying all instances of '20px' in the compiled css file.
 
#####Right align columns
Adding a class of __"pull-right"__ to your column wrappers will right align your columns.

---

###Benefits of ZedGrid:
1. Completely fluid column sizing.
2. Column gutters can be either fluid or fixed widths.
3. Gutters are handled with margins, allowing you to apply padding and border rules to your column containers.*

---

###Browser Support
* IE8+*
* Firefox 2.0+
* Chrome 4+
* Opera 7+
* Safari 2.0+
* Android Browser 2.1+*


_*IE8 and Android 4.3 and below do not support the margin-gutters and use a padding-based fallback_
