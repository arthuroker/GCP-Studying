*SSH*

Protocol to use computer remotely

Can execute commands, file uploads, port forwarding

It encrypts the data transfer

*Identity aware proxy (IAP) (connecting to VM without public IP*

Routes SSH connection through Google's infrastructure

Need to grant tunnel instances access through IAP command to relevant service or user accounts

Can have IAM interact in this

*OS Login*

User attempts to access VM -> IAM checks -> Make decision on whether it's allowed

Google handles SSH keys

Roles:

1. *Compute OS login* - access to VM with no admin privileges (no root access)
2. *Compute OS admin login* - can add software
3. *Compute OS Login external user* - same as 1, but for user's outside of the organization's domain
   
   *R*