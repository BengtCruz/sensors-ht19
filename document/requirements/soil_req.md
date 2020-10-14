Soil Moisture
* [ReqID:01] It shall be possible to have 1 soil moisture sensors.
* [ReqID:02] It shall be possible to initialize the module <soil_moisture>
* [ReqID:05] It shall be possible to get <soil_moisture_config_dry> from CAN bus.
* [ReqID:06] It shall be possible to read the <float> analouge value <soil_moisture_value> of the first soil moisture sensor once every second.
* [ReqID:09] It shall be possible to convert <soil_moisture_analouge_value> to <8 bits > <soil_moisture_value> representing a relative humidity procentage value. 
* [ReqID:10] The status of the sensor should be ERROR if <soil_moisture_value> is less than 0 or greater than 100.
* [ReqID:11] The program should output <soil_moisture_value> to the CAN bus.
* [ReqID:12] The program should output <soil_moisture_status> to the CAN bus.
* [ReqID:13] get <soil_moisture_config_wet> from CAN bus.
* [ReqID:14] When <soil_moisture_tolerance> has been confirmed okey, the value of <soil_moisture_status> should be INIITIALIZED.
