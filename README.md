# CampusBoost

A working prototype for the NxtWave Growth Intern challenge: get 500 final-year B.Tech students to register for a free workshop, "Build Your First AI Project in 60 Minutes", in 7 days with a ₹2,000 budget.

## What it does

- **Partner bot (WhatsApp-style):** campus ambassadors, influencers and placement coordinators onboard in a chat and get a unique referral code and link.
- **Referral tracking:** every sign-up is credited to the right ambassador or channel. The same WhatsApp number is never counted twice.
- **Ambassador race:** 25 campus ambassadors (goal: about 10 verified sign-ups each) compete on a live leaderboard. The top 3 win ₹250 / ₹200 / ₹150 by UPI, and everyone gets a certificate.
- **Automatic milestone messages:** the bot messages an ambassador at 5, 10, 20 and 50 sign-ups, and when they enter the top 3.
- **Rewards and budget:** top 3 ambassadors, 2 influencer posts (₹100 each), the highest student referrer (₹200) and AI certification exam vouchers (₹1,000). Rewards move from Pending → Approved → Paid, and the total can never go above ₹2,000.
- **Organiser dashboard:** progress to 500, daily target vs actual, sign-ups by channel and college, a Day 3 backup-plan alert, and a recommendation for where to push next.

## Notes

- This is a prototype. Data is stored in the visitor's own browser and starts with clearly labelled demo data. Use "Reset demo data" on the dashboard to start again.
- WhatsApp messages and UPI payments are simulated. A real launch would use the WhatsApp Business API, an authorised UPI payout service and a shared database.

## Run it

Open `index.html` in a browser, or publish it with GitHub Pages.
