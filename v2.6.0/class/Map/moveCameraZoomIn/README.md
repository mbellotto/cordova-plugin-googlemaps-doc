:green_heart: This is the latest document.

# map.moveCameraZoomIn()

Zooming in the camera without animation.

```
map.moveCameraZoomIn(callback);
```

## Parameters

name     | type      | description
---------|-----------|----------------------
callback | Function  | (optional) callback
--------------------------------------------

## Demo code

```html
<div id="map_canvas">
    <button>Click here</button>
</div>
```

```js
var div = document.getElementById("map_canvas");
var map = plugin.google.maps.Map.getMap(div);

var button = div.getElementsByTagName('button')[0];
button.addEventListener('click', function() {
  map.moveCameraZoomIn();
});
```

![](image.gif)
