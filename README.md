imagefx
=======

JavaScript Image Effects, focus, retro, color burning...

Credits: Test photo by Michael Dorausch <http://www.flickr.com/photos/chiropractic/5887094878/>

##Screenshot

![Screenshot](/img/screenshot.png)

##Usage

Load an image into a canvas element and call one of following functions:

  * image_fxpreset_cinemascope
  * image_fxpreset_retro
  * image_fxpreset_bnw  
  * image_fxpreset_focus

###Example:

```javascript
image_fxpreset_bnw('source');
```

Where 'source' is a canvas element.

###Example:

```html
<canvas id="source" width="520" height="350" onclick="image_fxpreset_focus('source');"></canvas>
```
