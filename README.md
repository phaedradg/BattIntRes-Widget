# BattIntRes-Widget
Frsky Horus widget that measures/estimates battery internal resistance
LUA script
Makes an estimation of the internal resistance of the flight battery during initial phase of the flight (takeoff)
A first measurement of the battery voltage is done while current is very low.  This representas the open-circuit voltage
As soon as the current exceeds a predefined threshold, a new voltage measurement is preformed.
Both voltages and the current measured then allow to calculate and display the estimated internal resitance of the battery
