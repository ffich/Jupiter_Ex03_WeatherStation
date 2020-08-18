Ex03_WeatherStation
===================

Weather station based on Jupiter System and Weather click. It can measure temperature, relative humidity and barometric pressure.

### HW

* Main Platform: Jupiter Model A (https://www.jupitersystem.it/product-page/jupiter-model-a)
* Sensor: Weather Click (https://www.mikroe.com/weather-click)

### SW
* Node-RED
* Dashboard package
* BME280 package


### Description
This simple flow creates a local web based Weather station, with a dashboard displaing temperature, relative humidity and barometric pressure (with both gauges and charts for each data). The measurement are retrieved by the Jupiter board from the Weather click fitted in one of the board's mikrobus sockets, using i2c interface (a specific Node-RED package is used for this purpose).