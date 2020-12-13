# Using Checkout for subscriptions

## How to run locally

Follow the steps below to run locally.

**1. Clone and configure the sample**

You will need a Stripe account in order to run the demo. Once you set up your account, go to the Stripe [developer dashboard](https://stripe.com/docs/development/quickstart#api-keys) to find your API keys.

```
STRIPE_PUBLISHABLE_KEY=<replace-with-your-publishable-key>
STRIPE_SECRET_KEY=<replace-with-your-secret-key>
```

**2. Create Products and Prices on Stripe**

This sample requires two [Price](https://stripe.com/docs/api/prices/object) IDs to create the Checkout page. Products and Prices are objects on Stripe that let you model a subscription.

**3. Confirm that you have set the account name**

**4. Follow the server instructions on how to run:**

```
cd server/node # there's a README in this folder with instructions
npm install
npm start
```
