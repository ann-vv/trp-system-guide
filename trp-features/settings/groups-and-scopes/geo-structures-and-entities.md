# Geo-Structures & Entities

The **Geo-Structures** and **Entities** functionalities work together to define what volume of shipment a group is able or willing to ship. They ensure that carrier groups can only quote on rate card lanes that fall under their defined area of responsibility.

### **Geo-Structures**

Geo-Structures allow the configuration of additional geographic fields (typically they could be **trade region**, **trade area, region**) for both origin and destination countries, providing more granular control.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-19 at 15.28.17.png" alt=""><figcaption></figcaption></figure>

**Configuration Steps:**

1. In the configuration table, add a new column for the desired geo-structure field.
2. Specify this geo-structure for the applicable country.
3. This geo-structure will be reflected in entity configurations.

### **Entities**

Entities define the volume thresholds and specify which group is responsible for handling shipments based on geographic and volume data.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-19 at 15.29.57.png" alt=""><figcaption></figcaption></figure>

**Entities configuration table contains 3 default columns:**

* **Transport Mode**: Pre-defined system transport modes.
* **Volume**: The maximum volume a group (entity) is capable of handling.
* **Entity**: The name of the entity responsible for that volume.

Geo-structures are displayed twice— for origin and for destination freights—allowing for detailed volume-based configurations. Different combinations of origin and destination geo-structures can be configured with varying volume thresholds.

### **Scopes Integration**

Once entities are configured, they can be included in the **Scopes** table under the "Scope Entities" column.

{% hint style="info" %}
**Advice**: Use the "copy" function to duplicate scopes with the same geographic fields but different scope entities. This makes it easier to manage configurations with varying volumes or responsibilities.
{% endhint %}

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-19 at 15.32.15.png" alt=""><figcaption></figcaption></figure>

### **Impact On the Rate Card**

The rate card coverage and quoting availability for groups are calculated based on the configured scope entities. Here’s how it works. The following rate card fields are taken into account:

* **Origin and Destination Countries**: As defined in geo-structures.
* **Scope Volume**: This rate card field **aggregates** all volume values for the specified geo-structures.

The system **calculates** which scope entity can cover the lanes based on the volume and geographical data. This ensures precise control over which carrier groups can **participate** in the tender and **quote** on specific lanes, depending on their volume and geographic responsibility.
