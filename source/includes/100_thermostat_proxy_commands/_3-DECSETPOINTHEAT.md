## DEC SETPOINT HEAT

Used to decrease the heat set point by 1. This command is handled by the proxy, and ends up creating a `SET_SETPOINT_HEAT` command to send to the protocol driver, unless the capability `can_inc_dec_setpoints` is set to true


### Signature

`DEC_SETPOINT_HEAT ()`


### Parameter

`None`


### Returns

`None`

