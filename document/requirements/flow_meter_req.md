### Flow Meter sensor requirements

* [ReqId:001] It shall be possible to initialize the module
* [ReqId:002] <flow_meter_status> should be UNINITILIZED until it gets valid calibration values
* [ReqId:003] The module shall wait until gets valid value for <flow_meter_min_cal_value> and <flow_meter_max_cal_value>
* [ReqId:004] It shall be possible to get <flow_meter_min_cal_value> from CAN bus every 1000ms
* [ReqId:005] It shall be possible to get <flow_meter_max_cal_value> from CAN bus every 1000ms
* [ReqId:006] It shall be possible to convert <pulse_frequecy> to miliiters/Second <flow_meter_value>
* [ReqId:007] If <flow_meter_value> is not in range of <flow_meter_min_cal_value> and <flow_meter_max_cal_value> the status of the sensor
            <sensor_status> shall be set to FLOW_RANGE_ERROR
* [ReqId:008] It shall be possible to send <flow_meter_value> to the CAN bus every 1000ms
* [ReqId:009] It shall be possible to send <flow_meter_status> to the CAN bus every 1000ms



