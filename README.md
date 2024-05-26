# leaflet-pulse-icon

<div style="text-align:center" align="center">
  <img src="http://mapshakers.github.io/projects/leaflet-pulse-icon/leaflet-pulsing-icon.gif" alt="leaflet-pulse-icon" />
</div>

A very simple [Leaflet](http://leafletjs.com) plugin provides pulsing icon.

_Requires Leaflet 0.7.0 or newer and modern browser_

## Demo

[Check out demo!]()

## Using the plugin

#### Install

`npm install @ansur/leaflet-pulse-icon` </br>
or clone repo & run `npm install` </br>
or copy files from releases

#### Use

Include the CSS and JavaScript files located in `\dist` directory.

```html
<script src="../L.Icon.Pulse.js" />
<link rel="stylesheet" href="../L.Icon.Pulse.css" />
```

### Usage

Create a new L.Icon.Pulse

```javascript
var pulsingIcon = L.icon.pulse({ iconSize: [20, 20], color: "red" });
var marker = L.marker([50, 15], { icon: pulsingIcon }).addTo(map);
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
