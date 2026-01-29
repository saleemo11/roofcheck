# RoofCheck - Full Business Plan

**Last Updated:** 2026-01-29

## Executive Summary

RoofCheck is a lead generation business that uses AI-powered roof analysis as a hook to capture homeowner leads and sell them to local roofing contractors.

**Business Model:** Consumer lead generation
**Revenue:** Pay-per-lead from roofers ($65-149/lead)
**Moat:** AI tool creates organic traffic, unique lead source vs competitors

---

## The Funnel

### Stage 1: Traffic Acquisition

**Target:** Homeowners 35-65 with homes built before 2005

**Channels:**
| Channel | Strategy | Est. CPA |
|---------|----------|----------|
| Google Ads | "how old is my roof", "roof replacement cost", "roof lifespan" | $15-25 |
| Facebook | Homeowner targeting, 35-65, property owners, older homes | $12-20 |
| TikTok | Before/after roof content, educational content | $8-15 |
| SEO | Blog content: "how long do roofs last", "signs roof needs replacement" | $0 |
| YouTube | "How to tell if your roof needs replacing" educational videos | $5-10 |

**Content Strategy:**
- Create 20+ SEO blog posts targeting roof-related questions
- TikTok/Reels showing dramatic roof damage examples
- YouTube educational content builds trust and organic traffic

### Stage 2: The Hook (Free AI Analysis)

**Value Prop:** "How Old Is Your Roof? Find Out Free in 30 Seconds"

**User Flow:**
1. Upload photo of roof (from ground or existing image)
2. AI analyzes: granule loss, curling, weathering, material type
3. Returns: age estimate, condition rating, recommendation

**Recommendation Categories:**
| Category | Criteria | Show Lead Form? |
|----------|----------|-----------------|
| Good | <10 years, <25% granule loss | No |
| Monitor | 10-15 years, 25-40% granule loss | 50% of time |
| Attention | 15-20 years, 40-55% granule loss | Yes |
| Urgent | >20 years, >55% granule loss | Yes |

### Stage 3: Lead Capture

**Form Fields:**
- Full Name (required)
- ZIP Code (required) - for routing
- Phone Number (required) - primary contact
- Email (optional) - follow-up

**Psychology:**
- Only shows AFTER they've received value (the analysis)
- Positioned as "Get 3 Free Quotes" - they get value, not us
- Trust signals: "No spam", "Your info is secure", "100% free"

### Stage 4: Lead Monetization

**Pricing:**
| Lead Type | Price | Sent To |
|-----------|-------|---------|
| Shared | $65 | Up to 3 roofers |
| Exclusive | $149 | 1 roofer only |

**Unit Economics:**
- Traffic CPA: $15-25
- Lead capture rate: 20-30% (of "Attention" or "Urgent" results)
- Effective CPL: $50-80
- Revenue per lead: $65-149
- **Margin: 30-65%**

**Scale Target:**
- 1,000 leads/month = $65K-149K revenue
- At 40% margin = $26K-60K profit/month

---

## Roofer Acquisition

### Target Customers
- Solo roofers and small roofing companies (1-10 employees)
- Currently buying leads from HomeAdvisor, Angi, Thumbtack
- Doing 5-20+ jobs/month
- Average job value: $10K-20K

### Value Prop for Roofers
1. **Pre-qualified leads** - homeowner already knows their roof needs work
2. **Unique data** - roof age/condition included (no one else has this)
3. **No contracts** - pay per lead, cancel anytime
4. **Exclusive option** - get leads no one else sees

### Acquisition Channels
1. **Cold outreach** - Email/call local roofers in target markets
2. **Facebook groups** - Roofing contractor groups
3. **Trade shows** - Local home shows, roofing conferences
4. **Referrals** - Incentivize existing roofers to refer others

### Roofer Onboarding
1. Fill out form on for-roofers.html
2. Verify business (license, insurance)
3. Set up payment (Stripe)
4. Configure service area (ZIP codes)
5. Choose lead type (shared/exclusive)
6. Start receiving leads

---

## Technical Architecture

### MVP (Week 1-2)
- [x] Consumer landing page with upload functionality
- [x] Simulated AI analysis (realistic random results)
- [x] Lead capture form
- [x] Roofer signup page

### Phase 2 (Week 3-4)
- [ ] Real AI analysis using vision API (GPT-4V or custom model)
- [ ] Lead storage database (Supabase/Firebase)
- [ ] Roofer dashboard
- [ ] Automated lead delivery (SMS + email)
- [ ] Stripe payment integration

### Phase 3 (Month 2+)
- [ ] Roofer CRM features
- [ ] Lead quality feedback loop
- [ ] A/B testing for conversion optimization
- [ ] Mobile app (PWA)
- [ ] API for integrations

---

## Go-To-Market Timeline

### Week 1-2: Build & Soft Launch
- [x] Build consumer-facing tool
- [x] Build roofer signup page
- [ ] Set up analytics (Mixpanel/Amplitude)
- [ ] Manual lead collection (Google Sheets)
- [ ] Recruit 5-10 beta roofers in 1-2 markets

### Week 3-4: Validate
- [ ] Run $500 test budget on Google/Facebook
- [ ] Measure: CPA, conversion rate, lead quality
- [ ] Get feedback from beta roofers
- [ ] Iterate on funnel

### Month 2: Scale
- [ ] Scale to $2-5K/month ad spend
- [ ] Expand to 5+ markets
- [ ] Automate lead delivery
- [ ] Build roofer referral program

### Month 3+: Optimize & Expand
- [ ] Hire VA for roofer support
- [ ] SEO content production (outsource)
- [ ] Expand to 20+ markets
- [ ] Test TikTok/YouTube ads

---

## Competitive Analysis

| Competitor | Model | Lead Price | Our Advantage |
|------------|-------|------------|---------------|
| HomeAdvisor | Shared leads | $20-60 | AI pre-qualification, roof data |
| Angi | Shared leads | $15-50 | Exclusive option, better targeting |
| Thumbtack | Bid-based | Varies | Fixed pricing, pre-qualified |
| Modernize | Exclusive | $100-200 | Lower price, AI hook |

**Our Moat:**
1. AI tool is a unique traffic source (organic + viral)
2. Roof condition data = better qualified leads
3. Lower CAC through content/organic
4. Proprietary data improves over time

---

## Financial Projections

### Year 1 Targets

| Month | Leads | Revenue | Expenses | Profit |
|-------|-------|---------|----------|--------|
| 1 | 50 | $5K | $2K | $3K |
| 3 | 200 | $20K | $8K | $12K |
| 6 | 500 | $50K | $20K | $30K |
| 12 | 1,500 | $150K | $50K | $100K |

**Assumptions:**
- Average lead price: $100 (mix of shared/exclusive)
- Blended CPA: $35/lead
- 40% margin maintained

### Path to $1M ARR
- 833 leads/month @ $100 avg = $83K/month = $1M ARR
- Requires ~$30K/month ad spend at $35 CPA
- Achievable in 12-18 months

---

## Risks & Mitigations

| Risk | Mitigation |
|------|------------|
| AI accuracy questioned | Clear disclaimers, "estimate only" language |
| Roofer churn | Quality leads, responsive support, exclusive option |
| Ad costs increase | Invest in SEO/content early |
| Competition copies | First mover advantage, build brand, data moat |
| Legal liability | Strong disclaimers, no guarantees, "informational only" |

---

## Legal Disclaimers (Required)

**On Consumer Tool:**
> RoofCheck provides AI-generated estimates for informational purposes only. Results are not a substitute for professional inspection. Roof age estimates are approximations based on visible indicators and may vary from actual age. Always consult a licensed roofing professional before making repair or replacement decisions. RoofCheck is not responsible for decisions made based on our analysis.

**On Lead Collection:**
- TCPA compliance (consent before SMS)
- Privacy policy (data usage disclosure)
- Opt-out mechanism

---

## Next Steps

1. **Validate AI Analysis** - Test with real roof images, calibrate results
2. **Recruit Beta Roofers** - 5-10 roofers in 1-2 test markets (Phoenix, Dallas)
3. **Run Traffic Test** - $500 Google/FB test
4. **Iterate** - Based on conversion data and roofer feedback
5. **Scale** - If unit economics hold, scale aggressively

---

## Do We Need a Strategic Agent?

**Current Gap:** The ideabrowser builds have been tactical (build the thing) but missing strategic oversight (market validation, unit economics, GTM sequencing).

**Recommendation:** Yes, create a "Strategy Agent" that:
- Reviews each ideabrowser build for business model fit
- Runs unit economics before building
- Creates GTM sequences
- Prioritizes ideas by ROI potential
- Connects dots between opportunities

This agent should be invoked BEFORE building, not after.

---

*Document created by Awf 🦁*
