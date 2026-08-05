---
author: jakfromspace
title: Renting the Horizon
pubDatetime: 2026-08-04T23:57:22Z
description: On Digital Feudalism, Planned Obsolescence, and Self-Hosting as an Act of Sovereignty
draft: false
tags:
  - digital-feudalism
  - planned-obsolescence
  - self-hosting
  - right-to-repair
  - solarpunk
  - digital-ownership
  - late-capitalism
  - privacy
  - open-source
  - piracy-ethics
---

# Renting the Horizon: Late-Stage Capitalism, Digital Feudalism, and the Solarpunk Case for Self-Hosting

## Table of Contents

There is a quiet, pervasive friction underlying almost every interaction we have with modern technology. Every morning, we wake up to a barrage of push notifications demanding subscription renewals, cloud storage warnings alerting us that our "quota is 92% full," and algorithmically tailored feeds prompting us to purchase sleek smart-home accoutrements to aestheticize our existential dread. We live in an era where we buy devices we do not control, stream media we do not own, and entrust our most intimate personal archives to cloud monopolies that treat our memories as recurring revenue line items.

As a CS grad working deep inside the film visual effects (VFX) pipeline, my day-to-day life revolves around digital assets — bit depths, storage balancing, high-throughput render farms, and distributed data orchestration. But as an artist, gamer, and lifelong tech enthusiast, I find myself deeply disillusioned by the trajectory of 2020s consumer technology. We have seamlessly transitioned from classical capitalism into a hyper-centralized, rent-seeking regime of **Digital Feudalism**.

The solution, however, is not tech-aversion or ludditism — it is **digital sovereignty** through open-source self-hosting, utility minimalism, and a green Solarpunk ethos.

## 1. The Architecture of Obsolescence: From Lightbulbs to Serialized Hardware

Planned obsolescence is not a modern glitch; it is the deliberate design philosophy of late capitalism. Its institutional roots trace back to the **Phoebus Cartel** of 1924, where leading incandescent bulb manufacturers — including OSRAM, Philips, and General Electric — colluded to artificially limit the lifespan of lightbulbs from 2,500 hours down to 1,000 hours to guarantee perpetual consumer demand [1].

A century later, Silicon Valley refined this practice into a fine art. The modern smartphone — pioneered by Apple's non-replaceable battery designs and sealed unibody chassis — turned hardware into a disposable commodity. When software updates intentionally slowed older hardware (a practice Apple paid $500 million to settle in the infamous "Batterygate" class action [2]), the industry established a new baseline: devices do not break; they are rendered obsolete by remote corporate decree.

Furthermore, hardware serialization (part-pairing) has systematically gutted the Right to Repair. Modern smartphones link individual display chips, camera modules, and batteries to the logic board via cryptographic keys. Swap an original OEM screen between two identical phones, and software will throw warnings or disable features like TrueTone and biometrics. The US Federal Trade Commission (FTC) confirmed this predatory reality in its landmark 2021 _Nixing the Fix_ report, finding scant evidence to support manufacturer claims that repair restrictions protect safety or privacy [3].

It doesn't have to be this way — companies like **Framework**, with laptops built around swappable, user-replaceable modules and openly published repair guides, prove that serviceable hardware is still commercially viable. Before your next purchase, a quick check of a device's **iFixit repairability score** tells you in seconds whether you're buying a tool or a ticking obsolescence timer.

## 2. The Evaporation of Physical Media & the "Code-in-a-Box" Illusion

Remember Blockbuster video stores, Walkman cassette players, or optical media drives on home PCs? They were not merely nostalgic relics; they were physical guarantees of ownership. When you purchased a DVD or a PlayStation 2 disc, you executed a permanent, legal transaction protected by the First Sale Doctrine. You could lend it, trade it, or play it thirty years later completely off-grid.

Today, physical media is systematically starved out. Console makers push disc-less variants, and retail shelves are cleared of media. Even when you "buy physical" today, major flagship releases are shifting toward digital download codes tucked inside empty plastic cases — GTA 6 among them. You aren't buying a game disc; you are buying landfill-bound plastic wrapped around a revocable license key. The collector's shelf has quietly become a display case for licenses that were never really yours.

> _"Digital storefronts are not libraries; they are temporary display cases managed by corporate rights-holders."_

The consequences of this transition are no longer theoretical:

- **Ubisoft (2024):** Shut down servers for _The Crew_ and then went a step further, actively revoking licenses from players' Ubisoft Connect accounts — rendering already-purchased software completely unplayable and unrecoverable, with no refunds offered [4].
- **Sony PlayStation (2022, 2026):** Deleted hundreds of purchased StudioCanal films (Germany/Austria in 2022; 551 titles including _Terminator 2_, _Paddington_, and _Rambo_ across the UK and Europe effective as of September 2026) from users' digital libraries once licensing deals lapsed — again, no refunds [5]. Sony's Network Terms of Service are explicit that "purchase" and "buy" do not mean or imply any transfer of ownership; everything sold through the PlayStation Store is a non-exclusive, revocable license.
- **Warner Bros. Discovery:** Deliberately pulled completed films (like _Coyote vs. Acme_) and legacy animated series from streaming platforms purely as corporate tax write-offs.

Not everyone has accepted this quietly. After _The Crew_'s shutdown, YouTuber Ross Scott launched **Stop Killing Games**, a campaign demanding publishers leave purchased games in a functional state — offline mode, private-server support, anything short of a remote kill switch. It gathered 1.29 million verified signatures as a European Citizens' Initiative, enough to force a formal European Commission response. In June 2026 the Commission declined to propose binding legislation, opting instead for a voluntary industry code of conduct — a reminder that public pressure can move the conversation without yet moving the law. Closer to home, the backlash to incidents exactly like Sony's Discovery removal directly inspired **California's AB 2426**, signed in 2024 and in effect since January 2025, which now legally requires digital storefronts to disclose when a "buy" button is actually a revocable license rather than let the word do the deceiving on its own.

It's also worth noting that ownership-respecting storefronts aren't hypothetical: **GOG (Good Old Games)** sells DRM-free downloads that are yours to keep, install offline, and play in thirty years with no client, license check, or company required — proof that the industry's current direction is a choice, not a technical necessity.

## 3. Cloud Centralization & the Shrinking Home Computer

In the 1990s and early 2000s, the personal computer was an open canvas. Users owned the file system, operated with administrator/root privileges, executed local applications, and stored data on local spinning hard drives. Today, the general-purpose computer is being rapidly replaced by sandboxed mobile operating systems, shell devices with little to no brains inside that stream content to it and thin clients tethered to corporate cloud hyperscalers - a la Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

We are told "the cloud" offers effortless convenience. In truth, _there is no cloud — it is just someone else's computer_. Centralized cloud infrastructure abstracts away local compute, replaces transparent file systems with opaque app sandboxes, and imposes perpetual rent on data storage and compute cycles. It isolates users from understanding how their own software operates, fostering a culture of technological helplessness — the same helplessness that makes the license revocations in the former Section feel inevitable rather than outrageous.

## 4. "If Buying Isn't Owning, Piracy Isn't Stealing": Cultural Salvage in an Age of Enclosure

When corporate cartels treat paid customers as temporary renters, the social contract breaks. This has catalyzed a massive ethical shift across developer and artist communities: **if buying isn't owning, then piracy isn't stealing.**

Communities built around this ethic ("free media dang yes!" IYKYK) — decentralized archives, mirror networks, and torrent trackers — are no longer just about getting free stuff; they function as digital conservation projects. When streaming conglomerates lock archival cinema and classic videogame ROMs behind six different paywalls or quietly remove legendary historical media entirely from their official catalogue, torrents become the _only_ such surviving copies of pieces of human culture.

Most of us would gladly pay creators directly for their work — a model seen in platforms like Bandcamp or direct artist support. But subscription fees paid to mega-corporations rarely trickle down to the actual VFX artists, software developers, or musicians who poured their lives into the work. They enrich boardrooms and streaming executives who hold the keys to the library gates.

## 5. Algorithmic Extraction, Brainrot, and the Enclosure of Childhood

Why do we tolerate all of this? Because 2020s consumer tech relies on sophisticated behavioral conditioning. Algorithmic feeds — TikTok, Instagram Reels, YouTube Shorts — use variable-ratio reinforcement schedules, the exact psychological mechanism that makes slot machines addictive. They flood our consciousness with hyper-curated, maximalist consumerism: aesthetic smart-home visualizers, 12-step skincare routines, $3,000 desk setups, constant hardware upgrades. They make us fetishize expensive, fragile lifestyles while distracting us from the reality that our real-world autonomy is evaporating — aesthetic maximalism disguising spiritual and financial depletion.

This system is particularly toxic for children. Kids deserve access to high-quality, enriching media without being subjected to monthly paywalls or targeted by ad-driven "brainrot." On ad-supported free-tier platforms, children's content is systematically optimized for engagement metrics, feeding them hyper-stimulating, low-effort content wrapped in endless commercial breaks and tracking scripts. The alternative shouldn't be paying $150 a month across eight streaming subscriptions just so your family can watch a movie uninterrupted.

## 6. The Cloud Photo Trap

Cloud photo services (Google Photos, Apple iCloud) exemplify this corporate trap. They offer zero-friction setup: snap a photo, and it vanishes into the cloud. But as high-megapixel camera sensors (48MP+ mobile, 60MP+ mirrorless) become standard, photo libraries balloon into hundreds of gigabytes or terabytes. Once you cross the 15GB free tier, you enter an ascending subscription ladder ($2.99/mo, $9.99/mo, $19.99/mo) that you can never leave without risking the loss of a decade of family memories.

### Technical Deep-Dive: How Cloud Compression Ruins Photography

As a VFX engineer and art enthusiast with a considerable amount of digital imaging knowledge, watching these consumer cloud platforms handle photography is agonizing. When platforms apply "Storage Saver"-type lossy compression, they perform destructive transformations:

1. **Bit-Depth Quantization:** 12-bit or 14-bit RAW camera files (e.g., Canon `.CR3`, Sony `.ARW`) are crushed into 8-bit JPEG/WebP formats. This drops color resolution from 68.7 billion colors down to a paltry 16.7 million, causing severe posterization and color banding across subtle sky gradients and skin tones.
2. **Dynamic Range & Highlight Clipping:** Sensor RAW data preserves latitude in highlight roll-offs and deep shadow details. Lossy compression tone-maps these curves aggressively, blowing out highlights and baking noise-reduction artifacts directly into shadow tones.
3. **Color Space Degradation:** Camera sensors capture wide gamut spaces (ProPhoto RGB, Rec.2020). Cloud compression forces conversion into narrow sRGB spaces, stripping rich cyan and deep magenta hues.
4. **Exposure & Metadata Mutilation:** Cloud transcoders strip embedded camera profiles, custom white-balance tables, and EXIF metadata required for proper color grading in Nuke, Lightroom, or DaVinci Resolve.

## 7. The AI Compute Paradox & Solarpunk Philosophy

The current hype cycle surrounding Generative AI represents another massive vector for cloud dependency. Monolithic cloud models require thousands of megawatt-hours of electricity and millions of gallons of datacenter cooling water. They turn high-utility technology into an environmental strain managed by a handful of corporate cartels.

Against this maximalist trajectory stands **Solarpunk** — a socio-technological vision that advocates for green sustainability, digital socialism, human-centric design, and technology in service of community rather than capital. Solarpunk asks: _how can we utilize cutting-edge technology while minimizing environmental footprint, eliminating corporate rent extraction, and fostering genuine human connection?_

The answer begins with digital self-reliance: local compute, utility minimalism, open-source software, and home infrastructure.

## 8. The Digital Sovereignty Starter Kit

Reclaiming your digital life does not require a Ph.D. in computer science or a $10,000 server rack. You can start with zero-cost browser defenses and scale up to a local home server using a modest mini-PC (e.g., an Intel N100), a few reliable drives, and Docker.

### Phase 0: Immediate Digital Hygiene

Before buying any hardware, take back control of your client browser:

- **Brave Browser / uBlock Origin:** Block tracking scripts, ad-tech fingerprinting, and algorithmic distractions at the network level. Eliminating corporate surveillance telemetry is step one in escaping the dopamine treadmill. If you're feeling "braver" also get Qbittorrent and find those aforementioned "liberated media" community sites to keep your favorite stuff saved offline in your own devices.

### Phase 1: Jellyfin — Personal Streaming Media System

- **What it is:** Jellyfin is a 100% Free and Open Source Software (FLOSS) media system. Unlike Plex — which collects telemetry, requires account login through central servers, and paywalls hardware transcoding behind "Plex Pass" — Jellyfin has no tracking, no subscription tiers, and zero remote dependencies.
- **Features:** Full hardware-accelerated transcoding (Intel QSV, NVENC, VAAPI), multi-user profiles, seamless subtitle rendering, and native client apps for Smart TVs, mobile devices, and browsers.

### Phase 2: Immich — High-Performance Self-Hosted Photo & Video Backup

- **What it is:** Immich is an open-source self-hosted alternative to Google Photos. It provides seamless automatic background backup from mobile devices while keeping your photo library completely local, uncompressed, and in full original fidelity.
- **Features:** Facial recognition, semantic vector search (a CLIP model that lets you search "dog on a beach"), album sharing, partner libraries, an interactive location map, and zero compression — preserving pristine 14-bit RAW files, custom EXIF metadata, and exact color spaces.
- **Under the hood:** Immich deploys via Docker Compose across a handful of microservices — `immich-server` (the core REST API and web UI), `immich-machine-learning` (local Python inference for facial recognition and CLIP search), `postgres` with the `pgvector` extension (for fast spatial and semantic search), and `redis` (job queuing for background processing).

### Phase 3: The 3-2-1 Storage Strategy

Self-hosting does not mean living recklessly without backups. Implement the industry-standard **3-2-1 Rule**:

- **3 Copies of Data:** Primary working copy, local backup copy, secondary offsite copy.
- **2 Different Storage Media:** e.g., local NVMe/SATA SSDs plus Network Attached Storage (NAS) HDDs.
- **1 Offsite Copy:** An encrypted backup pushed to an offsite location — such as a server at a family member's house running BorgBackup or Restic, or encrypted zero-knowledge cold storage like Backblaze B2.

### Phase 4: Habits That Don't Need a Server at All

Self-hosting is the deep end, but plenty of the underlying philosophy travels without any hardware at all:

- **Run a subscription audit.** Once a year, list every recurring charge and ask which ones you'd re-subscribe to today. The dopamine treadmill relies on you never looking directly at the receipt.
- **Buy secondhand and repairable first.** Refurbished hardware, right-to-repair-friendly brands, and local repair cafés keep devices — and money — out of the planned-obsolescence cycle.
- **Replace algorithmic feeds with chosen ones.** An RSS reader or a manually curated follow list gives you the content you actually asked for, without a recommendation engine deciding what keeps you scrolling.
- **Pay creators directly when you can.** Bandcamp, Patreon, itch.io, and direct sales route money around the platforms that take the largest cut and give artists the least visibility.
- **Remember that "smart" doesn't have to mean "cloud."** Tools like **Home Assistant** run your smart-home automations entirely on your own network — no third-party servers deciding whether your lights still work after a subscription lapses, and none of the cloud dependency this essay opened by mocking.

None of this requires ideological purity. Picking two or three is already a meaningful exit from the treadmill.

## 9. Personal Reflections: How Self-Hosting Reclaims Life and Community

When I deployed my first local Docker stack running Jellyfin and Immich, the psychological shift was immediate. Movie nights in my home transformed from thirty-minute scrolling sessions through algorithmic catalogues — only to discover the title you wanted was quietly removed last week — into smooth, high-bitrate cinematic experiences with uncompressed surround sound.

My family and kids can now watch classic animation and educational media without commercial interruptions, ad tracking, or predatory algorithmic suggestions. When shooting photography or working on visual sequences, syncing my devices to Immich preserves every photon, highlight, and raw color space exactly as sensor physics intended. I no longer worry about reaching arbitrary cloud storage caps or paying forced monthly increments to tech giants.

More importantly, self-hosting embodies Solarpunk in action. It transforms computing from a passive subscription into an active craft of digital stewardship. It fosters real human connection: hosting shared family photo albums where relatives can access uncompressed memories without ads; running a local server that consumes a modest 15 watts of power; and sharing open-source tools with friends so they, too, can reclaim their own hardware.

## 10. Conclusion: Reclaim Your Byte

We do not have to accept a future where every aspect of our digital lives is metered, monetized, and revoked at corporate whim. Late-stage capitalism thrives on learned helplessness, persuading us that convenience is worth the surrender of ownership, privacy, and control.

By hosting your own media, backing up your uncompressed photographs, blocking predatory ad-tech, choosing repairable hardware, and supporting open-source commons, you step off the consumer dopamine treadmill. You reclaim your data, your agency, and your piece of the digital horizon.

### References & Citations

1. Krajewski, M. (2014). "The Great Lightbulb Conspiracy." _IEEE Spectrum_, 51(10), 56–61. (Documentation of the Phoebus Cartel and artificial lifespan reduction; corroborated by University of Auckland's history of planned obsolescence and multiple industry retrospectives.)
2. _In re Apple Inc. Device Performance Litigation_, No. 5:18-md-02827 (N.D. Cal. 2020). Class-action settlement of up to $500 million regarding iOS performance throttling of older iPhones.
3. Federal Trade Commission (2021). _Nixing the Fix: An FTC Report to Congress on Repair Restrictions_. FTC.gov. ("There is scant evidence to support manufacturers' justifications for repair restrictions.")
4. Multiple outlets, April 2024 (PC Gamer, Eurogamer, Destructoid, MMORPG.com). Ubisoft revoked player licenses for _The Crew_ from Ubisoft Connect accounts weeks after shutting down its servers on March 31, 2024, with no refunds or download access offered.
5. Variety (2022); Notebookcheck, Cybernews, Nerdist, PlayStation LifeStyle (June–July 2026). Sony removed purchased StudioCanal titles from PlayStation libraries in Germany/Austria (2022) and is removing 551 titles across the UK and Europe on September 1, 2026, citing lapsed licensing agreements and offering no refunds. (Note: a separate December 2023 threat to remove purchased Discovery content was reversed after public backlash and a new licensing deal with Warner Bros. Discovery — included here for context on how precarious "ownership" is, even when threats don't fully materialize.)
6. Assemblymember Jacqui Irwin, press release (Sept. 24, 2024); Engadget, Sidley Austin, Greenberg Traurig. California AB 2426, signed by Governor Newsom and effective January 1, 2025, requires digital storefronts to disclose when "buy"/"purchase" language actually confers only a revocable license; its author cited disappearing-digital-media incidents like Sony's as motivating the bill.
7. Ross Scott / Accursed Farms, Stop Killing Games campaign (launched April 2024); European Citizens' Initiative registry; Eurogamer, Notebookcheck, Techdirt (2026). The "Stop Destroying Videogames" initiative reached 1,294,188 verified EU signatures; the European Commission declined to propose binding legislation in June 2026, committing instead to a voluntary industry code of conduct.
