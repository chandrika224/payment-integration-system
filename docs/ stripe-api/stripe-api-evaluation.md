# Stripe API Evaluation

Before implementing the **Stripe Provider Service**, the Stripe Checkout Session API was evaluated independently to understand its functionality, request format, authentication, and payment workflow.

The evaluation followed these steps:

1. Studied the official Stripe API documentation.
2. Tested the Checkout Session API using Postman.
3. Verified request and response payloads.
4. Completed an end-to-end payment using Stripe Hosted Checkout.
5. Verified payment details in the Stripe Dashboard.
6. Tested webhook notifications locally using Stripe CLI.

This evaluation provided a clear understanding of Stripe's payment lifecycle before integrating it into the Payment Integration System.

## Documentation

- 📄 [Stripe Functional Flow](docs/Functional%20flow%20of%20Stripe.pdf)
- 📄 [Checkout Session API Testing](docs/checkout%20session%20API%20-%20testing.pdf)
- 📄 [Webhook Processing Testing](docs/Testing%20Webhook%20processing.pdf)

## Screenshots

### Stripe Checkout Session API


![Stripe Create Session API](screenshots/postman/stripe-create-session-api.png)

### Stripe Hosted Checkout Payment Page

![Stripe Hosted Checkout](screenshots/postman/hosted-payment-page.png)

### Redirected Merchant Page

![Payment Success](screenshots/postman/redirected-merchant-page.png)

### Stripe Dashboard

![Stripe Dashboard](screenshots/postman/stripe-dashboard-payment.png)

### Stripe CLI Webhook Testing

![Stripe CLI](screenshots/postman/stripe-cli-webhook.png)
