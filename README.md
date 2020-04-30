# Minigrid
Responsive and lightweight CSS grid

## Installation
Simply include `minigrid.min.css` into your website.

## Usage 
```
<div class="container">
  <div class="row">
    <div class="col-3">
      <!-- This content will take up 3/12 (or 1/4) of the container -->
    </div>
    <div class="col-3">
      <!-- This content will take up 3/12 (or 1/4) of the container -->
    </div>
    <div class="col-6">
      <!-- This content will take up 6/12 (or 1/2) of the container -->
    </div>
  </div>
</div>
```
### Creating grids
Simply state the number of columns you want your content to occupy in the `.col` class.
For example, if you want your content to take up 8 columns (out of 12), simply give your content the class `.col-8`.

### Preserving grids on mobile
Minigrid is built mobile first, so all columns will expand to the full container width on smaller screens. If you don’t want columns to expand on mobile devices and small screens, simply add -sm to the end of your column class name.
For example, if you want to have two blocks of content floating side-by-side on small screens, each would be given the class name `.col-6-sm`.

### Positioning
simply give your content the `.left`, `.right`, `.center` or `.justify` class to position your content.
