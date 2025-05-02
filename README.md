Steps to Reproduce:

Objective
This test ensures the smooth operation of the e-commerce checkout process, including product addition, cart validation, checkout, payment, offers, and successful order ID generation.

Test Steps
1. Visit Website
Go to: [https://php811.funnelkitdemos.com/](url)

2. Add Product to Cart
Select any product and click on ‘Add to Cart’.

![image](https://github.com/user-attachments/assets/4bebd914-17f9-4fcc-9e80-ad16250dabe2)


3. Verify Cart
Check if the side cart auto-opens and displays the selected product.



4. Proceed to Checkout
Click the ‘Checkout’ button to move to the checkout page.



5. Fill in Checkout Form
Enter random customer details.

Choose ‘Cash on Delivery’ as the payment method.

6. Review and Apply Offer
If an offer appears, select the product and wait.

Accept the offer and proceed to payment.



7. Order Confirmation
After payment, verify the Thank You page loads with a displayed Order ID.

The test is successful if the order ID is visible.

Expected Outcome:
Cart opens and updates with added product.

Checkout process functions correctly.

Payment method is selectable.

Offer is applied successfully.

Order ID is displayed on the Thank You page.
