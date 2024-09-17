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

{% hint style="warning" %}
Participation Eligibility: To participate in the tender, the carrier group must cover at least one lane of the rate card.
{% endhint %}

This functionality ensures that only relevant carriers, whose services align with the tender specifications, are considered for the quoting process, optimizing the selection of carriers for each tender.

\
\
