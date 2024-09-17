# Manual allocation of the group in the rate card

In addition to the general configuration of groups and scopes in the system settings, the TRP system offers the flexibility to manually create and allocate groups within a specific tender. This feature provides more control over how carriers are assigned to lanes in the rate card.

{% hint style="warning" %}
Manual group allocation is only available while the tender is in the [**Draft**](../) status.
{% endhint %}

### **Step 1: Creating a Group within the Tender**

1. **Initiating Group Creation**:\
   To manually create a group within the tender, click the **"Create Group"** button. A popup window will appear, displaying the same group creation <mark style="color:red;">(TODO correct the Groups section and add the link there)</mark> functionality as found in the general system settings.
2. **Entering Group Details**:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-09-17 at 10.35.50.png" alt=""><figcaption></figcaption></figure>

* **Group Name**:\
  Enter a descriptive name for the group. This name will be used to reference the group throughout the tender.
* **Email List**:\
  Add a list of email addresses for the carriers or participants in this group. The system will create accounts for these email addresses if they do not already exist.

### **Step 2: Configuring Group Coverage in the Rate Card**

Once the group is created, it will initially have **0% coverage** in the rate card. This is because the group has not yet been assigned to any lane or scope within the tender.

1. Select the rate card in the **Rate Card Coverage** area.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-09-17 at 10.36.17.png" alt=""><figcaption></figcaption></figure>

2. **Allocating groups to lanes.** The system will guide you through the process with on-screen hints:

* **Select the lane(s)** in the rate card that you want to allocate the group to.
* **Press "Allocate Group(s)".**

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-09-17 at 11.03.42.png" alt=""><figcaption></figcaption></figure>

3. **Assign to freight type** (origin, main, or/and destination).

{% hint style="info" %}
The system supports the manual allocation of both the created groups inside the tender and groups that were previously set up in the general system settings.
{% endhint %}

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-09-17 at 11.07.44.png" alt=""><figcaption></figcaption></figure>

4. **Confirming Group Allocation**:\
   Once the group has been allocated to the relevant lanes, the system will automatically update the percentage of rate card coverage by this group. This ensures the newly created group is actively participating in the tender process.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-09-17 at 10.44.59.png" alt=""><figcaption></figcaption></figure>

### **Cancel Manual Allocations**

If needed, you can revert manual allocations by pressing the **"Discard Manual Allocations"** button. This will remove the group's association with the selected lanes, and the system will recalculate the rate card coverage percentage accordingly.

### **Impact on Tender Lifecycle**

Once the tender is launched and moves to the **Open** status, the system will enable lane quoting for manually allocated groups. These groups will now be able to submit quotes for the lanes they have been assigned to, and their contributions will be reflected in the tender's evaluation process.
