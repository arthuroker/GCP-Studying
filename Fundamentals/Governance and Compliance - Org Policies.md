**Motivation**: How do you enforce rules like region specific data, preventing traffic from certain countries, or encrypting VMs?

**Example Org policies**:

-constraints/compute.resourceLocations
	Constrains resources to only operate in certain geographic regions

-constraints/iam.allowedPolicyMemberDomains
	Controls which domains users must belong to in order to be added to IAM.

-constraints/compute.vmExternalIPAccess
	Constrains or blocks VMs from having external IPs

-constraints/compute.requireOSlogin
	Must use IAM to control SSH access to VMs

**Allow lists**:

Defines what is explicitly permitted, block everything else

**Deny lists**: 

Defines what is explicitly denied, block everything else


**Org policy Inheritance and Exceptions**:

Org policies can be set at any level

Policies flow down from the top level

**Exceptions**: policies can be overridden at lower level, but only to apply *stricter* restrictions

**Effective policy** =  inherited policies + exceptions