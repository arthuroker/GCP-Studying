
*Recovery Point Objective*

*Synchronization points* - when data is backed up/replicated

Data from last sync point and disaster could be lost, the time and data between this time is called the *Recovery Point Objective*

*RPO* - defines the maximum acceptable amount of data loss, measured in time, when a disaster/outage occurs

*Recovery Time Objective*

How much downtime can we tolerate?

Measured in time, x amount of downtime allowed

*Cloud SQL* - HA mode cross zone sync replica
	RPO = basically 0
	RTO = 60-120 seconds

*Cloud Spanner* - Regional or Multi-regional
	RPO = 0
	RTO = seconds

*BQ*
	RPO = 0
	RTO = seconds

*Cloud Storage* - Dual or multi region
	RPO = basically 0
	RTO = seconds

*Regional Persistent Disk* 
	RPO = basically 0
	RTO = minutes

