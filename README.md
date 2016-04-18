leaflet-color-markers
=====================

color variations of the standard leaflet markers:

| Color | Marker 2x  | Marker  |
| ------------- |:-------------:|:-----:|
| Blue | ![Marker Red 2x](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-blue.png?raw=true) | ![Marker Red](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-blue.png?raw=true) |
| Red | ![Marker Red 2x](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-red.png?raw=true) | ![Marker Red](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-red.png?raw=true) |
| Green | ![Marker Green 2x](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-green.png?raw=true) | ![Marker Green](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-green.png?raw=true) |
| Orange | ![Marker Orange 2x](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-orange.png?raw=true) | ![Marker Orange](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-orange.png?raw=true) |
| Yellow | ![Marker Grey 2x](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-yellow.png?raw=true) | ![Marker Grey](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-yellow.png?raw=true) |
| Violet | ![Marker Grey 2x](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-violet.png?raw=true) | ![Marker Grey](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-violet.png?raw=true) |
| Grey | ![Marker Grey 2x](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-grey.png?raw=true) | ![Marker Grey](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-grey.png?raw=true) |
| Black | ![Marker Grey 2x](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-black.png?raw=true) | ![Marker Grey](https://raw.github.com/pointhi/leaflet-color-markers/master/img/marker-icon-black.png?raw=true) |

### Usage
```javascript
var greenIcon = new L.Icon({
  iconUrl: 'https://cdn.rawgit.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-green.png',
  shadowUrl: 'https://cdnjs.cloudflare.com/ajax/libs/leaflet/0.7.7/images/marker-shadow.png',
  iconSize: [25, 41],
  iconAnchor: [12, 41],
  popupAnchor: [1, -34],
  shadowSize: [41, 41]
});

L.marker([51.5, -0.09], {icon: greenIcon}).addTo(map);
```
