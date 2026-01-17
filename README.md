# Trust-proof
# TrustProof 🔐⭐  
**Proof of Purchase. Proof of Trust.**

TrustProof is a next-generation review platform that ensures reviews come from **real transactions first**, then uses **AI intelligence** to understand *context, motivation, and relevance* — not just star ratings.

Unlike traditional platforms, TrustProof does not blindly trust reviews.  
It verifies the purchase, then evaluates **how much a review should matter**.

---

## 🚨 Problem

Online reviews are unreliable.

- Fake or biased reviews are easy to post
- Friends/relatives can influence ratings
- Old reviews distort current business quality
- Businesses receive noise instead of insights

Most platforms focus on **volume**, not **credibility**.

---

## ✅ Solution

TrustProof introduces a **transaction-first review system**:

1. **Proof of Purchase**
   - Every review must be tied to a real bill
   - Businesses generate a Bill ID + OTP at checkout

2. **OTP Verification**
   - Customers verify the bill using a time-bound OTP
   - OTPs are single-use and expire automatically

3. **Verified Review Submission**
   - Only verified sessions can submit reviews
   - Reviews are cryptographically linked to transactions

4. **AI-Powered Trust Intelligence (Gemini)**
   - Reviews are analyzed for:
     - Review motivation (genuine, emotional, retaliatory, biased)
     - Expectation vs Reality
     - Relevance over time
     - Language & behavior patterns

5. **Weighted Influence (Not Censorship)**
   - All verified reviews remain visible
   - Reviews affect ratings based on trust context, not equally

> Verified does not mean equally trusted.

---

## 🧠 Core AI Concepts

TrustProof avoids simple “fake vs real” logic and focuses on **review intelligence**:

- **Expectation vs Reality Analysis**  
  Detects whether a business under-delivered or over-delivered.

- **Review Motivation Detection**  
  Understands *why* a review was written, not just sentiment.

- **Trust Decay Over Time**  
  Older reviews lose influence if the business has changed.

- **Collusion Awareness**  
  Suspicious review clusters are detected without deleting reviews.

---

## 🧩 System Architecture

### Frontend
- React + Vite
- TailwindCSS
- Framer Motion
- Firebase Anonymous Auth

### Backend / Data
- Firebase Firestore
- OTP-based bill verification
- Wallet & reward system

### AI Layer
- Google Gemini API
- Review intelligence & business insights

---

## 📂 Firestore Collections

- `users` — anonymous users
- `bills` — transaction proof
- `otps` — OTP metadata
- `reviews` — verified reviews
- `wallet` — reward tracking
- `businesses` — merchant profiles

---

## 🎁 Incentive Model

- Users earn small in-app tokens for verified reviews
- Tokens can be redeemed for rewards
- Low incentives prevent review farming

---

## 🏢 Business Value

- Only purchase-backed reviews
- Reduced rating manipulation
- Actionable AI insights
- Scalable SaaS subscription model

---

## 🛡️ Security & Ethics

- Reviews are not deleted, only weighted
- No invasive tracking
- No exact location storage
- Fair visibility for honest feedback

---

## 🚀 Project Status

- Frontend flows completed
- Firestore structure implemented
- OTP verification logic working
- AI intelligence layer designed and demo-ready

---

## 🧪 Demo Note

Some AI responses are mocked for demonstration and evaluation purposes.  
The system design reflects real-world scalable architecture.

---

## 📜 License

MIT License

---

## 👤 Author

Built by **Aditya**  
B.Tech CSE | Full-Stack & AI Systems
