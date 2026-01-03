Examples:

**Organization Administrator**: Full access to all resources within the org

**Org policy administrator**: Manages organization policies, constraints, and conditions

**Viewer**: view-only access, useful for audits and monitoring

**Browser**: Read-only access to view structure and metadata of projects and folders

Roles at the Org level cascade down

**Effective IAM policy**:

If someone has different roles at different levels, what is their access at a given node?
	Union of policies at a given node