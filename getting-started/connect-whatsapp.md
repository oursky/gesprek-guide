# Connect with Whatsapp

With Gesprek, you can easily integrate with Whatsapp. After our team create a new account for your company, we will need these two things to help you setup the Whatsapp integration with our system:

1. Twilio Number
2. Facebook Business Manager Account ID

After your number is approved by Whatsapp, you will have a business account. It means that you are able to send direct message or use a templated notifications. In Gesprek, we can send a system message to notify your customer of the latest status update. Here is the list of status in our system that you can modify:

* Order Status Template Message \(System Message\)
  * Order Sent
    * e.g.

      ```text
       Order Confirmation (#IQma2srqAkqb7YQ0uYwFnA)

       Iphone 11 256GB Black
       Qty: 1
       Price: HKD 6,899.00

       Total: HKD 6,899.00

       Click here to track your order:
       https://customer.gesprek.chat/company1/order?token=xxxxxx
      ```
  * Paid
    * e.g.

      ```text
        Order Status Update (#12345678): Paid

        Click here to track your order:
        https://customer.gesprek.chat/company1/order?token=xxxxxx
      ```
  * Processing
  * Shipped
    * e.g:

      ```text
        Your order (#12345678) is on the way! Here is the details:

        Carrier: DHL
        Tracking No.: 1234

        Click here to track your order:
        https://customer.gesprek.chat/company1/order?token=xxxxxx
      ```
  * Completed
  * Outstanding Payment
  * Receipt Rejected
  * Payment Rejected
  * Refunding
  * Refunded
  * Return Request
  * Return Handling
  * Return Rejected
  * Returned
  * Cancelled

The above messages are just an example, you are free to modify the messages yourself! Tell us and we will update it for you.

On top of the above list, you can send another non-system message to your customers. We will help you apply your template message to Whatsapp. Here is another template message example of what you can send through our portal:

* Thank you for uploading the payment receipt. We will process your order ASAP after confirming your payment.
* I was able to do some follow-up based on our previous conversation, and I’ve found the answer to your question about our refund policy. If you’d like to continue our conversation, please say ‘yes’.
* Thank you for your reservation at Skygear. We look forward to seeing you on 1st of August. You can check in between 13.00 - 17.00. If you come before or after these times, you can reach us at 12345678. See you soon!
* Hi! Thanks for your question! We have received this and forwarded it to our tech department. If we have an update from them, we will keep you informed! Regards, Oursky

Your WhatsApp message templates must fall into one of the following categories. Templates that do not align clearly with these template types are more likely to be rejected by WhatsApp in the template approval process described below.

* **Account Update:** Let customers know about updates or changes to their accounts.
* **Alert Update:** Send important updates or news to customers.
* **Appointment Update:** Send confirmations, reminders, or other updates to customers about their appointments.
* **Auto-Reply:** Send auto-replies to customers when your business isn't online or available to respond right away.
* **Issue Resolution:** Respond to questions, concerns, or feedback from customers about your business.
* **Payment Update:** Send a message to customers about their payment.
* **Personal Finance Update:** Send a message to customers about their personal finances.
* **Reservation Update:** Send confirmations, reminders, or other updates to customers about their reservations.
* **Shipping Update:** Send shipping updates to customers about their orders.
* **Ticket Update:** Send ticketing information or updates to customers.
* **Transportation Update:** Send transportation information or updates to customers.

