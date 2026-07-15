# S51 Outbound Campaign - Phase 1: LinkedIn Presence & Activity Assessment

**Prepared:** 15 July 2026 · **Analyst:** S51 outbound research (automated web research + manual triangulation)
**Source list:** `S51_Potential_clients_Long_List_July13.csv` · **Prospects assessed:** 88 unique people (100 CSV rows; 12 duplicate rows collapsed)
**Method:** Public professional information only (LinkedIn search snippets, company sites, press, PR wires, conference/podcast bios, Crunchbase/aggregators). Live LinkedIn profile fetches are blocked (403/999) to automated tools, so activity is assessed from *indexed* public traces. No profiles, dates, titles, or activity were fabricated. Where a profile or activity could not be confidently established it is marked **Not verified** / **Not assessable publicly**, which is not the same as proven inactivity.

---

## The headline finding (read this first)

**This is a stale contact list - a lead export roughly 7-8 years old (companies, titles, funding stages, and technographics all point to 2017-2018).** That single fact reframes the whole campaign:

- **70 of 88 people (80%) have LEFT the company listed in the CSV.** Only 14 are confirmed still in their CSV role; 4 are unknown.
- **68 of 88 CSV email addresses (77%) are almost certainly dead** - the person changed employers, or the company was acquired/renamed/shut down. Only 17 look likely-valid.
- **Graded against each person's CURRENT company, ICP fit collapses:** 4 Strong, 10 Moderate, 20 Weak, 54 Excluded. Most "Excluded" cases are people who moved *up and out* of S51's sweet spot - to Databricks, Rocket Lawyer, TreviPay, Pantheon, LexisNexis-scale employers - or whose current company is B2C, a nonprofit, a VC fund, or India/APAC-domestic.

**Implication for the 20-client goal:** this list, used at face value (blast the CSV emails), will not produce 20 clients - the emails are mostly dead and most current employers are out of ICP. The value in the list is different and still real: it is a **network of proven B2B-SaaS marketing leaders and founders**, most of whom have moved to *new* companies. The path to pipeline is to re-target the ~14-18 who now sit at ICP-fit companies, at their **current** company with a **fresh** contact, plus mine the strong-relationship "movers" as warm re-introductions. Phase 2 builds the sequence for exactly that set. The realistic near-term qualified-conversation pool from this specific list is ~14-18 people, not 88; hitting 20 signed clients will require either topping up the list (Apollo/LinkedIn sourcing against the ICP) or a very high close rate. This is called out honestly rather than implied away.

---

## Summary dashboard

**Total prospects assessed:** 88 (of 100 CSV rows; see Data Quality below)

### Profile verification
| Status | Count | % |
|---|---|---|
| Verified | 73 | 83% |
| Likely match | 11 | 12% |
| Not verified | 4 | 5% |

### LinkedIn activity category
| Category | Count | % |
|---|---|---|
| Highly active | 2 | 2% |
| Moderately active | 6 | 7% |
| Occasionally active | 21 | 24% |
| Inactive | 20 | 23% |
| Not verified (activity not assessable) | 39 | 44% |

> The large "Not verified" activity bucket is a direct consequence of two things: (1) LinkedIn hides post history from logged-out/automated access, so absence of indexed posts is *not* proof of inactivity, and (2) many of these people are genuinely low-profile operators. Where a profile is confidently matched but no recent post surfaced, the person is still reachable - activity is simply *not publicly assessable*, which pushes them to email-first rather than LinkedIn-first.

### Recommended first-touch channel
| Path | Count | % |
|---|---|---|
| LinkedIn first | 8 | 9% |
| LinkedIn + email | 28 | 32% |
| Email first | 42 | 48% |
| Email only | 10 | 11% |

### ICP fit (graded against CURRENT company, mid-2026)
| Fit | Count | % |
|---|---|---|
| Strong | 4 | 5% |
| Moderate | 10 | 11% |
| Weak | 20 | 23% |
| Excluded | 54 | 61% |

### Email reachability (is the CSV address still live?)
| | Count |
|---|---|
| Likely valid | 17 |
| Likely dead | 68 |
| Unknown | 3 |

---

## Strongest LinkedIn-first opportunities

These are the prospects where a confidently-verified profile, genuine recent activity, and a real personalization hook line up - LinkedIn is a credible first touch.

1. **Elay Cohen - CEO & Co-Founder, SalesHood** (row-idx 63). The one unambiguous LinkedIn-first target: *Highly active* (multiple posts/month, verified), Strong ICP (US founder-led sales-enablement SaaS, ~$7M ARR), valid contact, live trigger (SalesHood "Agentic Search" launch + 18 Jun 2026 C-suite fireside chat). Peer-to-peer founder outreach fits perfectly.
2. **Aditya Bhashyam - President, Motorq** (76). *Moderately active*; just posted a public "why I joined Motorq" note (appointed 30 Mar 2026). Fresh-start job-change hook, connected-vehicle AI platform, Series B. LinkedIn-first while the new-role narrative is warm.
3. **Andrea Calcagno - CEO & Co-Founder, Cloud4Wi** (52). Strong ICP, valid email, verified periodic posting; live triggers (AI rebrand to cloud4wi.ai, "Top Enterprise WiFi Platform 2026" award, Apr 2026). LinkedIn + email in parallel.
4. **Utpal Bhatt - CMO, Luminary Cloud** (74). Strong ICP, brand-new CMO (2026) at an NVIDIA-backed engineering-AI SaaS ($72M Series B). Classic "first 30 days, inherited the GTM build" trigger - but CSV email is dead, so LinkedIn is the way in.
5. **Oscar Jofre - CEO & Co-Founder, Kore (ex-KoreConX)** (58). Strong ICP, valid email, very active historically; live trigger ($40M Series B announced Mar 2026; just retained a PR agency). LinkedIn + email.

**Also LinkedIn-viable with strong hooks:** Jim Yang (CMO, Super Dispatch - "2026: Our Biggest Year Yet" post), Dave Deasy (CMO, Wordly - Feb 2026 rebrand), Joe Montgomery (CRO, Overfuel - Oct 2025 growth round), Stuart Wall (CEO, Setpoint - S&P ratings-agency approval), Brad Keywell (Founder, Gigawatt AI - new AI-utilities venture).

## Prospects that should skip LinkedIn (email-only / de-prioritize)

- **No usable profile or activity (Email only, 10):** Jayme Williams, Sandy Soule, Scott Harris (corrupted row), Diana Shih, Kimberly Goldsworth, Hannu Impola, Alexandra Pestretsova, plus Sairam Vedam / Daniel Druker / Matthew Levin (verified but LinkedIn not a fit - see notes).
- **Retired / out of a buying seat:** Daniel Druker (retired since ~2018), Maria Alegre (now runs a VC fund), Leslie Leach (now adjunct professor), Betsy Gorgei (company went public/defense).
- **Anyone graded Excluded** should not receive LinkedIn *or* email effort in *this* campaign - the current employer is out of ICP. They can stay in the CRM as relationship contacts (several are now senior at attractive logos and could be warm intros later).

---

## Data-quality issues & missing information

**Duplicates in the source CSV (12 rows → collapsed to unique people):**
- Bob Paulsen / PlayerLync appears **4×** (rows 53, 57, 64, 65).
- Ajeet Singh / ThoughtSpot **3×** (95-97); Brad Keywell / Uptake **3×** (89-91).
- Deborah Holstein (1, 18), Josie Johnson (20, 27), Vikram Joshi (60, 67), Maria Alegre (68, 69), Patrick Rogers (77, 81) each appear **2×**.
- De-duplication alone removes 12 wasted touches and, more importantly, prevents the embarrassment of emailing the same person twice from the same sender.

**Corrupted / mismatched rows:**
- **Scott Harris / Bulb (row 32):** name is "Scott Harris" but the LinkedIn slug is `/in/bobbush` and the email is `bob@hellobulb.com` - the row conflates two identities. Do not use as-is.
- **Andrew Lovasz / The Control Group (row 36):** the `lastName` field is mangled to `Andrew.Lovaszthecontrolgroup.Com` (an email fragment). Company name is also misspelled ("compant").
- **Company LinkedIn slug used as a personal profile:** Jayme Williams (`/in/globalitcom`), Keith Johnson (`/in/thermoanalytics`) - these are company handles, not the person's profile, so identity can't be confirmed from the slug.

**Company-status flags that invalidate the row's premise:**
- Acquired/absorbed since the list was built: Hightail→OpenText (2018), ID Analytics→LexisNexis (2020), Cedexis→Citrix (2018), Periscope Data→Sisense (2019), Attivio→ServiceNow (2019), Ayasdi→SymphonyAI, Rancher→SUSE (2020), Cloud4Wi still independent, and more.
- Defunct: Pro.com (shut 2021), Airtime, several others.

**Missing fields:** `annualRevenue` blank for ~30 rows; `companyState` blank for a few; `personCountry` occasionally differs from `companyCountry` (e.g., Sairam Vedam listed US company / India person). Funding stages are as-of-2017 and unreliable.

**LinkedIn-specific gap:** because live profiles are not machine-readable, "most recent activity date" is only as good as what search engines have indexed. For the priority set, a human should open each profile while logged in to confirm the exact last-post date before the Day-0 touch (the knowledge base's "L1: PENDING manual confirmation" rule).

---

## Trends across roles, industries, company types & ICP fit

- **The "mover" pattern dominates.** 80% changed jobs. Marketing leaders and founders on a 7-year-old list don't sit still - the CSV is best read as a *2018 snapshot of a talent network*, not a current buyer list. Several are now at bigger, out-of-ICP companies; a valuable minority moved *laterally* into fresh ICP-fit SaaS roles (Jim Yang→Super Dispatch, Utpal Bhatt→Luminary Cloud, Joe Montgomery→Overfuel, Dave Deasy→Wordly) - these are the gold, because the person is a known-good buyer persona *and* has a brand-new-role trigger.
- **Founder/CEO rows convert to ICP better than the marketing-leader rows.** Founders tend to still run their company (Cohen/SalesHood, Calcagno/Cloud4Wi, Jofre/Kore, Wall/Setpoint, Harris/Black Crow), giving stable targeting; the VP-Marketing rows churned hardest.
- **Secondary (Data & AI) segment is thin on true fit.** Of 25, only 1 Strong / 5 Moderate. The segment includes several enterprise-scale names now (Databricks, ThoughtSpot, C3.ai alumni) that are Excluded for having in-house teams. The genuine Data-&-AI-services ICP that S51's LatentView proof speaks to (Tiger/Tredence/Fractal-type firms) is barely represented on this list.
- **Geography:** 83 US / 2 UK / 1 NL / 1 NO / 1 IN. The list is US-heavy, which is S51's *expansion* market rather than its *lead* market (UK/NL/SG). No structural problem, but it means the "founder LinkedIn culture" tailwind S51 relies on in the UK is weaker here.
- **Activity reality:** only **8 people (9%)** show genuinely current, verifiable LinkedIn activity worth building a LinkedIn-first motion around. For the rest, email is the spine and LinkedIn is a warm-up at best. Any plan that assumes "these are active LinkedIn users we can engage with" would be over-reaching the evidence.

---

## Full sortable assessment table

Sorted by outreach priority (ICP fit → activity → live email). The same data, sortable/filterable, is in **`phase1_assessment_ranked.csv`** (and unranked in `phase1_assessment.csv`). Columns follow the 13 required fields plus current-role, company-status, and email-reachability context.

| # | Name | CSV Co. | Current role (2026) | Still in CSV role? | LinkedIn | Verif. | Last activity | Freq | Activity cat. | Channel | Email live? | Conf. | ICP fit |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Elay Cohen | saleshood | CEO & Co-Founder, SalesHood (sales enablement B2B SaaS… | Yes | linkedin.com/in/elaycohen | Verified | June 18, 2026 fireside chat 'Winning Over the C-Suite … | High - multiple posts per m… | Highly active | LinkedIn first | Likely valid | High | Strong |
| 2 | Andrea Calcagno | cloud4wi | President, CEO & Co-founder, Cloud4Wi (AI-powered WiFi… | Yes | linkedin.com/in/andreacalcagno | Verified | Verified LinkedIn posts on slug andreacalcagno: compan… | Periodic LinkedIn posting (… | Occasionally active | LinkedIn + email | Likely valid | High | Strong |
| 3 | Utpal Bhatt | neo4j | Chief Marketing Officer, Luminary Cloud, Inc. (Palo Al… | No | linkedin.com/in/ubhatt | Verified | Third-party LinkedIn announcement of him as new Lumina… | Not precisely assessable fo… | Occasionally active | LinkedIn + email | Likely dead | High | Strong |
| 4 | Oscar Jofre | KoreConX | Co-Founder, President & CEO, Kore (formerly KoreConX) … | Yes | linkedin.com/in/oscarjofre | Verified | Newest dated LinkedIn post found ~May 2025 (activity 7… | Historically frequent - mul… | Not verified | LinkedIn + email | Likely valid | High | Strong |
| 5 | Aditya Bhashyam | c3 iot | President, Motorq (appointed March 30, 2026; leading G… | No | linkedin.com/in/adityabhashyam | Verified | LinkedIn posts around his Motorq move: 'Why Adi Bhashy… | Multiple visible posts acro… | Moderately active | LinkedIn first | Likely dead | High | Moderate |
| 6 | David Frieberg | planalytics | VP Marketing, Planalytics (predictive weather-driven d… | Yes | linkedin.com/in/david-frieberg-1a436513 | Verified | Confirmed dated personal posts through approx Nov 2024… | Historically roughly monthl… | Occasionally active | LinkedIn + email | Likely valid | High | Moderate |
| 7 | Dave Deasy | trustarc | CMO / SVP Marketing, Wordly (AI real-time translation … | No | linkedin.com/in/davedeasy | Verified | Quoted by name in Wordly's Feb 2026 brand-refresh anno… | A few visible brand/product… | Occasionally active | LinkedIn + email | Likely dead | High | Moderate |
| 8 | Jim Yang | illuminate education inc | Chief Marketing Officer, Super Dispatch (B2B SaaS tran… | No | linkedin.com/in/jlyang | Verified | Visible LinkedIn post '2026: Our Biggest Year Yet - Su… | At least occasional; one cl… | Occasionally active | LinkedIn + email | Likely dead | High | Moderate |
| 9 | Joe Montgomery | 250ok | Chief Revenue Officer at Overfuel (automotive/powerspo… | No | linkedin.com/in/joemontgomery317 | Verified | Confirmed LinkedIn post ~May 2025 (posts/joemontgomery… | Periodic - LinkedIn posts p… | Occasionally active | LinkedIn + email | Likely dead | High | Moderate |
| 10 | Brad Keywell | uptake | Founder & Executive Chairman, Gigawatt AI (AI-native o… | No | linkedin.com/in/bradkeywell | Verified | LinkedIn Pulse article 'Introducing Gigawatt: The foun… | Prolific thought-leadership… | Occasionally active | LinkedIn first | Likely dead | High | Moderate |
| 11 | Stuart Wall | Setpoint Capital | CEO & Co-Founder, Setpoint (setpoint.io) - fintech inf… | Yes | linkedin.com/in/stuartwall | Verified | LinkedIn post ~Jan 2026 ('Exciting news at Setpoint');… | Periodic founder posts cont… | Occasionally active | LinkedIn + email | Likely dead | High | Moderate |
| 12 | Victoria Satran | mwa intelligence inc | VP of Marketing, Computer Guidance Corporation (cloud … | No | linkedin.com/in/victoria-satran-b5572512 | Verified | Last visible personal LinkedIn post approx July 2021 (… | Very low personal cadence -… | Inactive | Email first | Likely dead | High | Moderate |
| 13 | Jessica Reiter | c3 iot | CMO at TruTechnologies (makers of TruLab), also positi… | No | linkedin.com/in/jessicajonesreiter | Verified | Not assessable publicly - no dated personal LinkedIn p… | Not assessable | Not verified | Email first | Likely dead | Medium | Moderate |
| 14 | Richard Harris | intent media inc | Founder & CEO, Black Crow AI (machine-learning / predi… | No | linkedin.com/in/richardlharris | Verified | LinkedIn post ~Oct 2023 ('building Black Crow since 20… | Not assessable (only a stal… | Not verified | Email first | Likely dead | High | Moderate |
| 15 | Loc Nguyen | feedzai | Founder & Chief Go-to-Market Officer, Braincodex.ai (S… | No | linkedin.com/in/locnguyen1 | Verified | Multiple LinkedIn posts for Braincodex ('Codex Princip… | Posts a recurring thought-l… | Moderately active | LinkedIn first | Likely dead | High | Weak |
| 16 | Nir Polak | exabeam | Co-founder & 'Builder' at WhiteRabbit (cybersecurity v… | No | linkedin.com/in/nir-polak-1564934 | Verified | LinkedIn post about WhiteRabbit hiring/CISO ~Jan 6, 20… | Sporadic - a handful of pos… | Occasionally active | LinkedIn + email | Likely dead | Medium | Weak |
| 17 | Deepak Mittal | to the new | CEO & Founder, CloudKeeper (cloud cost optimization / … | No | linkedin.com/in/mittaldeepak | Verified | 2026 LinkedIn posts on FinOps for AI, CloudKeeper's ou… | Several posts across 2026 (… | Occasionally active | LinkedIn + email | Unknown | High | Weak |
| 18 | Bob Paulsen | playerlync | Co-Founder, President & CEO, PlayerLync (mobile/deskle… | Yes | linkedin.com/in/bpaulsen | Verified | Verified LinkedIn posts on slug bpaulsen: 'join forces… | Sparse LinkedIn posting (ro… | Inactive | Email first | Likely valid | High | Weak |
| 19 | Stephen Huson | procom | Unknown as of mid-2026. Last known: VP/Head of Marketi… | No | linkedin.com/in/stephenhuson | Verified | LinkedIn post ~mid-2023 promoting Yesler (activity_708… | Rare - only one indexed per… | Inactive | LinkedIn + email | Likely dead | Medium | Weak |
| 20 | Nick Noyer | duedil ltd | Unknown - last confirmed role CMO at Planet (Nov 2022-… | No | uk.linkedin.com/in/nicknoyer | Verified | LinkedIn post ~Jan 2023 (announcing joining Planet aft… | Not assessable (no posts fo… | Inactive | LinkedIn + email | Likely dead | Medium | Weak |
| 21 | Christopher Etesse | flat world education | Founder, Chairman & CEO, Fusion Cyber (cybersecurity r… | No | linkedin.com/in/cetesse | Verified | Last clearly-dated LinkedIn posts are 2022-2023 (activ… | No confirmed LinkedIn posti… | Inactive | Email first | Likely dead | High | Weak |
| 22 | Betsy Gorgei | edge technologies inc | Unknown / uncertain. She founded and long led Edge Tec… | No | linkedin.com/in/betsy-romanoff-gorgei-329… | Verified | Most recent visible LinkedIn post ~Dec 4, 2024 (on cli… | Sparse - last visible Linke… | Inactive | Email first | Likely dead | Medium | Weak |
| 23 | Vikram Joshi | xcalar inc | Founder, President & CTO, Compute.AI (data lakehouse /… | No | linkedin.com/in/vikramjoshi | Verified | Newest visible LinkedIn post ~Jan 2024 (activity 71483… | Sparse; last indexed Linked… | Inactive | Email first | Likely dead | High | Weak |
| 24 | Maria Alegre | chartboost | Co-founder & Managing Partner, Flori Ventures (seed-st… | No | linkedin.com/in/marialegre | Verified | Most recent visible LinkedIn posts are 2021-2022 (Flor… | Low on LinkedIn (last visib… | Inactive | Email first | Likely dead | High | Weak |
| 25 | Keith Johnson | thermoanalytics inc | Co-Founder & Board Chairman, ThermoAnalytics, Inc. (st… | No | linkedin.com/in/thermoanalytics | Likely match | Not assessable publicly - no personal posts or dated L… | Not assessable (no personal… | Not verified | Email first | Likely valid | Medium | Weak |
| 26 | Nell Hurley | educationsuperhighway | Strategy, Marketing & Special Projects at Orijin (edte… | No | - | Likely match | Not assessable publicly (no indexed personal LinkedIn … | Not assessable | Not verified | Email first | Likely dead | Medium | Weak |
| 27 | Matthew Levin | simplereach | Co-Founder & CEO, Lariat (AI-native prospecting softwa… | No | linkedin.com/in/mblevin | Verified | LinkedIn post ~June 2025 (Lariat launch announcement, … | Not assessable (only two in… | Not verified | LinkedIn + email | Likely dead | High | Weak |
| 28 | Karen Sebold | ministry brands | VP Marketing, LivTech (PE-backed healthcare/aging-care… | No | linkedin.com/in/karensebold | Likely match | Not assessable publicly (no LinkedIn posts found for t… | Not assessable | Not verified | Email first | Likely dead | Medium | Weak |
| 29 | Olivera Ojdanic | snap interactive inc | Marketing Director outside the CSV company - CSV slug … | No | linkedin.com/in/olivera-ojdanic-57a9a83 | Verified | Not assessable publicly | Not assessable | Not verified | Email first | Likely dead | Medium | Weak |
| 30 | Scott Harris | bulb | Unknown | Unknown | - | Not verified | Not assessable publicly | Not assessable | Not verified | Email only | Unknown | Low | Weak |
| 31 | Leslie Leach | zaplabs | Adjunct Professor at SF State (Lam Family College of B… | No | linkedin.com/in/lrleach | Verified | Not assessable publicly | Not assessable | Not verified | Email first | Likely dead | High | Weak |
| 32 | Priya Rajan | feedzai | Co-Founder & CEO, StageZero (StageZeroAI - AI product-… | No | linkedin.com/in/priya-rajan-32a0b12 | Verified | Most recent visible: ~Aug 27, 2025 'Launching StageZer… | Moderate historically (a cl… | Not verified | LinkedIn + email | Likely dead | High | Weak |
| 33 | Patrick Rogers | ayasdi | Unknown (verified as the ex-Ayasdi CMO / ex-Cohesity V… | No | linkedin.com/in/patrickrogers1 | Verified | Not assessable publicly - high namesake density (multi… | Not assessable | Not verified | Email first | Likely dead | Low | Weak |
| 34 | Daniel Druker | ayasdi | Retired Silicon Valley executive (board member / mento… | No | linkedin.com/in/danieldruker | Verified | Not assessable publicly - no dated LinkedIn posts foun… | Not assessable | Not verified | Email only | Likely dead | High | Weak |
| 35 | Warren Smith | vbrick | Independent AI-native product & technology executive /… | No | linkedin.com/in/warrendsmith | Verified | LinkedIn article 'The Latest AI Problem Isn't Intellig… | Roughly weekly (steady Link… | Highly active | LinkedIn first | Likely dead | High | Excluded |
| 36 | Ali Ghodsi | databricks | Co-founder & CEO, Databricks (unchanged). Databricks r… | Yes | linkedin.com/in/alighodsi | Verified | Own LinkedIn post 'Conversation with Databricks CEO Al… | Personal posts roughly ever… | Moderately active | LinkedIn first | Likely valid | High | Excluded |
| 37 | Sairam Vedam | cigniti | Chief Marketing Officer, QualityKiosk Technologies (ap… | No | linkedin.com/in/saivram | Verified | Most recent VISIBLE dated post ~Oct 2025 ('The Coforge… | Roughly weekly during 2025 … | Moderately active | Email only | Likely dead | High | Excluded |
| 38 | Kevin Shively | tagboard | VP of Corporate Marketing at Pantheon (since ~April 20… | No | linkedin.com/in/kevinshively1 | Verified | ~Feb 2026 LinkedIn post ('wherethewebworks', activity-… | Roughly monthly cadence vis… | Moderately active | LinkedIn first | Likely dead | High | Excluded |
| 39 | Robert Day | lynx software technologies formerly lynuxworks | Director, Automotive Go-To-Market / Autonomous Vehicle… | No | linkedin.com/in/robert-day-77028b | Verified | Confirmed speaking slot at SOAFEE/AutoTech 2026 (Jun 2… | About 1-3 public activities… | Moderately active | LinkedIn + email | Likely dead | High | Excluded |
| 40 | Scott Sellers | azul systems | President, CEO & Co-Founder, Azul (Sunnyvale, CA) - st… | Yes | linkedin.com/in/ssellers | Verified | Multiple self-authored LinkedIn posts through 2025; fr… | Regular historically - nume… | Occasionally active | LinkedIn + email | Likely valid | High | Excluded |
| 41 | Brent Shroyer | listrak | VP of Marketing, Listrak (Lititz, PA) - still in the C… | Yes | linkedin.com/in/brent-shroyer-7713555 | Verified | ~Sept 2025 LinkedIn post (Listrak fashion/beauty retai… | Roughly monthly company-con… | Occasionally active | LinkedIn + email | Likely valid | High | Excluded |
| 42 | Steve Miff | pcci | President & CEO, PCCI (Parkland Center for Clinical In… | Yes | linkedin.com/in/steve-miff-a313495 | Verified | Visible LinkedIn post 'PCCI 2026 Annual Impact Report'… | Roughly monthly-or-less on … | Occasionally active | LinkedIn + email | Likely valid | High | Excluded |
| 43 | Ajeet Singh | thoughtspot | Co-founder & Executive Chairman, ThoughtSpot (day-to-d… | No | linkedin.com/in/ajeetsinghmann | Verified | LinkedIn post ~Feb 2026 re: ThoughtSpot named Leader i… | Periodic milestone posts (s… | Occasionally active | LinkedIn + email | Likely valid | High | Excluded |
| 44 | Anshu Agarwal | cedexis | General Partner at Converge (early-stage B2B tech VC);… | No | linkedin.com/in/anshuagarwal | Verified | #sftechweek LinkedIn post ~Oct 2025 (posts/anshuagarwa… | Sporadic - occasional Linke… | Occasionally active | LinkedIn + email | Likely dead | High | Excluded |
| 45 | Allen Bonde | repsly | Chief Marketing Officer at TreviPay (since Jan 2023) | No | linkedin.com/in/allenbonde | Verified | Most recent clearly-datable LinkedIn post ~Dec 2025 ('… | Consistent thought-leadersh… | Occasionally active | LinkedIn first | Likely dead | High | Excluded |
| 46 | Adam Von Reyn | placester | Head of Growth & Operations, Mindbloom (at-home ketami… | No | linkedin.com/in/adamvonreyn | Verified | Multiple LinkedIn posts on DTC/telehealth growth refer… | Appears regular across 2025… | Occasionally active | LinkedIn + email | Likely dead | High | Excluded |
| 47 | Melissa Wallace (Melissa Hudson Wallace) | splashthat | Co-Founder, Fivefoottwo (marketing collective, since 2… | No | linkedin.com/in/melissahudsonwallace | Verified | Most recent visible LinkedIn post ~late 2025 (Fierce F… | Sporadic on LinkedIn (a han… | Occasionally active | LinkedIn + email | Likely dead | High | Excluded |
| 48 | Stephen Spellicy | guavus | VP, Product Marketing & Solutions, Extreme Networks (G… | No | linkedin.com/in/stephenspellicy | Verified | 2026 LinkedIn post re: Wildix 2026 Summit (AI in UC&C)… | A handful of visible posts … | Occasionally active | LinkedIn + email | Likely dead | High | Excluded |
| 49 | Jonathan Symonds | ayasdi | CMO at Radiant (Brookfield-backed AI infrastructure co… | No | linkedin.com/in/jtsymonds | Verified | Feb 2026 LinkedIn posts re: Radiant launch / Ori merge… | Several posts clustered aro… | Occasionally active | LinkedIn + email | Likely dead | High | Excluded |
| 50 | Lindsay Sanchez | koreai | Chief Marketing Officer, Pricefx (appointed March 2025) | No | linkedin.com/in/lindsaysanchez1 | Verified | Personal LinkedIn post ~May 2024 ('why every CMO shoul… | Roughly a few visible posts… | Occasionally active | LinkedIn + email | Likely dead | High | Excluded |
| 51 | Yousef Javadi | ltn global communications | Co-founder, President & CEO, LTN Global Communications… | Yes | linkedin.com/in/yousef-javadi-b32aa010 | Verified | Most recent clearly-dated LinkedIn post found is ~2019… | No meaningful personal Link… | Inactive | Email first | Likely valid | High | Excluded |
| 52 | Frank Renwick | Boweryfarming | VP, Marketing & Communications at May Mobility (autono… | No | linkedin.com/in/frankrenwick | Verified | ~Apr/May 2025 LinkedIn post re: 'Uber Adds May Mobilit… | A couple of visible posts i… | Inactive | Email first | Likely valid | High | Excluded |
| 53 | Nathan Ellering | coschedule | Digital Marketing Strategy at Sinch (individual-contri… | No | linkedin.com/in/nathanellering | Verified | Most recent VISIBLE dated LinkedIn post ~Feb 2023 ('I … | Not assessable recently; la… | Inactive | Email first | Likely dead | Medium | Excluded |
| 54 | Rebekah Audic | mirriad | Partner / Senior Marketing Partner for Branding & Grow… | No | linkedin.com/in/rebekahaudic | Verified | Most recent VISIBLE dated LinkedIn post ~Mar 2024 (Int… | Not assessable recently; la… | Inactive | Email first | Likely dead | High | Excluded |
| 55 | Daniel Smith | bookbub | SVP of Marketing, ButcherBox (DTC meat-subscription / … | No | linkedin.com/in/dlls | Likely match | LinkedIn post ~Dec 2023 via /in/dlls ('something a bit… | Rare - one indexed post (~l… | Inactive | Email first | Likely dead | Medium | Excluded |
| 56 | Tara Grant | jet reports | COO & Partner, Big Room Creative Inc. (B2B tech / Micr… | No | linkedin.com/in/taralgrant | Verified | LinkedIn post ~April 2024 ('Happy Birthday to us!', Bi… | Rare - one indexed post (~A… | Inactive | Email first | Likely dead | High | Excluded |
| 57 | Michael Shearer | selecthub | Owner/Operator, Shemash (independent digital marketing… | No | linkedin.com/in/mfshearer | Verified | Last visible LinkedIn post ~Nov 2021 ('hack week at Cl… | Not assessable on LinkedIn … | Inactive | Email first | Likely dead | High | Excluded |
| 58 | Andrew Lovasz | the control group media compant | VP of Marketing, AgelessRx (San Diego) - a B2C longevi… | No | linkedin.com/in/andrewlovasz | Verified | Only indexed LinkedIn post found is 'We are hiring at … | None visible in ~5+ years (… | Inactive | Email first | Likely dead | High | Excluded |
| 59 | Ron Brumbarger | bitwise solutions | Founder & President, Struinova Innovation (innovation … | No | linkedin.com/in/brumbarger | Verified | ~March-April 2024 indexed LinkedIn posts (Apprentice N… | Sparse in public index - a … | Inactive | Email first | Likely dead | High | Excluded |
| 60 | Spencer Leu | redapt inc | Founder & Designer, Aloha Timepieces (consumer watch b… | No | linkedin.com/in/speleu | Verified | Newest visible LinkedIn post ~Sept 2021 (activity 6849… | Sparse on LinkedIn (last in… | Inactive | Email first | Likely dead | High | Excluded |
| 61 | Anand Shah | pcci | VP, Social Health at Kaiser Permanente (national socia… | No | linkedin.com/in/anand-shah-30166623 | Verified | Most recent visible personal LinkedIn post ~Nov 2025 (… | Sparse: a handful of visibl… | Inactive | Email first | Likely dead | High | Excluded |
| 62 | Matthew Levin | grandeproductioncedar heroku | Co-founder & former CEO of Donut Media (automotive You… | No | linkedin.com/in/matthew-levin-7205033b | Verified | Last visible personal LinkedIn post ~Jan 9, 2023 (acti… | Dormant on LinkedIn - last … | Inactive | Email only | Likely dead | Medium | Excluded |
| 63 | Kim Pallas | genfed financial credit union, inc. | VP, Chief Marketing Officer, GenFed Financial Credit U… | Yes | linkedin.com/in/kim-pallas-87148357 | Likely match | Not assessable publicly | Not assessable | Not verified | Email first | Likely valid | Medium | Excluded |
| 64 | Diana Shih | topmost world inc | Unknown | Unknown | - | Not verified | Not assessable publicly | Not assessable | Not verified | Email only | Likely valid | Low | Excluded |
| 65 | Don Faace | drmcnatty  associates inc | President & CEO, D.R. McNatty & Associates, Inc. (Miss… | Yes | linkedin.com/in/don-mcnatty-psp-faace-234… | Verified | Not assessable publicly (no datable personal LinkedIn … | Not assessable for the indi… | Not verified | Email first | Likely valid | High | Excluded |
| 66 | Manish Bhardwaj | prospance inc | Co-Founder, President & CEO, Prospance Inc (Fremont, C… | Yes | linkedin.com/in/bhardwajmanish | Likely match | Not assessable publicly (no dated indexed LinkedIn pos… | Not assessable | Not verified | Email first | Likely valid | Medium | Excluded |
| 67 | Deborah Holstein | hightail | Chief Growth Officer, Rocket Lawyer (joined 2023) | No | linkedin.com/in/deborahholstein | Verified | Twilio SIGNAL 2025 fireside chat on multi-touch attrib… | Not assessable | Not verified | Email first | Likely dead | High | Excluded |
| 68 | Eric Lindeen | id analytics | VP Marketing & co-founder, Anna Buys Houses (real-esta… | No | linkedin.com/in/ericlindeen | Verified | Not assessable publicly | Not assessable | Not verified | Email first | Likely dead | High | Excluded |
| 69 | Jayme Williams | global it | Unknown | Unknown | - | Not verified | Not assessable publicly (no personal profile could be … | Not assessable | Not verified | Email only | Unknown | Low | Excluded |
| 70 | Dominic Gallello | airtime | Managing Director & Head of Digital and AI, Bridgepoin… | No | uk.linkedin.com/in/dominicgallello | Verified | Most recent dated post on the verified profile is 'Bri… | Not assessable in-window; o… | Not verified | Email first | Likely dead | High | Excluded |
| 71 | Steve Machesney | kelser corp | Fractional CMO / GovTech marketing specialist - founde… | No | linkedin.com/in/stevemachesney | Likely match | Not assessable publicly within the window. He maintain… | Not assessable - content-cr… | Not verified | LinkedIn + email | Likely dead | Medium | Excluded |
| 72 | Josie Johnson | prodagio software | Chief Client Experience Officer, Blickstein Group (leg… | No | linkedin.com/in/josie-johnson-65653615 | Verified | Not assessable publicly - no indexed LinkedIn posts/ar… | Not assessable | Not verified | Email first | Likely dead | High | Excluded |
| 73 | Sandy Soule | bedandbreakfastcom | Retired (LinkedIn/press indicate she retired from Beda… | No | linkedin.com/in/sandy-soule-4440aa12 | Verified | Not assessable publicly | Not assessable | Not verified | Email only | Likely dead | Medium | Excluded |
| 74 | Brad Morris | periscope data | At Figma (Marketing Strategy & Operations, per LinkedI… | No | linkedin.com/in/cbradmorris | Verified | Not assessable publicly | Not assessable | Not verified | Email first | Likely dead | Medium | Excluded |
| 75 | Maryanne Sinville | attivio | Principal, MAS Venture Group, Inc. (Boston-area real e… | No | linkedin.com/in/msinville | Verified | Not assessable publicly | Not assessable | Not verified | Email first | Likely dead | High | Excluded |
| 76 | Louise Westoby | rancher labs inc | Uncertain - listed as VP of Marketing at Fingerprint (… | No | linkedin.com/in/lwestoby | Likely match | Not assessable publicly (no indexed recent posts/artic… | Not assessable | Not verified | Email first | Likely dead | Low | Excluded |
| 77 | Kimberly Goldsworth | prism skylabs | Unknown - aggregators (RocketReach) list a 'Realtor at… | No | linkedin.com/in/kimberlygoldsworth | Likely match | None visible / Not assessable publicly - no indexed Li… | Not assessable | Not verified | Email only | Likely dead | Medium | Excluded |
| 78 | Kate Farmer | baker technologies | VP Marketing, Notion (a Comcast company) - smart-home … | No | linkedin.com/in/farmerkate | Verified | No recent dated posts found. Notion's own account refe… | Not assessable (no recent d… | Not verified | Email first | Likely dead | High | Excluded |
| 79 | Stephen Philip | appdome | Senior Marketing Consultant (self-employed), Mountain … | No | linkedin.com/in/stephenphilip | Verified | Not assessable publicly | Not assessable | Not verified | LinkedIn + email | Likely dead | High | Excluded |
| 80 | Kim Jamerson | sharpspring mail | Director of Demand Generation at Bugcrowd (per RocketR… | No | linkedin.com/in/kimjamerson | Verified | Not assessable publicly | Not assessable | Not verified | LinkedIn + email | Likely dead | Medium | Excluded |
| 81 | Hannu Impola | conax | Unknown | Unknown | - | Not verified | Not assessable publicly | Not assessable | Not verified | Email only | Likely dead | Low | Excluded |
| 82 | Jacob Shin | media temple | Director of Operations, Crossing Borders Ministry Inc … | No | linkedin.com/in/jacobdshin | Verified | Not assessable publicly (no dated LinkedIn posts/artic… | Not assessable | Not verified | Email first | Likely dead | High | Excluded |
| 83 | Paul Friesen | panoply | Self-employed - Fractional CMO (AI / Dev Tools / Infra… | No | linkedin.com/in/pfriesen | Verified | Not assessable publicly (profile is current as of 2026… | Not assessable | Not verified | Email first | Likely dead | Medium | Excluded |
| 84 | Alexandra Pestretsova | mycom | Founder & Partner, Unlock Partners (games/digital mark… | No | linkedin.com/in/redlynxi | Likely match | Not assessable publicly | Not assessable | Not verified | Email only | Likely dead | Medium | Excluded |
| 85 | Kevin Granath | elacarte | VP, Membership Development at MMA Global (marketing/mo… | No | linkedin.com/in/kevingranath | Likely match | Not assessable publicly | Not assessable | Not verified | Email first | Likely dead | Medium | Excluded |
| 86 | Kate Lowry | listrak | Director of Strategic Partnerships, Saint Joseph's Uni… | No | linkedin.com/in/kate-lowry-35a7606 | Verified | Not assessable publicly - her specific profile's posts… | Not assessable | Not verified | Email first | Likely dead | High | Excluded |
| 87 | Donghui Wu | pcci | Chief Scientist, DW Health LLM (his own healthcare-AI … | No | linkedin.com/in/donghui-wu-phd-mba-7959053 | Verified | Not assessable publicly (academic Google Scholar prese… | Not assessable | Not verified | Email first | Likely dead | Medium | Excluded |
| 88 | Swati Choksi | guavus | Senior Leader, Solutions Architecture (Data, Analytics… | No | linkedin.com/in/swatichoksi | Verified | Not assessable publicly - no dated personal LinkedIn p… | Not assessable | Not verified | Email first | Likely dead | High | Excluded |


---

### Column legend
- **Still in CSV role?** - Yes/No/Unknown: is the person still at the company the CSV lists.
- **Verif.** - Verified / Likely match / Not verified (identity confidence for the LinkedIn URL).
- **Last activity / Freq** - most recent *publicly indexed* LinkedIn trace and estimated cadence; "Not assessable publicly" = profile exists but post history isn't machine-visible (≠ inactive).
- **Window** (in CSV) - 90d default; 180d where activity was too thin at 90d.
- **Channel** - LinkedIn first / LinkedIn + email / Email first / Email only.
- **Email live?** - whether the CSV email address itself is likely still deliverable given the person's current employer.
- **ICP fit** - graded against the person's CURRENT company vs S51's ICP (Primary B2B SaaS $5-30M; Secondary Data & AI services), with exclusions applied.

*Per-prospect reasoning and the full source URL list for every assessment are in the CSV (`reasoning`, `icp_reason`, `sources` columns).*
