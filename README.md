# leaflet-pulse-icon

fork From [mapshakers/leaflet-icon-pulse](https://github.com/mapshakers/leaflet-icon-pulse)

_Requires Leaflet 0.7.0 or newer and modern browser_

I just add feature imageIcon inside pulsing

## Demo

[Check out demo!](https://hallofajar.github.io/leaflet-icon-pulse/example/)

## Using the plugin

#### Use

Include the CSS and JavaScript files located in `\dist` directory.

```html
<script src="../L.Icon.Pulse.js" />
<link rel="stylesheet" href="../L.Icon.Pulse.css" />
```

### Usage

Create a new L.Icon.Pulse

```javascript
var pulsingImage = L.icon.pulse({
  iconSize: [20, 20],
  color: "red",
  iconImage: "img/icon.png",
});
var marker = L.marker([50, 15], { icon: pulsingImage }).addTo(map);
```

### Options

| Property  | Description       | Default Value | Possible values        |
| --------- | ----------------- | ------------- | ---------------------- |
| color     | color of pulse    | 'red'         | any CSS color          |
| fillColor | color of dot      | 'red'         | any CSS color          |
| iconSize  | size of L.divIcon | [12,12]       | <Point> [width,height] |
| animate   | enable pulsing    | true          | true\|false            |
| heartbeat | pulsing beat      | 1             | number (seconds)       |
| iconImage | image Icon        | 'null'        | url image png          |

## License

**leaflet-pulse-icon** is free software, and may be redistributed under the MIT-LICENSE.
