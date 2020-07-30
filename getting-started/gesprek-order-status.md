# Gesprek Order Status

## Gesprek Built-in Order Status

We have 16 built-in order statuses in our portal that we tailor to fit all your business needs. Here is the detailed information about our order status and the occasions which you can use it.


|Order Status                      |Description/Situation                     |
|----------------------------------|------------------------------------------|
|Order Sent|Upon creating order and send to customer, the status will become **Order Sent**|
|Receipt Received|After the customer upload the receipt in checkout when using bank transfer, the status will be automatically changed from **Order Sent** to **Receipt Received**|
|Paid|When using bank transfer, after the receipt is confirmed by the staff, the status will be automatically changed to **Paid**|
||When using credit card, and the payment is accepted/successful, the status will automatically be changed to **Paid**|
|Processing|The order is currently being processed|
|Shipped|The order has been shipped. This status can also include the carrier and the tracking number|
|Completed|The order is received by the customer and the staff will not be able to change the status anymore|
|Outstanding Payment| If there is a deposit in the payment process, this status can notify that there's an **outstanding payment** needed to be paid|
||Can also be used if the client did not pay enough money and then the seller requires an additional payment|
|Receipt Rejected|Can be used if the customer uploaded the wrong receipt/image and this status can notify the customer that the receipt is rejected and customer needs to upload the receipt again|
||Also can be used if the receipt is blurry and can't be read by the staff|
|Payment Rejected|Can be used in case of payment got cancelled or not sucessfully sent by the customer side or not received by the seller side.|
|Refunding|Refund is being processed|
|Refunded|Refund process is finished. The money is sent back to the customer|
|Return Request|The customer requested a return|
|Return Handling|The customer is handling the product return|
||The staff is handling the refund/return process|
|Return Rejected|The return request is rejected|
|Returned|The product is returned to the seller and the customer get the refund|
|Cancelled|The order is cancelled by request or after 30 days of being pending|


## State Flow

> This is the ideal flow that we recommend and we do not enforce this flow. You are free to adjust the flow based on your needs

**Order Sent** > Receipt Received | Paid | Cancelled

**Receipt Received** > Receipt Rejected | Outstanding Payment | Paid

**Paid** > Processing | Shipped | Completed | Refund Request

**Processing** > Shipped | Completed | Refunding

**Shipped** > Completed | Return Request | Return Handling (Return By Carrier)

**Completed** > Return Request

**Outstanding Payment** > Paid | Refunding

**Receipt Rejected** > Paid | Refunding

**Refunding** > Refunded

**Refunded** > Cancelled

**Return Request** > Return Handling

**Return Handling** > Return Rejected | Returned

**Returned** > Refunding

**Cancelled** > N/A
