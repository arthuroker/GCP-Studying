
*Example*

Fleet of delivery vehicles with IoT sensors
	Speed, location, fuel-level, etc.

This generates lots of time-series data

*How do we optimize for efficient read and writes?*

Row key = vehicle_id#timestamp

Column family = sensor data

Column qualifier = sensor_type(speed, fuel_level, temperature, location)

*Why is this good?*

Row key distributes writes across tablets

Column family groups related sensor metrics

Column qualifier identifies specific sensor reading

*Comparison of approaches*

Good - id#timestamp

Bad - timestamp#id (timestamp all go to the same tablet)

Also bad - vehicle_type#timestamp (vehicle type is not high enough cardinality)

