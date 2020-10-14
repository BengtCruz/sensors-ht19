### water level sensor requirement

* [ReqId:001] It shall be possible to initialize the module
* [ReqId:002] It shall be possible to read the analog value of the water level sensor <analog_level_value> every 1000ms
* [ReqId:003] It shall be possible to convert <analog_level_value> to a percentage representing the water level <water_level>
* [ReqId:004] If <water_level> is less than <water_level_min_value> or greater than <water_level_max_value> then
            <water_level_status> shall be set to WATER_LEVEL_ERROR
* [ReqId:005] It shall be possible to send <water_level> to the CAN bus
* [ReqId:006] It shall be possible to send <water_level_status> to the CAN bus
