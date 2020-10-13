### Flow Meter sensor requirements

[ReqId:001] It shall be possible to initialize the module
[ReqId:002] It shall be possible to read the <pulse_frequecy> when <pump_status> is ON every <meassuring_frequency>
[ReqId:003] It shall be possible to convert <pulse_frequecy> to Liters/Second <flow_meter_value>
[ReqId:004] It shall be possible to send <flow_meter_value> to the CAN bus
[ReqId:005] It shall be possible to send <flow_meter_status> to the CAN bus
[ReqId:006] It shall be possible to read <pump_status> from CAN bus
[ReqId:007] If <pump_status> is ON and <pulse_frequency> is 0 then <flow_meter_status> shall be set to FLOW_ERROR
[ReqId:008] If <pump_status> is OFF and there is change in <pulse_frequency> then <flow_meter_status> shall be set to FLOW_ERROR




