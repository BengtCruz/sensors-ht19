# Light intensity sensor requirements

* [ReqID:001] It shall be possible to initialize the module
* [ReqId:002] <ldr_status> should be UNINITILIZED until it gets valid calibration values
* [ReqID:004] The module shall wait until gets valid value for <ldr_min_cal_value> and <ldr_max_cal_value>
* [ReqID:005] It shall be possible to get <ldr_min_cal_value> from CAN bus
* [ReqID:006] It shall be possible to get <ldr_max_cal_value> from CAN bus
* [ReqID:007] It shall be possible to read current light intensity analog value <ldr_analog_value> as a float number every 1000ms
* [ReqID:008] It shall be possible to convert <ldr_analog_value> to a 10 bits digital value <ldr_value>
* [ReqID:009] It shall be possible to convert <ldr_value> to a light intensity value <ldr_intensity_value> between 0 and 100
* [ReqID:010] If <ldr_intensity_value> is not in the range of <ldr_min_cal_value> and <ldr_max_cal_value>, the status of the sensor
            <ldr_status> shall be set to LDR_RANGE_ERROR
* [ReqID:011] It shall be possible to send <ldr_intensity_value> to the CAN bus every 1000ms
* [ReqID:012] It shall be possible to send <ldr_status> to the CAN bus