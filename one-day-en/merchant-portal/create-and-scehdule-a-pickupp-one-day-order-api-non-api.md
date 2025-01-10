---
description: >-
  Order creation can be conducted in two ways: via API or through non-API
  methods.
---

# Create & Scehdule a Pickupp One Day Order (API/Non-API)

#### Non-API Merchant Single Order Creation

1. **Access the Portal:**
   * Log in to the Pickupp merchant portal
2. **Start Order Creation:**
   * Select 'Create Standard Order' within the Orders section.

<figure><img src="../.gitbook/assets/Screenshot 2024-04-09 at 5.29.22 PM.png" alt=""><figcaption></figcaption></figure>

3. **Fill in Sender Details:**

* Complete the Sender Info with the necessary details, including name, phone number (8 digits) and address (with address number and name and building).

4. **Enter Recipient Information:**

* Complete the Recipient Info, and choose either 'To door delivery' or 'Self pickup service'.&#x20;
* If selecting self pickup, this means the recipient / consignee will be going to a designated locker to perform a self pick-up process. Click "self pick up store" link to open a separate screen. Please ensure you choose the desired self pickup store number.

<figure><img src="../.gitbook/assets/Screenshot 2024-04-09 at 5.39.58 PM.png" alt=""><figcaption></figcaption></figure>

5. **Provide Item Details:**

* Enter accurate measurements of the parcel including length, width, height, and weight in the Item info.

6. **Select Service Preferences:**

* Choose the service that best suits your needs based on service type, timing, and cost. Proceed to confirm your choices and then move to payment.

#### Non-API Merchant Bulk Order Creation

1. **Access the Portal:**
   * Log in to the Pickupp merchant portal using the new version page.
2. **Prepare for Bulk Creation:**
   * Click on 'Bulk Create' under the Orders section.
3. **Use the Template:**
   * Download the STANDARD SERVICE TEMPLATE and accurately fill in the bulk upload template.
4. **Upload Order Details:**
   * UPLOAD the completed template. If creating a self pickup order, be sure to include the self pickup store number in the 'Partner Store Number (Self Pick Up)' column.
5. **Fill in Sender Details:**
   * Complete the Sender Info section.
6. **Enter Recipient Information:**
   * Complete the Recipient Info, choosing between 'To door delivery' or 'Self pickup service'. If self pickup is chosen, select the appropriate store number.
7. **Provide Item Details:**
   * Accurately detail the parcel's dimensions and weight in the Item info section.
8. **Select Service Preferences:**
   * Choose your desired service based on your preference for service type, timing, and cost. Confirm your choices and proceed to payment.
9. **Finalize Upload:**
   * Select UPLOAD if everything is correct and confirmed, then proceed to confirm and pay.

#### API Merchant Order Creation

1. **System Confirmation:**
   * Ensure system settings are confirmed with Pickupp, including service pricing and waybill version.
2. **API Settings Configuration:**
   * Adjust API settings on the merchant side as needed.
3. **Pickupp System Settings:**
   * Confirm settings within the Pickupp system.
4. **Service Offering Selection:**
   * Choose the correct Pickupp Service Offering ID as per the instructions provided.
5. **Order Creation via API:**
   * Create the order using the API with the selected Pickupp Service Offering, referring to the provided screenshot in the API documentation.

#### For Merchants with Unique Waybills

1. **Enable System Setup:**
   * Confirm the system setup with Pickupp if you intend to use your own waybill with a unique Client Reference Number (CRN) and barcode.
2. **CRN Requirements:**
   * Ensure that the CRN pattern is unique and not duplicated within the platform; the system will reject any non-unique CRNs or secondary parcels under an existing CRN. Contact Pickupp for system setup assistance prior to order creation.
