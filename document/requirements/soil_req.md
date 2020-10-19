Soil Moisture
* [ReqID:001] It shall be possible to have 1 soil moisture sensors.
* [ReqID:002] It shall be possible to initialize the module <soil_moisture>
* [ReqId:003] The module shall wait until gets valid value for <soil_moisture_min_cal_value> and <soil_moisture_max_cal_value>
* [ReqID:004] It shall be possible to get <soil_moisture_min_cal_value> from CAN bus.
* [ReqID:005] It shall be possible to get <soil_moisture_max_cal_value> from CAN bus.
* [ReqID:006] It shall be possible to read the <integer> analouge value <soil_moisture_analouge_value>
* [ReqID:007] It shall be possible to convert <soil_moisture_analouge_value> to <7 bits > <soil_moisture_value> representing a relative humidity procentage value. 
* [ReqID:008] The status of the sensor <soil_moisture_status> should be ERROR if <soil_moisture_value> is less than  <soil_moisture_min_cal_value>  or greater than <soil_moisture_max_cal_value>.
* [ReqID:009] It shall be possible to send <soil_moisture_value> to the CAN bus every 1000ms.
* [ReqID:010] <soil_moisture_status> should be UNIITIALIZED until it get valid  <soil_moisture_min_cal_value> and <soil_moisture_max_cal_value>. 
