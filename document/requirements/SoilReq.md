#Soil Moisture
* [ReqID:01] It shall be possible to have 1 soil moisture sensors.
* [ReqID:02] It shall be possible to have a function to initialize the module <soil_moisture>
* [ReqID:03] The value of <soil_moisture_status> should be UNINITIALIZED by default.
* [ReqID:04] It shall be possible to get <soil_moisture_tolerance> from CAN bus.
* [ReqID:05] It shall be possible to get <soil_moisture_config_dry> from CAN bus.
* [ReqID:06] It shall be possible to read the <float> analouge value <soil_moisture_one_analouge_value> of the first soil moisture sensor once every second.
* [ReqID:07] It shall be possible to read the analouge value <soil_moisture_two_analouge_value> of the second soil moisture sensor once every second.
* [ReqID:09] It shall be possible to convert <soil_moisture_one_analouge_value> to <8 bits signed integer> <soil_moisture_one_value> representing a relative humidity procentage value. 
* [ReqID:14] The status of the sensor should be ERROR if <soil_moisture_one_value> is less than 0 or greater than 100.
* [ReqID:16] The status of the first soil moisture sensor should be OK if the status has not been set to ERROR.
* [ReqID:18] The program should output <soil_moisture_one_value> to the CAN bus.
* [ReqID:20] The program should output <soil_moisture_status> to the CAN bus with 3 bits.
* [ReqID:21] The first bit for the state of the module. (UNINITILAIZED | INIITIALIZED)
* [ReqID22] The second bit for the state of soil moisture sensor 1. (OK | ERROR)
* get <soil_moisture_config_wet> from CAN bus.
* [ReqID:23] When <soil_moisture_tolerance> has been confirmed okey, the value of <soil_moisture_status> should be INIITIALIZED.
