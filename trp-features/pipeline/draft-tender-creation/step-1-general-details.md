# Step 1: General details

This section gathers the basic information needed to identify and manage the tender.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-16 at 16.24.48.png" alt=""><figcaption></figcaption></figure>

***

### Basic Information

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-17 at 00.23.22 (1).png" alt=""><figcaption></figcaption></figure>

* **Tender Number (Auto-generated)**:\
  The system automatically generates a unique tender ID in the format:\
  `OP<year><month><day><3-digit number starting from 001>`.\
  _Example_: OP20230824001. This field is non-editable and serves as a unique identifier for each tender.
* **Title**<mark style="color:red;">**\***</mark>** (Mandatory)**:\
  Enter a clear and descriptive name for the tender. This field is a free-text field, and the name will be used for easy identification in the tender pipeline.
* **Customer**<mark style="color:red;">**\***</mark>** (Mandatory)**:\
  Select or enter the customer associated with the tender. This free-text field provides a dropdown of previously entered customers for quicker selection. If the customer is new, simply enter the name, and it will be saved for future use.
* **Description**:\
  Enter a detailed description of the tender. You can format the text using the formatting options available in the popup toolbar (see the image below). Additionally, you can drag and drop text or images into this field for a more detailed overview. If needed, this text can also be **copied** directly into the "Invitation" section.

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-16 at 17.13.59.png" alt=""><figcaption></figcaption></figure>

* **Invitation**:\
  This field contains the text that will append in the invitation email sent to carriers after the tender is [launched](step-6-final-check-and-launch.md). Like the description field, it can be formatted, and images can be dragged into the field.
* **Reporting Currency**<mark style="color:red;">**\***</mark>** (Mandatory)**:\
  Choose the reporting currency for the tender from the dropdown list. If a default currency is set in the [company settings](../../settings/company.md), it will be automatically selected but can be changed if necessary.
* **Industries**:\
  This informational field captures the industries relevant to the tender.
* **Tags**:\
  Add relevant tags to the tender for better organization and search-ability. Tags can include keywords related to the tender's scope, industry, or any custom identifier.

***

### **Tender Deadlines**

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-17 at 00.21.09.png" alt=""><figcaption></figcaption></figure>

* **Internal and Customer Deadlines**<mark style="color:red;">**\***</mark>** (Mandatory)**:\
  These fields set the timelines for the tender. If the tender passes the **Customer Deadline**, the system will automatically change its status to [**Closed**](../closed.md), making it unavailable for carrier participation. Ensure these deadlines are carefully set to align with your tender strategy.
* **Exchange Rate Date**:\
  This field provides informational data about the date when the exchange rates were set, which is important for rate evaluation in tenders involving multiple currencies.
* **Rates Validity Dates (From, Till)**:\
  Specify the date range during which the tender rates are valid. These dates ensure that quoted rates from carriers remain relevant and aligned with the tender timeline.

***

### **Team Responsibilities Setup**

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-17 at 00.31.55.png" alt=""><figcaption></figcaption></figure>

* **Tender Team**:\
  Here, you can assign managers who will oversee and monitor the tender’s progress. Select from existing managers using the dropdown list, or enter a new manager’s email to add them to the system. If an email is entered for a new manager, the system will create an account for that user upon tender launch.
* **Sales Responsible**:\
  Select the sales manager responsible for this tender from the dropdown list. As stated in the field placeholder, they will be able to access launched tender in read-only mode.

***

### **Additional Configuration**

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-17 at 00.34.17.png" alt=""><figcaption></figcaption></figure>

* **Instructions**:\
  Upload any relevant files (e.g., tender instructions, requirements, or guidelines) that will assist carriers in submitting accurate bids. These files can be essential for clarifying tender terms and conditions, and setup of the rate card. (<mark style="color:red;">TODO</mark> link to rate card section when it's ready)
* **Additional Information**:\
  This section allows you to add any extra details not covered by the previous fields. Provide a descriptive title and add the required information that may assist in the tender evaluation or execution.

***

After entering all the required information, review the details carefully to ensure accuracy. You can modify any section before finalizing the tender. Once satisfied, proceed to **save** or navigate to the **next** step - [Rate Card(s) upload](step-2-rate-card-s.md).&#x20;
