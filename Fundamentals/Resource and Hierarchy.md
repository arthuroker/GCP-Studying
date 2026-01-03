**Project**: Fundamental, lowest level of organization in GCP
	1) Where the resources/services lie
	2) Distinct entity for billing, access management and APIs
	3) Everything must be associated with a project

**Organization**: Top level container
	Can represent an entire company, organization, or division
	Technically optional
	Useful for centralizing projects
	Tied to a *Cloud Identity* or *Google Workspace*
	Manage resources, policies, and billings within the org
	Roles can be grated at this level

**Folders**: Optional intermediate container
	Used to organize projects into logical groups
	Inherit policies and permission from the parent organization
	Can be nested