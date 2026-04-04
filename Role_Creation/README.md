# Role Creation

📹 **Demo Video:** [Watch the demo](https://drive.google.com/file/d/1hYuZyJwq3PTPRfiL2f-y2uE018wW7CdA/view?usp=sharing)

**Story Type:** Story  
**Duration:** 59m  
**Assigned to:** SRIDHAR D

---

## Project Context

**Revolutionizing Agriculture with AgriEdge Or-Mange Ltd: A Salesforce-Driven Order Management Solution**

This documentation covers the role creation process in Salesforce for the AgriEdge Or-Mange Ltd organizational hierarchy.

---

## Description

### Creation Roles

This guide provides step-by-step instructions for creating and managing role hierarchies in Salesforce. Roles define the organizational structure and control user permissions based on their position within the company.

---

## Prerequisites

Before getting started, ensure you have:

- Administrative access to Salesforce
- Understanding of your organizational hierarchy
- Definitions of roles that need to be created

---

## Step-by-Step Instructions

### 1. Understanding Roles

Set up your role hierarchy to control how your organization's roles and accounts relate. Salesforce Role Hierarchy provides:

- **Visual Representation** of organization structure
- **Permission Control** based on role assignments
- **Data Access** inheritance from parent to child roles
- **Multiple Roles Per User** capability

---

### 2. Access the Roles Setup

1. From Setup, search for and select **Roles**
2. Navigate to **Setup** → **Users** → **Roles**
3. You will see the Roles page with the existing role hierarchy

---

### 3. Add CEO Role (Root Role)

1. Click **Add Roles** option below the organization root
2. Create the top-level CEO role
3. Set appropriate permissions and access levels
4. Click **Save**

---

### 4. Create Additional Roles

#### Example: Sales Representative Role

1. Click **Add Role** under the appropriate parent role
2. Fill in the role details:
   - **Label:** Sales Representative
   - **Role Edit:** [Configure as needed]
   - **Developer Name:** Auto-populated based on label
3. Specify "This Role Reports To: CEO"
4. Configure role-specific settings:
   - Check permissions based on organizational requirements
   - Set data access rules
   - Define delegated administration if needed
5. Click **Save and New** to create additional roles or **Save** to finish

---

### 5. Role Hierarchy Structure Example

```
CEO
├── CFO
├── COO
└── Sales Manager
    └── Sales Representative
        └── Sales Executive
```

---

## Key Features

- **Role Reports To:** Establishes the reporting hierarchy
- **Add Role:** Create new child roles under any existing role
- **Edit/Delete:** Manage existing roles
- **Assign Users:** Link users to roles after creation

---

## Best Practices

1. **Plan your hierarchy** before implementation
2. **Keep role names consistent** and descriptive
3. **Limit hierarchy depth** to maintain clarity
4. **Document role responsibilities** and permissions
5. **Test role assignments** before full rollout
6. **Review and update regularly** as organization changes

---

## Notes

- Roles are optional but recommended for organizations with multiple users
- Role hierarchy is separate from "Organization Wide Defaults"
- Users can be assigned to only one role at a time (however, users can have multiple profile assignments)
- Changing a user's role may affect their data access

---

## Related Documentation

- [Understanding Roles](https://help.salesforce.com/)
- [Creating the Role Hierarchy](https://help.salesforce.com/)
- Salesforce Administrator Guide

---

**Status:** In Progress  
**Last Updated:** April 4, 2026
