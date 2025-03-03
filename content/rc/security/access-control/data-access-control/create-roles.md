---
Title: Assign permissions to roles
LinkTitle: Create roles
description: 
weight: 20
alwaysopen: false
toc: "true"
headerRange: "[1-3]"
categories: []
aliases: 
---

To assign [Redis ACLs]({{<relref "rc/security/access-control/data-access-control/configure-acls">}}) to a data access role:

1. Go to **Data Access Control > Roles** and either select `+` to create a new role or point to an existing role and select the pencil icon to edit it.

1. In the **Associations** section of the **Edit role** or **Create new role** screen, you can select `+` to create a new association or point to an existing association and select the pencil icon to edit it.

1. Select one or more databases from the **Databases** list.

1. To set the role's level of access to the selected databases, pick a **Redis ACL** from the list.

1. Select the check mark to confirm the association.

1. Select **Save role**.

When you assign a user-defined ACL rule to a role and associate it with one or more databases, Redis will verify that the ACL rule will work with the selected databases. 

After you create a role, you can assign it to a user. Users with this role can access the databases according to the role's associated Redis ACLs. For more information, see [Assign roles to users]({{<relref "rc/security/access-control/data-access-control/create-assign-users#assign-roles-to-users">}}).

To assign Redis ACLs to a role for an [Active-Active subscription]({{<relref "rc/databases/active-active-redis">}}), see [Active-Active access roles]({{<relref "rc/security/access-control/data-access-control/active-active-roles">}}).

