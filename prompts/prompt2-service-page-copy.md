# Prompt 2 — Service Page Copy

## Purpose
Generate SEO-optimized service/procedure pages for your practice website. These pages attract patients actively searching for your services and convert them into appointment bookings.

## HIPAA + FTC Note
No unsubstantiated health claims. No guaranteed outcomes ("you WILL feel better"). Comparative claims require substantiation. This prompt is designed to produce benefit-focused, patient-reassurance copy without crossing into medical claim territory.

---

## The Prompt

```
You are a healthcare copywriter specializing in medical practice websites. Generate complete service page copy for the following practice.

PRACTICE DETAILS:
- Practice name: [PRACTICE NAME]
- Specialty: [SPECIALTY]
- Location: [City, State]
- Services to write pages for: [LIST 3 SERVICES]
- Ideal patient for each service: [e.g., "adults 30-55 with chronic back pain", "patients anxious about dental work", "women 35+ interested in anti-aging"]
- Unique approach or technology: [e.g., "laser treatment instead of traditional", "sedation available", "same-day crowns with CEREC"]

For EACH service, generate:

1. SEO TITLE (max 60 characters)
   Format: [Service] in [City] | [Practice Name]

2. META DESCRIPTION (max 160 characters)
   Benefit-led, include city name, soft CTA ("Book today")

3. H1 HEADLINE
   Patient benefit-focused, not procedure-focused

4. ABOVE-THE-FOLD PARAGRAPH (50–75 words)
   - Lead with patient concern, not procedure
   - Address the #1 fear or objection for this service
   - Mention the city/neighborhood
   - End with soft CTA

5. "WHAT TO EXPECT" SECTION (numbered steps, 4–6 steps)
   Walk through the experience from "call us" to "leave the office"
   Each step: bold title + 1 sentence description
   Reduce anxiety by making the process predictable

6. "IS THIS RIGHT FOR YOU?" QUALIFYING SECTION
   3–4 bullet points of ideal candidate characteristics
   (Helps pre-qualify patients and reduces no-show rate)

7. FAQ BLOCK (5 questions)
   Answer the top 5 questions patients search before booking this service
   Format: Q: [question]\nA: [answer in 2–3 sentences]
   Include FAQ schema markup in JSON-LD format after the questions

8. CLOSING CTA
   One paragraph + button text
   Create urgency without false scarcity
   Mention new patient special if applicable

HEALTHCARE ADVERTISING RULES TO FOLLOW:
- No "cure", "guaranteed", "best", "most effective" without evidence
- No before/after claims about outcomes
- Patient testimonials in copy require signed HIPAA authorization to be used
- Focus on process and experience, not medical outcomes
```

---

## Example Output (Dental — Teeth Whitening)

**SEO Title:** Teeth Whitening in Henderson, NV | Desert Smile Dental  
**Meta:** Get a brighter smile at Desert Smile Dental in Henderson. Professional whitening that's safe, fast, and supervised by our dental team. Book today.

**H1:** A Brighter Smile — Without the Sensitivity

**Above the Fold:**
> Whether you're prepping for a big event or just ready to feel more confident in your smile, professional whitening at Desert Smile Dental gives you results you can actually see — supervised by our team so it's safe for your teeth. Serving Henderson and the Las Vegas valley. Book your whitening consultation today.

**What to Expect:**
1. **Consultation (15 min)** — We check your enamel health and shade match to make sure whitening is right for you.
2. **Custom Tray Fitting** — We take impressions for trays that fit your exact teeth.
3. **Take-Home Kit** — You leave with your trays and professional-grade gel.
4. **Wear at Home** — Most patients wear trays 1–2 hours daily for 2 weeks.
5. **Check-In Call** — We follow up at the one-week mark to answer questions.
6. **Enjoy Your Results** — Shade guide included to track your progress.

**Is This Right for You?**
- Your teeth are generally healthy with no active cavities or gum disease
- You have staining from coffee, tea, wine, or tobacco
- Over-the-counter strips haven't given you the results you wanted
- You want a supervised process with predictable, consistent results

**FAQ:**
Q: How long do whitening results last?  
A: Results typically last 1–2 years with proper maintenance. Touch-up treatments (using the same trays) are a quick and affordable way to maintain your shade.

*(+ 4 more Q&As and JSON-LD schema block)*

**CTA:** Ready to love your smile? New patients at Desert Smile Dental receive a complimentary shade assessment with their first whitening consultation. [**Book My Free Consultation**]
