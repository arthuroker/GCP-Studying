
*Separate VPC in each project (Network layer isolation)*

Creating separate VPCs in each project and ensuring there is no peering or routing between them should be sufficient. Works at the network layer

*VPC service Controls (Service layer isolation)*

Create a security perimeter around each project, preventing data exfiltration and ensuring resource cannot access sources in another project. Works at the service layer