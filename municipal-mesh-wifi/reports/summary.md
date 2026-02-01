# Municipal Mesh WiFi Research Summary

Data extracted from 6 LLM research reports. Where sources disagree, discrepancies are flagged with source attribution.

---

## Table 1: ISP Bandwidth Cost Comparisons

### NYC Incumbent ISP Pricing

| Provider | Speed Tier | Promo Price | Standard Price | Source(s) |
|----------|-----------|-------------|----------------|-----------|
| Spectrum | 200/10 Mbps | — | $65.99/mo | ChatGPT-Pro |
| Spectrum | 300 Mbps | $70/mo | $70+/mo | ChatGPT-DR-02 |
| Spectrum | 400/20 Mbps | — | $90.99/mo | ChatGPT-Pro |
| Spectrum | 940/35 Mbps | $70/mo | $125.99/mo | ChatGPT-Pro, Claude-02 |
| Optimum | 300/35 Mbps | — | $44.99/mo | ChatGPT-Pro |
| Optimum | 400/40 Mbps | — | $64.99/mo | ChatGPT-Pro |
| Optimum Fiber | 1 Gbps | $70/mo | $90/mo | Claude-02 |
| Verizon FiOS | 1 Gbps | $74.99/mo | $89.99-$104.99/mo | Claude-02 |
| **NYC Average** | ~365 Mbps | — | **$96/mo** | ChatGPT-DR-01, ChatGPT-DR-02 |
| **National Urban Avg** | ~365 Mbps | — | **$84/mo** | ChatGPT-DR-01, ChatGPT-DR-02 |

### NYC Borough Price Variation

| Borough | Avg Price (100 Mbps) | Source(s) |
|---------|---------------------|-----------|
| Bronx | $79.83/mo | Claude-01, Claude-02 |
| Brooklyn | $69.76/mo | Claude-02 |
| Staten Island | $66.68/mo | Claude-02 |
| Queens | $62.89/mo | Claude-02 |
| Manhattan | $56.00/mo | Claude-02 |
| **Median** | **$66.68/mo** | — |
| **Mean** | **$67.03/mo** | — |

### Competitive/Municipal Comparison

| Provider/City | Speed | Price | Source(s) | Notes |
|---------------|-------|-------|-----------|-------|
| Chattanooga EPB | 1 Gbps | $67.99-$70/mo | Claude-01, Claude-02, ChatGPT-DR-02, ChatGPT-Pro | ⚠️ Range: $67.99 (Claude-02) to $70 (ChatGPT-DR-02) |
| Fort Collins Connexion | 1 Gbps | $59.95-$70/mo | Claude-01, Claude-02 | ⚠️ $59.95 (Claude-02) vs $70 (Claude-01) |
| Fort Collins (low-income) | 1 Gbps | $20/mo | Claude-01 | Income-qualified |
| Google Fiber | 1 Gbps | $70/mo | Claude-01, ChatGPT-DR-02, ChatGPT-Pro | Consistent |
| Longmont NextLight | 1 Gbps | $70/mo | Claude-01 | |
| Ammon, Idaho | 1 Gbps | $9.99/mo | Claude-01 | Open access model |
| Brooklyn Fiber | 1 Gbps | $75/mo | ChatGPT-Pro | |
| Brooklyn Fiber | 500 Mbps | $50/mo | ChatGPT-Pro | |
| Brooklyn Fiber | 100 Mbps | $25/mo | ChatGPT-Pro | |
| Honest Networks | 1 Gbps | $50/mo | ChatGPT-Pro | Symmetrical |
| NYC Mesh | Best effort | $20/mo | Multiple | Suggested donation |
| People's Choice Coop | 200 Mbps | $0-$30/mo | ChatGPT-DR-02 | With federal subsidy |
| People's Choice Coop | 500 Mbps | $45/mo | ChatGPT-DR-02 | |
| People's Choice Coop | 1 Gbps | $60/mo | ChatGPT-DR-02 | |

### Monopoly Premium Analysis

| Metric | Value | Source(s) |
|--------|-------|-----------|
| NYC vs municipal cities (annual) | $948-$1,092/yr more | Claude-01 |
| Monopoly vs competitive premium | $35-45/mo ($420-540/yr) | Claude-02 |
| Least vs most competitive counties | $269.90 vs $174.23/mo (35% premium) | Claude-01 |
| AT&T in Google Fiber vs non-competitive | $70 vs $110-130/mo | Claude-02 |
| **Mean monopoly premium** | **~$40/mo (~$480/yr)** | — |

---

## Table 2: Distributed Deployment Cost Assessments

### Per-Node/Installation Costs

| Network | Equipment Cost | Install Cost | Total | Monthly | Source(s) |
|---------|---------------|--------------|-------|---------|-----------|
| NYC Mesh | $110-$240 | $50 | $160-$290 | $20-$60 (donation) | ChatGPT-DR-01, ChatGPT-Pro, Claude-01, Claude-02, Grok |
| Red Hook WiFi | $50-$85 | 3-5 work-hrs | ~$100-$150 | — | ChatGPT-DR-01, ChatGPT-Pro, Grok |
| Bulk purchase (10k nodes) | ~$500/node | included | $5-8M total | — | ChatGPT-DR-01 |

⚠️ **Discrepancy**: NYC Mesh equipment costs vary from $110 (ChatGPT-Pro) to $240 (ChatGPT-DR-01, Grok)

| Metric | Low Estimate | High Estimate | Source(s) |
|--------|--------------|---------------|-----------|
| NYC Mesh equipment | $110 | $240 | ChatGPT-Pro vs ChatGPT-DR-01/Grok |
| NYC Mesh total install | $160 | $290 | Claude-01/02 vs ChatGPT-DR-01 |
| **Mean install cost** | — | **$225** | — |
| **Median install cost** | — | **$225** | — |

### Operational Costs (Annual)

| Network | Annual Budget | Nodes Served | Cost/Node/Year | Source(s) |
|---------|--------------|--------------|----------------|-----------|
| NYC Mesh | $500,000-$602,211 | 2,000+ | ~$250-$300 | Claude-01, Claude-02 |
| Red Hook WiFi | ~$36,000 | ~10-48 | ~$750-$3,600 | ChatGPT-DR-01, ChatGPT-Pro |
| Combined community mesh | <$600,000 | — | — | Claude-01 |

⚠️ **Discrepancy**: Red Hook node count varies (10 current vs 48 at expansion peak)

| Metric | Value | Source(s) |
|--------|-------|-----------|
| Red Hook backhaul/electricity | $3,000/mo ($36k/yr) | ChatGPT-DR-01, ChatGPT-Pro, Grok |
| NYC Mesh 2024 revenue | $507,752 | Claude-01, Claude-02 |
| NYC Mesh 2024 expenses | $602,211 | Claude-01, Claude-02 |
| NYC Mesh net assets | ~$492,000 | Claude-01 |
| **Mean annual operating budget** | **~$550,000** | — |

### Large-Scale Investment Estimates

| Program | Investment | Coverage/Goal | Source(s) |
|---------|-----------|---------------|-----------|
| NYC Internet Master Plan (2020) | $157M | 1.5-1.6M residents | ChatGPT-DR-01, ChatGPT-DR-02, ChatGPT-Pro |
| NYC Internet Master Plan (full) | $2.1B | Citywide fiber | Claude-01 |
| Big Apple Connect (current) | $39.4M/yr (~$90M/3yr) | 330k NYCHA residents | Claude-01, Claude-02 |
| Chattanooga EPB | $220-$396M | Citywide | Claude-01, Claude-02 |
| Fort Collins Connexion | $45.3M | 80,000 premises | Claude-01 |
| NYS ConnectALL Municipal | $228M | Statewide municipal | Claude-01 |
| Proposed NYS S7987 | $250M revolving fund | Municipal loans | Claude-01 |
| Recommended hybrid approach | $2-3M/yr | — | Claude-02 |

⚠️ **Discrepancy**: Chattanooga investment reported as $220M (Claude-02) vs $396M (Claude-01). The $396M figure includes $229M bonds + $111M DOE grant + other costs.

| Metric | Value |
|--------|-------|
| **Median large investment** | **$157M** |
| **Mean large investment** | **~$500M** (skewed by $2.1B outlier) |

### Return on Investment

| City | Investment | Documented Benefit | ROI | Source |
|------|-----------|-------------------|-----|--------|
| Chattanooga EPB | $396M | $5.3B | 6.4x (13x per Claude-02) | Claude-01 |
| Chattanooga EPB | $220M | $2.69B | 12.2x | Claude-02 |

⚠️ **Discrepancy**: Different investment/benefit figures but both show strong positive ROI

---

## Table 3: Monopoly/Choice Assessment by Borough

### Provider Choice Distribution (Citywide)

| # of ISP Options | % of Households | Source(s) |
|------------------|-----------------|-----------|
| 1 provider (monopoly) | 13.54-14% | ChatGPT-DR-01, ChatGPT-Pro |
| 1-2 providers | 69% | ChatGPT-DR-01, ChatGPT-Pro |
| 3+ providers | 31% | ChatGPT-Pro |
| NY State single-provider | 42% | Claude-02 |

| Metric | Value |
|--------|-------|
| **Mean single-provider %** | **13.8%** |

### Borough-Level Monopoly Data

| Borough | Single ISP Only | Duopoly | 3+ Options | Source(s) |
|---------|-----------------|---------|------------|-----------|
| Bronx | 27.98% | ~72% | ~0% | ChatGPT-Pro, ChatGPT-DR-01 |
| Staten Island | 8.45% | ~91% | ~0% | ChatGPT-Pro, ChatGPT-DR-01 |
| Manhattan | Low | Low | High (7-15 ISPs in some areas) | ChatGPT-DR-01, ChatGPT-DR-02 |
| Brooklyn | — | — | 31%+ (central areas) | ChatGPT-Pro |
| Queens | — | — | Limited | — |

### Broadband Disconnection Rates by Borough

| Borough | % Without Broadband | Source(s) |
|---------|---------------------|-----------|
| Bronx | 36.7% | Claude-01, Claude-02 |
| Brooklyn | 24.0% | Claude-02 |
| Queens | 24.5% | Claude-02 |
| Staten Island | 23.5% | Claude-02 |
| Manhattan | 19.5% | Claude-02 |
| **Citywide** | 25.1-31% | Claude-01, ChatGPT-DR-01, ChatGPT-DR-02 |
| **Median** | **24.0%** | — |
| **Mean** | **25.6%** | — |

⚠️ **Discrepancy**: Citywide disconnection rates vary from 25.1% (Claude-01, 2023) to 31% (ChatGPT-DR-02, 2018 data)

### Worst-Connected Neighborhoods

| Neighborhood | Disconnection Rate | Borough | Source(s) |
|--------------|-------------------|---------|-----------|
| Fordham/Bedford Park/Norwood | 47.8% | Bronx | Claude-01, Claude-02 |
| Highbridge/Concourse | 45.6% | Bronx | Claude-01 |
| Morris Heights/Mount Hope | 45.4% | Bronx | Claude-01 |
| Melrose/Mott Haven/Longwood/Hunts Point | 41.7% | Bronx | Claude-01 |
| Edgemere (Rockaways) | 32% | Queens | ChatGPT-DR-01, ChatGPT-DR-02 |

**19 NYC community districts exceed 33% disconnection rates** (Claude-01)

### Market Concentration Index (HHI)

| Area | HHI Score | Interpretation | Source |
|------|-----------|----------------|--------|
| Manhattan | 1,044.69 | Most competitive in US | Claude-01 |
| Westchester County | 4,508.56 | Highly concentrated | Claude-01 |
| Nassau County | 4,534.10 | Highly concentrated | Claude-01 |
| Suffolk County | 5,081.86 | Highly concentrated | Claude-01 |

(HHI > 2,500 = highly concentrated; < 1,500 = competitive)

### Income-Based Digital Divide

| Income Level | Without Broadband | Source(s) |
|--------------|-------------------|-----------|
| Under $20,000/yr | 37-46% | Claude-01, ChatGPT-DR-01 |
| Over $75,000/yr | 5-7% | Claude-01 |
| **Disparity ratio** | **7x** | Claude-01 |

| Demographic | Without Broadband | Source |
|-------------|-------------------|--------|
| Black households | >33% | Claude-01 |
| Hispanic households | >33% | Claude-01 |
| Below poverty line | 46% | ChatGPT-DR-01 |

---

## Key Cross-Report Findings

### Consistent Findings (All or Most Sources Agree)
1. NYC residents pay $10-15/month more than national average for comparable speeds
2. The Bronx has the worst connectivity and highest prices
3. Municipal/competitive broadband costs 30-50% less than incumbent pricing
4. NYC Mesh operates on ~$500-600k annually serving 2,000+ nodes
5. 69% of NYC has only 1-2 ISP choices
6. Digital divide strongly correlates with income and race

### Significant Discrepancies

| Data Point | Range | Sources |
|------------|-------|---------|
| NYC Mesh install cost | $160-$290 | Claude vs ChatGPT |
| Chattanooga EPB investment | $220-$396M | Different scope definitions |
| Citywide disconnection | 25-31% | Different years (2018 vs 2023) |
| Fort Collins gigabit price | $59.95-$70/mo | Claude-02 vs Claude-01 |

---

*Summary compiled from: chatgpt-52-dr-01.md, chatgpt-52-dr-02.md, chatgpt-52-pro.md, claude-report-01.md, claude-report-02.md, grok.md*
