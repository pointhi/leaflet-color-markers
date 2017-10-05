leaflet-color-markers
=====================

color variations of the standard leaflet markers:

| Color | Marker 2x  | Marker  |
| ------------- |:-------------:|:-----:|
| Blue | ![Marker Red 2x](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-blue.png) | ![Marker Red](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-blue.png) |
| Red | ![Marker Red 2x](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-red.png) | ![Marker Red](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-red.png) |
| Green | ![Marker Green 2x](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-green.png) | ![Marker Green](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-green.png) |
| Orange | ![Marker Orange 2x](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-orange.png) | ![Marker Orange](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-orange.png) |
| Yellow | ![Marker Grey 2x](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-yellow.png) | ![Marker Grey](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-yellow.png) |
| Violet | ![Marker Grey 2x](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-violet.png) | ![Marker Grey](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-violet.png) |
| Grey | ![Marker Grey 2x](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-grey.png) | ![Marker Grey](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-grey.png) |
| Black | ![Marker Grey 2x](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-2x-black.png) | ![Marker Grey](https://raw.githubusercontent.com/pointhi/leaflet-color-markers/master/img/marker-icon-black.png) |

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
