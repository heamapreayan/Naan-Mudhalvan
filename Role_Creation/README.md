# Revolutionizing Agriculture with AgriEdge Or-Mange Ltd: A Salesforce-Driven Order Management Solution - Role Creation

**Salesforce** | **Salesforce Security** | **Salesforce Development**

## Overview

AgriEdge Or-Mange Ltd is implementing a comprehensive Salesforce-driven Order Management Solution to transform its operations. This role creation documentation covers the essential process of establishing role hierarchies in Salesforce for the AgriEdge Or-Mange Ltd organizational structure. Roles define the organizational hierarchy and control user permissions based on their position within the company, ensuring proper data access, visibility, and governance.

---

## Requirements

To successfully implement role creation and management in Salesforce for AgriEdge Or-Mange Ltd, the following requirements must be fulfilled:

- **Administrative Access:** Users must have administrative privileges to access and configure the role hierarchy in Salesforce Setup
- **Organizational Clarity:** A clear understanding of your organizational hierarchy and reporting structure before implementation
- **Role Definition:** Complete definitions of all roles that need to be created, including titles, responsibilities, and reporting relationships
- **Permission Strategy:** Well-defined permission requirements for each role to ensure appropriate data access and system visibility
- **Compliance Requirements:** Adherence to data security standards and organizational governance policies

---

## What You'll Learn

Through this implementation, you will gain expertise in:

1. Salesforce Role Hierarchy concepts and architecture
2. Creating and managing role structures in Salesforce Setup
3. Establishing reporting relationships and organizational hierarchies
4. Setting permissions and access control based on roles
5. Data inheritance and visibility management
6. Best practices for role-based access control

---

## Skills Required

Salesforce Administration | User Management | Salesforce Configuration

---

## Team Members

| Name             | Role      |
| ---------------- | --------- |
| HEAMA PREAYAN V  | Team Lead |
| SRIDHAR D        | Member    |
| SANTHOSH KUMAR A | Member    |
| JEFFREY SAMUEL J | Member    |

---

## Project Stats

| Metric        | Count       |
| ------------- | ----------- |
| Total Stories | 1           |
| Duration      | 59m         |
| Status        | In Progress |

---

## Instructions

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
- **Visual Representation:** Organization structure clearly displayed
- **Permission Control:** Role-based access management
- **Data Inheritance:** Automatic permission inheritance from parent roles

📹 **Demo Video:** [Watch the demo](https://drive.google.com/file/d/1hYuZyJwq3PTPRfiL2f-y2uE018wW7CdA/view?usp=sharing)

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
