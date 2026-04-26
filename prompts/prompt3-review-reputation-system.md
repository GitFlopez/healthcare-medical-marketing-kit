# Prompt 3 — Review & Reputation System

## Purpose
Generate a complete review request and response system that grows your star rating, turns satisfied patients into advocates, and protects your practice from the legal risk of HIPAA-violating public responses.

## Critical HIPAA Warning
A practice responding to a review must NEVER: confirm or deny that the person is a patient, discuss any appointment details, reference any treatment or condition, or reveal any information that could identify a health-related interaction — even in response to information the patient disclosed themselves. This is not just best practice; it's federal law.

---

## The Prompt

```
You are a healthcare reputation management specialist. Generate a complete review request and response system.

PRACTICE DETAILS:
- Practice name: [PRACTICE NAME]
- Specialty: [SPECIALTY]
- Primary review platforms to target: [Google / Healthgrades / Zocdoc / Yelp — list in priority order]
- Top 3 things satisfied patients typically say: [e.g., "staff is friendly", "no wait time", "painless experience"]
- Preferred request timing: [e.g., at checkout, 48-hour post-appointment email, end of treatment completion]

Generate the following:

1. REVIEW REQUEST SYSTEM (10 templates — 5 email, 5 SMS)
   Rules for all templates:
   - ZERO PHI — do not reference the appointment, treatment, diagnosis, or condition
   - No implied medical outcome ("now that your treatment is complete")
   - Focus on the relationship and experience, not the medical event
   - One specific platform link placeholder per message
   - Under 160 chars for SMS versions
   
   Email templates: long warm version, short direct version, "we value your feedback" version, referral-focused version, re-request version (30-day follow-up)
   SMS templates: same 5 scenarios in under 160 chars

2. REVIEW RESPONSE TEMPLATES (10 templates)
   
   Positive responses (5):
   - Standard 5-star response (warm, not generic "thanks for your review!")
   - Detailed/story response (patient mentioned specific team member or procedure)
   - New patient first visit
   - Long-term patient
   - Patient who mentioned referring someone
   
   Rules: Thank them by first name if possible. Never confirm they are a patient. Never reference their treatment. Invite future visits. Keep under 150 words.
   
   Negative responses (5):
   - 1–2 star "bad experience" complaint
   - Insurance/billing complaint
   - Wait time complaint
   - Rude staff complaint
   - Factually incorrect review (e.g., "you charged me twice")
   
   Rules: NEVER confirm or deny they are a patient. NEVER discuss specifics publicly. Invite them to call the office. De-escalate. Do not get defensive. Limit to 3 sentences max.

3. 3-TOUCH RE-REQUEST SEQUENCE
   For patients who didn't leave a review after first request
   Touch 1 (Day 7): gentle follow-up
   Touch 2 (Day 21): value framing ("your feedback helps other families")
   Touch 3 (Day 45): final ask, different platform suggestion
   HIPAA rules apply to all three

4. PLATFORM STRATEGY GUIDE
   Based on the specialty provided, recommend:
   - Which platform to prioritize first and why
   - Minimum star threshold to respond to reviews publicly
   - How to handle fake reviews (competitor, disgruntled former employee)
   - Monthly volume target (how many new reviews per month is realistic)

5. HIPAA REVIEW COMPLIANCE CHECKLIST
   10 "NEVER say in a public review response" rules with explanations
   Examples: never confirm appointment, never reference medication, never mention a diagnosis, never say "I'm sorry you felt that way" (implies they have grounds)
```

---

## Example Output (Partial)

**Review Request — Email (Short Direct Version):**
> Subject: Quick favor — would mean the world to us  
> Hi [First Name], Thank you for choosing [Practice Name]. If you had a positive experience, we'd be so grateful if you'd take 60 seconds to leave us a Google review. Your feedback helps other families in [City] find quality care. [GOOGLE REVIEW LINK]  
> Warm regards, The [Practice Name] Team

**Review Request — SMS:**
> "[Practice Name]: Thank you for visiting us! Would you mind leaving us a quick Google review? It means so much to our team: [LINK] Reply STOP to opt out."

**Positive Response (Standard):**
> "Thank you so much, [First Name]! We're so glad you had a great experience. Our entire team works hard to make every visit as comfortable and efficient as possible, and it's truly rewarding to hear. We look forward to seeing you next time!"

**Negative Response (Billing Complaint):**
> "We're sorry to hear about your experience. Billing questions can be complex and we want to make sure they're fully resolved. Please give our office manager a call at [PHONE] — we'd love the opportunity to look into this and make it right."

*(Note: Never say "your account" or "your bill" — don't confirm financial relationship publicly)*
