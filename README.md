# KD Amazon FBA — VSL Call Funnel
**Client:** Kaden Derouen (@thereal.kd)
**Built:** 2026-02-20
**Framework:** Jeremy Haynes VSL SOP + SabboOS Amazon OS
**Status:** Ready for video recording + embed configuration

---

## What's in This Repo

```
kd-amazon-fba/
├── funnel/
│   ├── index.html          ← VSL landing page (headline + VSL + Typeform)
│   ├── confirmation.html   ← Post-booking page (pixeled — qualified only)
│   └── drop-sell.html      ← Disqualified applicants (NEVER pixeled)
├── scripts/
│   ├── vsl-script.md       ← Full 15–18 min VSL script (7-step JH framework)
│   ├── closing-call-script.md  ← 45–60 min sales call framework
│   └── setter-outreach-script.md  ← Post-booking setter outreach
├── emails/
│   └── all-email-sequences.md  ← All 6 email flows (lead magnet → win-back)
├── sms/
│   └── sms-workflows.md    ← All SMS sequences (booking → no-show → onboarding)
└── ads/
    └── ad-copy.md          ← Meta + YouTube ads (3 angles + retargeting)
```

---

## Funnel Architecture

```
Cold Traffic (Meta / YouTube / IG)
        ↓
[index.html] — Headline → VSL → Typeform Application
        ↓                   ↓
  Qualified               Disqualified
  Applicants              Applicants
        ↓                   ↓
[confirmation.html]    [drop-sell.html]
  ← PIXEL HERE           ← NO PIXEL
        ↓
  Sales Call
        ↓
  Close ($5,997 or $997/mo)
```

---

## Setup Checklist

### Video
- [ ] Record VSL using script in `scripts/vsl-script.md` (15–18 min)
- [ ] Record 2–4 min confirmation video for `confirmation.html`
- [ ] Record 6 breakout videos for `confirmation.html`
- [ ] Upload all videos to Wistia
- [ ] Add chapter markers in Wistia (see timestamps in VSL script)
- [ ] Create video thumbnail for VSL (key moment from video — not a static image)

### Forms
- [ ] Build Typeform application (5–7 questions, conditional logic)
- [ ] Connect Typeform to Calendly for qualified leads
- [ ] Set Typeform redirect for disqualified leads → `drop-sell.html`
- [ ] Embed Typeform in `index.html` (replace the placeholder block)

### Pages
- [ ] Replace Wistia embed placeholder in `index.html`
- [ ] Replace confirmation video embed in `confirmation.html`
- [ ] Replace breakout video embeds in `confirmation.html`
- [ ] Update all `[LINK]` placeholders in HTML files
- [ ] Add real testimonials (name, city, result) in `confirmation.html`
- [ ] Update footer links (Privacy Policy, ToS, Disclaimer pages)
- [ ] Add Meta Pixel base code to `index.html` and `confirmation.html` only
- [ ] Add Lead event to `confirmation.html` ONLY

### CRM (GoHighLevel or ActiveCampaign)
- [ ] Build all email flows from `emails/all-email-sequences.md`
- [ ] Build all SMS workflows from `sms/sms-workflows.md`
- [ ] Set triggers: opt-in → nurture flow, booking → pre-call flow, no-show → recovery flow
- [ ] Configure opt-out handling for SMS (STOP compliance)

### Ads
- [ ] Set up Meta ad account with 3 campaign angles from `ads/ad-copy.md`
- [ ] Set up YouTube pre-roll campaign
- [ ] Set up retargeting audiences (VSL viewers, opt-ins, bookers, email list)
- [ ] Start with $75–150/day testing budget; scale winning angle after 3–5 days

### Sales Infrastructure
- [ ] Stripe account configured with payment links ($5,997 and $997/mo)
- [ ] Enrollment agreement / contract drafted
- [ ] Coaching calendar set up (Calendly linked to coaching schedule)
- [ ] Disposition tracking system in CRM

---

## Key Numbers to Track

| Metric | Target |
|---|---|
| VSL Play Rate | 30%+ |
| Application Completion Rate | 15%+ of VSL viewers |
| Show Rate | 70%+ |
| Close Rate | 25–30% |
| Cost per Booked Call | < $200 |
| Cost per Enrolled Student | < $1,200 |

---

## Price

- **One-time:** $5,997
- **Payment plan:** $997/month × 7 months

---

## Built With

- Jeremy Haynes VSL Framework (`directives/jeremy-haynes-vsl-sop.md`)
- SabboOS Amazon OS (`SabboOS/Amazon_OS.md`)
- SabboOS DOE Agent Framework
