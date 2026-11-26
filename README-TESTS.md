# Playwright test suite

This project contains example end-to-end UI tests for the public Sauce Demo practice site.

## Covered scenarios

- Successful login
- Invalid password feedback
- Required username validation
- Adding a product to the cart
- Removing a product from the cart
- Completing a checkout flow

## Requirements

- Node.js (LTS recommended)
- npm
- Internet connection to access https://www.saucedemo.com

## Run locally

```bash
npm install
npx playwright install
npm test
```

Open the HTML report:

```bash
npm run report
```

Run with a visible browser:

```bash
npm run test:headed
```

## Test account

The public Sauce Demo practice site documents this standard test account:

- Username: `standard_user`
- Password: `secret_sauce`

Use this only on the public demo site, never on a real account.

## Notes

These are portfolio practice tests against a third-party demo application. They are not tests of Syncfusion products or proprietary systems. Review selectors and site behavior if the demo application changes.
