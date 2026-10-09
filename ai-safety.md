---
page: AI Safety
url: https://homenodes.ca/ai-safety
last_mirrored: 2026-10-09
---

# What this has to do with AI safety.

Compute governance is one of the most concrete near-term mechanisms available for AI oversight. The logic is straightforward: training powerful AI systems requires significant compute resources, and if those resources can be monitored and regulated, the development of potentially dangerous AI systems becomes more observable and controllable. HomeNodes challenges a core assumption in every compute governance proposal being developed today.

### THE ASSUMPTION

Every serious compute governance proposal — hardware telemetry monitoring, training run verification, export controls on advanced chips, data center reporting requirements — shares one assumption: compute happens in identifiable, regulated facilities. That assumption is becoming less true every year.

### THE GAP

Distributed compute platforms already route real AI workloads to residential hardware. If inference and training can run on nodes in homes — hardware not subject to data center regulations, not covered by export control reporting, and not visible to hardware-level monitoring proposals — then the oversight mechanisms being built today have a blind spot built into them from the start.

### THE THREAT MODEL

There are four ways residential compute could weaken oversight: use without a regulated provider, work split across small nodes to stay under thresholds, workloads hidden in ordinary household power use, and no operator to shut it down. The threat model sets out each one, what the project is not claiming, and what Phase 1 will show.

[Read the threat model](https://homenodes.ca/threat-model)

### THE GOAL

HomeNodes does not claim residential compute is currently a significant AI safety risk. It argues that governance frameworks being built now will govern AI systems for decades, and they should account for residential nodes from the start. Retrofitting governance onto an established infrastructure pattern is harder than getting ahead of it.

### THE TEST

The proof-of-concept node runs as an ordinary host on a public compute marketplace. From the homeowner's side, we will record what a host can and cannot see: what software is running, who rented the hardware, and whether power and bandwidth use are enough to identify a workload. The node exists to produce evidence, not to grow residential compute.

### THE OPERATOR

Residential nodes could reach homes in different ways: added by individual homeowners, managed by an internet provider, or run with a public utility. Each puts a different party in charge of the hardware, and that decides whether regulators have anyone to reach. A carrier or public body can be held to standards. Thousands of individual homeowners are much harder to oversee. Phase 2 will study this directly.

## Getting ahead of the problem is the point.

The compute governance mechanisms under development by AI safety researchers and policymakers are the right response to a real risk. HomeNodes exists to make sure those mechanisms are complete — that the governance net has no gaps a residential node can fall through.

[See the Project](https://homenodes.ca/the-project)
