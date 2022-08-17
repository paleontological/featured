# featured
files for What's New? sections on [PRI](https://www.priweb.org), [CNC](https://www.cayuganaturecenter.org) and [MOTE](https://www.museumoftheearth.org).

> **Warning** - any changes here will auto-populate to all three sites, so make sure you're all set before you push any updates!

## how to update
### 1. create new thumbnail images 🖼️
  * images should be 16:9 aspect ratio
  * max 1000px wide and [webp format](https://developers.google.com/speed/webp/) to save on file size
  * run through [tinyPNG](https://tinypng.com/) compression tool
  * use the same file names and overwrite old images (this way you don't have to update the image URLs in the HTML)

### 2. update link text and URLs 📝
  * in featured.html, link text and URLs for each section are indicated by `<!--UPDATE LINK URLS & TEXT HERE-->`
  * the first URL should also be updated on each section's thumbnail, indicated by `<!--UPDATE IMAGE LINK HERE-->`

### 3. that's all! 😎
  * pat yourself on the back for a job well done (also, probably refresh the PRI home page one more time to make sure your changes work correctly!)
  
## how to add to a page
add the following code to a page. this is intended to be used on a squarespace index page in one of the sections, but can be adapted to use elsewhere as well.
```html
<div id="featured-content">	
</div>
<script src="https://paleontological.github.io/featured/featured.js" integrity="sha512-aC7jd2p39ug8GKd3DjJ+pYSZAgjvYi4Nw0K90KDaI49HvPZsYzEI/jFgB4wyHudYWXpG75GawpfCbNQ7kCwxLQ==" crossorigin="anonymous"></script>
```
