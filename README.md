# jQuery plugin "jquery_tabbed_images"
jQuery plugin for swithching images with tabs

## Usage
1. Load plugin ( with &lt;script&gt;, require() e.t.c.)
2. To add plugin functionality to a DOM structure simply use:
```javascript
$( 'container' )
  .tabbedImages({
    img_list : [ /* paths in string format */ ] // i.e. [ 'imgs/image01.jpg', 'imgs/image02.jpg' ]  
  });
```

## Plugin options
Edit plugin inner object configMap to setup plugin options or pass them on viewer initialization (see example above).

|           Option         |  Type  |            Description            |              Example              |
|--------------------------|--------|-----------------------------------|-----------------------------------|
| img_list                 | array  | images paths the array of strings | [ 'imgs/image01.jpg', 'imgs/image02.jpg' ] |

## Git pages
https://web-developer-poletski.github.io/jquery_tabbed_images/

## Releases
1.0.0 https://github.com/web-developer-poletski/jquery_tabbed_images/releases/tag/v1.0.0
