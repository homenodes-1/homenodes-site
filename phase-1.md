---
page: Phase 1
url: https://homenodes.ca/phase-1
last_mirrored: 2026-10-09
---

# Phase 1: one home, one node, sixteen weeks.

Phase 1 runs one consumer GPU node in one home in Medicine Hat, Alberta. The node is listed on a public compute marketplace for eight weeks. The study measures what a household hosting AI compute can see, what its power and network data reveal, how much energy it uses, and where existing rules give the household no clear answer. The method is fixed in advance and published before the node is listed.

![Phase 1 overview: the setup in one home, the 16-week schedule, and the four research questions with what each one publishes.](https://raw.githubusercontent.com/homenodes-1/homenodes-poc/main/diagrams/phase-1-overview.png)

*Phase 1 at a glance. Planned design. Hardware has not been purchased yet.*

### WHAT IT TESTS

- **Host visibility.** What can a host see about the workloads and renters on their hardware, using only normal host tools?
- **Workload identifiability.** Can power and network data tell types of AI workload apart, and at what meter resolution does that stop working?
- **Energy use.** How much energy does a node use in each operating state?
- **Governance gaps.** Where do existing rules give a household no clear answer?

### THE SETUP

- One consumer GPU node in the basement of one home
- A dedicated internet line whose terms permit hosting, separate from the household line
- A firewall that keeps the node on its own network segment
- An energy monitor on the node circuit only, recording every second
- One public GPU marketplace, with the listing set to end when the study ends

### THE SCHEDULE

- **Weeks 0 to 2.** Purchase
- **Weeks 2 to 4.** Build, harden, and isolate the node
- **Weeks 4 to 6.** Baseline, using the project's own test workloads
- **Weeks 6 to 14.** Operation, with the node listed and the host's view audited every week
- **Weeks 14 to 15.** Close-out, repeating the test workloads
- **Weeks 15 to 16.** Report, data, and gap log published

### WHAT IS NEVER COLLECTED

Renter workload contents. Renter identity. Whole-home energy use. Other household network activity.

### WHAT IT COSTS

- Node hardware: CAD $5,523 including GST
- Dedicated internet line for four months: CAD $1,134 including GST
- Electricity for the study period: about CAD $150
- Research time: unpaid

The external funding need for Phase 1 is USD $4,950.

### WHAT IT CANNOT SHOW

Phase 1 is one home. A finding may be about this household, this hardware, or this internet provider, and not about residential compute in general. It measures energy at the node circuit, so it does not test whether a node can be picked out of a whole-home meter signal. It does not test what happens when work is split across many nodes.

## The full plan is public.

The protocol, budget, and bill of materials are on GitHub.

[Read the Phase 1 plan on GitHub](https://github.com/homenodes-1/homenodes-poc/blob/main/PHASE-1.md)

[See Phase 2](https://homenodes.ca/phase-2)
