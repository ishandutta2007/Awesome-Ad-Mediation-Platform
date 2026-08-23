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

- **[AppLovin MAX](https://www.applovin.com/max/)**  
  Leading mediation platform with strong in-app bidding, high eCPM performance (especially in Tier-1 markets), broad network support, and tight integration with AppLovin demand.

- **[Unity LevelPlay](https://unity.com/products/levelplay)**  
  Unity’s mediation platform (formerly ironSource) optimized for games, offering advanced segmentation, A/B testing, bidding, and native Unity Ads demand.

- **[Google AdMob Mediation](https://admob.google.com/)**  
  Google’s mediation solution that combines AdMob demand with third-party networks via open-source and versioned adapters, supporting both waterfall and bidding.

- **[Chartboost Mediation](https://www.chartboost.com/)**  
  Mediation platform focused on mobile games with bidding capabilities and Chartboost’s own demand.

- **[TopOn](https://www.toponad.com/)**  
  Popular mediation platform (especially in Asia and among hyper-casual/mid-core publishers) offering strong optimization tools and multi-network support.

- **[CAS.AI](https://cas.ai/)**  
  Ad mediation platform providing automated optimization, multiple networks, and tools aimed at maximizing publisher revenue.

- **[TradPlus](https://www.tradplus.com/)**  
  Mediation solution with a focus on global publishers, bidding, and performance optimization across networks.

- **[Yodo1 MAS](https://www.yodo1.com/)**  
  Mediation and monetization platform tailored for game publishers, offering network aggregation and optimization features.

- **[Appodeal](https://appodeal.com/)**  
  All-in-one mediation and monetization platform with automated tools, multiple ad formats, and publisher-friendly features.

- **[Chartboost](https://www.chartboost.com/)**  
  Ad network and mediation platform popular in the mobile gaming space for interstitials, rewarded video, and playable ads.

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
