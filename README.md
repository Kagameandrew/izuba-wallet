# Izuba Wallet: prototype

A clickable prototype of a mobile wallet for Rwanda. It runs entirely in the browser on **fake sandbox money**. There's no backend, and real money is never moved.

## Features
- Send money to Izuba, MTN MoMo and Airtel Money numbers, or to a bank account, with the name and fee shown before you confirm
- Scam warnings for large first-time transfers and "send back my money" requests
- Shop payments by till number or a simulated QR scan
- Bills (REG Cash Power with token, WASAC, Canal+, StarTimes, Irembo, RRA) and airtime
- Split a bill, and set up scheduled payments
- Savings goals with an optional lock and 6% a year interest
- Small loans with a flat fee, a credit score, and the Boost overdraft
- Cash out at an agent with a one-time code
- Spending and fee insights

## Run it
Open `index.html` in any browser. The demo PIN is **1234**.

To put it online for free, go to the repo's **Settings → Pages**, choose the `main` branch, and save. Your link will be `https://<your-username>.github.io/<repo-name>/`.

## Note
All names, numbers, merchants, fees and rates are invented for the demo. A live service needs a National Bank of Rwanda payment service provider licence or a licensed partner, plus real integrations such as the MTN MoMo API.
