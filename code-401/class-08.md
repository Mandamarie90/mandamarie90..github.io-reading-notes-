### What is Role Based Access Control (RBAC) and why do we care?
Role Based Access Control (RBAC) is a security paradigm where user access is based on their roles within an organization rather than the individual's identity. We care about RBAC because it simplifies management and enhances security by ensuring that users only have access to the information and functionality necessary for their roles.

### Describe a Role/Permission hierarchy that you might implement using RBAC.
In a typical RBAC system, you might have roles like `Admin`, `Manager`, and `Employee` with varying levels of permissions: `Admins` can access, create, modify, and delete all records; `Managers` can access and modify records within their department; `Employees` can access only their personal records.

### What approach might you take to implement RBAC?
To implement RBAC, I would start by defining clear roles within the organization and the specific permissions each role has. Then, implement these roles and permissions in the system using a security framework or custom code to check a user's role and permissions before granting access to any resource.

### If Authentication is “you are who you say you are,” what is Authorization?
Authorization is the process of determining if a user is permitted to perform a requested action or access a specific resource.

### Name three primary rules defined for RBAC.
1. **Role Assignment:** A user can execute a transaction only if the user has been assigned a role.
2. **Role Authorization:** A user's active role must be authorized for the user.
3. **Permission Authorization:** A user can access a resource only if the user's active role has permission to do so.

### Describe RBAC to a non-technical friend.
Imagine you're at a music festival with different access passes: General Admission, VIP, and Artist. Each pass allows you to go to certain areas — that's kind of like RBAC, where your "pass" (or role) determines what parts of a system you can access.

### What Are access rights Associated with? The User? or The Role? Explain.
Access rights are associated with the role, not the user. This means that permissions are set based on roles (like Manager or Staff), and users are given roles rather than individual permissions, simplifying management and ensuring consistent access control across users with similar job functions.

### Access Rights, or Authorization, is activated after a user successfully does what?
Access rights, or Authorization, is activated after a user successfully authenticates, which means proving their identity, usually through a login process.

### Explain how RBAC might benefit a business.
RBAC can benefit a business by reducing the administrative burden and complexity of managing individual user permissions, improving security by limiting access to sensitive information based on roles, and ensuring compliance with data access regulations.