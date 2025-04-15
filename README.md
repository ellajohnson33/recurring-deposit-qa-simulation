# Recurring Deposit QA Simulation 💸

This is a QA automation project inspired by Acorns' recurring micro-investment feature. It simulates how recurring deposits are scheduled, executed, and tested — including feature flag logic, user flows, and error states.

## 🔍 What It Does

- Mocks recurring deposit behavior (like Acorns' weekly investments)
- Allows deposits to be scheduled by user, amount, and frequency
- Handles API testing with Postman
- Includes feature flag logic (coming soon!)
- Easily expandable for unit tests (Jest) and CI testing (GitHub Actions)

## 🧪 Tech Stack

- Node.js + Express
- Postman (manual API testing)
- JSON (mock data + feature flags)
- GitHub for version control

## 🚀 How to Use

1. Clone the repo  
   `git clone https://github.com/YOUR-USERNAME/recurring-deposit-qa-simulation.git`
2. Run `npm install`
3. Start the server: `npm start`
4. Use Postman to test:
   - `POST /deposit` to schedule a deposit
   - `GET /deposits/:userId` to view a user's deposits

## 🎥 Demo

Coming soon — 60-second walkthrough via Loom

## 🙋 Why I Built This

Acorns’ mission to make investing automatic inspired me to think like a QA engineer: testing edge cases, simulating real user behavior, and building trust through reliability. This project reflects how I approach quality, problem-solving, and product-focused engineering.

---
