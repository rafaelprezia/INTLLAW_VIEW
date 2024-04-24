"""
# INTLLAW VIEW Payment Portal

This is the first version (currently in test mode) of the payment portal for the INTLLAW Platform. This version allows you to simulate transactions to ensure the smooth integration and functionality of the payment system.

## Test Card Information

Use the following test cards to simulate different scenarios with the payment gateway. These cards will not result in real transactions.

### Standard Test Cards

- **Visa**: 
  - Number: 4242424242424242
  - CVV: Any 3 digits
  - Expiry: Any future date

- **Visa (Debit)**:
  - Number: 4000056655665556
  - CVV: Any 3 digits
  - Expiry: Any future date

- **Mastercard**:
  - Number: 5555555555554444
  - CVV: Any 3 digits
  - Expiry: Any future date

- **Mastercard (2-series)**:
  - Number: 2223003122003222
  - CVV: Any 3 digits
  - Expiry: Any future date

- **Mastercard (Debit)**:
  - Number: 5200828282828210
  - CVV: Any 3 digits
  - Expiry: Any future date

### International Test Cards

- **United States (US)**:
  - Number: 4242424242424242
  - Brand: Visa

- **Argentina (AR)**:
  - Number: 4000000320000021
  - Brand: Visa

- **Brazil (BR)**:
  - Number: 4000000760000002
  - Brand: Visa

- **Canada (CA)**:
  - Number: 4000001240000000
  - Brand: Visa
    
### More information on completing a purchase in test mode

To complete a purchase using the test mode, follow the steps outlined in the Stripe documentation for testing:

[Stripe Testing Documentation](https://docs.stripe.com/testing#cards)
## Feedback

As this is a test version, any feedback or issues encountered during the testing process would be greatly appreciated to improve the system. Please direct your feedback and reports to rafael.prezia@storaged-us.com.
