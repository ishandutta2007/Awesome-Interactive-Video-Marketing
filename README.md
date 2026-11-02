# Awesome-Interactive-Video-Marketing

# Top Interactive Video Marketing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Interactive Players, Branching Video & Self-Hosted Engagement Tooling*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Interactive Video Marketing**. These tools enable marketers to turn passive viewers into active participants—adding clickable hotspots, quizzes, branching paths, lead-capture forms, and shoppable links directly into video content to drive engagement and conversions.

**Examples** include HubSpot Interactive Video, Wistia, Vidyard, Vimeo Interactive, Tolstoy, Mindstamp, Spott, Wirewax, Hippo Video, and Vizia (the category leaders).

**Open-source emphasis**: Interactive Video Marketing is a domain where open-source tooling is **genuinely emerging but still catching up to commercial platforms on marketing-specific workflows**. The strongest active project is **OVAL Interactive Video Player**—a BSD-2-Clause licensed, feature-rich player with real-time annotations, timeline comments, embedded quizzes (multiple-choice and free-text), full interaction tracking, LMS/LTI integration, and data export for analysis . **IVA (Interactive Video Application)** is a research-backed, open-source framework using React and YAML specifications to define interactive regions, informative panels, jumpers, and quizzes—explicitly designed for extensibility by researchers in education, marketing, and entertainment . **H5P Interactive Video** provides a mature open-source content type for adding texts, tasks, and media overlays to video within the H5P ecosystem . The critical caveat: **no open-source project matches the lead-capture, CRM integration, and shoppable-video workflows** of Mindstamp or Wistia—open-source players focus on engagement (quizzes, annotations) rather than conversion (forms, product links, paywalls) .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[HubSpot Interactive Video](https://www.hubspot.com/)**  
  Interactive video capabilities within HubSpot's marketing platform; embed videos with lead-capture forms, CTAs, and branching, tied directly to CRM contact records.

- **[Wistia](https://wistia.com/)**  
  Video hosting and marketing platform with interactive elements including turnstile lead gates, annotations, and CTAs; deeply integrated with HubSpot and Salesforce for attribution.

- **[Vidyard](https://www.vidyard.com/)**  
  Video hosting and async communication platform with interactive CTAs, forms, and AI avatars; CRM integrations for sales enablement.

- **[Vimeo Interactive](https://vimeo.com/)**  
  Interactive video features within Vimeo's platform; supports clickable hotspots, shoppable links, and branching for brand content.

- **[Tolstoy](https://www.tolstoy.com/)**  
  Interactive video platform focused on shoppable video and branching conversations for ecommerce; turns video into a conversational sales tool.

- **[Mindstamp](https://mindstamp.com/)**  
  Interactive video platform built for business workflows; features questions, buttons, hotspots, branching, **lead capture, personalization, shoppable video, paywalls**, and viewer-level analytics with CRM/webhook/API integrations . Pricing from $99–$499/month .

- **[Spott](https://www.spott.it/)**  
  Interactive content platform for marketing; adds clickable links, shoppable tags, and PDF documents to images and videos for product promotions .

- **[Wirewax](https://www.wirewax.com/)**  
  Interactive video platform (acquired by Vimeo); pioneered clickable hotspots, shoppable video, and interactive overlays.

- **[Hippo Video](https://www.hippovideo.io/)**  
  Video marketing platform with screen recording, webcam capture, and interactive elements for sales outreach and marketing.

- **[Vizia](https://vizia.co/)**  
  Interactive video platform for commerce and marketing; adds shoppable elements, quizzes, and branching to video content.

## Open-Source GitHub Projects

### Interactive Video Players (OVAL, IVA)

- **[OVAL Interactive Video Player](https://github.com/c3l-lab/OVAL)**  
  The **most feature-complete open-source interactive video player** available (BSD 2-Clause) . Features: **real-time annotations** (view annotations made by other users for collaborative learning) ; **timeline comments** for discussions directly on the video; **embedded quizzes** (multiple-choice and free-text) at predetermined points to test comprehension; **full interaction tracking** (annotations, comments, quiz responses, viewing behavior) with **data export** for analysis; **LMS/LTI integration** for embedding into Canvas, Open edX, and other LMS platforms; **customization** to enable/disable annotations, comments, and player controls . Uses **YouTube as the primary video source** . **Best for education and training** wanting a free, feature-rich interactive player with data export—but it is education-focused rather than marketing-focused (no lead capture or CRM integration) .

- **[IVA (Interactive Video Application)](https://github.com/Schez-Sobrino/IVA)**  
  An open-source, **web-based framework for building interactive videos** (React frontend, documented in SoftwareX) . Features: **YAML-based interactive video specification**; four interactive component types: **interactive regions** (clickable areas that trigger actions like jumping to a specific millisecond), **informative panels** (additional information overlays), **jumpers**, and **quizzes**; **modular architecture** with a `VideoComponentFactory` class for registering new component types; **analytics module** using Google Analytics for tracking performance, events, and user interaction . **Best for researchers and developers** wanting a scalable, extensible framework for interactive video experiments—explicitly designed for education, marketing, and entertainment research, but it is a framework requiring development work rather than a turnkey tool .

- **[H5P Interactive Video](https://github.com/h5p/h5p-interactive-video)**  
  A mature open-source **H5P content type** for adding texts, tasks, and other media on top of video (MIT for H5P core) . **H5P** is a broad interactive learning-content framework with open-source and hosted paths; the Interactive Video content type is widely used in Moodle, Canvas, WordPress, and Drupal . **Best for education and LMS-native learning**—but H5P is positioned as an educational framework rather than a business marketing tool; marketing-specific features like lead capture and shoppable video are not its focus .

- **[Interactive Video Animation Player](https://github.com/fix2015/interactive-video-player)**  
  An open-source **library for stitching video clips into interactive animations or branching games** . Features: **combine multiple video files** into cohesive animations; **interactive flow buttons** for branching scenarios; **dynamic video quality adjustment** based on detected internet speed; **caching and buffering** for smooth playback; **cross-browser compatibility**; **poster generation** to prevent white screens during transitions . **Best for interactive games and branching narratives**—but it is a technical library for video stitching, not a marketing engagement platform .

### Shoppable Video Components (DIY)

- **shoppable-video (rohitraj-11)** — An open-source **serverless web app** that lets users snap scenes, identify items, shop products, and get movie suggestions (JavaScript, 1.7MB) . **Early-stage** (1 star, pushed 12 months ago) — a proof-of-concept for shoppable video rather than a production platform .
- **Cloudinary Shoppable Video Demo** — A **tutorial and code sample** for building a shoppable video player in Next.js using Cloudinary's video capabilities . **Best for developers** wanting a starting point to build custom shoppable video—not a standalone tool .

**Frameworks for building custom systems**: For an **education-focused interactive player with quizzes, annotations, and LMS integration**, OVAL provides the most complete open-source option . For a **research-backed, extensible framework with YAML specifications**, IVA . For **H5P ecosystem integration**, H5P Interactive Video . For **branching video games/animations**, Interactive Video Animation Player . **No open-source project matches the lead-capture, CRM integration, and shoppable-video workflows** of Mindstamp or Wistia—open-source players focus on engagement (quizzes, annotations) rather than conversion (forms, product links, paywalls) .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Interactive video platforms handling viewer data and engagement metrics must comply with applicable privacy regulations (GDPR, CCPA) and consent requirements; **self-hosted solutions place full responsibility for data storage, security, and analytics accuracy on the operator**.
- **Open-source interactive video is mature for engagement features but fragmented for marketing conversion**—OVAL and IVA provide robust quiz, annotation, and branching capabilities , but **no open-source project matches the lead-capture, CRM integration, and shoppable-video workflows** of Mindstamp or Wistia. Choose based on whether you need engagement (OVAL, IVA, H5P) or conversion (commercial platforms).
- Verify license terms for commercial use; OVAL uses BSD 2-Clause , IVA is open-source (check repository) , and H5P uses MIT for its core .

---

**Made for marketers, instructional designers, and developers building interactive video experiences.**  
Let's make interactive video more open at the engagement layer, but with clear eyes about the lead-capture and shoppable-video conversion gaps that commercial platforms still fill.
