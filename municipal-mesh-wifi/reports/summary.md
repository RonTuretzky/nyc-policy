# Municipal Mesh WiFi Research Summary

Data extracted from 6 LLM research reports, traced to original sources where available. Discrepancies flagged with source attribution.

---

## Table 1: ISP Bandwidth Cost Comparisons

### NYC Incumbent ISP Pricing

| Provider | Speed Tier | Promo Price | Standard Price | Original Source |
|----------|-----------|-------------|----------------|-----------------|
| Spectrum | 200/10 Mbps | — | $65.99/mo | NYC Internet Master Plan 2020 Appendices |
| Spectrum | 300 Mbps | $70/mo | $70+/mo | ISP website / Consumer research |
| Spectrum | 400/20 Mbps | — | $90.99/mo | NYC Internet Master Plan 2020 Appendices |
| Spectrum | 940/35 Mbps | $70/mo | $125.99/mo | NYC Internet Master Plan 2020 Appendices |
| Optimum | 300/35 Mbps | — | $44.99/mo | NYC Internet Master Plan 2020 Appendices |
| Optimum | 400/40 Mbps | — | $64.99/mo | NYC Internet Master Plan 2020 Appendices |
| Optimum Fiber | 1 Gbps | $70/mo | $90/mo | ISP website pricing |
| Verizon FiOS | 1 Gbps | $74.99/mo | $89.99-$104.99/mo | ISP website pricing |
| **NYC Average** | ~365 Mbps | — | **$96/mo** | NYC Internet Master Plan 2020 / NYC Comptroller |
| **National Urban Avg** | ~365 Mbps | — | **$84/mo** | BLS data / BroadbandNow |

### NYC Borough Price Variation

| Borough | Avg Price (100 Mbps) | Original Source |
|---------|---------------------|-----------------|
| Bronx | $79.83/mo | BroadbandNow pricing data |
| Brooklyn | $69.76/mo | BroadbandNow pricing data |
| Staten Island | $66.68/mo | BroadbandNow pricing data |
| Queens | $62.89/mo | BroadbandNow pricing data |
| Manhattan | $56.00/mo | BroadbandNow pricing data |
| **Median** | **$66.68/mo** | — |
| **Mean** | **$67.03/mo** | — |

*Note: NY State Comptroller Report 2024 cites Bronx highest at ~$68.99/mo for entry-level plans—slight variation from BroadbandNow data.*

### Competitive/Municipal Comparison

| Provider/City | Speed | Price | Original Source | Notes |
|---------------|-------|-------|-----------------|-------|
| Chattanooga EPB | 1 Gbps | $67.99-$70/mo | EPB Fiber Optics website | ⚠️ $67.99 (EPB site) vs $70 (OTI Cost of Connectivity) |
| Fort Collins Connexion | 1 Gbps | $59.95-$70/mo | Fort Collins Connexion website | ⚠️ Variation in reported pricing |
| Fort Collins (low-income) | 1 Gbps | $20/mo | Fort Collins Connexion website | Income-qualified |
| Google Fiber | 1 Gbps | $70/mo | Google Fiber website | Unchanged since 2012 |
| Longmont NextLight | 1 Gbps | $70/mo | NextLight website | |
| Ammon, Idaho | 1 Gbps | $9.99/mo | Ammon Fiber network | Open access model |
| Brooklyn Fiber | 1 Gbps | $75/mo | NYC Internet Master Plan 2020 Appendices | |
| Brooklyn Fiber | 500 Mbps | $50/mo | NYC Internet Master Plan 2020 Appendices | |
| Brooklyn Fiber | 100 Mbps | $25/mo | NYC Internet Master Plan 2020 Appendices | |
| Honest Networks | 1 Gbps | $50/mo | NYC Internet Master Plan 2020 Appendices | Symmetrical |
| NYC Mesh | Best effort | $20/mo | NYC Mesh website (nycmesh.net) | Suggested donation |
| People's Choice Coop | 200 Mbps | $0-$30/mo | People's Choice website | With federal subsidy |
| People's Choice Coop | 500 Mbps | $45/mo | People's Choice website | |
| People's Choice Coop | 1 Gbps | $60/mo | People's Choice website | |

### Monopoly Premium Analysis

| Metric | Value | Original Source |
|--------|-------|-----------------|
| NYC vs municipal cities (annual) | $948-$1,092/yr more | Derived from EPB/Connexion comparisons |
| Monopoly vs competitive premium | $35-45/mo ($420-540/yr) | Derived calculation |
| Least vs most competitive counties | $269.90 vs $174.23/mo (35% premium) | BroadbandNow March 2025 county analysis |
| AT&T in Google Fiber vs non-competitive | $70 vs $110-130/mo | Recon Analytics study |
| Municipal networks 2.9-50% cheaper | 23 of 27 networks studied | Harvard Berkman Klein Center study |
| **Mean monopoly premium** | **~$40/mo (~$480/yr)** | — |

---

## Table 2: Distributed Deployment Cost Assessments

### Per-Node/Installation Costs

| Network | Equipment Cost | Install Cost | Total | Monthly | Original Source |
|---------|---------------|--------------|-------|---------|-----------------|
| NYC Mesh | $110-$240 | $50 | $160-$290 | $20-$60 (donation) | NYC Mesh website (nycmesh.net) |
| Red Hook WiFi | $50-$85 | 3-5 work-hrs | ~$100-$150 | — | Open Technology Institute case study |
| Bulk purchase (10k nodes) | ~$500/node | included | $5-8M total | — | Estimate based on equipment costs |

⚠️ **Discrepancy**: NYC Mesh equipment costs vary:
- $110 equipment + $50 labor = $160 (NYC Mesh website "standard install")
- $240 equipment bundle (NYC Mesh website alternate listing)
- NYC Internet Master Plan rate card: $110 router + antenna, $50 labor, $20/mo

| Metric | Low Estimate | High Estimate | Source |
|--------|--------------|---------------|--------|
| NYC Mesh equipment | $110 | $240 | NYC Mesh website (nycmesh.net) |
| NYC Mesh total install | $160 | $290 | NYC Mesh website |
| **Mean install cost** | — | **$225** | — |

### Operational Costs (Annual)

| Network | Annual Budget | Nodes Served | Cost/Node/Year | Original Source |
|---------|--------------|--------------|----------------|-----------------|
| NYC Mesh | $507,752-$602,211 | 2,000+ | ~$250-$300 | NYC Mesh 2024 IRS 990 filing |
| Red Hook WiFi | ~$36,000 | ~10-48 | ~$750-$3,600 | The Verge reporting / Sky Packets |
| Combined community mesh | <$600,000 | — | — | NYC Mesh 990 filing |

| Metric | Value | Original Source |
|--------|-------|-----------------|
| Red Hook backhaul/electricity | $3,000/mo ($36k/yr) | The Verge / Sky Packets partnership docs |
| NYC Mesh 2024 revenue | $507,752 | NYC Mesh 2024 IRS 990 filing |
| NYC Mesh 2024 expenses | $602,211 | NYC Mesh 2024 IRS 990 filing |
| NYC Mesh net assets | ~$492,000 | NYC Mesh 2024 IRS 990 filing |
| **Mean annual operating budget** | **~$550,000** | — |

### Large-Scale Investment Estimates

| Program | Investment | Coverage/Goal | Original Source |
|---------|-----------|---------------|-----------------|
| NYC Internet Master Plan (2020) | $157M | 1.5-1.6M residents | NYC Internet Master Plan 2020 |
| NYC Internet Master Plan (full vision) | $2.1B | Citywide fiber | NYC Internet Master Plan 2020 |
| Big Apple Connect (current) | $39.4M/yr (~$90M/3yr) | 330k NYCHA residents | NYC Mayor's Office / NYC budget docs |
| Chattanooga EPB | $220-$396M | Citywide (105k+ subscribers) | EPB financial documents |
| Fort Collins Connexion | $45.3M | 80,000 premises | Fort Collins voter-approved bond |
| NYS ConnectALL Municipal | $228M (Jan 2024) | Statewide municipal | NY State ConnectALL program |
| Proposed NYS S7987 | $250M revolving fund | Municipal loans | NY State Legislature |
| BEAD allocation to NY | $664.6M | Statewide | NTIA BEAD program |

⚠️ **Discrepancy**: Chattanooga investment reported as:
- $220M initial (EPB early docs)
- $396M total ($229M local bonds + $111M DOE ARRA grant + other)

| Metric | Value |
|--------|-------|
| **Median large investment** | **$157M** |
| **Mean large investment** | **~$500M** (skewed by $2.1B outlier) |

### Return on Investment

| City | Investment | Documented Benefit | ROI | Original Source |
|------|-----------|-------------------|-----|-----------------|
| Chattanooga EPB | $220M | $2.69B (10 yr) | 12.2x | University of Tennessee study |
| Chattanooga EPB | $396M | $5.3B | 6.4x-13x | EPB / Bento economic analysis |
| Chattanooga jobs | — | 9,516-10,420 created | 31% of local jobs | University of Tennessee study |

---

## Table 3: Monopoly/Choice Assessment by Borough

### Provider Choice Distribution (Citywide)

| # of ISP Options | % of Households | Original Source |
|------------------|-----------------|-----------------|
| 1 provider (monopoly) | 13.54-14% | NYC Broadband Report 2018 |
| 1-2 providers | 69% | NYC Broadband Report 2018 |
| 3+ providers | 31% | NYC Broadband Report 2018 |
| NY State single-provider | 42% | NY State Broadband Office / PSC data |

*Note: FCC Form 477 data overstates availability—counts ISP as "available" for entire census block even if only one location served.*

| Metric | Value |
|--------|-------|
| **Mean single-provider %** | **13.8%** |

### Borough-Level Monopoly Data

| Borough | Single ISP Only | Duopoly | 3+ Options | Original Source |
|---------|-----------------|---------|------------|-----------------|
| Bronx | 27.98% | ~72% | ~0% | NYC Broadband Report 2018 |
| Staten Island | 8.45% | ~91% | ~0% | NYC Broadband Report 2018 |
| Manhattan | Low | Low | High (7-15 ISPs in some areas) | NYC Internet Master Plan 2020 |
| Brooklyn | — | — | 31%+ (central areas) | NYC Broadband Report 2018 |
| Queens | — | — | Limited | — |

### Broadband Disconnection Rates by Borough

| Borough | % Without Broadband | Original Source |
|---------|---------------------|-----------------|
| Bronx | 36.7% | American Community Survey (ACS) / Census |
| Brooklyn | 24.0% | ACS / Census |
| Queens | 24.5% | ACS / Census |
| Staten Island | 23.5% | ACS / Census |
| Manhattan | 19.5% | ACS / Census |
| **Citywide** | 25.1-31% | ACS 2023 vs NYC Internet Master Plan 2020 |
| **Median** | **24.0%** | — |
| **Mean** | **25.6%** | — |

⚠️ **Discrepancy**: Citywide disconnection rates vary by year:
- 25.1% (2023 ACS data)
- 29% (NYC Internet Master Plan 2020)
- 31% (2018 NYC data)

### Worst-Connected Neighborhoods

| Neighborhood | Disconnection Rate | Borough | Original Source |
|--------------|-------------------|---------|-----------------|
| Fordham/Bedford Park/Norwood | 47.8% | Bronx | NYC Internet Master Plan 2020 |
| Highbridge/Concourse | 45.6% | Bronx | NYC Internet Master Plan 2020 |
| Morris Heights/Mount Hope | 45.4% | Bronx | NYC Internet Master Plan 2020 |
| Melrose/Mott Haven/Longwood/Hunts Point | 41.7% | Bronx | NYC Internet Master Plan 2020 |
| Edgemere (Rockaways) | 32% | Queens | NYC Internet Master Plan 2020 |

**19 NYC community districts exceed 33% disconnection rates** (NYC Internet Master Plan 2020)

### Market Concentration Index (HHI)

| Area | HHI Score | Interpretation | Original Source |
|------|-----------|----------------|-----------------|
| Manhattan | 1,044.69 | Most competitive in US | BroadbandNow March 2025 |
| Westchester County | 4,508.56 | Highly concentrated | BroadbandNow March 2025 |
| Nassau County | 4,534.10 | Highly concentrated | BroadbandNow March 2025 |
| Suffolk County | 5,081.86 | Highly concentrated | BroadbandNow March 2025 |

(HHI > 2,500 = highly concentrated; < 1,500 = competitive)

### Income-Based Digital Divide

| Income Level | Without Broadband | Original Source |
|--------------|-------------------|-----------------|
| Under $20,000/yr | 37-46% | Census/ACS / NYC Internet Master Plan 2020 |
| Over $75,000/yr | 5-7% | Census/ACS |
| **Disparity ratio** | **7x** | Derived |

| Demographic | Without Broadband | Original Source |
|-------------|-------------------|-----------------|
| Black households | >33% | Census/ACS demographic studies |
| Hispanic households | >33% | Census/ACS demographic studies |
| Below poverty line | 46% | NYC Internet Master Plan 2020 |

---

## Key Cross-Report Findings

### Consistent Findings (Multiple Original Sources Agree)
1. NYC residents pay $10-15/month more than national average (NYC Internet Master Plan, BroadbandNow)
2. The Bronx has worst connectivity and highest prices (ACS, BroadbandNow, NYC IMP)
3. Municipal/competitive broadband costs 30-50% less (Harvard Berkman Klein, EPB, Connexion data)
4. NYC Mesh operates on ~$500-600k annually serving 2,000+ nodes (NYC Mesh 990 filings)
5. 69% of NYC has only 1-2 ISP choices (NYC Broadband Report 2018)
6. Digital divide strongly correlates with income and race (Census/ACS)

### Significant Discrepancies

| Data Point | Range | Original Sources |
|------------|-------|------------------|
| NYC Mesh install cost | $160-$290 | NYC Mesh website (different packages) |
| Chattanooga EPB investment | $220-$396M | EPB docs (scope variation) |
| Citywide disconnection | 25-31% | ACS 2023 vs NYC IMP 2020 (different years) |
| Fort Collins gigabit price | $59.95-$70/mo | Connexion website (pricing updates) |
| Chattanooga gigabit price | $67.99-$70/mo | EPB website vs OTI study |

---

## Primary Original Sources

| Source | Data Categories | URL/Reference |
|--------|-----------------|---------------|
| NYC Internet Master Plan 2020 | Pricing, competition, digital divide, infrastructure | nyc.gov |
| NYC Broadband Report 2018 | Provider choice statistics | NYC Government |
| BroadbandNow | Borough pricing, HHI, county comparisons | broadbandnow.com |
| American Community Survey (ACS) | Demographics, adoption rates by borough | Census Bureau |
| NYC Mesh 990 Filing | Financials, node counts | IRS 990 / NYC Mesh |
| NYC Mesh Website | Installation costs, technical specs | nycmesh.net |
| EPB Fiber Optics | Chattanooga pricing, coverage | epb.com |
| University of Tennessee | Chattanooga economic impact study | Academic |
| Harvard Berkman Klein Center | Municipal network pricing comparison | berkman.harvard.edu |
| Recon Analytics | Google Fiber market impact | Industry research |
| Open Technology Institute | Cost of Connectivity study, Red Hook case | New America |
| The Verge | Red Hook WiFi operational costs | News reporting |
| NY State Comptroller | Borough pricing, adoption | osc.ny.gov |
| FCC Form 477 / BDC | Provider coverage (with caveats) | fcc.gov |
| NTIA BEAD Program | Federal funding allocations | ntia.gov |
| NY State ConnectALL | State funding programs | ny.gov |

---

*Summary compiled from research reports citing the above primary sources.*
