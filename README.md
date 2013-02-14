# Noisy URIs

Ready-made noise images as data URIs. Available in [Sass](http://sass-lang.com/), [LESS](http://lesscss.org/), and vanilla CSS flavours.

### What is this?
Data URIs (unique resource identifiers) are resources (such as images) converted into text so that they can be used with webpages without referencing external files. A great explanation  of data URIs can be found on [CSS-Tricks.com](http://css-tricks.com/data-uris/)

Repeating noise images are very useful for adding a little texture to all kinds on element on a web page. When you're designing in Photoshop it's simple to adjust the opacity and brightness of your noise textures, however within CSS it's not that easy. Noisy URIs was created to let people who 'design in the browser' a quick and flexible way to design with noise textures.

### Example
Basic noise example. Light and dark noise images are also provided.

![noisy URIs example](http://markdurrant.github.com/noisy-uris/example.png)

### Usage
#### Sass
To use the noisy URIs with Sass first import one of the .scss files to your stylesheet with `@import`. You can then use the noisy URIs variables in your stylesheet. For example…

```sass
@import "_base_noise_uris.scss";

.noise{
  background-image: url($base-noise-050);
}
```


#### LESS
To use the noisy URIs with LESS first import one of the .less files to your stylesheet with `@import`. You can then use the noisy URIs variables in your stylesheet. For example…

```sass
@import "base_noise_uris.less";

.noise{
  background-image: url(@base-noise-050);
}
```

#### CSS
To use the noisy URIs in vanilla CSS simply copy and paste the class you require into your stylesheet. 

### Browser support
Data URIs are supported in all modern browsers and in IE8+. If you require IE7 support you can use one of the included images as a fallback.

### File sizes
It is important to remember that data URIs have slightly larger files sizes than the original files, so use them sparingly. Be careful not to use the same data URI more than once in a stylesheet. Do not use data URIs with a Sass or LESS mixin that generates duplicate CSS for example mixins that handle vendor prefixing. 

### Creation
Raw data URI's were created with [image2css](https://github.com/mhuckaby/image2cssConverter).

### Licence
Noisy URIs is licence under the [WTFPL](http://www.wtfpl.net/about/) licence.

### Author
Created by [Mark Durrant](https://twitter.com/M6_D6) during 10% time at [pebble {code}](https://twitter.com/pebblecode)
