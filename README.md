# CampusBoost

A working prototype for the NxtWave Growth Intern challenge: get 500 final-year B.Tech students to register for a free workshop, "Build Your First AI Project in 60 Minutes", in 7 days with a ₹2,000 budget.

## What it does

- **Partner bot (WhatsApp-style):** campus ambassadors, influencers and placement coordinators onboard in a chat and get a unique referral code and link.
- **Referral tracking:** every sign-up is credited to the right ambassador or channel. The same WhatsApp number is never counted twice.
- **Automatic milestone messages:** the bot messages a partner at 10 sign-ups and at every 25% of their target.
- **Rewards and budget:** 3 ambassadors with targets of 250 / 150 / 100 earn ₹1.20 per verified sign-up (up to ₹300 / ₹180 / ₹120). Rewards move from Pending → Approved → Paid, and the total can never go above ₹2,000.
- **Organiser dashboard:** progress to 500, daily target vs actual, sign-ups by channel and college, a Day 3 backup-plan alert, and a recommendation for where to push next.

## Notes

- This is a prototype. Data is stored in the visitor's own browser and starts with clearly labelled demo data. Use "Reset demo data" on the dashboard to start again.
- WhatsApp messages and UPI payments are simulated. A real launch would use the WhatsApp Business API, an authorised UPI payout service and a shared database.

## Run it

Open `index.html` in a browser, or publish it with GitHub Pages.
