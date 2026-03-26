# CoreBridge Website — Vendor Partnerships

Sales page for **corebridge.net** that tells potential vendor partners what working with CoreBridge looks like and gives them a clear way to sign up for a partnership review.

---

## Site Voice & Style Reference

Pulled from corebridge.net homepage, /feature, /about, /pricing, /contact, and /blog:

**Voice:** Direct, confident, outcome-focused. Short declarative sentences. Speaks to "you" / "your." Uses "we" naturally. Honest and transparent ("setup takes real work"). Always ties back to business results.

**Headline style:** Short, punchy, statement-style. Examples from the site:
- "The Most Successful Shops Run on CoreBridge"
- "All-In-One Tools to Manage Your Business"
- "Let's talk about your business."
- "Find The Right Plan For Your Shop"

**CTA style:** "Schedule a Discovery Call" is the primary CTA across the site. Secondary: "Get Started," "Try Now," "See the Results →"

**Page structure pattern:** Hero (headline + 1-2 sentences + CTA) → Content sections (typically 3-column grids or step flows) → Social proof / stats → Testimonials → FAQ → Footer CTA ("Ready to connect your business operations?")

**Stats used across the site:**
- 18 years in business
- 58 countries serviced
- 20,000+ users daily
- 70%+ of major manufacturing franchise networks
- 46% increase in profitability
- 200+ hours saved each month
- 12x faster quoting across teams

**Contact form fields (existing /contact page):** First Name, Last Name, Email, Phone Number, Company Name, Number of Employees, "Anything you'd like us to know?"

---

## Page 1 — Partner With CoreBridge (`/partners`)

### Hero

**Headline:**
> Grow Your Business Inside the Platform That Runs Custom Manufacturing

**Subhead:**
> CoreBridge connects your product to thousands of print shops, sign shops, and custom fabricators who already rely on us every day. Schedule a partnership review and find out if we're a fit.

**CTA Button:** Schedule a Partnership Review

---

### Section: CoreBridge by the Numbers

Same stat-callout style used on the homepage (large number + label):

| Stat | Label |
|------|-------|
| 18 | Years in Business |
| 20,000+ | Users Daily |
| 58 | Countries Serviced |
| 70%+ | Of Major Franchise Networks |

---

### Section: Who We Work With

**Section Header:**
> Built for Partners Who Serve Custom Manufacturers

**Body:**
> If your product helps shops quote, produce, ship, manage, or get paid — there's a place for it inside CoreBridge. We partner with companies across these categories:

**Category cards** (4-column grid, each with a category banner image from `CATERGORY_BANNER_IMAGE_MAP` and inline 80×80 partner icons from `INTEGRATIONS_CARD_IMAGE_MAP_SMALL`):

| Category | Integrations Shown | Description |
|----------|-------------------|-------------|
| Accounting, Finance & Tax | QuickBooks, Xero, CoreBridge Tax, TaxJar, Avalara | Streamline financials, automate bookkeeping, and stay tax-compliant. |
| Payments & Processing | Stripe, Fiserv, Nexio | Accept online payments instantly and securely. |
| Calendars & Scheduling | Google Calendar, Microsoft Calendar | Keep appointments organized and sync across platforms. |
| Email & Productivity | Gmail, Outlook, CoreBridge File Management | Manage messages, files, and documents; collaborate in real time. |
| Customer Engagement | Listen360, LoyaltyLoop | Automate feedback and build stronger customer relationships. |
| Suppliers & Vendor Catalogs | SanMar, S&S Activewear | Track supplies and maintain material availability. |
| Shipping & Logistics | CoreBridge Shipping | Automate fulfillment, real-time rates, labels, and tracking. |

**Closing line:**
> Don't see your category? We're always looking for partners who make shops more efficient. Let's talk.

---

### Section: Why Partner With CoreBridge

**Section Header:**
> What a CoreBridge Partnership Looks Like

3-column grid, each with a short headline and 1-2 sentences (matches the Features page pattern):

**Reach**
> Get your product in front of 20,000+ daily users across print shops, sign shops, apparel decorators, and custom fabricators. CoreBridge is the platform they already use to run their business.

**Ecosystem**
> CoreBridge manages the full workflow — estimates, orders, production, invoicing, and payments. Your integration plugs into a complete system, not a point solution.

**Support**
> You won't build alone. CoreBridge provides a dedicated contact, technical documentation, and hands-on support to get your integration live and performing.

---

### Section: What to Expect

**Section Header:**
> A Straightforward Process From Start to Launch

Step-by-step visual flow (similar to the Import → Quote → Automate section on the homepage):

**Step 1 — Schedule a Review**
> Fill out a short form and our partnerships team will reach out to set up an introductory call. No commitment, no pressure — just a conversation.

**Step 2 — Discovery Call**
> We learn about your product. You learn about CoreBridge. We talk through customer overlap, goals, and whether there's a fit worth pursuing.

**Step 3 — Partnership Agreement**
> If it makes sense for both sides, we work through the details — partnership structure, terms, and a plan for how we'll work together.

**Step 4 — Build & Integrate**
> Your team gets API access, documentation, and a dedicated CoreBridge contact. We work alongside you to make sure the integration meets our shared standards.

**Step 5 — Go Live**
> Your integration launches in the CoreBridge Marketplace and becomes available to our entire customer base. We help promote it and track performance together.

---

### Section: Social Proof / Trust

**Existing partner logos** (horizontal row of 80×80 icons from `end-web/src/assets/Images/integrations/`, wrapping on smaller screens):
> QuickBooks | Xero | Stripe | Fiserv | Gmail | Outlook | Google Calendar | SanMar | Listen360 | LoyaltyLoop | TaxJar | Avalara | CoreBridge Shipping | CoreBridge File Management

**Pull quote (optional — use if a vendor partner testimonial is available):**
> "[Quote from an existing vendor partner about the experience working with CoreBridge]"
>
> — Name, Title, Company

**If no vendor testimonial is available yet, use the existing customer quote that's most relevant:**
> "Having a system that ties estimating, job tracking, and production together has changed how we run the shop. We're faster, more efficient, and a lot less stressed."
>
> — Stewart West, Owner, Sign Weave

---

### Section: CTA (bottom of page)

Matches the repeated footer CTA pattern on every page of the site:

> ### Ready to explore a partnership?
> Schedule a review and find out how your product fits inside the platform that powers custom manufacturing.
>
> **[Schedule a Partnership Review]** → links to `/partners/review`

---

### Section: FAQ

Same expandable FAQ format used on every page. Partner-specific questions:

**How long does the partnership process take?**
> It depends on the complexity of the integration, but most partners go from first call to live integration within a few months. We'll give you a realistic timeline during the discovery call.

**Is there a cost to become a partner?**
> We'll discuss partnership structure and terms during the review process. Our goal is to find a model that works for both sides.

**What kind of technical support do you provide?**
> You get API documentation, a sandbox environment, and a dedicated CoreBridge contact who works with your engineering team throughout the build.

**Do I need to be in the print or sign industry?**
> Not necessarily. If your product serves custom manufacturers — whether that's accounting, payments, scheduling, shipping, or something else — we want to hear about it.

**What if my product only serves a niche within your customer base?**
> That's fine. Some of our most valuable integrations serve specific workflows or industries. If it helps even a segment of our customers work better, it's worth exploring.

---

## Page 2 — Partnership Review Form (`/partners/review`)

### Layout

Matches the existing `/contact` page layout: headline, subhead, clean form, simple confirmation.

---

### Hero

**Headline:**
> Let's Talk About a Partnership

**Subhead:**
> Tell us about your company and what you're looking to do. Our partnerships team will follow up to schedule a review.

### Form Fields

Keep it close to the existing `/contact` form structure. Light, conversational, not an application:

| Field | Type | Required |
|-------|------|----------|
| First Name | Text | Yes |
| Last Name | Text | Yes |
| Email | Email | Yes |
| Phone Number | Phone | No |
| Company Name | Text | Yes |
| Company Website | URL | No |
| How does your product help custom manufacturers? | Textarea | Yes |
| Anything else you'd like us to know? | Textarea | No |

---

### Post-Submit

**Success message** (same style as existing contact form):
> Thank you! Our partnerships team will be in touch within a few business days to schedule your review.

**Confirmation email:**
> Subject: We Got Your Partnership Request
>
> Hi [First Name],
>
> Thanks for reaching out about partnering with CoreBridge. Our team will review your information and follow up within a few business days to schedule a call.
>
> In the meantime, here are a few resources:
> - [About CoreBridge](https://www.corebridge.net/about)
> - [Features Overview](https://www.corebridge.net/feature)
> - [CoreBridge Blog](https://www.corebridge.net/blog)
>
> Talk soon,
> The CoreBridge Partnerships Team

---

## Navigation Placement

The existing site nav is: **Home | Features | Pricing | About | Blog | Contact**

Options for where `/partners` fits:
1. **Top nav link:** Add "Partners" between "About" and "Blog" — makes it discoverable for vendors browsing the site.
2. **Footer link:** Add "Partners" under the "Contact" column in the footer alongside "Contact Sales" and "Contact Support."
3. **Both** — top nav for visibility, footer for completeness.

The footer currently has:
- CoreBridge: Home, Features, Pricing, About
- Contact: Contact Sales, Contact Support, Terms of Service
- Customer: CoreBridge Login, Help-Center

**Recommendation:** Add "Partners" to the footer under **Contact** and optionally to the top nav. The `/contact` page could also include a line like: "Interested in a vendor partnership? [Learn more →](/partners)"

---

## Data Sources — Integration Categories & Logos

The "Who We Work With" categories and partner logos on the partnerships page are sourced from the live codebase, not hand-curated. Here's where they live:

### Categories

**Backend** (`end-integrations`): `SystemIntegrationCategoryType` enum in
`Endor.Integrations.Core\Endor.Integrations.SharedKernel\Entities\SystemIntegrationCategory.cs`

| ID | Backend Category | Website Display Name |
|----|-----------------|---------------------|
| 1 | Accounting | Accounting & Finance |
| 2 | Communication | Email & Productivity |
| 4 | CRM | Customer Engagement |
| 8 | Calendar | Calendars & Scheduling |
| 9 | Vendor | Suppliers & Vendor Catalogs |
| 10 | Payment | Payments & Processing |
| 11 | Shipping | Shipping & Logistics |
| 12 | Tax | Tax |
| 3 | FileManagement | *(internal — not shown)* |
| 5 | SystemMonitoring | *(internal — not shown)* |
| 6 | IT | *(internal — not shown)* |
| 7 | Free | *(tier, not a category)* |

**Frontend** (`end-web`): `IntegrationCategoryType` enum in `src/app/models/integration.ts` mirrors the same IDs. Category icon mapping in `src/evo/pages/settings/pages/integrations-marketplace/integrations-marketplace.component.ts` uses Font Awesome:

| Category | FA Icon |
|----------|---------|
| Finance | `fa-chart-line` |
| Payment | `fa-credit-card` |
| Calendar | `fa-calendar-days` |
| Communication | `fa-comments` |
| CustomerEngagement | `fa-users-gear` |
| Suppliers | `fa-truck-fast` |
| Shipping | `fa-truck-fast` |
| Tax | `fa-chart-line` |
| FileManagement | `fa-folder-open` |

### Logos & Images

All integration images live in `end-web/src/assets/Images/integrations/`. Mappings are defined in
`src/evo/pages/settings/pages/integrations-marketplace/integrations-marketplace.interface.ts`:

| Map | Size | Example |
|-----|------|---------|
| `INTEGRATIONS_CARD_IMAGE_MAP` | 3452×280 | `quickbooks_online_image_3452x280.png` |
| `INTEGRATIONS_CARD_IMAGE_MAP_BIG` | 592×380 | `quickbooks_online_image_592x380.png` |
| `INTEGRATIONS_CARD_IMAGE_MAP_SMALL` | 80×80 | `quickbooks_online_ico_80x80.png` |
| `INTEGRATION_DETAIL_BANNER_IMAGE_MAP` | 2000×750 | `quickbooks.jpg`, `stripe_banner_2000x750.jpg` |
| `CATERGORY_BANNER_IMAGE_MAP` | varies | `Accounting.png`, `Payment.png`, `Vendor_805079335.jpeg` |

**Integration IDs** (`IntegrationID` enum in `src/app/services/integrations/integrations.interfaces.ts`):

| ID | Integration |
|----|------------|
| 3 | QBO Summary Sync |
| 4 | Xero Summary Sync |
| 5 | CoreBridge Tax |
| 6 | TaxJar |
| 7 | Avalara |
| 8 | Gmail |
| 9 | Outlook |
| 10 | Google Calendar |
| 11 | Microsoft Calendar |
| 12 | Alphabroder |
| 13 | SanMar |
| 14 | S&S Activewear |
| 15 | Xero Detail Sync |
| 16 | Listen360 |
| 17 | CoreBridge Shipping |
| 18 | Nexio |
| 19 | Fiserv (AUS) |
| 20 | Fiserv (US) |
| 21 | Stripe |
| 22 | QBO Detail Sync |
| 23 | CoreBridge File Management |
| 24 | LoyaltyLoop |

### How the Website Page Maps to the Codebase

The `partners.html` example now uses **real images copied from `end-web/src/assets/Images/integrations/`** into `Web-Partnerships/assets/integrations/`. This includes:

- **Category banner images** from `CATERGORY_BANNER_IMAGE_MAP` (e.g., `Accounting.png`, `Payment.png`, `Vendor_805079335.jpeg`)
- **80×80 integration icons** from `INTEGRATIONS_CARD_IMAGE_MAP_SMALL` for both the logo bar and inline category display
- All 8 integration categories are now represented (including Shipping and Tax)

When this moves to production:
1. **Categories** should pull from the `SystemIntegrationCategoryType` enum or its API (`GET /api/system/integration/category`) so the page stays in sync as new categories are added.
2. **Logos** can be uploaded to Webflow from the local `assets/integrations/` folder, or served from the app's asset path.
3. **Category banners** and **80×80 icons** are already included in the example and ready for Webflow upload.

---

## Decisions Made

| Question | Answer |
|----------|--------|
| Nav placement | Both top nav and footer |
| Response SLA | No specific commitment — "Our partnerships team will be in touch" |
| Vendor testimonial | Skip for now |
| Partner logos | Real 80×80 icons from codebase — 14 integrations shown in logo bar |
| Form location | Embedded at the bottom of the /partners page (single page) |
| Format | Standalone HTML example — see `partners.html` |

## Open Questions

1. **Form routing** — Where do partnership review submissions go? Shared inbox, CRM, or the internal vendor queue from POC-Vendor?
2. ~~**Partner logos**~~ — Resolved. Using real 80×80 icons from `end-web/src/assets/Images/integrations/`.
3. **Design hand-off** — Does the site team build from the HTML example, or do they need a separate design file?

---

## Next Steps

- [ ] Review `partners.html` example with stakeholders
- [ ] Confirm form routing workflow
- [x] Replace placeholder logos with real 80×80 icons from codebase
- [ ] Finalize copy and hand off to site team for production build
