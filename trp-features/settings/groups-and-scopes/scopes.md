# Scopes

### Overview

Scopes define the range and specifics of the services offered by carriers participating in a tender.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-16 at 14.09.27.png" alt=""><figcaption></figcaption></figure>

They are configured using the following parameters:

* Rate Export: Option to enable or disable the possibility to export rate card(s) for this scope.
* Transportation Modes: Types of transport services provided (e.g., air, sea, road).
* Service Types: The specific types of logistics services offered (e.g.,airport-to-door, door-to-door, airport-to-airport).
* Geographic Coverage: Countries, states or ports both of freight origin and destination covered by the carrier.&#x20;
* Quoting groups at Origin, Main, and Destination Points: List of groups that provide services at the points of origin, during the main transport, and at destination locations.
* Responsible Managers: Emails or managers responsible for overseeing the services within each scope.
* Additional Parameters: Any other relevant information necessary for accurate rate card configuration, cost estimation, and quoting. Go to <mark style="color:red;">Entities</mark> for more information.

Scopes ensure that the system accurately reflects the capabilities and coverage areas of each carrier, facilitating effective tender management and decision-making.

### **Adding a Scope**

{% hint style="warning" %}
Before adding scopes, ensure that **groups** have been created, as scopes will be associated with these groups for proper configuration.
{% endhint %}

**Steps to Add a Scope**

1. **Click "Add Scope"**:\
   To create a new scope, click the **"Add Scope"** button. The system will display a side panel with fields to configure.
2. **Configure Scope Fields**:\
   The configuration of the scope depends on the requirements of the tender’s rate card. You need to ensure that the scope settings align with the fields in the rate card for accurate coverage and matching.
   * **Transport Modes**: Select applicable modes such as air, ocean, or road transport.
   * **Service Types**: Specify service types like Full Truckload (FTL), Less than Truckload (LTL), or Express.
   * **Origin Countries**: Add the countries from where the shipments originate.
   * **Destination Countries**: Define the countries for delivery destinations.
   * **Origin Ports**: Indicate specific origin ports for maritime transport.
   * **Destination Ports**: Add destination ports for the end points of sea freight.
   * **Quoting Groups**: Set up quoting groups for origin, main freight, and destination segments.
   * **Rate Export Allowance**: Enable or disable rate export functionality using the checkbox.

### **Importing and Exporting Scopes**

* **Export Scopes**:\
  You can export the configured scopes as an Excel file. This is useful for external review or further editing of scope configurations.
* **Import Scopes**:\
  Instead of manually creating scopes, you can import a pre-configured Excel file. The file should contain the required scope data, ensuring quick setup.

{% hint style="danger" %}
Be aware that importing a new scopes file will **override** any existing scopes previously created.
{% endhint %}

### **Reset**

Reverts any unsaved changes, restoring the scope to its previous state, preventing any unintended modifications.

### Save

Confirms and saves the scope configurations you’ve made. There are two ways to save:

1. **Update system scopes only**: Updates scopes in the system without impacting existing tenders.
2. **Update also tender scopes**: Also updates scopes for active tenders, potentially affecting rate card coverage and carrier participation.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-19 at 09.53.46.png" alt=""><figcaption></figcaption></figure>
