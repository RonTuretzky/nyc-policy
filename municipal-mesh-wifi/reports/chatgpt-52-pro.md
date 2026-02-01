Here’s a research-backed, proposal-oriented synthesis you can drop into a memo to Mayor Mamdani—plus some strategic recommendations on how to fund decentralized connectivity without accidentally recreating the same dependency structures we’re trying to escape.


Big picture framing for a municipal mesh program
A citywide “mesh WiFi” program succeeds or fails on one non-sexy point: mesh is the “last 500–1500 meters,” not the whole internet. The real question is whether the City builds (or buys) shared backhaul + rooftop/pole access + resilient power so community networks can scale sustainably.

That leads to a practical hybrid model:

Community mesh for last-mile distribution (fast to deploy, low capex per connection, locally governable)
Municipal “core” for backhaul + interconnection (stable opex, redundancy, bulk purchasing power, citywide equity targets)

This framing matches the City’s own “open access / neutral host” thinking from the Internet Master Plan. (New York City Government)


Existing community/mesh networks in the city: what we can learn (and fund)
1) Red Hook WiFi: resilience + local stewardship, but fragile funding
What it is / why it matters

A community-built mesh that became a communications lifeline during and after Hurricane Sandy, when commercial networks failed.
Operated by Red Hook Initiative with a “digital stewards” approach (local maintenance + training pipeline). (redhookinitiative.org)

Cost signals we can actually cite

Early deployment economics (from the Open Technology Institute case study):

Hardware: routers in the $50–$85 range (at that time)
Labor: roughly 3–5 work-hours per router installation
Bandwidth: in that deployment phase, bandwidth was donated by a local ISP, and routers were loaned to partners (These numbers are older, but they’re still useful as order-of-magnitude for public budgeting.)

Later expansion funding:

A $1M expansion (adding 48 new hotspots) funded via **U.S. Department of Housing and Urban Development Community Development Block Grant disaster recovery funding; hotspots planned with solar panels for outage resilience. (Patch)

Ongoing operating costs (critical for municipal planning):

When grant funding dried up, the network’s operator handed operations to **Sky Packets, which agreed to manage roughly $3,000/month in data + electrical costs and routine maintenance. (The Verge)

Scale / impact claims

The org reports “more than 7,000 residents” able to access free/reliable internet via the network (impact-report framing, not the same as “subscribers,” but still useful). (redhookinitiative.org)

Organizational risks (and what they teach us)

Grant cliff risk is existential: the network’s handoff to a private operator was explicitly driven by the end of a grant stream. (The Verge)
Governance drift risk: once operations move to a private firm (even a friendly one), priorities can shift from community resilience to business survivability.
Opex is the choke point: $3k/month is not huge in city terms—meaning the City could stabilize systems like this cheaply if it chooses to fund ongoing operating costs, not just ribbon-cutting capex.

Implication for a Mamdani proposal

If the City wants resilient neighborhood networks, it should create multi‑year operating support (internet transit + power + maintenance) tied to democratic governance + open access principles, rather than short grants that force eventual privatization.


2) NYC Mesh: low per-connection cost, volunteer strengths, scaling constraints
What it is

A community-owned network that connects people building-to-building via rooftop radios; it has explicit “network commons” values and is designed to expand by adding nodes. (NYC Mesh)

What it costs (member-facing, which matters for budgeting subsidies) From NYC Mesh’s own published installation/payment info:

Typical installation costs are often around $250, with cheaper install paths depending on building type (e.g., apartment/window installs). (NYC Mesh)

A “standard connection” includes a hardware bundle with about $240 worth of equipment (their stated equipment cost), and they suggest a $20/month donation for the standard connection. (NYC Mesh)

The City’s Internet Master Plan appendices also list NYC Mesh pricing in a “rate card” style:

$20/month optional contribution
$50 one-time “labor” charge
$110 one-time “WiFi router + rooftop antenna” charge (New York City Government) (Different NYC Mesh pages describe costs differently; in a municipal partnership you’d want a single standardized “City-supported install package.”)

Operational risks we should be honest about

Volunteer capacity + key-node fragility: NYC Mesh itself has documented that losing a major node can knock many people offline, requiring emergency reroutes and community mobilization. (NYC Mesh)
Building access risk: rooftop permission is political real estate; it’s not guaranteed and it can disappear.
Backhaul dependence: mesh needs reliable upstream connections; if upstream links are consumer-grade or donated, reliability becomes uneven.

Efficiency question: fund them vs build a municipal core? A clean way to present this to Mayor Mamdani:

Funding NYC Mesh directly is the fastest way to connect new households cheaply (subsidize installs; underwrite upstream links; pay for organizers/tech stewards).
But relying on a volunteer-led network alone to solve citywide access is structurally unfair: it makes working-class connectivity depend on uncompensated labor and precarious rooftop arrangements.

So: fund NYC Mesh and build municipal core infrastructure that makes community networks less precarious. The City can “socialize the hard part” (access to rooftops/poles, backhaul, resilient power, fiber where needed) while keeping last-mile governance community-rooted.


Citywide ISP landscape: who controls access, and where monopoly/duopoly still rules
Who the major providers are (fixed broadband)
A practical list to use in the proposal:

Cable incumbents: **Spectrum and **Optimum (plus smaller cable footprints like **Astound Broadband)
Fiber: **Verizon (FiOS footprint is not uniform)
Building/MDU challengers (limited footprint): **Honest Networks, **Brooklyn Fiber, **Starry Internet
Community/public-ish access layer: **LinkNYC (important, but not a substitute for stable home broadband)

(Your proposal can treat the “challengers” as proofs that better pricing is possible when real competition exists.)
How much of the city has limited choice (and how “monopolized” it is)
The City’s own broadband report is blunt:

69% of households have only 1 or 2 choices of broadband providers. (New York City Government)

13.54% of households have only 1 ISP option (i.e., functionally monopolized). (New York City Government)

Provider choice is also extremely uneven by borough (same table):

Bronx: 27.98% of households reported with only 1 ISP
Staten Island: 8.45% with only 1 ISP, but overwhelmingly “2 ISP” areas (duopoly)
Citywide: 31.02% reported with 3+ ISPs (with big concentration in Manhattan/Brooklyn) (New York City Government)

Two crucial caveats you should include (to preempt pushback):

The report emphasizes Federal Communications Commission Form 477 limitations: an ISP can be counted as “available” for a whole census block even if only one location can actually be served—so “choice” is often overstated. (New York City Government)
Adoption (the “digital divide” isn’t just infrastructure—it’s affordability)
The City previously reported 31% of households lacked a home broadband subscription (2018 framing). (New York City Government)
A newer state-level analysis found that one in four households had no cable/fiber/DSL subscription as of 2023 (availability is high; adoption lags). (osc.ny.gov)


The “rent”: what monopoly/duopoly costs New Yorkers in pricing
Apples-to-apples inside NYC (best evidence we have in one place)
The Internet Master Plan appendices compile “month-to-month” offerings (dated, but still a strong structured comparison):

Incumbent cable (examples)

Spectrum month-to-month listed as:

200/10 at $65.99
400/20 at $90.99
940/35 at $125.99 (New York City Government)

Optimum listed as:

300/35 at $44.99
400/40 at $64.99 (New York City Government)

Competitive/challenger offerings (limited footprint, but revealing)

Honest Networks listed at $50 for symmetrical 1 Gig (“one price,” no contract). (New York City Government)
Brooklyn Fiber listed at $75 for 1 Gig (and $50 for 500 Mbps; $25 for 100 Mbps). (New York City Government)
NYC Mesh listed at $20/month optional contribution with low one-time charges. (New York City Government)

What this implies (you can put this directly in a proposal)

If we take Spectrum’s gig-tier price ($125.99) versus:

Brooklyn Fiber’s gig ($75) → “competition discount” ≈ $50.99/month
Honest’s gig ($50) → “competition discount” ≈ $75.99/month (New York City Government) This is a concrete way to talk about monopoly/duopoly rent: tens of dollars per month per household for comparable speeds when real alternatives exist.
Cross-metro comparison (the cleanest cited “apples-to-apples” line)
A prior NYC Comptroller report (building on an Open Technology Institute “Cost of Connectivity” comparison) highlighted that consumers in places like Kansas City and Chattanooga could access 1 gigabit for under $70/month, while NYC’s fastest offering at the time was far more expensive and slower. (NYC Comptroller Mark Levine) And OTI’s later work again flags New York as among the more expensive U.S. cities in international comparisons. (New America)

How to handle the “that data is old” critique Say this explicitly in the proposal:

The exact dollar figures change year to year, but the structural pattern is stable: where competition is thin, prices are higher and adoption lags.
The City should update the price comparison annually using a transparent method (e.g., address-level offer scraping like The Markup data used in a Federal Reserve Bank of New York affordability study). (Federal Reserve Bank of New York)


Advantages of decentralized internet in NYC beyond “cheaper access”
1) Disaster resilience and “graceful degradation”
Red Hook’s experience shows mesh can keep local communications working even when upstream internet is down—especially when combined with resilient power (solar/battery). (Patch)
2) Community governance + skill-building (jobs pipeline, not charity)
The “digital stewards” model trains residents to install/maintain networks—turning connectivity into workforce development and community capacity. (Patch)
3) Anti-monopoly leverage
Even partial mesh coverage creates credible outside options that pressure incumbents on price and service terms (and gives City Hall bargaining power).
4) Privacy and civic integrity
The City’s broadband report warns that, absent strong privacy rules, ISPs can collect and monetize sensitive user data; community/municipal networks can set different norms (data minimization, no ad-tech). (New York City Government) (You can frame this as “digital self-determination.”)
5) Local economic multipliers
Money spent on community network maintenance stays local (stipends, co-op jobs, training), rather than extracting rents to national monopolies.


What Mayor Mamdani can contribute materially (not just rhetorically)
Think of these as “city superpowers” that community networks cannot do alone:
1) Rooftops, poles, and right-of-way as public commons
Create a fast path for siting antennas on:

municipal buildings (schools, libraries, firehouses, clinics)
public housing rooftops
select street furniture/poles (where safe/appropriate)

Standardize permits + insurance + engineering templates so community groups aren’t reinventing bureaucracy per building.
2) A municipal “backhaul spine” (open access / neutral host)
The Internet Master Plan explicitly prioritizes shared infrastructure that multiple operators can use (“open access / neutral host”). (New York City Government) Key point: if the City funds shared backhaul, it can support multiple last-mile models simultaneously: co-ops, nonprofit mesh, small MWBEs, etc.
3) Pay for the boring OPEX
Red Hook’s story makes this lesson unavoidable:

A few thousand dollars a month in upstream + power can decide whether a community network stays community-controlled or gets handed off. (The Verge) So the City should budget:
upstream internet transit (ideally multi-provider)
colocation / safe equipment rooms where needed
power + battery backup for critical nodes
maintenance staffing stipends (not only volunteers)
4) A procurement + standardization layer
Bulk-buy radios/routers and offer them as a city-subsidized “install kit.”
Set interoperability standards so NYC Mesh-like networks, Red Hook-style hotspot meshes, and building fiber ISPs can interconnect cleanly.
5) A democratic governance wrapper
If this is going to be Mamdani-era public infrastructure, don’t bury the governance:

Neighborhood network boards / participatory budgeting for expansion targets
A public “Network Commons License” requirement for City-funded last-mile nodes
Transparent reporting (uptime, speeds, subscription/adoption, complaint resolution)


Should the City fund existing orgs, or build a municipal core?
I’d frame it as a 3-part answer:
Fund existing community networks when:
the goal is fast deployment and trusted local stewardship
the City can “buy down” install cost per household (NYC Mesh-style) and stabilize upstream links
governance is demonstrably community-rooted (digital stewards, local accountability)
Build municipal core infrastructure when:
the goal is citywide equity (not volunteer-capacity-dependent)
you need shared backhaul and site access at scale
you want to avoid vendor lock-in and preserve bargaining power
Integrate them with a “public wholesaler” model
City invests in open access backhaul; community networks and small ISPs compete/cooperate on last-mile.
This aligns with the City’s own open access orientation. (New York City Government)


What you might be missing (and what I’d add)
1) The hardest equity problem is MDU/building-level gatekeeping
Even when a neighborhood “has options,” a specific building may be effectively monopolized. Your proposal should include:

“Right to receive broadband” style rules for building owners
pro-tenant transparency (disclose existing ISP deals, wiring access, rooftop access)
2) Mesh ≠ indoor service quality by default
Mesh can be incredible for backhaul + bridging + public space coverage, but indoor apartment penetration can be uneven. A realistic plan includes:

rooftop-to-building backhaul + managed indoor Wi-Fi distribution (or fiber-to-building where feasible)
a device + digital literacy component (or you’ll fund access that people can’t fully use)
3) Avoid recreating surveillance infrastructure
Make it explicit:

no ad-tech monetization
minimal logging
strong encryption defaults
community oversight on any data retention
4) Budget lines you must name (or the plan will fail in year 2)
upstream transit + redundancy
maintenance labor (paid)
insurance + replacements (radios get stolen, fried, or misaligned)
resilient power for critical nodes
5) Policy timing: the affordable broadband floor is shifting
New York’s Affordable Broadband Act regime (low-cost plan requirements) changes the “baseline” for affordability politics, but it doesn’t solve:

quality
building gatekeeping
neighborhood resilience
privacy
democratic control (Reuters)


Concrete proposal elements you can lift into a memo
If I were drafting the “Mamdani Municipal Mesh + Open Access” plan structure, I’d pitch:

Neighborhood Mesh Accelerator Fund
City pays for install kits + stipends for local tech stewards
Prioritize census tracts with lowest adoption / highest poverty
Municipal Backhaul + Rooftop Commons Program
City-funded backhaul nodes at public buildings
Standard rooftop/pole agreements and fast permits
Resilience-First Hotspot Mesh
Solar/battery-backed hotspots at community anchors (modeled on Red Hook expansion approach) (Patch)
Interconnection + “Network Commons” governance
Require open standards + interop + community governance for anything City-funded
Annual “Broadband Rent” report
Publish a transparent apples-to-apples price/speed comparison by neighborhood to quantify extraction and justify continued public buildout (tie to affordability + adoption metrics). (Federal Reserve Bank of New York)



If you want, I can also help you turn this into a tight 2–3 page “Mayor-ready” brief (problem → opportunity → plan → budget categories → wins in first 100 days), but the core research and argument structure above should already be usable as the spine of your proposal.
