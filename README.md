ZedGrid
=======

[View on github pages](http://emitstop.github.io/ZedGrid/)

An intuitive, fluid grid with flexible gutters.


###Markup Usage

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
 
Gutter width is controlled by the $gutterMarkup variable on line 68 of the SCSS/LESS file. You will need to recompile the SCSS/LESS with your updated gutter width in order to change it.
 
#####Right align columns
Adding a class of __"pull-right"__ to your column wrappers will right align your columns.


---

###Semantic Edition
ZedGrid 1.2 adds support for semantically creating css grids through a SASS & LESS mixin.


**Semantic Usage**

  Include the zedGrid mixin in your SASS project, and specify a **fraction numerator**, a **fraction denominator** and a **gutter width**. Gutter width values can be specified in any of the browser-supported CSS units.

  ```scss
  //For example, if you wanted 1/4th size columns with 20px gutters:
  .my-column {
    @include zedGrid(1, 4, 20px);
  }

 ```

 **Note**: A clearfix is required on all column containers!
 
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
