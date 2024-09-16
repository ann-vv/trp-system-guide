# Tender Creation

To create a new tender in the TRP system, follow the steps outlined below. Each section of the tender setup process is designed to capture all the necessary details and configurations required for successful tender management.

## **Step 1: Initiating Tender Creation**

**Click "New Tender"**:\
In the top right corner of the screen, click the **"New Tender"** button to begin the tender creation process. The system will redirect you to the tender creation page.

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-16 at 16.28.17.png" alt=""><figcaption></figcaption></figure>

## **Step 2: General Details**

This section gathers the basic information needed to identify and manage the tender.

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-16 at 16.24.48.png" alt=""><figcaption></figcaption></figure>

***

### Basic Information

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-17 at 00.23.22 (1).png" alt=""><figcaption></figcaption></figure>

* **Tender Number (Auto-generated)**:\
  The system automatically generates a unique tender ID in the format:\
  `OP<year><month><day><3-digit number starting from 001>`.\
  _Example_: OP20230824001. This field is non-editable and serves as a unique identifier for each tender.
* **Title (Mandatory)**:\
  Enter a clear and descriptive name for the tender. This field is a free-text field, and the name will be used for easy identification in the tender pipeline.
* **Customer (Mandatory)**:\
  Select or enter the customer associated with the tender. This free-text field provides a dropdown of previously entered customers for quicker selection. If the customer is new, simply enter the name, and it will be saved for future use.
* **Description**:\
  Enter a detailed description of the tender. You can format the text using the formatting options available in the popup toolbar (see the image below). Additionally, you can drag and drop text or images into this field for a more detailed overview. If needed, this text can also be copied directly into the "Invitation" section.

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-16 at 17.13.59.png" alt=""><figcaption></figcaption></figure>

* **Invitation**:\
  This field contains the text that will be appended to the invitation email sent to carriers after the tender is launched. Like the description, it can be formatted, and images or text can be dragged into the field.
* **Reporting Currency (Mandatory)**:\
  Choose the reporting currency for the tender from the dropdown list. If a default currency is set in the [company settings](../settings/company.md), it will be automatically selected but can be changed if necessary.
* **Industries (Optional)**:\
  This informational field captures the industry or industries relevant to the tender. This is useful for categorization or filtering<mark style="color:red;">(?)</mark>.
* **Tags (Optional)**:\
  Add relevant tags to the tender for better organization and searchability. Tags can include keywords related to the tender's scope, industry, or any custom identifier.

***

### **Tender Deadlines**

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-17 at 00.21.09.png" alt=""><figcaption></figcaption></figure>

* **Internal and Customer Deadlines (Mandatory)**:\
  These fields set the timelines for the tender. If the tender passes the **Customer Deadline**, the system will automatically change its status to **Closed**, making it unavailable for carrier participation. Ensure these deadlines are carefully set to align with your tender strategy.
* **Exchange Rate Date**:\
  This field provides informational data about the date when the exchange rates were set, which is important for rate evaluation in tenders involving multiple currencies.
* **Rates Validity Dates (From, Till)**:\
  Specify the date range during which the tender rates are valid. These dates ensure that quoted rates from carriers remain relevant and aligned with the tender timeline.

***

### **Team and Responsibility Setup**

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-17 at 00.31.55.png" alt=""><figcaption></figcaption></figure>

* **Tender Team**:\
  Here, you can assign managers who will oversee and monitor the tender’s progress. Select from existing managers using the dropdown list, or enter a new manager’s email to add them to the system. If an email is entered for a new manager, the system will create an account for that user upon tender launch.
* **Sales Responsible**:\
  Select the sales manager responsible for this tender from the dropdown list. This role is critical in managing communication and tender strategy with the customer and internal teams.

***

### **Additional Configuration**

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-17 at 00.34.17.png" alt=""><figcaption></figcaption></figure>

* **Instructions**:\
  Upload any relevant files (e.g., tender instructions, requirements, or guidelines) that will assist carriers in submitting accurate bids. These files can be essential for clarifying tender terms and conditions.
* **Additional Information**:\
  This section allows you to add any extra details not covered by the previous fields. Provide a descriptive title and add the required information that may assist in the tender evaluation or execution.

***

After entering all the required information, review the details carefully to ensure accuracy. You can modify any section before finalizing the tender. Once satisfied, proceed to **save** or navigate to the **next** step - Rate Card upload.&#x20;

## **Step 3: Rate Card(s)**

In this step, you will upload and configure rate cards that are essential for the tender. The TRP system allows multiple rate cards per tender, providing flexibility in managing various lanes, services, and cost structures.

### **Initiating Rate Card Upload**

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-17 at 01.01.37.png" alt=""><figcaption></figcaption></figure>

To begin, click the **"Create First Rate Card"** button if no rate card has been added yet, or simply press the **"+ Rate Card"** button to add more rate cards to the tender. This will open a configuration panel where you can set up the initial parameters for the rate card.

### **Rate Card Configuration Panel**

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-17 at 01.05.09.png" alt=""><figcaption></figcaption></figure>

In the popup panel, you will need to configure the following initial parameters:

* **Transport Mode**:\
  Select the available transport mode for the rate card. This ensures that the rate card is aligned with the mode of transport required for the tender.
* **Rate Card Title**:\
  Enter a descriptive title for the rate card. This title will help distinguish between different rate cards in tenders with multiple configurations.
* **Baseline File Upload**:\
  Upload the baseline rate card file. This file typically contains pre-set pricing data and lane configurations that will be used as a basis for the tender’s bidding process. For more details jump to [Reviewing and Mapping Rate Card Fields](tender-creation.md#reviewing-and-mapping-rate-card-fields).
* **Bid Rules Configuration**:\
  Set up bid rules that determine how lanes with errors will be handled during the rate card upload process. The system offers the following options:
  * **Save Valid**:\
    Only valid rows in the rate card will be saved, ignoring any cells with errors.
  * **Reject Lane**:\
    If any data in a lane contains errors, the entire lane will not be saved.
* **Additional Options**:\
  There are three additional checkboxes that further configure how the system handles the rate card upload: blanks overriding, off-scope, and baseline grouping. Hover over the **info icon** next to each checkbox to view detailed explanations of these configurations.

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-17 at 01.14.40.png" alt=""><figcaption></figcaption></figure>

### **Reviewing and Mapping Rate Card Fields**

Once you have uploaded the baseline file, the system will present a popup that enables you to review the field mappings. This step is crucial to ensure that the data in the rate card aligns with the system’s expected fields.

<figure><img src="../../.gitbook/assets/Screenshot 2024-09-17 at 01.15.59.png" alt=""><figcaption></figcaption></figure>

* **Field Mapping**:\
  The system automatically attempts to map the fields in your uploaded rate card to the predefined fields in the system. Review these mappings carefully, and make any necessary adjustments to ensure accurate data alignment. For detailed instructions on how to use the field mapping feature, refer to the **Field Mapping Guide** \[link to page].
* **Confirm and Proceed**:\
  Once you have confirmed the mappings, click **Proceed** to proceed with the rate card configuration.

**Step 7.3: Finalizing Rate Card Setup**

After the field mapping is complete, the system will display the uploaded rate card. From this view, you can review, edit, and take further actions on the rate card.\
If any corrections are needed, you can modify the rate card directly in the system. For more information on editing rate cards, refer to the **Rate Card Guide** <mark style="color:red;">\[link to page]</mark>.
