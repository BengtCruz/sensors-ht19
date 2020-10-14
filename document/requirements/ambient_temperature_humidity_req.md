### Ambient temperature and humidity sensor requirements

* [ReqId:001] It shall be possible to initilize the module
* [ReqId:002] The module shall wait until gets valid value for <temperature_min_cal_value> and <temperature_max_cal_value>
* [ReqId:003] The module shall wait until gets valid value for <humidity_min_cal_value> and <humidity_max_cal_value>
* [ReqId:004] It shall be possible to get <temperature_min_cal_value> from CAN bus
* [ReqId:005] It shall be possible to get <temperature_max_cal_value> from CAN bus
* [ReqId:006] It shall be possible to get <humidity_min_cal_value> from CAN bus
* [ReqId:007] It shall be possible to get <humidity_max_cal_value> from CAN bus
* [ReqId:008] It Shall be possible to read current temperature <temperature_value> as a float number every 1000ms
* [ReqId:009] It shall be possible to read current humidity <humidity_value> as a float number every 1000ms
* [ReqId:010] If <temperature_value> is not in range of <temperature_min_cal_value> and <temperature_max_cal_value> the status of the sensor
            <sensor_status> shall be set to TEMPERATURE_RANGE_ERROR
* [ReqId:011] If <humidity_value> is not in range of <humidity_min_cal_value> and <humidity_max_cal_value> the status of the sensor
            <sensor_status> shall be set to HUMIDITY_RANGE_ERROR
* [ReqId:012] It shall be possible to send <temperature_value> to the CAN bus every 1000ms
* [ReqId:013] It shall be possible to send <humidity_value> to the CAN bus every 1000ms
* [ReqId:014] It shall be possible to send <sensor_status> to the CAN bus