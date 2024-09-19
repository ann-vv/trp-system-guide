# Groups

### Overview

Groups in the TRP system organise the carriers, shippers, and internal teams, facilitating streamlined tender management. Users can manually create groups or import/export them to ensure efficient handling of participants. Below are the detailed steps for adding, importing, exporting, and managing groups.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-16 at 14.04.27.png" alt=""><figcaption></figcaption></figure>

Each group is defined by two key parameters:

* **Category Title**: The name identifier for the group.
* **Accounts**: A list of email addresses for the persons within the group.

You need to configure scopes to define the participation of groups in the tender. For more information please refer to [Scopes](scopes.md).

### **Add Group**

1. Click "Add Group".
2. Enter the group title and the email addresses of participants who will belong to this group.
3. Once the group title and emails are entered, click **Save** to finalize the group creation.

***

### **Import Groups**

Instead of manual entry, groups can also be imported via an Excel file, making the process faster when dealing with multiple participants or predefined groups.

**Steps to Import Groups:**

1.  Prepare the Excel file. Ensure your Excel file contains two columns:

    * **Column 1**: "Category Title" – The group’s name.
    * **Column 2**: "Accounts" – A comma-separated list of email addresses for the group members.

    Example of file configuration:

| Category title |                                                   |
| -------------- | ------------------------------------------------- |
| Group 1        | user1@gmail.com, user2@gmail.com                  |
| Group 2        | user3@gmail.com, user4@gmail.com, user5@gmail.com |

2. Upload the file via the **Import groups** button. The system will validate the file and create the groups configured in the file.

{% hint style="danger" %}
Be aware that importing a new group file will **override** any existing groups previously created.
{% endhint %}

***

### **Export Groups**

Groups can be exported from the system for external review or further **editing outside the system**.

To export the groups press the Export button to download the list of groups. The downloaded file will be in Excel format.

***

### **Save Groups**

After making changes to group settings or adding/removing groups, click **Save groups** to apply the changes.

***

### **Reset Groups**

If changes were made but not yet saved, click **Reset** to undo the modifications and revert to the last saved configuration.
