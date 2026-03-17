# Product Marketing Context

*Last updated: March 16, 2026*

## Product Overview

**One-liners:**
- **Investor pitch:** MyDola transforms traditional lending circles into a digital financial network for diaspora communities.
- **User-facing:** MyDola makes lending circles simple, secure, and built for your community.
- **Media / PR:** MyDola is bringing centuries-old lending circles into the digital age.

**What it does:** MyDola is a community-powered finance app that helps immigrants and diaspora families manage money with purpose. The hero feature, **WealthLoop**, is MyDola's version of the Rotating Lending Circle — a digitalized, trust-scored, escrow-protected system where community members contribute a fixed amount on a recurring schedule and each member receives a lump-sum payout in rotation. Beyond WealthLoop, MyDola offers free peer-to-peer transfers, linked wallets, global remittances via MoneyGram, ACH and wire transfers, and a Visa card for everyday use. The platform is designed with a Trust Score that grows as you contribute on time, get vouched for, and invite others — unlocking access to public Loops and future credit products.

**Product category:** Community finance / Digital Rotating Lending Circle platform (sits at the intersection of neobanking, community lending, and cross-border payments — a category being created, not joined)

**Product type:** Mobile-first fintech app (Flutter) with blockchain infrastructure (Stellar + Bridge for ACH-to-USDC conversion), delivered as a consumer product with B2B2C distribution through community organizers

**Business model:**
- **Loop Participation Fee:** One-time fee per person, per Loop. A portion of this fee goes to the Organizer as compensation for managing the circle
- **Wallet & Transaction Fees:** Fees on wallet activity and transactions within the platform (MoneyGram Fintech partnership — no FX margin; fee structure to be refined with marketing skills analysis)
- **Card Interchange & Transaction Fees:** Revenue from Visa card spend and associated transaction processing
- **Future — Premium Subscriptions:** Financial Insights and Credit Building tools as a paid tier
- **Future — Credit Products:** Micro-lending (modeled after Cash App's "Borrow" feature), underwritten by Loop participation data and Trust Score history

## Target Audience

**Target communities:**
- Immigrant and diaspora families in the U.S. who already practice informal lending circles
- Initial geographic focus: South Florida (Miami-Dade, Broward, Palm Beach)
- Priority diaspora groups by local population density:
  - Haitian (~250–300K in South Florida) — practice "Sol" / "Min"
  - Colombian (~170–200K) — practice "Natillera" / "Cadena"
  - Venezuelan (~120–150K) — practice "Cadena" / "Bolso" / "San"
  - Jamaican / Caribbean (~80–100K) — practice "Pardna" / "Sou Sou"
  - West African (Nigerian, Ghanaian) — practice "Esusu" / "Ajo" / "Susu"
- Secondary markets: Northeast U.S. (NYC metro), Atlanta, Houston, DMV
- **Key professional community:** Nurses — highly organized, stable income, strong community networks, and active lending circle participants across multiple diaspora groups

**Decision-makers:**
- Community organizers (the person who runs the lending circle in their community — typically a trusted elder, church leader, community association figure, respected family matriarch, or professional community leader such as a nurse supervisor)
- These organizers are the primary acquisition target — each brings 15–30 participants

**Primary use case:** Digitalize the lending circle the organizer is already running offline — eliminating cash handling risk, manual tracking, geographic constraints, and default ambiguity

**Jobs to be done:**
- "I need to run my lending circle without chasing people for cash every month"
- "I want to save and lend with my community but I moved to a different city/state"
- "I need to send my payout home to family without paying Western Union fees"
- "I want proof that I'm financially reliable but I don't have a credit score"
- "I can handle more than 3 Loops at a time thanks to the platform's structure" — unlike the traditional way, organizers can create and manage more Loops without personally participating in each one, since the platform handles tracking, reminders, and escrow

**Use cases:**
- Haitian church group running a monthly Sol of 15 members, $200/person — organizer tracks everything in a notebook today
- Young professional from Nigeria who wants to participate in Esusu but doesn't trust doing it with strangers and no accountability
- Organizer who lost money when a participant defaulted and disappeared — wants escrow protection
- Immigrant with no credit history who needs proof of financial discipline for a future loan or apartment application
- Nursing community in South Florida running a Pardna of 20 members — organizer manages multiple circles simultaneously and needs digital tools to keep track without burnout
- Organizer managing 4 Loops simultaneously — impossible offline, but the platform's automated tracking and escrow makes multi-Loop management viable

## Personas

| Persona | Cares about | Challenge | Value we promise |
|---------|-------------|-----------|------------------|
| **The Organizer** (primary) | Reputation, community trust, not losing money, efficiency, scaling to more Loops | Manually tracking contributions, chasing late payments, handling cash, dealing with defaults — all of which risk their personal reputation. Can't manage more than 2–3 circles offline without burnout | "Run your circles digitally. No more cash. No more chasing. Your reputation is protected by the platform. And you can manage as many Loops as your community needs." |
| **The Participant** | Receiving their payout on time, lending and saving consistently, sending money home | No accountability if someone defaults, geographic distance from the group, high remittance fees when sending payout abroad | "Lend and save with your community from anywhere. Get your payout on time, every time. Send it home for less." |
| **The Trust-Builder** | Building financial credibility in the U.S., accessing future credit | No credit history, thin file, traditional banks won't look at their lending circle participation as proof of reliability | "Every on-time contribution builds your Trust Score. Turn community participation into financial credibility." |

## Problems & Pain Points

**Core problem:** Over 1.4 billion people worldwide participate in informal lending and savings circles, but these systems break when communities migrate. Geography, cash handling, manual tracking, and zero accountability for defaults make them fragile — exactly when diaspora families need them most.

**Why current solutions fall short:**
- **Doing it offline (status quo):** Cash-based, requires physical presence, no default protection, organizer bears all risk personally, no record of participation for credit purposes, organizer can't scale beyond 2–3 circles without burnout
- **Traditional banks:** Don't understand or serve community lending models. Require credit history that immigrants often don't have. Products designed for individuals, not groups. Cultural mismatch in everything from language to UX to trust assumptions
- **Existing fintech apps (Venmo, Zelle, Cash App):** Solve P2P payments but not group lending structure. No escrow, no payout scheduling, no trust scoring, no ROSCA-specific logic. Using them for lending circles is a workaround, not a solution
- **SafeCircle Capital (US):** U.S.-based digital ROSCA platform using Dwolla for ACH, organizer/admin model, tiered pricing (Free/Standard/Premium). Focuses on "group savings" framing. Currently live with app on iOS and Android. Falls short because: savings-only framing (not lending), no integrated remittance, no trust scoring system, no multi-community/multi-cultural positioning, no blockchain escrow, no credit-building path
- **Mission Asset Fund / MAF (US):** Nonprofit lending circles with 0% interest credit-building loans, reports to all three credit bureaus, 100+ nonprofit partners, 10K+ clients served. Average credit score increase of 168 points. Falls short because: nonprofit model (not scalable as a tech platform), requires nonprofit intermediary, no mobile-first consumer product, no remittance integration, no organizer compensation, circles limited to 6–12 people / $300–$2,400 range
- **MoneyFellows (Egypt, $37M raised, 8.5M users):** Proved the digital ROSCA model works at scale and reached profitability. Falls short because: Egyptian domestic market only, no U.S. presence, no cross-border remittance, no multi-community platform
- **Bloom Money (UK, £1.5M raised):** Targeting UK immigrant communities. Falls short because: UK-only, very early stage, no U.S. market entry

**What it costs them:**
- Organizers lose personal money and reputation when participants default (no escrow protection)
- Participants miss payouts when organizers mismanage or groups dissolve
- Families pay 5–12% in remittance fees to send payout money home through legacy corridors
- Immigrants with years of reliable lending circle participation have zero credit history to show for it
- Communities fragment as members move — circles that worked in Port-au-Prince or Lagos can't survive across Miami, NYC, and Montreal
- Organizers burn out managing 2–3 circles manually and can't serve more community demand

**Emotional tension:**
- Fear of betrayal by someone in the circle (default anxiety)
- Shame when an organizer can't collect from a participant (reputation risk)
- Frustration at being financially invisible despite years of disciplined participation
- Isolation from community financial practices after immigration
- Distrust of institutions that have never served people who look like them

## Competitive Landscape

### U.S.-Based (Primary Watch)

**Direct:** SafeCircle Capital — U.S.-based digital ROSCA platform. Organizer/admin-first model with tiered pricing. Live app on iOS/Android. Uses Dwolla for ACH. Positioned as "group savings." Falls short because: no trust scoring, no integrated remittance, no blockchain escrow, no credit-building path, savings-only framing, no multi-cultural/multi-community positioning.

**Direct (Nonprofit):** Mission Asset Fund (MAF) — San Francisco-based nonprofit running Lending Circles since 2008. Reports to all three credit bureaus. 100+ nonprofit partners, 10K+ clients, 168-point average credit score increase. 60% women, 90% people of color, 60% immigrants. Actively expanding into Florida. Falls short because: nonprofit model requiring intermediary organizations, not a consumer tech product, no mobile-first experience, no remittance integration, circles limited to 6–12 people and $300–$2,400 range, no organizer compensation mechanism.

### International (Market Validation)

**MoneyFellows (Egypt)** — 8.5M users, $37M raised, profitable. Proved digital ROSCA works at massive scale. Egyptian domestic market only. Important as proof-of-concept and investor reference.

**Bloom Money (UK)** — £1.5M raised. Targeting UK immigrant communities. Very early stage. UK-only.

### Alternative Solutions

**Secondary:** Venmo / Zelle / Cash App — used as workarounds for collecting lending circle contributions, but provide zero ROSCA-specific functionality. Solve payments, not community lending structure.

**Secondary:** Traditional banks / credit unions — occasionally offer "savings clubs" but these are individual products with no group mechanics, no cultural understanding, and no diaspora-specific features.

**Indirect:** Keeping it offline — the notebook-and-cash approach that has worked for generations. Falls short when communities are geographically dispersed, when trust breaks down without accountability mechanisms, and when participants want their lending discipline to count toward credit access.

## Differentiation

**Key differentiators:**
- **Trust Score:** Proprietary reputation system that grows as participants contribute on time, get vouched for by organizers, and complete Loops — creating a portable, verifiable financial identity for people with thin credit files. No other U.S. platform offers this.
- **Multi-signature escrow on Stellar:** Contributions held in blockchain-based escrow with multi-sig release — neither MyDola nor any single party can unilaterally access funds. Full crypto abstraction for users (they never see blockchain). SafeCircle uses basic ACH via Dwolla — no escrow protection.
- **Integrated remittance via MoneyGram:** Payout goes directly to family abroad through MoneyGram's 350K+ cash-out locations across 200+ countries. No separate remittance step. No other digital ROSCA platform in the U.S. offers integrated cross-border payout.
- **Multi-community, multi-cultural platform:** Designed from day one to serve Haitian, Caribbean, West African, Colombian, Venezuelan, South Asian, Filipino, and other diaspora groups — not a single-country or single-culture product
- **Organizer compensation:** Part of the Loop Participation Fee goes directly to the organizer. This formalizes the organizer's role and creates economic incentive for growth. MAF doesn't compensate organizers; SafeCircle's model is unclear.
- **Credit scaffolding path:** Loop participation data + Trust Score designed to eventually underwrite credit products (micro-lending), turning community lending behavior into formal financial access
- **Multi-Loop management:** Platform enables organizers to create and manage more than 3 Loops simultaneously without personally participating in each — impossible offline

**How we do it differently:** MyDola starts with the organizer (B2B2C), not the individual consumer. Every organizer brings their existing circle of 15–30 people. The platform digitizes what they're already doing — it doesn't ask them to adopt a new behavior. The trust layer is community-native (vouching, reputation, group accountability) rather than institution-imposed (credit scores, income verification).

**Why that's better:** Acquisition cost approaches zero when each organizer brings a pre-formed group. Retention is structurally embedded — leaving a Loop mid-cycle has social and financial consequences. Network effects compound at the community level, not just the individual level.

**Why customers choose us:** "Because you're the only app that actually understands how our circle works. You didn't try to make us use a banking app. You made our circle better."

## Objections & Responses

| Objection | Response |
|-----------|----------|
| "I don't trust putting my circle money in an app" | Your money is held in multi-signature escrow — not even MyDola can move it without the group's approval. It's actually safer than handing cash to one person. You can see every contribution in real time. |
| "My circle works fine the way it is" | It works until someone moves, or someone defaults, or you can't collect cash in person. MyDola doesn't change how your circle works — it makes it work even when life gets complicated. |
| "I don't want my financial information tracked / reported" | MyDola doesn't report to credit bureaus without your explicit consent. Your Trust Score is yours — it helps you access better features on MyDola and, only if you choose, can be used to demonstrate financial reliability. |
| "What happens if someone in my circle doesn't pay?" | The platform flags missed contributions immediately, sends automated reminders, and your escrow structure means payouts are protected. The organizer has tools to manage defaults before they become crises. |
| "Is this legal?" | Lending circles are legal in the U.S. MyDola operates within federal and state financial regulations, partnering with licensed banking and payment infrastructure. We're building the compliant bridge between your community's financial traditions and the regulated financial system. |

**Anti-persona:**
- People who want individual savings/investment products (use a bank or Acorns)
- People who don't participate in any form of group lending or savings (no existing behavior to digitalize)
- People looking for high-yield investment returns (Loops are lending and savings vehicles, not investments)
- Crypto enthusiasts who want to interact with blockchain directly (MyDola fully abstracts crypto — if you want to trade tokens, use Coinbase)

## Switching Dynamics

**Push (away from current solution):**
- Lost money when a participant defaulted and disappeared
- Circle fell apart after members moved to different cities
- Organizer burned out tracking contributions in a notebook
- Embarrassment of chasing friends/family for late payments
- Paying 8–12% to send payout to family back home
- Years of disciplined lending circle participation with nothing to show to a bank or landlord

**Pull (toward MyDola):**
- Digital tracking means no more manual record-keeping
- Members can participate from anywhere — the circle survives migration
- Escrow protection means the organizer's reputation (and money) is safe
- Trust Score turns invisible financial behavior into visible credibility
- Integrated remittance saves money on sending payouts home
- Organizer gets compensated through the Loop Participation Fee
- Multi-Loop management lets organizers serve more community demand
- App designed by and for diaspora communities — it feels familiar, not foreign

**Habit (keeps them stuck):**
- "We've always done it this way" — deep cultural inertia around in-person, cash-based circles
- Comfort with the organizer personally holding the money (paradoxically, this is both the trust mechanism and the risk)
- Distrust of technology / apps with money, especially in communities burned by financial institutions
- Social ritual of gathering in person to contribute (the circle is also a social event)

**Anxiety (about switching):**
- "What if the app goes down and I lose my money?"
- "What if the government tracks my money through this?"
- "I don't want to learn a new app — I barely use the ones I have"
- "What if my circle members don't want to switch?"
- "Will this change the dynamic of our group?"

## Customer Language

**How they describe the problem:**
- "I'm tired of chasing people for their money every month"
- "Someone ran off with the pot and now nobody trusts anyone"
- "My sister moved to New York and now she can't be in the circle anymore"
- "I've been doing this for 20 years and the bank still treats me like I don't exist"
- "Western Union is eating my payout"
- "I keep everything in a notebook and if I lose it, the whole circle is in trouble"
- "I can't take on another circle — I'm already drowning managing three"

**How they describe us:**
- "It's like our Sol but on the phone"
- "Finally, someone made an app for what we already do"
- "It's like Venmo but it actually understands how our circle works"
- "It keeps everyone honest without me having to be the bad guy"

**Words to use:**
- Lending circle, lending and savings circle (lending first, always)
- Circle, Loop (not "fund" or "pool")
- Community, family, group (not "users" or "customers")
- Organizer (not "admin" or "manager")
- Contribution (not "payment" or "deposit")
- Payout (not "withdrawal" or "distribution")
- Trust Score (not "credit score" or "rating")
- Send money home (not "remit" or "transfer funds")
- Lend and save together (not "pool resources")
- Your circle, your way (not "our platform")

**Words to avoid:**
- Blockchain, crypto, Stellar, USDC (full abstraction — users never need to know)
- ROSCA (academic term — no community uses this word for their own circle)
- Savings circle / savings alone without "lending" — always say "lending" or "lending and savings." Never "savings" alone or before "lending"
- Disrupt, revolutionize (don't position against their traditions — position as an upgrade)
- Unbanked, underbanked (deficit framing — these communities are financially sophisticated, they just operate outside formal institutions)
- Investment, returns, yield (Loops are not investment products)
- Algorithm (Trust Score is built on community behavior, not opaque math)

**Glossary:**

### Core MyDola Terms

| Term | Meaning |
|------|---------|
| Loop | MyDola's term for a digitalized lending circle — the core unit of the WealthLoop feature |
| WealthLoop | The branded product name for MyDola's digital rotating lending circle feature — the hero feature of the platform |
| Trust Score | Reputation metric built from on-time contributions, vouches from organizers, completed Loops, and community participation |
| Organizer | The community leader who creates and manages a Loop — MyDola's primary acquisition target. Each brings 15–30 participants |
| Contribution | A member's periodic payment into the Loop |
| Payout | The lump-sum a member receives when it's their turn in the rotation |
| Loop Participation Fee | One-time fee per person, per Loop — a portion goes to the Organizer as compensation |
| Escrow | Multi-signature blockchain-based holding of contributions until payout (invisible to users) |
| Bridge | ACH-to-USDC conversion rail (invisible to users) |
| MoneyGram Access | Last-mile payout network for cross-border remittance (350K+ locations globally) |

### ROSCA Terminology by Community

#### West Africa

| Term | Alt. Spellings | Culture / Ethnicity | Country | Diaspora Hubs (US) | Est. South FL Size | Typical Group Size |
|------|---------------|--------------------|---------|--------------------|-------------------|-------------------|
| Esusu | Osusu, Enusu | Yoruba / Nigerian | Nigeria | Houston, NYC (Bronx), DMV, Atlanta | ~15–20K | 10–20 |
| Ajo | Àjọ | Yoruba / Nigerian | Nigeria | Houston, NYC, DMV, Chicago | ~15–20K | 5–15 |
| Susu | Sou-Sou, Asusu | Ghanaian / Akan | Ghana | NYC (Bronx), DMV, NJ, Columbus OH | ~5–10K | 5–20 |
| Tontine | Tonton | Francophone West African | Senegal, Mali, Ivory Coast, Cameroon | NYC (Harlem), DMV, Atlanta | ~10–15K | 10–30 |
| Njangi | Jangi, Ujangi, Djanggi | Cameroonian | Cameroon | DMV, Houston, Dallas | ~5–8K | 10–25 |
| Osusu | Compin | Gambian / Sierra Leonean | Gambia, Sierra Leone | NYC, DMV, Atlanta | ~2–5K | 5–15 |
| Stokvel | Stockfair | South African | South Africa | NYC, DMV, Atlanta | ~2–5K | 10–30 |

#### East Africa

| Term | Alt. Spellings | Culture / Ethnicity | Country | Diaspora Hubs (US) | Est. South FL Size | Typical Group Size |
|------|---------------|--------------------|---------|--------------------|-------------------|-------------------|
| Equb | Ekub, Ikub, እቁብ | Ethiopian / Eritrean | Ethiopia, Eritrea | DMV (DC/MD/VA), Seattle, Minneapolis, Dallas | ~5–10K | 10–20 |
| Chama | Chamaa | Kenyan / East African | Kenya | Dallas, Houston, DMV, Minneapolis | ~3–5K | 5–30 |
| Hagbad | Ayuuto, Shaloongo | Somali | Somalia | Minneapolis, Columbus OH, Seattle, San Diego | ~2–5K | 5–20 |
| Upato | Upatu | Tanzanian / Zambian | Tanzania, Zambia | DMV, Dallas | ~1–3K | 5–15 |

#### Caribbean

| Term | Alt. Spellings | Culture / Ethnicity | Country | Diaspora Hubs (US) | Est. South FL Size | Typical Group Size |
|------|---------------|--------------------|---------|--------------------|-------------------|-------------------|
| Sol | Sòl | Haitian | Haiti | South FL (Miami, Ft Lauderdale), NYC, Boston, NJ | ~250–300K | 5–15 |
| Min | — | Haitian | Haiti | South FL, NYC, Boston | ~250–300K | 5–12 |
| Pardna | Pardner, Partnerhand, Partner | Jamaican | Jamaica | NYC (Brooklyn), South FL, Hartford CT, Atlanta | ~80–100K | 8–20 |
| Sou-Sou | Susu, Su-Su | Trinidadian / Caribbean | Trinidad & Tobago | NYC, South FL, DMV | ~15–25K | 5–15 |
| Box Hand | Box | Eastern Caribbean | Barbados, St. Lucia, Dominica | NYC (Brooklyn), Hartford CT, Boston | ~10–15K | 5–12 |

#### Latin America

| Term | Alt. Spellings | Culture / Ethnicity | Country | Diaspora Hubs (US) | Est. South FL Size | Typical Group Size |
|------|---------------|--------------------|---------|--------------------|-------------------|-------------------|
| Natillera | Cadena | Colombian | Colombia | South FL (Miami, Doral, Weston), NYC (Queens, Jackson Heights), NJ, Houston | ~170–200K | 5–20 |
| Cadena | Bolso, San | Venezuelan | Venezuela | South FL (Miami, Doral, Weston), Houston, NYC | ~120–150K | 5–15 |
| Tanda | Cundina | Mexican | Mexico | LA, Houston, Chicago, Dallas, Phoenix, Miami | ~40–60K | 8–20 |
| Consórcio | Pandeiro | Brazilian | Brazil | South FL, NYC, Boston, Newark NJ | ~40–60K | 10–50+ |
| Junta | Pandero, Panderos | Peruvian | Peru | NJ (Paterson), Miami, LA, NYC | ~30–40K | 5–15 |
| Cuchubál | — | Guatemalan / Mayan | Guatemala | LA, Houston, NYC, DMV | ~20–30K | 5–15 |
| Pasanaku | — | Bolivian | Bolivia | DC, Arlington VA, NYC | ~3–5K | 5–15 |

#### South Asia

| Term | Alt. Spellings | Culture / Ethnicity | Country | Diaspora Hubs (US) | Est. South FL Size | Typical Group Size |
|------|---------------|--------------------|---------|--------------------|-------------------|-------------------|
| Committee | Kameti, BC, Komiti | Pakistani / South Asian | Pakistan | NYC, Houston, Chicago, DMV, NJ | ~8–12K | 10–20 |
| Chit Fund | Chitty | Indian (South) | India | NYC, NJ, Bay Area, Chicago, Houston | ~25–35K | 10–40 |
| Visi | વિસિ | Gujarati / Indian | India (Gujarat) | NJ (Edison), Bay Area, Chicago | ~8–12K | 10–20 |
| Dhukuti | — | Nepali | Nepal | NYC (Queens, Brooklyn), Dallas, DMV | ~2–3K | 5–15 |

#### Southeast Asia

| Term | Alt. Spellings | Culture / Ethnicity | Country | Diaspora Hubs (US) | Est. South FL Size | Typical Group Size |
|------|---------------|--------------------|---------|--------------------|-------------------|-------------------|
| Paluwagan | — | Filipino | Philippines | LA, Bay Area, NYC, Chicago, Las Vegas, Honolulu | ~15–20K | 5–20 |
| Arisan | — | Indonesian | Indonesia | LA, Bay Area, NYC | ~2–3K | 10–30 |
| Hui | Hụi, Hội | Vietnamese | Vietnam | LA (Westminster/Orange County), Houston, Bay Area, DMV | ~10–15K | 10–30 |

#### East Asia

| Term | Alt. Spellings | Culture / Ethnicity | Country | Diaspora Hubs (US) | Est. South FL Size | Typical Group Size |
|------|---------------|--------------------|---------|--------------------|-------------------|-------------------|
| Hui | 會, Biaohui | Chinese | China, Taiwan | NYC, Bay Area, LA, Boston | ~10–15K | 10–30 |
| Gye | Kye, 계 | Korean | South Korea | LA (Koreatown), NYC, NJ, DMV | ~5–8K | 10–20 |
| Tanomoshi | Mujin, 頼母子講 | Japanese | Japan | LA, NYC, Honolulu | ~2–3K | 5–15 |

#### MENA

| Term | Alt. Spellings | Culture / Ethnicity | Country | Diaspora Hubs (US) | Est. South FL Size | Typical Group Size |
|------|---------------|--------------------|---------|--------------------|-------------------|-------------------|
| Gameya | Gam'eya, جمعية, Jam'iya | Egyptian / Arab | Egypt | NYC (Queens, Brooklyn), NJ, LA | ~5–8K | 5–20 |
| Dart | دارت | Moroccan | Morocco | NYC, DMV | ~2–3K | 5–15 |
| Gün | — | Turkish | Turkey | NYC, NJ, LA | ~2–3K | 5–15 |

## Brand Voice

**Tone:** Warm, direct, community-rooted. Speaks like a trusted neighbor who also happens to understand technology. Never corporate. Never condescending. Never "Silicon Valley explains your culture to you." Confident but humble — we didn't invent lending circles, we're honored to help them thrive.

**Style:** Conversational, culturally aware, bilingual-ready (English primary, Spanish and Haitian Creole in-product). Short sentences. Active voice. Concrete over abstract. Stories over statistics (though we use both). Code-switching fluency — can speak to a Haitian church organizer in Little Haiti and a VC partner on Sand Hill Road in the same day.

**Personality:** Trustworthy, community-first, practical, culturally fluent, quietly innovative (the technology is sophisticated but the experience is simple)

## Proof Points

**Metrics:**
- 1.4B+ people worldwide participate in informal lending and savings circles (academic research)
- $650B+ in annual global remittance flows (World Bank)
- $500B+ estimated annual ROSCA volume globally (Interledger Foundation / academic estimates)
- MoneyFellows proved the model: 8.5M users, profitable, $37M raised in Egypt alone
- MAF proved credit-building works: 168-point average credit score increase through Lending Circles
- South Florida diaspora TAM: 500K+ potential participants across Haitian, Colombian, Venezuelan, Caribbean, and West African communities
- Average traditional remittance fee: 5–12% (MyDola targets significantly lower via MoneyGram / Stellar rails)

**Customers:** Pre-launch — building waitlist through community organizer outreach in South Florida

**Testimonials:** Pre-launch — collecting voice-of-customer through community research and organizer interviews

**Value themes:**

| Theme | Proof |
|-------|-------|
| Community trust digitalized | Multi-sig escrow, Trust Score, organizer compensation, default management tools |
| Lend and save together from anywhere | Mobile-first, no geographic constraint on circle membership |
| Your lending circle, upgraded | Same cultural practice, better tools — not a new behavior |
| Financial visibility | Trust Score turns informal lending discipline into verifiable credibility |
| Send money home for less | Integrated MoneyGram remittance at fraction of legacy corridor cost |
| Organizers empowered | Compensation through Loop Participation Fee, multi-Loop management tools |

## Goals

**Business goal:** Launch WealthLoop in South Florida with 50 active organizers running Loops within 6 months of launch, each bringing 15–30 participants (750–1,500 active users)

**Conversion action:** Organizer waitlist signup → first Loop created → first full Loop cycle completed

**Current metrics:** Pre-launch. Waitlist building. Key metrics to track post-launch:
- Organizer activation rate (signed up → created first Loop)
- Participant fill rate (Loop created → all slots filled)
- Contribution on-time rate (scheduled → paid on time)
- Loop completion rate (started → all members received payout)
- Viral coefficient (each organizer's network effect — participants who become organizers)
- Remittance attach rate (payouts sent cross-border via integrated MoneyGram)
- Trust Score progression (new user → established scorer)
- Multi-Loop rate (organizers managing 2+ Loops simultaneously)

---

## MyDola-Specific Context for Marketing Skills

*This section extends the standard product-marketing-context template with context unique to MyDola's market, distribution model, and regulatory position. Other marketing skills should reference this for diaspora fintech-specific framing.*

### Distribution Model: Organizer-Led (B2B2C)

MyDola does NOT acquire individual users through paid ads or app store optimization. The primary acquisition motion is:

1. **Identify and recruit community organizers** who already run lending circles offline
2. **Onboard the organizer** — they create a Loop on MyDola
3. **Organizer invites their existing circle members** — 15–30 participants per organizer
4. **Participants experience the product** and some become organizers themselves (viral loop)

This means:
- All top-of-funnel marketing targets organizers, not participants
- The "sale" is convincing an organizer to move their circle digital — not convincing an individual to download an app
- Community events, church partnerships, community association partnerships, professional networks (especially nursing communities), and word-of-mouth are the primary channels — not Facebook ads
- The waitlist is segmented: organizer waitlist (primary) and participant waitlist (secondary)
- Content marketing should speak to organizer pain points (tracking, defaults, cash handling, reputation risk, burnout from managing multiple circles) not generic savings tips

### Regulatory Context

- Lending circles exist in a federal regulatory gray zone in the U.S. — no agency-specific guidance
- Primary compliance risks: FinCEN money transmitter classification, state money transmitter license (MTL) requirements
- MyDola's strategy: bank partnership / BaaS structure as the compliance path
- Marketing must NEVER position Loops as investment products or interest-bearing accounts
- Marketing must NEVER make claims about credit score improvement from Trust Score alone (Trust Score is internal to MyDola unless explicitly opted in to future credit products)
- Marketing CAN use the word "lending" — this is the correct framing for what circles do. Always say "lending circle" or "lending and savings circle." Never "savings circle" alone.
- Marketing should frame compliance as a strength: "We're building the bridge between your community's financial traditions and the regulated financial system"

### Cultural Sensitivity Rules

- Never use deficit framing ("unbanked," "underbanked," "financially excluded") — these communities are financially sophisticated, they just operate outside formal institutions
- Never position MyDola as "teaching" communities about finance — position as upgrading tools for practices they've mastered for generations
- Always use the community's own name for their lending circle (Sol, Tanda, Susu, Pardna, etc.) — never use "ROSCA" in consumer-facing content
- Visual identity should reflect the diversity of diaspora communities — not stock photos of generic "diverse" people
- Language must be accessible in English, Spanish, and Haitian Creole at minimum
- Never invoke crypto/blockchain language in consumer-facing content — the technology is invisible
- Respect the social/cultural dimension of lending circles — they're not just financial, they're community gatherings, trust networks, and cultural preservation

### Competitive Positioning Notes

- **SafeCircle Capital** is the closest U.S. direct competitor. Monitor closely. Differentiate on: Trust Score (they don't have it), escrow (they use basic ACH via Dwolla), remittance integration (they don't have it), multi-cultural positioning (they're generic), organizer compensation (unclear if they offer it), and credit scaffolding path (they don't have it).
- **Mission Asset Fund** is a nonprofit, not a tech competitor, but they validate the credit-building thesis and are actively expanding into Florida. They could be a partnership opportunity or a channel conflict. Their 168-point credit score increase stat is a powerful proof point for the category. Key difference: MAF requires nonprofit intermediaries; MyDola is a direct consumer product.
- **MoneyFellows** is the proof-of-concept, not the competitor. They validated the model in Egypt. MyDola brings it to the U.S. diaspora market. In investor communications, MoneyFellows is a case study. In consumer communications, they don't exist (different market).
- The real "competitor" is the status quo: cash + notebook + trust. Marketing must reduce switching anxiety, not attack the current approach. "Your circle works. We make it work better."
- Venmo/Zelle/Cash App are not competitors — they're infrastructure that people awkwardly repurpose. MyDola is purpose-built.
