
*How does encryption work in Cloud Storage?*

GCS automatically encrypts all data at rest with Google-managed keys

Ensures baseline level of security

Google manages these keys for ease of use

*Cloud KMS*

Can also create your own key with KMS (key management service) and set that as a default for the bucket

Called a CMEK (customer-managed encryption key)

Can observe and control key:

1) Creation
2) Usage
3) Rotation
4) Revocation

*Customer-supplied encryption keys*

Steps:

1) On-prem with a CSEK (key is stored in a config file "BOTO file" contains key and credentials that gsutil references)
2) Uploaded and the key and gsutil work to upload is to GCS


Key itself is never stored in GCS

Keys are passed in each API request to encrypt and decrypt data

