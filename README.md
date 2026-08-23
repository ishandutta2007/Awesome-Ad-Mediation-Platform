# Awesome-Ad-Mediation-Platform

## Top Ad Mediation Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Mobile Ad Monetization, Waterfall & Bidding Mediation, Cross-Network Optimization & Publisher Revenue Maximization*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Ad Mediation**. These tools help mobile app and game publishers integrate multiple ad networks, optimize fill rates and eCPMs through waterfall or in-app bidding, and maximize advertising revenue from a single SDK.

**Examples** include AppLovin MAX, Unity LevelPlay, Google AdMob Mediation, Chartboost Mediation, TopOn, CAS.AI, TradPlus, Yodo1 MAS, Appodeal, and Chartboost (the category leaders).

**Open-source emphasis**: Full-featured open-source ad mediation platforms are rare, but there are important projects (especially OpenMediation) plus open adapters, custom SDK examples, and tools that publishers can build upon. This section highlights every significant available option.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- |
| **[AppLovin MAX](https://www.applovin.com/max/)** | Leading mobile mediation platform with real-time in-app bidding, cross-network waterfall optimization, and deep integration with AppLovin Exchange (ALX). | **$0 platform fee** (0% publisher fee for 3rd-party mediation; monetizes via ~5% buyer fee on ALX exchange) | **Free forever** with unlimited apps, ad requests, impressions, and unrestricted access to in-app bidding & reporting. |
| **[Unity LevelPlay](https://unity.com/products/levelplay)** | Unity’s ad mediation platform (formerly ironSource) optimized for games, offering advanced user segmentation, A/B testing, real-time bidding, and Unity Ads integration. | **$0 platform fee** (0% publisher cut on third-party network mediation; monetized through Unity Ads demand ecosystem) | **Free forever** with unlimited impressions, apps, waterfalls, and ad units with no user or revenue caps. |
| **[Google AdMob Mediation](https://admob.google.com/)** | Google’s mediation platform combining AdMob demand with 30+ 3rd-party ad networks via open-source/versioned adapters for waterfall and bidding. | **$0 platform fee** (0% mediation fee for 3rd-party networks; standard Google revenue share applies solely to AdMob Network demand: 68% publisher / 32% Google cut) | **Free forever** with unlimited mediated ad requests, impressions, and app integrations without usage limits. |
| **[Chartboost Mediation](https://www.chartboost.com/)** | Unified auction and mediation platform (formerly Helium) focused on mobile games, interstitial, rewarded video, and playable ad monetization. | **$0 platform fee** (0% upfront/monthly SDK license fee; monetized via auction demand and optional payout processing fees e.g. $10–$25 per wire transfer) | **Free forever** with unlimited ad impressions, apps, and access to unified programmatic auction without usage caps. |
| **[TopOn](https://www.toponad.com/)** | Mediation management tool offering waterfall optimization, multi-network in-app bidding, and analytics tailored for hyper-casual and mid-core publishers. | **$0 platform fee** (0% commission on 3rd-party network mediation using own accounts; separate terms apply for optional TopOn ADX programmatic exchange) | **Free forever** with unlimited ad requests, apps, SDK mediation features, and reporting with no time limits. |
| **[CAS.AI](https://cas.ai/)** | Automated ad mediation platform (Clever Ads Solutions) providing unified auctions, waterfall management, and automated yield optimization across 30+ ad networks. | **10% revenue share** on generated ad revenue (0% upfront fee, $0/month base cost) | **Free integration forever** with $0 upfront cost, no trial expiration, and full access to 30+ demand sources (10% rev-share applies to earnings). |
| **[TradPlus](https://www.tradplus.com/)** | Global mobile ad mediation solution supporting multi-network bidding, transparent waterfall analytics, and automated eCPM optimization. | **$0 platform fee** (0% fee for standard 3rd-party network mediation; monetized via optional TPX programmatic exchange & VisiX services) | **Free forever** with unlimited DAU, ad impressions, mediated networks, and analytics access without caps. |
| **[Yodo1 MAS](https://www.yodo1.com/)** | Managed Ad Services platform aggregating 17+ ad networks, automated waterfall/bidding optimization, and unified account management for mobile games. | **15% revenue share** on mediated ad revenue (0% upfront fee, $0/month subscription cost) | **Free integration forever** with $0 upfront cost, no trial expiration, and full access to 17+ ad networks and auto-optimization (15% rev-share applies to earnings). |
| **[Appodeal](https://appodeal.com/)** | All-in-one growth and ad mediation platform featuring automated yield optimization, 70+ ad demand sources, in-app bidding, and built-in BI analytics. | **$0 platform fee** (0% base software fee for mediation SDK and BI tools; monetized via demand partnerships and optional accelerator revenue share) | **Free forever** with unlimited impressions, unlimited apps, full access to 70+ ad demand sources, and BI analytics tools. |

## Open-Source GitHub Projects

- **[OpenMediation](https://github.com/OpenMediationProject/OpenMediation)**  
  Fully open-source end-to-end ad mediation platform including Android/iOS SDKs, server-side mediation logic, dashboard, data aggregation, and support for major networks (AdMob, AppLovin, Unity, Meta, Vungle, Chartboost, Mintegral, etc.) plus header bidding.

- **[Google Mobile Ads Mediation Adapters](https://github.com/googleads/googleads-mobile-android-mediation)**  
  Official open-source mediation adapters for Android (and corresponding iOS repository) that allow publishers to integrate third-party networks into AdMob Mediation with publicly available source code.

- **[Google Mobile Ads iOS Mediation](https://github.com/googleads/googleads-mobile-ios-mediation)**  
  Open-source adapters and sample code for mediating third-party ad networks through the Google Mobile Ads SDK on iOS.

- **[Custom Ad Mediator SDK examples](https://github.com/fatemeh-afshari/ad-mediator-SDK)**  
  Open-source Android mediation SDK examples (e.g., managing multiple networks such as Tapsell + Unity Ads) built with modern architecture (Kotlin, Hilt, Coroutines, Clean Architecture).

- **[SotiAds & automation tools](https://github.com/shtse8/SotiAds)**  
  Open-source tools that automate AdMob ad unit creation, mediation group management, and eCPM floor optimization, often synchronized with Firebase Remote Config.

- **[OpenDSP / related ad platforms](https://github.com/javagossip/opendsp)**  
  Open-source mobile DSP and advertising platform components that can be studied or extended for custom demand-side or mediation-related systems.

### Additional Strong Open-Source Options

- **Adapter & custom event templates**: Community and official samples for building your own mediation adapters.
- **Bidding & auction logic**: Research and prototype repositories implementing simple in-app auction or waterfall logic.
- **Analytics & reporting helpers**: Open-source tools for aggregating revenue data from multiple ad networks.
- **Privacy & consent frameworks**: Libraries that help implement GDPR/CCPA consent flows required for mediation setups.
- **Testing & debugging tools**: Mock ad servers and mediation testing harnesses.
- Many publisher-built internal mediation wrappers and network abstraction layers shared on GitHub.

**Frameworks for building custom systems**:  
The most complete open-source starting point is **OpenMediation** (SDK + server + dashboard).  
Alternatively, use **Google AdMob Mediation** with its open-source adapters as the core and build custom optimization logic on top.  
For full control, implement a lightweight waterfall or bidding layer in your app that calls multiple network SDKs directly, combined with server-side decisioning and reporting.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Ad mediation involves complex relationships with ad networks, privacy regulations (GDPR, CCPA, COPPA, etc.), and revenue share agreements. Publishers remain responsible for compliance and accurate implementation.
- Open-source mediation solutions require ongoing maintenance of network adapters, handling of policy changes, and careful testing to avoid revenue loss or policy violations.

---

**Made for mobile game and app publishers, monetization managers, and ad technology developers.**  
Let's make ad mediation more transparent, flexible, and accessible through open tools.
