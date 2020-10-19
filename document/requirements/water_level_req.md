### water level sensor requirement

* [ReqId:001] It shall be possible to initialize the module
* [ReqId:002] <water_level_status> should be UNINITILIZED until it gets valid calibration values
* [ReqId:003] The module shall wait until gets valid value for <water_level_min_value> and <water_level_max_value>
* [ReqId:004] It shall be possible to get <water_level_min_value> from CAN bus
* [ReqId:005] It shall be possible to get <water_level_max_value> from CAN bus
* [ReqId:006] It shall be possible to read the analog value of the water level sensor <analog_level_value> every 1000ms
* [ReqId:007] It shall be possible to convert <analog_level_value> to a percentage representing the water level <water_level>
* [ReqId:008] If <water_level> is less than <water_level_min_value> or greater than <water_level_max_value> then
            <water_level_status> shall be set to WATER_LEVEL_ERROR
* [ReqId:009] It shall be possible to send <water_level> to the CAN bus every 1000ms
* [ReqId:010] It shall be possible to send <water_level_status> to the CAN bus every 1000ms