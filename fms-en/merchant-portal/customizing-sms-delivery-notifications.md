---
description: >-
  You can create and manage customizable SMS notifications to be pushed to the
  consignee or other specific contacts at various stages of the delivery
  process.
---

# Customizing SMS Delivery Notifications

## Setting up an SMS Template

1. Login to the Merchant Portal.
2. Click on the “Profile“ tab on the left-hand side of the screen.
3. Navigate to the “Email & SMS SMS Template“ tab.
4.  Click on the “+” icon (this looks like a plus sign) to create a new template.\


    <figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>
5.  A form will open, asking for some information about the new template.\


    <figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

The table below explains each field in the form:

<table><thead><tr><th width="181.33333333333331">Item</th><th width="146">Options </th><th>Description</th></tr></thead><tbody><tr><td>Template Title</td><td></td><td>This will be the name of your template for your reference.</td></tr><tr><td>Notification Type</td><td></td><td>Select SMS.</td></tr><tr><td>Trigger at</td><td>After dropoff After pickup After accept</td><td><p></p><p>Decide when the SMS notification should be sent:</p><ul><li>'After dropoff' - The notification will be sent once the order status is updated to 'Delivered'.</li><li>'After pickup' - The notification goes out when the order status is updated to 'Enroute'.</li><li>'After accept' - The notification is triggered when the order status is updated to 'Accepted'.</li></ul></td></tr><tr><td>Send to</td><td>Contact 1 Contact 2<br>Sender<br>Recipient</td><td><p>Choose who will receive the SMS:</p><ul><li>'Contact 1' - This is the Contact A under Optional: Extra Notification Contacts in the <a href="creating-and-managing-orders.md#bulk-order-creation-with-csv">Fleet Delivery Template</a>.</li><li>'Contact 2' - This is the Contact B under Optional: Extra Notification Contacts in the <a href="creating-and-managing-orders.md#bulk-order-creation-with-csv">Fleet Delivery Template</a>.</li><li>Sender - Sender of the delivery order.</li><li>Recipient - Recipient of the delivery order.</li></ul></td></tr><tr><td>Status</td><td>Suspended Active</td><td><p></p><p>Select the current state of your SMS notification:</p><ul><li>'Active': If you want the notification to be sent out, please make sure the status is set to 'Active'.</li><li>'Suspended': If you decide to stop sending the notification, change the status to 'Suspended'.</li></ul></td></tr><tr><td>Content</td><td></td><td><p>This will be the body of your SMS. You can include related order details such as:</p><ol><li>Sender Information</li><li>Dropoff Information</li><li>Order Information</li></ol><p>To insert this info, place the cursor where you want the relevant detail to appear and select from (1), (2), or (3). It will show up as {{xxxx}} in the content area. When the system sends the SMS notification, this placeholder will automatically be replaced by the actual order detail.</p><p><br>To add a line break in the SMS content, simply include '\n' where you want the break.</p></td></tr></tbody></table>

6.  After you have filled in all the details, click on “Update“.\


    <figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

\
Please note that the SMS cannot auto-switch to other languages. If necessary, you can send out the SMS in both Chinese and English in one message. Please note the actual word count for SMS will likely be greater than one SMS.

## Troubleshooting

1. The "Update" button is disabled when trying to create a new template.
   * This could be because your SMS count has reached the maximum of five. Consider reducing the length of the SMS content or dividing it into separate messages.
2. Recipients are not receiving the notifications.
   * Check the Status of your templates and make sure they are set to "Active". Also, confirm that the contact information for the recipients is correct.
