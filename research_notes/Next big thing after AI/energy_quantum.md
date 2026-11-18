# Energy Infrastructure and Quantum Computing as "Next Big Things" (as of Nov 18, 2026)

Research note: direct fetches of iea.org and world-nuclear-news.org were blocked in this session (network allowlist), so many figures come from search-result summaries of primary reports and from secondary coverage. Dates of figures are labeled. Items marked (secondary) should be checked against the primary source before publication.

## 1. Electricity demand growth and data centers (IEA, EIA, LBNL, interconnection queues)

### Takeaway
Demand growth is real and already in the data: the IEA (Feb 2026, raised in its Jul/Aug 2026 mid-year update) forecasts global electricity demand growth of about 3.6%/yr through 2030, with data centers driving about half of US demand growth. LBNL's 2025 update projects US data centers at about 11.8% of US electricity by 2030 (range 9.5–15.3%), up from 4.4% in 2023. The constraint is grid connection: about 2,060 GW of generation and storage sat in US interconnection queues at end-2025.

### Cited Findings
- IEA *Electricity 2026* (published Feb 2026): global demand is forecast to grow at an average 3.6%/yr over 2026–2030 ("more than 3.5%" in the press release). — [IEA Executive Summary](https://iea.org/reports/electricity-2026/executive-summary); [IEA news release](https://www.iea.org/news/global-electricity-demand-is-set-to-grow-strongly-to-2030-underscoring-need-for-investments-in-grids-and-flexibility)
- IEA *Electricity Mid-Year Update 2026* (Jul/Aug 2026): global demand growth is now expected at 3.6% in 2026 and 3.8% in 2027, up from 3% in 2025. — [IEA Mid-Year Update 2026](https://www.iea.org/reports/electricity-mid-year-update-2026/executive-summary); [Engineering News, Jul 23 2026](https://www.engineeringnews.co.za/article/global-power-demand-to-accelerate-in-2026-and-2027-iea-says-2026-07-23)
- IEA *Electricity 2026*: US demand is projected to grow nearly 2%/yr through 2030, with about half of the increase from data centers. In 2025, data centers accounted for about 50% of US demand growth (secondary). — [Down To Earth](https://www.downtoearth.org.in/energy/global-electricity-demand-set-to-surge-through-2030-as-data-centres-evs-and-cooling-drive-new-age-of-electricity-iea); [IEA Electricity 2026 Demand](https://www.iea.org/reports/electricity-2026/demand)
- IEA: growth in data-center demand over 2025–2030 is forecast to more than double compared with the previous five years, rising from 206 TWh to over 460 TWh. These appear to be five-year increments, not annual levels (secondary). — [Down To Earth](https://www.downtoearth.org.in/energy/global-electricity-demand-set-to-surge-through-2030-as-data-centres-evs-and-cooling-drive-new-age-of-electricity-iea)
- IEA *Energy and AI* (Apr 2025) base case: global data-center electricity reaches about 945 TWh by 2030, roughly double. In the US, more than 250 TWh in 2026, rising to nearly 400 TWh by 2029. — [S&P Global, Apr 10 2025](https://www.spglobal.com/energy/en/news-research/latest-news/electric-power/041025-global-data-center-power-demand-to-double-by-2030-on-ai-surge-iea)
- EIA STEO (latest, late 2026): forecasts record US electricity consumption in 2026 and 2027, driven by AI data centers and electrification. The EIA does not break out data-center demand; the commercial sector, which contains data centers, saw the largest upward revisions. — [Inside AI News](https://insideai.news/news/ai-hardware-infrastructure/us-power-demand-ai-data-centers/14912/); [DCD](https://www.datacenterdynamics.com/en/news/eia-projects-record-us-data-center-power-use-amid-ai-and-crypto-boom/)
- LBNL 2024 report (Dec 2024): US data centers used about 176 TWh in 2023 (4.4% of US electricity). The report projected 325–580 TWh in 2028 (6.7–12%). — [LBNL 2024 report](https://eta-publications.lbl.gov/sites/default/files/2024-12/lbnl-2024-united-states-data-center-energy-usage-report_1.pdf)
- LBNL 2025 Update (circulated mid-2026): data centers could account for 11.8% of US electricity by 2030, with scenarios from 9.5% to 15.3%. — [LBNL 2025 update PDF via RTO Insider](https://www.rtoinsider.com/wp-content/uploads/2026/06/data-center-energy-usage-2025-update.pdf); [LBNL modeling page](https://datacenters.lbl.gov/modeling-forecasting)
- Interconnection queues: about 2,060 GW of generation and storage was in US queues at end-2025, down 10% year over year (Berkeley Lab). Breakdown cited: about 1,312 GW of generation and about 749 GW of storage. Including large-load requests, the total is about 2,600 GW (secondary). — [Enki AI](https://enkiai.com/data-center/ai-data-center-energy-2026-2600-gw-queue-pjm-plan/); [Interconnection queue tracker](https://ahasignals.com/interconnection-queue-tracker/)
- ERCOT's large-load queue was about 410 GW as of April 2026, of which about 73% was data centers (secondary). — [Presenc AI](https://presenc.ai/research/grid-interconnection-queue-ai-datacenters-2026)
- Policy: FERC ordered six grid operators to revise interconnection rules for large loads (data centers over 20 MW) on a 60-day clock (secondary, 2026). — [Avanza Energy substack](https://avanzaenergy.substack.com/p/the-60-day-clock-ferc-just-forced)

### Inferences
- The forecasts are converging. US data-center share roughly triples from 4.4% (2023) to about 9–15% by 2030, and data centers make up about half of incremental US demand. This is the main structural driver of the energy buildout "next big thing."
- A queue of about 2,000+ GW of mostly unbuilt projects, against a US peak load of roughly 750 GW, shows that the bottleneck is interconnection and transmission rather than proposed supply.
- The ranges are still wide (LBNL 9.5–15.3%). Speculative or duplicate data-center load requests, especially in ERCOT, likely inflate the queues.

### Gaps
- Could not fetch the IEA page directly to confirm US-specific TWh figures in *Electricity 2026*.
- No exact EIA STEO November 2026 headline numbers (TWh, % growth) were verified.
- Found no reliable national GW figure for data-center-only load in queues.

## 2. Nuclear fission and SMRs: tech PPAs, executive orders, NRC, uranium, Oklo, NuScale, TerraPower

### Takeaway
Nuclear has moved from announcements to some physical construction. TerraPower's Natrium received an NRC construction permit (Mar 2026), and Kairos's Hermes 2 for Google broke ground (Apr 2026). The Crane (TMI-1) restart for Microsoft is targeted for 2027. Commercial SMR electricity remains about 2030 or later. Uranium term prices hit a record of about $96/lb (Aug 2026). NuScale still has the only certified SMR design but no firm commercial customer.

### Cited Findings
- May 23, 2025 executive orders (four EOs): they target an increase in US nuclear capacity from about 100 GW to 400 GW by 2050. They require the NRC to reach a final decision on new reactor applications within 18 months and on license renewals within 1 year, with proposed rules within 9 months and final rules within 18 months. A DOE pilot program aimed for three experimental reactors reaching criticality by July 4, 2026. — [DOE "9 Key Takeaways"](https://www.energy.gov/ne/articles/9-key-takeaways-president-trumps-executive-orders-nuclear-energy); [Holland & Knight](https://www.hklaw.com/en/insights/publications/2025/05/president-trump-signs-4-executive-orders); [AAF](https://www.americanactionforum.org/insight/trumps-nuclear-executive-orders-overview-and-analysis/)
- Microsoft–Constellation (Crane Clean Energy Center, formerly TMI-1, 835 MW, about $1.6B restart): DOE issued a $1B loan in Nov 2025. The NRC environmental assessment found no significant impact; sources differ on whether the draft (Jun 2026) or final (Sep 2026) version is current. The restart is on track for 2027. — [PA Capital-Star](https://penncapital-star.com/energy-environment/concern-persists-as-crane-nuclear-plant-progresses-toward-2027-restart/); [NRC news release 2026](https://www.nrc.gov/about-nrc/news-releases/2026/nrc-hold-public-meeting-discuss-progress-potential-restart-crane-clean-energy-center)
- Google–Kairos: a Master Plant Development Agreement (Oct 2024) covers up to 500 MW by 2035. The Hermes 2 PPA via TVA (Aug 2025) is for 50 MW. Hermes 2 broke ground on Apr 17, 2026 and targets commercial operation in 2030. The operating license application was being prepared as of Feb 2026, with an expected NRC review of 18–24 months. — [Kairos Power (Wikipedia)](https://en.wikipedia.org/wiki/Kairos_Power); [ANS Nuclear Newswire](https://www.ans.org/news/article-7291/a-new-collaboration-among-kairos-tva-and-google/); [Yahoo Finance/Kairos CTO interview](https://finance.yahoo.com/news/nuclear-needs-humility-kairos-power-115440258.html)
- Meta (Jan 2026): agreements with Oklo, TerraPower and Vistra total up to 6.6 GW by 2035. Oklo's share is 1.2 GW of Aurora; TerraPower's is 2.8 GW of Natrium plus 1.2 GW of storage (secondary). — [Introl](https://introl.com/blog/meta-nuclear-power-deal-oklo-terrapower-vistra-6gw-2026)
- TerraPower Natrium (Kemmerer, WY): NRC construction permit issued March 2026, and nuclear construction of Unit 1 began the following month. — [SMR Intel NRC tracker](https://smrintel.com/smr-nrc-approval-tracker/)
- NuScale: the 50 MWe design was certified by the NRC in Jan 2023, and a 77 MWe Standard Design Approval was granted in May 2025. It is the only SMR with NRC design approval. On Oct 29, 2026 it signed a component-fabrication deal with Doosan Enerbility but still lacks a major commercial offtake. — [NuScale 10-K FY2025](https://www.sec.gov/Archives/edgar/data/1822966/000182296626000018/smr-20251231.htm); [Motley Fool, Nov 6 2026](https://www.fool.com/investing/2026/11/06/not-oklo-not-x-energy-this-smr-stock-just-signed-a/)
- Oklo Aurora is still early in licensing. Trackers disagree on whether it is a resubmitted application or at pre-application with a COLA targeted for 2026. Oklo acquired manufacturer ARMEC in Aug 2026. — [SMR Intel tracker](https://smrintel.com/smr-nrc-approval-tracker/); [SMR Intel Aug 2026 roundup](https://smrintel.com/news/smr-industry-roundup-august-2026/)
- Uranium: the long-term contract price hit a record $96/lb in Aug 2026 (Sprott). Spot spiked to about $101/lb in late Jan 2026 and has since mostly traded at $83–90. — [Streetwise Reports, Nov 9 2026](https://www.streetwisereports.com/article/2026/11/09/uranium-contract-prices-hit-a-record-as-two-explorers-ramp-up-drilling.html)
- Hermes 2 is described as the only new data-center-linked reactor under construction as of Oct 2026 (secondary; note that TerraPower's Kemmerer is also under construction, but it is utility/DOE-linked and later Meta-linked). — [Construction Review Online](https://constructionreviewonline.com/how-is-googles-10b-nuclear-reactors-project-going-to-power-its-ai-data-centers/)

### Inferences
- Realistic timeline: restarts (Palisades, Crane in 2027) and uprates deliver the first new nuclear MW for tech. First SMR or advanced-reactor power to grid is about 2030 (Hermes 2, Natrium). Multi-GW fleets (Meta 6.6 GW, Google 500 MW) are 2030–2035 roadmaps, not commercial reality.
- The 400 GW by 2050 target requires about 10 GW/yr of additions. Nothing in the 2026 pipeline approaches that rate.

### Gaps
- Amazon–X-energy (Energy Northwest "Cascade", Xe-100) 2026 status was not verified in this session.
- Could not confirm whether any DOE pilot reactor actually reached criticality by July 4, 2026.
- Financial terms of the Microsoft–Constellation PPA were not re-verified (widely reported as a 20-year PPA signed Sep 2024, but not sourced here).
- The NRC approval list for Oklo and X-energy should be confirmed directly at nrc.gov.

## 3. Fusion: private funding, CFS SPARC, Helion–Microsoft

### Takeaway
Private fusion funding hit a record $4.48B in the 12 months to July 2026 (+69% YoY), bringing the cumulative total to $14.24B (FIA 2026). No device has yet produced net electricity. CFS SPARC's first plasma has reportedly slipped to 2027, and Helion's 2028 Microsoft delivery target is widely seen as very aggressive.

### Cited Findings
- FIA *The Global Fusion Industry in 2026* (Jul 2026): $4.48B was raised in the past 12 months, a record and 69% above the prior year. The cumulative total is $14.24B across 56 surveyed companies, 28 of them US-based. All five companies with more than $1B in funding are in the US. — [FIA 2026 report PDF](https://www.fusionindustryassociation.org/wp-content/uploads/2026/07/FIA-Industry-report-2026_d9.pdf); [Energy Live News, Jul 22 2026](https://www.energylivenews.com/2026/07/22/fusion-sector-secures-record-4-48bn-in-funding/); [Physics World](https://physicsworld.com/a/private-investment-in-fusion-firms-jumps-by-4-5bn/)
- Major rounds include the CFS $863M Series B2 (Aug 2025) plus 2026 rounds for Inertia Enterprises, Helion and Proxima Fusion. — [Energy Live News](https://www.energylivenews.com/2026/07/22/fusion-sector-secures-record-4-48bn-in-funding/)
- The IAEA World Fusion Outlook 2026 cites more than $14B in cumulative private investment. — [FIA on IAEA Outlook](https://www.fusionindustryassociation.org/iaea-releases-2026-world-fusion-outlook/)
- CFS SPARC: reported nearly 80% complete in Aug 2026, with first plasma targeted for 2027 (originally 2025, later 2026). — [Discovery Alert, Oct 2026](https://discoveryalert.com/analysis/nuclear-fusion-commercialisation-unproven-october-2026/); [PDP Spectra](https://pdpspectra.com/blog/fusion-energy-2026-commonwealth-helion/)
- Helion: the Polaris prototype reached about 150 million °C (Feb 2026) but has shown no net electricity. Construction of the Orion plant in Malaga, WA began in July 2025, targeting at least 50 MWe to Microsoft in 2028, a timeline described by analysts as "extremely aggressive." — [TechCrunch, Feb 13 2026](https://techcrunch.com/2026/02/13/fusion-startup-helion-hits-blistering-temps-as-it-races-toward-2028-deadline/); [Discovery Alert](https://discoveryalert.com/analysis/nuclear-fusion-commercialisation-unproven-october-2026/)

### Inferences
- Fusion is a venture-scale bet with real capital ($14B cumulative) but no commercial reality. Scientific net-gain demos are plausible around 2027–2028, and grid-scale fusion is credibly a 2035+ story.
- If Helion misses 2028, the first PPA milestone in fusion slips, which will test investor patience.

### Gaps
- Could not retrieve the FIA survey's company-reported "first power to grid" timeline distribution.
- Public (government) fusion funding totals for 2026 were not captured.

## 4. Battery storage, enhanced geothermal (Fervo), transformers and transmission

### Takeaway
US grid batteries are in a record build: 18.9–20.2 GWh in Q2 2026 depending on source, with average duration rising to 3.5 h. Fervo's Cape Station delivered the world's first utility-scale enhanced-geothermal power (Sep 24, 2026), but only one 33 MW block of a 100 MW Phase I. Transformer and transmission shortages could not be quantified with fresh 2026 data in this session.

### Cited Findings
- SEIA/Benchmark (Q3 2026 outlook, Sep 1 2026): a record 20.2 GWh was installed in Q2 2026, bringing H1 2026 to 30.8 GWh (+23% YoY). Arizona contributed 6.2 GWh. The 2030 cumulative forecast is 683 GWh. — [Renewables Now](https://renewablesnow.com/news/us-battery-storage-installations-hit-record-20-2-gwh-in-q2-1300511/)
- ACP/Wood Mackenzie (Q3 2026 monitor): Q2 2026 installations were 5.4 GW / 18.9 GWh. GWh was up 17% YoY while GW was down 7%, and average duration rose from 2.8 h to 3.5 h. The forecast is 207 GW / 715 GWh cumulative by 2031. — [Wood Mackenzie press release](https://www.woodmac.com/press-releases/u.s.-energy-storage-market-posts-record-18.9-gwh-in-q2-as-longer-duration-systems-drive-growth); [ACP](https://cleanpower.org/news/usesm-q3-2026/)
- Fervo Cape Station (Beaver County, UT): first power on Sep 24, 2026, the first utility-scale EGS power anywhere. Phase I is about 100 MW (three 33 MW GeoBlocks), with GeoBlocks 2–3 expected in early 2027. About 900 MW of offtake is contracted, including Shell Energy. First power came ahead of the Q4 2026 guidance in Fervo's 10-Q. — [Fervo press release](https://fervoenergy.com/fervo-energy-achieves-first-power-at-cape-station-a-landmark-moment-for-the-future-of-enhanced-geothermal-systems/); [ThinkGeoEnergy](https://www.thinkgeoenergy.com/fervo-energy-reports-first-power-generation-at-cape-station-enhanced-geothermal-site-utah/); [mgrid analysis](https://mgrid.org/2026/09/27/fervo-first-power-cape-station-33-mw-geoblock-phase-i/)
- IEA *Electricity 2026* calls for major grid and flexibility investment to accommodate demand growth. — [IEA news release](https://www.iea.org/news/global-electricity-demand-is-set-to-grow-strongly-to-2030-underscoring-need-for-investments-in-grids-and-flexibility)

### Inferences
- Batteries are the fastest-deploying "firming" asset today and are commercial reality. EGS has crossed from pilot to first commercial MW, but scale (GW) is a 2028–2035 question.
- The two Q2 storage figures (18.9 vs 20.2 GWh) reflect different methodologies and should be presented as a range.

### Gaps
- No fresh 2026 data was retrieved on power transformer lead times or prices, or on transmission miles built. Wood Mackenzie and NREL have published on this, but nothing was verified in this session.
- BloombergNEF global storage figures were not captured.

## 5. Quantum computing: funding, hardware milestones, stocks, DARPA QBI, PQC deadlines

### Takeaway
Quantum is at an early commercial stage. McKinsey (Apr 2026) counts $12.6B in 2025 start-up investment (6.3x 2024) and more than $1B in 2025 QC revenue, rising to as much as $4.4B by 2028. IBM committed more than $10B over five years (Jun 2026) toward fault tolerance by 2029. DARPA QBI's final stage now includes six firms (Oct 2026). Pure-play quantum stocks trade at extreme sales multiples and are volatile. NIST IR 8547 was finalized in Oct 2026: quantum-vulnerable public-key crypto is deprecated after 2030 and disallowed after 2035.

### Cited Findings
- McKinsey Quantum Technology Monitor 2026 (Apr 2026): quantum start-up investment was $12.6B in 2025, 6.3x 2024, with 90% going to computing. The public-sector share of start-up funding fell from about one third in 2024 to 3% in 2025. QC company revenue exceeded $1B in 2025 and could reach up to $4.4B by 2028. The total quantum technology market is projected at $60–100B by 2035, of which QC is $43–71B. Some commentators question the $12.6B methodology. — [McKinsey QTM 2026](https://www.mckinsey.com/capabilities/mckinsey-technology/our-insights/mckinsey-quantum-technology-monitor-2026-a-commercial-tipping-point); [PostQuantum commentary](https://postquantum.com/industry-news/mckinsey-quantum-monitor-2026/)
- IBM (Jun 2, 2026): committed more than $10B to quantum over five years (R&D, manufacturing, M&A, ecosystem). It reports more than $1.1B in cumulative signed client contracts since 2017. Its roadmap targets the first fault-tolerant quantum computer (Starling) by 2029, with "quantum advantage" claims targeted for 2026. — [IBM Newsroom](https://newsroom.ibm.com/2026-06-02-ibm-commits-more-than-10-billion-to-quantum-computing,-funding-its-roadmap-from-todays-leading-systems-to-the-worlds-first-fault-tolerant-quantum-computers); [Denkstrom](https://denkstrom.org/en/goodnews/quantum-computing-ibm-google-race-2026/)
- Google: the Willow chip (Dec 2024) demonstrated below-threshold error correction, and the later "Quantum Echoes" result was presented as a verifiable advantage. Google also invested in QuEra (secondary). — [Quantum Security Defence](https://quantumsecuritydefence.com/quantum-news/quantum-computing-progress-2026-ibm-google/); [New Market Pitch](https://newmarketpitch.com/blogs/news/quantum-computing-who-is-ahead)
- Quantinuum: reported 48 error-corrected logical qubits and 99.9995% logical fidelity on Helios (Oct 2026), with 2025 revenue of about $30.9M (secondary, low-quality source, unverified). — [New Market Pitch](https://newmarketpitch.com/blogs/news/quantum-computing-who-is-ahead)
- US CHIPS Act quantum incentives: about $2.013B across nine firms (May 2026), including $1B for an IBM quantum foundry subsidiary (single secondary source, unverified). — [Tech Insider](https://tech-insider.org/quantum-computing-in-2026-from-laboratory-curiosity-to-practical-utility/)
- DARPA QBI: 11 companies entered Stage B in Nov 2025. In Oct 2026, Atom Computing, Diraq, IBM and IonQ advanced to Stage C, joining Microsoft and PsiQuantum, which entered via the predecessor US2QC program. Quantinuum, QuEra, Xanadu, Photonic, Nord Quantique, Quantum Motion and SQC reportedly remain in Stage B. The program goal is to verify whether utility-scale QC is possible by 2033. — [DARPA news 2026](https://www.darpa.mil/news/2026/four-more-teams-enter-quantum-benchmarking-initiative-final-stage); [HPCwire, Oct 7 2026](https://www.hpcwire.com/2026/10/07/atom-computing-diraq-ibm-and-ionq-advance-to-darpa-qbi-stage-c/); [R&D World](https://www.rdworldonline.com/darpas-quantum-benchmarking-push-can-a-useful-quantum-computer-exist-by-2033/)
- Stocks (2026): IonQ fell about 39% and D-Wave about 36% over the year to late Sep 2026, and two quantum stocks lost more than half their value YTD. In Jan 2026, IonQ, Rigetti and D-Wave sold off 10.9%, 18% and 18.9%. As of Aug 28, 2026, price-to-sales was about 69x for IonQ, 407x for Rigetti and 532x for D-Wave. Insiders were net sellers of about $863M over three years. — [24/7 Wall St, Sep 30 2026](https://247wallst.com/investing/2026/09/30/one-year-later-only-one-quantum-stock-call-paid-off-heres-what-changed/); [Motley Fool, Oct 20 2026](https://www.fool.com/investing/2026/10/20/ionq-rigetti-dwave-quantum-computing-shaking-wall-street-to-core-with-1-billion-warning/); [BigGo Finance](https://finance.biggo.com/news/4338d4a5-bbe5-47b7-a725-5ef8d698a800)
- IonQ fundamentals: Q2 2026 revenue was $80.1M (+287% YoY), and FY2026 guidance was raised to $280–290M. — [Motley Fool](https://www.fool.com/investing/2026/10/20/ionq-rigetti-dwave-quantum-computing-shaking-wall-street-to-core-with-1-billion-warning/)
- Skeptical view: Morningstar puts early commercialization 5–10 years away. — [Motley Fool, Jan 2026](https://www.fool.com/investing/2026/01/09/5-reasons-quantum-computing-stocks-crash-in-2026/)
- PQC: NIST IR 8547 was finalized on Oct 27, 2026. All quantum-vulnerable public-key algorithms (RSA, ECC, including RSA-3072 and P-256) are deprecated after 2030 and disallowed after 2035, with ML-KEM, ML-DSA and SLH-DSA as replacements. The 2035 date aligns with NSM-10. The 2024 draft had deprecated only 112-bit strength after 2030. — [CSA research note, Oct 30 2026](https://labs.cloudsecurityalliance.org/research/csa-research-note-nist-ir8547-pqc-transition-20261030-csa-st/); [Encryption Consulting](https://www.encryptionconsulting.com/nist-ir-8547-final-pqc-transition/)

### Inferences
- Commercial reality: about $1B in industry revenue (2025), mostly R&D, government and cloud access, while private valuations and public market caps run far ahead. Roadmap: IBM 2029 fault tolerance, DARPA 2033 utility-scale verification.
- The most certain near-term "quantum market" is PQC migration, which is driven by hard regulatory deadlines (2030/2035) whether or not a cryptographically relevant quantum computer arrives.
- Public-equity sentiment is bubble-prone. Valuations of 400–500x sales imply large downside if roadmaps slip.

### Gaps
- No reliable 2026 source on the scientific debate over Microsoft's Majorana 1 topological qubit. Critiques from 2025 exist but were not captured; a claim that "Microsoft will spend $10B on quantum" seen in one result was not verified and may confuse IBM's commitment.
- PsiQuantum 2026 funding and valuation, and its Brisbane/Chicago facility status, were not verified.
- Quantinuum figures come from a low-quality source; check against Quantinuum or Honeywell IR.
- Current share prices as of Nov 2026 were not reliably obtained.

## 6. Expert-consensus timelines and skeptical views (cross-cutting)

### Takeaway
Energy infrastructure is a "next big thing" with near-term commercial reality: demand, storage builds, nuclear restarts and first EGS power are all happening in 2026–2027. Advanced nuclear (about 2030+), fusion (2035+) and fault-tolerant quantum (2029–2033 roadmaps) remain roadmap-stage, and key schedules have already slipped.

### Cited Findings
- Demand: about half of US demand growth comes from data centers, and US data centers reach about 9.5–15.3% of electricity by 2030. — [IEA](https://iea.org/reports/electricity-2026/executive-summary); [LBNL 2025 update](https://www.rtoinsider.com/wp-content/uploads/2026/06/data-center-energy-usage-2025-update.pdf)
- SMR first commercial operation is about 2030 (Hermes 2), with NRC operating-license review of 18–24 months still pending. — [Yahoo/Kairos CTO](https://finance.yahoo.com/news/nuclear-needs-humility-kairos-power-115440258.html)
- Fusion: SPARC slipped 2025 → 2026 → 2027, and Helion's 2028 target is considered "extremely aggressive." — [Discovery Alert](https://discoveryalert.com/analysis/nuclear-fusion-commercialisation-unproven-october-2026/)
- Quantum: IBM targets fault tolerance by 2029, DARPA asks whether utility scale is possible by 2033, and Morningstar puts early commercialization 5–10 years out. — [IBM](https://newsroom.ibm.com/2026-06-02-ibm-commits-more-than-10-billion-to-quantum-computing,-funding-its-roadmap-from-todays-leading-systems-to-the-worlds-first-fault-tolerant-quantum-computers); [R&D World](https://www.rdworldonline.com/darpas-quantum-benchmarking-push-can-a-useful-quantum-computer-exist-by-2033/); [Motley Fool](https://www.fool.com/investing/2026/01/09/5-reasons-quantum-computing-stocks-crash-in-2026/)

### Inferences
- Ranking by commercial maturity (Nov 2026): grid/storage > gas and nuclear restarts > EGS > SMRs/advanced fission > quantum (pre-fault-tolerant revenue of about $1B) > fusion (pre-revenue).
- Energy investment is backed by contracted demand (PPAs, offtake) from hyperscalers, while quantum and fusion rely on venture and strategic capital ahead of revenue. That makes energy a nearer-term, lower-variance theme and quantum and fusion option-like bets.

### Gaps
- No formal expert survey (e.g., Global Risk Institute quantum threat timeline 2025/2026, FIA's company timeline survey) was retrieved in this session.
