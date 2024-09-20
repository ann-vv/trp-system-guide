# Rate Card Coverage

After the rate card(s) are uploaded, the system calculates and displays the coverage statistics for each rate card based on the scopes of carriers configured in the system.

### **Coverage Definition**

Coverage is determined by matching the parameters defined in the Scopes configuration against the corresponding fields in the Rate Card. The following parameters are used to evaluate coverage:

* Transport Mode
* Origin Region
* Origin Port
* Origin Country
* Destination Region
* Destination Port
* Destination Country

### **Coverage Calculation**

The system calculates the coverage percentage (%) by comparing the scope settings of each carrier group against the fields specified in the rate card. The coverage percentage indicates how well a group's services align with the tender requirements.

{% hint style="info" %}
**Participation Eligibility**: To participate in the tender, the carrier group must cover at least one lane of the rate card.
{% endhint %}

This functionality ensures that only relevant carriers, whose services align with the tender specifications, are considered for the quoting process, optimizing the selection of carriers for each tender.

### **Activation and Deactivation of Group Participation**

In the TRP system, users have the flexibility to manage the participation of carrier groups in a tender. This includes the ability to **activate** or **deactivate** groups that cover the rate card baseline. Deactivating a group means that it will not be invited to participate in the tender, and its rate card coverage will no longer apply. This functionality is useful for controlling which carriers are involved in a specific tender based on changing requirements or participation criteria.

<figure><img src="../../../../../.gitbook/assets/Screenshot 2024-09-19 at 00.45.33.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Deactivating a group will result in a reduction of rate card coverage. The system will adjust the percentage of lanes covered by the active groups.
{% endhint %}

#### **Steps to Deactivate a Group**

1. Select the group or groups you wish to deactivate in the Participants area.
2. Unselect the "Status" checkbox.
3. **System Response**:\
   Once the group is deactivated, the system will automatically update its rate card coverage:
   * The group’s **rate card coverage** will be reduced to 0%, meaning it no longer contributes to fulfilling the tender requirements.
   * A **Suspended** label will appear next to the group, indicating that it has been deactivated and will not be invited to participate in the tender.

<figure><img src="../../../../../.gitbook/assets/Screenshot 2024-09-18 at 08.33.45.png" alt=""><figcaption></figcaption></figure>

#### **Reactivating a Group**

1. Select the group or groups you wish to activate in the Participants area.
2. Recheck the "Status" checkbox.
3. **System Response**:\
   Once reactivated, the group will be invited to participate in the tender and can submit quotes for the rate card.
