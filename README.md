# Awesome-Composable-CDP

## Top Composable CDP Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Warehouse-Native Customer Data, Reverse ETL, Event Collection, Audience Activation & Data Activation*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Composable CDPs**. These systems treat the data warehouse as the source of truth for customer data—collecting events, modeling audiences, and activating data into business tools via reverse ETL and streaming—rather than storing a separate customer profile store.



**Examples** include Hightouch, RudderStack, mParticle, Segment, Treasure Data, ActionIQ, Zeotap, Simon Data, Blotout, Jitsu, GrowthLoop, Census, ActionIQ CX Hub, MessageGears, and Tealium (the category leaders).



**Open-source emphasis**: Composable CDP has strong open-source foundations. **RudderStack**, **Jitsu**, **Multiwoven**, and related event + reverse ETL projects let teams own collection and activation pipelines. This section heavily expands those options.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Hightouch](https://hightouch.com/)**  

  Leading composable CDP and reverse ETL platform—warehouse-native audiences, activation to 250+ destinations, and marketing-friendly audience builders.



- **[RudderStack](https://www.rudderstack.com/)**  

  Warehouse-native customer data platform with open-source data plane—event streaming, transformations, reverse ETL, and profiles on your infrastructure.



- **[mParticle](https://www.mparticle.com/)**  

  Enterprise customer data platform strong on mobile, real-time event orchestration, and multi-channel activation.



- **[Segment](https://segment.com/)**  

  Classic CDP for event collection, identity, and routing to destinations—still widely used as the collection layer in hybrid stacks.



- **[Treasure Data](https://www.treasuredata.com/)**  

  Enterprise CDP and customer data cloud for collection, unification, and activation at scale.



- **[ActionIQ](https://www.actioniq.com/)**  

  Enterprise composable / CX hub CDP focused on audience management and activation for large organizations.



- **[Zeotap](https://zeotap.com/)**  

  Customer data and identity platform for privacy-centric collection, enrichment, and activation.



- **[Simon Data](https://www.simondata.com/)**  

  Customer data and marketing activation platform built around warehouse and journey orchestration.



- **[Blotout](https://blotout.io/)**  

  Privacy-first edge and composable CDP approaches for first-party data collection and activation.



- **[Jitsu](https://jitsu.com/)**  

  Open-source Segment alternative with commercial hosting—event collection, transformation, and warehouse delivery.



- **[GrowthLoop](https://www.growthloop.com/)**  

  Composable customer data and activation platform oriented toward growth and marketing teams.



- **[Census](https://www.getcensus.com/)**  

  Reverse ETL and data activation platform (now in the Fivetran ecosystem) for syncing warehouse data to business tools.



- **[MessageGears](https://www.messagegears.com/)**  

  Enterprise data activation and messaging platform that works with existing customer data stores.



- **[Tealium](https://tealium.com/)**  

  Customer data platform and tag management suite for collection, enrichment, and real-time activation.



## Open-Source GitHub Projects

- **[RudderStack (rudder-server)](https://github.com/rudderlabs/rudder-server)**  

  Leading open/source-available warehouse-native CDP data plane—Segment-compatible event collection, transformations, and warehouse/destination routing.



- **[Jitsu](https://github.com/jitsucom/jitsu)**  

  Fully open-source (MIT) Segment alternative—collect events from web/apps, transform in flight, and stream to warehouses and tools.



- **[Multiwoven](https://github.com/Multiwoven/multiwoven)**  

  Open-source reverse ETL and data activation platform positioned as an alternative to Hightouch and Census.



- **[Airbyte](https://github.com/airbytehq/airbyte)**  

  Open-source data integration platform often used to move SaaS and event data into the warehouse that powers a composable CDP.



- **[dbt](https://github.com/dbt-labs/dbt-core)**  

  Open-source transformation framework that models customer entities, identities, and audience tables inside the warehouse.



- **[Snowplow](https://github.com/snowplow/snowplow)**  

  Open-source behavioral data pipeline for high-quality event collection into your own warehouse.



- **[Segment open protocols / community destinations](https://github.com/segmentio)**  

  Open protocols and community connectors that influence many Segment-compatible open collectors.



- **[Reverse ETL open connectors and sync engines](https://github.com/)**  

  Community projects for SQL-based extraction and sync from warehouses to CRM, marketing, and support tools.



- **[Identity resolution open experiments](https://github.com/)**  

  Libraries and notebooks for deterministic and probabilistic identity stitching on warehouse data.



- **[Documentation and composable CDP open playbooks](https://www.rudderstack.com/docs/)**  

  Guides for building warehouse-native collection → transform → activate pipelines with open tools.



### Additional Strong Open-Source Options

- Collecting events with **Jitsu** or **RudderStack** open data planes into your warehouse.

- Modeling audiences and customer 360 tables with **dbt**.

- Activating with **Multiwoven** or custom reverse ETL jobs.

- Using **Snowplow** when behavioral event quality and ownership are critical.

- Accepting that no-code audience builders, large destination catalogs, enterprise governance, and managed SLAs still favor commercial composable CDPs (Hightouch, Census, RudderStack Cloud, Segment, mParticle, Tealium, etc.).

- Focusing open-source efforts on data ownership, cost control at high event volume, and warehouse-centric architecture.



**Frameworks for building custom systems**: Collect with Jitsu/RudderStack/Snowplow → land in warehouse → transform with dbt → activate with Multiwoven or SQL syncs → govern schemas in code. Suitable for data and engineering-led teams. Marketing-led organizations often still prefer commercial composable CDPs for self-serve activation.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Customer data platforms handle personal data and must comply with privacy regulations. Open-source deployments require proper security, consent, and governance. This list is not legal or privacy advice.



---

**Made for data engineers, growth teams, and open-source CDP advocates.**

Let's keep customer data owned, activated, and as open as practical.
