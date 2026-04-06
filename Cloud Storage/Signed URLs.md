
Secured time-limited way to grant access to a specific object in a bucket without requiring authentication

*Process*

1) Signed URL created with an expiry time
2) External party uses signed URL
3) Signed URL expires, no longer accessible

*Errors*

403 error with signed URLS

*Solution* - increase the validity period of the signed URL