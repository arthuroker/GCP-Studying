
*Lifecycle rules*

Can be used to help manage the transition of objects to different storage classes, or their deletion, based on specific conditions

Can be defined in Cloud Console, or in a JSON and applied via gsutil or gcloud

*Examples*

1) Set transition rules based on conditions such as age of the data
2) Deleing outdated or unnecessary data

This management can help reduce costs

*Object versioning*

Mechanism to keep track of different version of an object within the same bucket

When versioning is enabled, when you replace an object with another object with the same name, makes the old one a non-current version in the same bucket

Deleting an object creates a delete marker, making the previous version non-current in a versioned bucket

![[Pasted image 20260406154030.png]]

*Retention policy*

A bucket retention policy sets a retention period during which objects cannot be deleted or replaced

The policy applied retroactively is applied to all existing and new objects in the bucket

It is useful for regulatory or internal governance compliance

*Bucket lock* - A retention policy can be locked to make it permanent, once locked, it cannot be removed or reduced in duration

Locked policies prevent bucket deletion until all objects meet the retention period but allow for an increase in the retention period

Helps further comply with data retention and compliance

Retention policies and object versioning cannot be used simultaneously

*Autoclass*

Automatically transitions objects based on access patterns

Must be enabled, off by default

Still potentially more savings with Lifecycle rules, because for Autoclass it starts out by storing everything at Standard


