
*Storage Classes*

![[Pasted image 20260406104241.png]]

*Min storage duration* = minimum time data must stay in a Cloud Storage class

Can do object-level override, where a certain bucket has a storage class but objects within it can override the bucket default

*Archive Storage special case*

Generally once a year or less

However, it can be good for data accessed only 2-3 times per year if cost is a priority and data storage cost savings are greater than data retrieval costs

*Location options*

*Regional* - When you need to keep data in a specific location (ie. compliance), need low latency in that location, generally cheaper

*Multi-region* - US, EU, Asia. Access across multiple regions, highest availability and global access with minimal latency

