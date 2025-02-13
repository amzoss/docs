---
title: "Settings > Users"
linkTitle: "Users"
date: 2021-11-09
weight: 220
tags: ["subtopic"]   
---

The Users section in the Settings app provides configuration options for managing user records, including user information, patron blocks, fee/fine processing, permissions, and service points.

## Permissions

The following are all the permissions for Users Settings:

-   **Settings (Users): Can create, edit and remove address types.** 
-   **Settings (Users): Can create, edit and remove all feefines-related entries.**
-   **Settings (Users): Can create, edit and remove comments.**
-   **Settings (Users): Can create, edit and remove feefines.**
-   **Settings (Users): Can create, edit and remove owners.**
-   **Settings (Users): Can create, edit and remove patron blocks conditions.**
-   **Settings (Users): Can create, edit and remove patron blocks limits.**
-   **Settings (Users): Can create, edit and remove patron groups.**
-   **Settings (Users): Can create, edit and remove payments.**
-   **Settings (Users): Can create, edit and remove sets.**
-   **Settings (Users): Can create, edit and remove refunds.**
-   **Settings (Users): Can create, edit and remove transfer accounts.**
-   **Settings (Users): Can create, edit and remove transfer criteria.**
-   **Settings (Users): Can create, edit and remove waives.**
-   **Settings (Users): Can create, edit, and view custom fields.**
-   **Settings (Users): Can create, edit, view and delete custom fields.**
-   **Settings (Users): Can view custom fields.**
-   **Settings (Users): Create, edit, and view departments.**
-   **Settings (Users): Create, edit, view, and delete departments.**
-   **Settings (Users): View departments.**

## Settings \> Users \> Permission sets

Use this setting to create permission sets for your library. Permission sets are customized collections of permissions that can be assigned to users. For example, you can create permission sets that correspond to specific job roles and assign the set, rather than each individual permission, to all library staff with that role.

Additionally, if permissions change because of a new release, a FOLIO administrator can edit the permission set for a particular role to update the assigned permissions. The change to the permission set then propagates out to the users who have that permission set assigned, and the administrator doesn't have to update permissions for each individual user.

### Creating a permission set

1.  In the Permission sets pane, click **New**.
2.  To name the permissions set, enter a **Permission set name**.
3.  Optional: Enter a **Description** of the permission set.
4.  Under **Assigned permissions**, click **Add permission**. 
5.  In the **Select Permissions** dialog, check the box next to each permission you want to assign to the permission set. You can also add an existing permission set to another permission set.
6.  Click **Save & close**. The permissions are added to the set.
7.  Click **Save & close**. The permission set is saved.

### Editing a permission set

1.  Find the permission set you want to edit and select it.
2.  In the **permission set** pane, click **Edit**.
3.  Make your desired changes to the permission set.
4.  Click **Save & Close**. 

### Deleting a permission set

Note: A permission set can be deleted even if it is currently assigned to a user. Deleting the permission set removes it from the users to whom it was assigned.

1.  Find the permission set you want to delete and select it.
2.  In the **permission set** pane, click **Edit**.
3.  In the **Edit** window, click **Delete**.
4.  In the **Delete permission set** dialog, click **Delete**. A confirmation message appears and the permission is deleted.

## Settings \> Users \> Patron Groups

Use this setting to create patron groups for your library. Patron groups are classes of library users. For example, you may want to create a patron group called Faculty or Undergraduates.

Only one patron group can be assigned to a user record. Patron groups are also used to create [Circulation rules](../../settings_circulation/settings_circulation/#settings--circulation--circulation-rules).

### Creating a patron group

1.  In the **Patron groups** pane, click **New**.
2.  Enter a name for the **Patron group** in the box. Patron group names need to be unique.
3.  Optional: Enter a **Description** of the patron group.
4.  Click **Save**. The patron group is saved.

### Editing a patron group

1.  Find the patron group you want to edit and click the **pencil icon**.
2.  Make your changes to the **Patron group** or **Description**.
3.  Click **Save**. The patron group is saved.

### Deleting a patron group

A patron group can only be deleted if it is no longer applied to any user records. To delete a patron group, you should first check to be sure that no users are currently assigned to that group.

To see the number of user records assigned to a patron group, complete the following: 

-   In the **Users app**, in the **User search** pane, select the checkbox next to the appropriate Patron group. The list of user records assigned to that patron group appears in the User search results pane. The number of records found displays at the top of the pane.

To delete a patron group, follow these steps:

1.  In the **Settings app**, select **Users \> Patron groups**.
2.  In the **Patron groups** pane, find the patron group you want to delete and click the **trash can icon**.
3.  In the **Delete Patron group** dialog, click **Delete**. A confirmation message appears and the patron group is deleted.

## Settings \> Users \> Address Types

Use this setting to configure address types. Address types are used to categorize the addresses that are entered in the [Contact information](../../../users/#contact-information) section of a user record. For example, you may want to create the address types: office, work, or home address.

Note: Address types should be first configured here before bulk loading of patrons occurs if mailing addresses are to be stored.

### Creating an address type

1.  In the **Address Types** pane, click **New**.
2.  Enter a name for the **Address Type** in the box. The Address Type must be unique.
3.  Optional: Enter a **Description** of the Address Type.
4.  Click **Save**. The Address Type is saved.

### Editing an address type

1.  Find the Address Type you want to edit and click the **pencil icon**.
2.  Make your changes to the **Address Type** or **Description**.
3.  Click **Save**. The Address Type is updated.

### Deleting an address type

1.  Find the Address Type you want to delete and click the **trash can icon**.
2.  In the **Delete Address Type** dialog, click **Delete**. A confirmation message appears and the Address Type is deleted.

## Settings \> Users \> Departments

Use this setting to configure departments. Departments can be added in the [Extended information](../../../users/#extended-information) section of a user record. For example, you may want to add departments to reflect library staff or faculty's departments.

### Creating a department

1.  In the **Departments** pane, click **New**.
2.  Enter a **Name** for the department in the box.
3.  Enter a department **Code** in the box.
4.  Click **Save**. The department is saved.

### Editing a department

1.  Find the department you want to edit and click the **pencil icon**.
2.  Make your changes to the **Name** or **Code**.
3.  Click **Save**. The department is updated.

### Deleting a department

1.  Find the department you want to delete and click the **trash can icon**.
2.  In the **Delete Department** dialog, click **Delete**. A confirmation message appears and the department is deleted.

## Settings \> Users \> Profile pictures

This field in the user record is not being developed at this time. 

## Settings \> Users \> Custom fields

Use this setting to configure custom fields, which you can add to the user record to track additional information about the user not already recorded.

### Creating a custom field

1.  In the **Custom fields** pane, click **New**.
2.  In the **Edit custom fields** pane, in the **Accordion title** box, enter the name of the user record section, which contains the custom fields you add below.
3.  Click **Add custom field** and select the type of field you want to create: Checkbox, Multi-select, Radio button set, Single select, Text area, or Text field.
4.  Configure the custom field.
5.  Optional: To add additional custom fields, repeat steps 3-4.
6.  Click **Save & close**. The custom field(s) are saved.

### Editing a custom field

1.  In the **Custom fields** pane, click **Edit**.
2.  In the **Edit custom fields** pane, make your changes to the custom fields.
3.  Click **Save & close**. The custom field(s) are updated.

### Deleting a custom field

Note: Custom fields can be deleted if they are in use, but any information tied to the fields is also deleted.

1.  In the **Custom fields** pane, click **Edit**.
2.  In the **Edit custom fields** pane, next to the custom fields you want to delete, click the **trash can icon**. Clear out all of the fields to remove the accordion from appearing in user records.
3.  Click **Save & close**.
4.  In the **Delete field data** dialog, click **Save & lose data**. 

## Settings \> Users \> Owners

Use this setting to configure the fee/fine owners at your library. A Fee/fine owner is the agent or office that manages fines for FOLIO transactions. Fee/fine owners collect fees/fines for FOLIO service points.

Libraries may use these in different ways, such as creating a fee/fine owner for each service point, or creating a fee/fine owner for each library's accounting office, that may collect fee/fines for multiple service points. 

When manually creating a fee/fine, Fee/fine owner is a required field.

### Creating a fee/fine owner

1.  In the **Fee/fine: Owners** pane, click **New**.
2.  Enter a name for the **Owner** in the box.
3.  Optional: Enter a **Description** about the owner.
4.  Optional: Select any **Associated service points**. If no service point is associated with the owner, they can be used at any service point.
5.  Click **Save**. The fee/fine owner is saved.

### Editing a fee/fine owner

1.  Find the owner you want to edit and click the **pencil icon**.
2.  Make your changes to the **Owner, Description,** or **Associated service points**.
3.  Click **Save**. The owner is updated.

### Deleting a fee/fine owner

1.  Find the owner you want to delete and click the **trash can icon**.
2.  In the **Delete Fee/fine Owner** dialog, click **Delete**. A confirmation message appears and the owner is deleted.

## Settings \> Users \> Manual charges

Use this setting to configure fee/fine types. For example, fee/fine types could be overdue fines, processing fees, or lost item fees. When manually creating a fee/fine, Fee/fine type is a required field.

### Creating a fee/fine type

1.  In the **Fee/fine: Manual charges** pane, select the **Fee/fine Owner** from the drop-down list.
2.  Optional: Click **Edit** to assign a **Default Charge Notice** and/or **Default Action Notice** to the template and click **Save**.
3.  Click **New**.
4.  Enter a name for the **Fee/Fine type**.
5.  Optional: Enter the **Default Amount** for the fee/fine.
6.  Optional: Select a **Charge Notice**.
7.  Optional: Select an **Action Notice**.
8.  Click **Save**. The fee/fine type is saved.

### Editing a fee/fine type

1.  Find the fee/fine type you want to edit and click the **pencil icon**.
2.  Make your changes to the manual charge.
3.  Click **Save**. The manual charge is updated.

### Deleting a fee/fine type

1.  Find the fee/fine type  you want to delete and click the **trash can icon**.
2.  In the **Delete Fee/fine Type** dialog, click **Delete**. A confirmation message appears and the fee/fine type is deleted.

## Settings \> Users \> Waive reasons

Use this setting to configure waive reasons. When waiving a fee/fine, Waive reason is a required field.

### Creating a waive reason

1.  In the **Fee/fine: Waive reasons** pane, click **New**.
2.  Enter a name for the **Reason** in the box.
3.  Optional: Enter a **Description** about the waive reason.
4.  Click **Save**. The waive reason is saved.

### Editing a waive reason

1.  Find the waive reason you want to edit and click the **pencil icon**.
2.  Make your changes to the **Reason** or **Description**.
3.  Click **Save**. The waive reason is updated.

### Deleting a waive reason

1.  Find the waive reason you want to edit and click the **trash can icon**.
2.  In the **Delete Waive reason** dialog, click **Delete**. A confirmation message appears and the waive reason is deleted.

## Settings \> Users \> Payment methods

Use this setting to configure payment methods. Payment methods are fee/fine owner specific. When paying a fee/fine, Payment method is a required field.

### Creating a payment method

1.  In the **Fee/fine: Payment methods** pane, select the **Fee/fine Owner** from the drop-down list.
2.  Click **New**.
3.  Enter a **Name** for the payment method.
4.  Select whether a **Refund method allowed**.
5.  Click **Save**. The payment method is saved.

### Editing a payment method

1.  Find the payment method you want to edit and click the **pencil icon**.
2.  Make your changes to the **Name** or **Refund method allowed**.
3.  Click **Save**. The payment method is updated.

### Deleting a payment method

1.  Find the payment method you want to edit and click the **trash can icon**.
2.  In the **Delete Payment method** dialog, click **Delete**. A confirmation message appears and the payment method is deleted.

## Settings \> Users \> Refund reasons

Use this setting to configure refund reasons. When refunding a fee/fine, Refund reason is a required field.

### Creating a refund reason

1.  In the **Fee/fine: Refund reasons** pane, click **New**.
2.  Enter a **Name** for the refund reason.
3.  Optional: Enter a **Description** about the refund reason.
4.  Click **Save**. The refund reason is saved.

### Editing a refund reason

1.  Find the refund reason you want to edit and click the **pencil icon**.
2.  Make your changes to the **Name** or **Description**.
3.  Click **Save**. The refund reason is updated.

### Deleting a refund reason

1.  Find the refund reason you want to edit and click the **trash can icon**.
2.  In the **Delete Refund reason** dialog, click **Delete**. A confirmation message appears and the refund reason is deleted.

## Settings \> Users \> Comment required

Use this section to configure whether comments are required when fees/fines are paid, waived, refunded, or transferred. By default, comments are not required.

### Require comment when fee/fine fully/partially paid

-   To require a comment when a fee/fine is fully or partially paid, under **Require comment when fee/fine fully/partially paid**, select **Yes**. A confirmation message appears and the comment setting is saved.

### Require comment when fee/fine fully/partially waived

-   To require a comment when a fee/fine is fully or partially waived, under **Require comment when fee/fine fully/partially waived**, select **Yes**. A confirmation message appears and the comment setting is saved.

### Require comment when fee/fine fully/partially refunded

-   To require a comment when a fee/fine is fully or partially refunded, under **Require comment when fee/fine fully/partially refunded**, select **Yes**. A confirmation message appears and the comment setting is saved.

### Require comment when fee/fine fully/partially transferred

-   To require a comment when a fee/fine is fully or partially transferred, under **Require comment when fee/fine fully/partially transferred**, select **Yes**. A confirmation message appears and the comment setting is saved.

## Settings \> Users \> Transfer accounts

Use this setting to configure transfer accounts. Transfer accounts are used when your library needs to transfer transactions (for charge or credit) to entities outside of the library. For example, a transfer account may be the bursar's office or a collection agency.

### Creating a transfer account

1.  In the **Fee/fine: Transfer accounts** pane, select the **Fee/fine Owner** from the drop-down list.
2.  Click **New**.
3.  Enter a **Name** for the transfer account.
4.  Optional: Enter a **Description** of the transfer account.
5.  Click **Save**. The transfer account is saved.

### Editing a transfer account

1.  Find the transfer account you want to edit and click the **pencil icon**.
2.  Make your changes to the **Name** or **Description**.
3.  Click **Save**. The transfer account is updated.

### Deleting a transfer account

1.  Find the transfer account you want to edit and click the **trash can icon**.
2.  In the **Delete Transfer account** dialog, click **Delete**. A confirmation message appears and the transfer account is deleted.

## Settings \> Users \> Conditions

Automatic patron blocks allow the library to set limits that are automatically enforced. The limits are calculated in real time and displayed in the same areas as manual blocks. Patrons can be automatically blocked from checking out, renewing, and/or requesting.

Automatic patron blocks are displayed in the Users app in the Patron blocks section of a user record. Depending on which actions are blocked, the blocks also display in the Check out app after patron barcode entry or patron look-up or if an item barcode is scanned, in the Users app Loans section if you want to renew an item, and in the Requests app after a patron barcode/patron look-up.

The patron block is automatically removed once the patron falls below the limit.

Note: Conditions and limits have to be in place in order for automated patron blocks to work.

### Conditions/Limits categories

Conditions determine what actions patrons are barred from doing once they hit the limits as outlined for their patron group in [Settings \> Users \> Limits](#settings--users--limits).

These are all the categories for which you can set conditions and limits:

-   Maximum number of items charged out
-   Maximum number of lost items
-   Maximum number of overdue items
-   Maximum number of overdue recalls
-   Maximum outstanding fee/fine balance
-   Recall overdue by maximum number of days

### Create patron block conditions

1.  In the **Conditions** pane, select the condition you want to configure.
2.  In the **condition** pane, select the actions that occur when the defined limits are exceeded: Block borrowing, Block renewals, and/or Block requests.
3.  Enter a **Message to be displayed**.
4.  Click **Save**. A confirmation message appears and the block condition is saved.

### Editing patron block conditions

1.  In the **Conditions** pane, select the condition you want to edit.
2.  In the **condition** pane, make your changes to the condition.
3.  Click **Save**. A confirmation message appears and the block condition is saved.

### Removing patron block conditions

1.  In the **Conditions** pane, select the condition you want to remove.
2.  In the **condition** pane, clear out any blocks and messages.
3.  Click **Save**. A confirmation message appears and the block condition is saved.

## Settings \> Users \> Limits

Limits determine the maximum number of materials, recalls, fee/fines, or overdues, that when reached, the conditions you configured in [Settings \> Users \> Conditions](#settings--users--conditions) are applied to a patron's account. Limits are established based on patron groups.

### Create patron block limits

1.  In the **Limits** pane, select the patron group for which you want to configure limits.
2.  In the **patron group** pane, enter a limit for each category. Leave the field blank if you do not want to set a limit for a certain category.
3.  Click **Save**. A confirmation message appears and the block limits are saved.

### Edit patron block limits

1.  In the **Limits** pane, select the patron group with the limits you want to edit.
2.  In the **patron group** pane, make your changes to the limits.
3.  Click **Save**. A confirmation message appears and the block limits are saved.

### Remove patron block limits

1.  In the **Limits** pane, select the patron group with the limits you want to remove.
2.  In the **patron group** pane, clear out the limits.

Click **Save**. A confirmation message appears and the block limits are saved.
