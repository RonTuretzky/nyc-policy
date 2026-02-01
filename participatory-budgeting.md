# Participatory Budgeting with Quadratic Voting

## What is Quadratic Voting?

Quadratic voting (QV) is a voting mechanism where voters receive a budget of "voice credits" to allocate across issues or proposals. The key innovation: the cost of votes increases quadratically with intensity.

| Votes Cast | Credits Spent |
|------------|---------------|
| 1 vote     | 1 credit      |
| 2 votes    | 4 credits     |
| 3 votes    | 9 credits     |
| 4 votes    | 16 credits    |


In standard voting, everyone gets one vote regardless of how much they care. A person mildly in favor counts the same as someone deeply affected. This creates two problems: first, small passionate minorities can be steamrolled by apathetic majorities; second, strategic voting and winner-take-all dynamics dominate.

QV solves this by making it increasingly expensive to signal strong preference on any single issue. If you care intensely about one proposal, you can cast multiple votes on it, but each additional vote costs quadratically more credits. Meanwhile, those credits are now unavailable for other issues you might care about.

The result: voters naturally spread their support across multiple proposals they care about, and issues that have broad moderate support surface alongside those with intense minority support. QV finds the "common ground" that other voting systems miss.

```
Credits Cost Diagram
                    
        16 |         ●
           |        
        12 |        
           |        
         9 |      ●
           |     
         4 |   ●
         1 | ●
         0 +──────────────
             1  2  3  4    Votes
```

---

## Case Studies

### NYC Harlem District 9 (2023)

The first time a US public official used secure online quadratic voting open to their whole constituency. RadicalxChange partnered with [Secure Internet Voting (SIV)](https://siv.org) and Council Member Kristin Richardson Jordan.

- **Outcome**: 80% voter satisfaction rate
- **Top-funded projects**: Baxter affordable housing ($1M), Marcus Garvey Playground ($275K)
- **Link**: [radicalxchange.org/wiki/nyc-qv](https://www.radicalxchange.org/wiki/nyc-qv/)

### Colorado House Democrats (2019)

First QV experiment in the state. Used to prioritize budget bills when the caucus had "a limited pot of money to spend on new legislation" and weeks of discussion had produced no clear conclusions. The poll generated a clear prioritization.

- **Link**: [radicalxchange.org/wiki/colorado-qv](https://www.radicalxchange.org/wiki/colorado-qv/)

### Colorado Executive Branch (2020)

Governor's Office used QV for interagency working groups to prioritize yearly goals. A cross-agency behavioral health taskforce used QV across 19 proposals and identified strong support for forming a new state agency. The Governor endorsed it; the Behavioral Health Administration for Colorado is now in development.

- **Link**: [radicalxchange.org/wiki/colorado-qv](https://www.radicalxchange.org/wiki/colorado-qv/)

### Colorado Legislature (2021-2023)

House and Senate Democrats used the RxC QV web app to prioritize 80+ spending bills with a $50M budget. Senate Republicans joined in 2022. Polls were anonymous and non-binding. "My hope is to... make this a regular part of how we do business in the legislature," said Senator Chris Hansen.

- **Challenge**: Faced legal scrutiny (see Practical Problems below)
- **Link**: [radicalxchange.org/wiki/colorado-qv](https://www.radicalxchange.org/wiki/colorado-qv/)

### Nashville Metro Council (2023)

Metro Council used QV to aid budget deliberations for 2023. "The quadratic voting process allowed council members, representing their constituents, to prioritize projects in a very objective way... The detailed ranking simplified the process of deciding which and how many of the possibilities we should spend our limited funds on," said Burkley Allen, district council member.

---

## Practical Problems

### 1. Voter Budget Utilization

In the Harlem pilot, **18% of participants did not use their entire QV budget**. Unused credits mean unexpressed preferences, potentially skewing results toward more confident participants.

### 2. Sign-up Complexity

The Harlem pilot required **verification materials via physical mail**, creating friction that delayed participation and excluded those without stable addresses.

### 3. Legal Challenges

In Colorado, a **judge ruled against the QV procedure** Democrats had been using, finding it conflicted with requirements around secret ballots. Formal QV adoption can run into archaic rules designed for traditional voting.

**Source**: [Colorado Public Radio](https://www.cpr.org/2024/01/05/democrats-secret-voting-system-colorado-legislature/)
