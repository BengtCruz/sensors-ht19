### Ambient temperature and humidity sensor requirements

* [ReqId:001] It shall be possible to initilize the module
* [ReqId:002] <sensor_status> should be UNINITILIZED until it gets valid calibration values
* [ReqId:003] The module shall wait until gets valid value for <temperature_min_cal_value> and <temperature_max_cal_value>
* [ReqId:004] The module shall wait until gets valid value for <humidity_min_cal_value> and <humidity_max_cal_value>
* [ReqId:005] It shall be possible to get <temperature_min_cal_value> from CAN bus
* [ReqId:006] It shall be possible to get <temperature_max_cal_value> from CAN bus
* [ReqId:007] It shall be possible to get <humidity_min_cal_value> from CAN bus
* [ReqId:008] It shall be possible to get <humidity_max_cal_value> from CAN bus
* [ReqId:009] It Shall be possible to read current temperature <temperature_value> as a integer number every 1000ms
* [ReqId:010] It shall be possible to read current humidity <humidity_value> as a integer number every 1000ms
* [ReqId:011] It shall be possible to convert <humidity_value> to a percentage representing the humidity level <humidity_level>
* [ReqId:012] If <temperature_value> is not in range of <temperature_min_cal_value> and <temperature_max_cal_value> the status of the sensor
            <sensor_status> shall be set to TEMPERATURE_RANGE_ERROR
* [ReqId:013] If <humidity_value> is not in range of <humidity_min_cal_value> and <humidity_max_cal_value> the status of the sensor
            <sensor_status> shall be set to HUMIDITY_RANGE_ERROR
* [ReqId:014] It shall be possible to send <temperature_value> to the CAN bus every 1000ms
* [ReqId:015] It shall be possible to send <humidity_level> to the CAN bus every 1000ms
* [ReqId:016] It shall be possible to send <sensor_status> to the CAN bus every 1000ms

