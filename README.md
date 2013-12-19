ZedGrid
=======

A simple, flexible, fluid grid with gutters that *make sense*.



###Usage

To get started all you need to do is include the ZedGrid CSS in your project.

 ```html
 <link rel="stylesheet" href="zedgrid.css"/>
 ```
 
 **Basic Markup Structure**
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
 
Note: adding a class of __"pull-right"__ to your column wrappers will right align your columns.

---

###Subjective Benefits of ZedGrid:
1. Column gutters are created using margins and calc() rather than padding. This allows you to **apply padding directly to your column wrappers**, if you so wish.
2. The "column" class name is spelled out, rather than being abbreviated to something more ambiguous.
3. Supports every variation of X/X through numbers 1 - 12.
4. Completely fluid grid.

---

###Browser Support
* IE9+
* Firefox 4.0+
* Chrome 19+
* Opera 15+
* Safari 6.0+
* Android Browser 4.4+



