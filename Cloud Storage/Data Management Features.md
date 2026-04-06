
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

