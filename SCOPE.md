# Product Scope: What OpenCloud Is and What It Isn't

**OpenCloud lets everyone edit and share content together: as simply as possible, regardless of budget, ability, or corporate accounts.**

## Who is OpenCloud for?

**For everyone, explicitly including the people who usually aren't taken into account.**

- For people with limited financial means.
- For people with visual, motor, or cognitive impairments.
- For people who don't want a Google or Microsoft account, or can't have one.
- For people who depend on protection from surveillance and oppression.

The same goes for running it: OpenCloud isn't aimed only at professional admins, but especially at private operators without specialist knowledge.

## What content is OpenCloud specialized in?

**In focus:** office documents, PDFs, and text-based formats like Markdown. For this content we optimize things like organization and discoverability through good navigation, search, and metadata.

**Not in focus:** code and media files (audio, video, photos). You can of course store these files, but the core application does not aim to optimize managing them. There are specialized programs for that: Git for code, Immich for photos, Jellyfin for video, Navidrome for music.

**Core vs. extensions:** where integrating such applications makes sense, we do it through extensions, so the core application stays stable and controllable.

## How is OpenCloud different from other clouds?

**KISS - Keep it Simple Stupid: for end users and admins**

- **Simple for end users**: usable without having to read a manual. Where it makes sense, supported by automation or AI.
- **Simple for admins**: as little effort as SaaS, but on-premises. Operations stay simple, no matter how much data comes in and how large it gets. And the data stays where it belongs: with you. No unwanted leakage, no loss.
- **Stupid standards instead of building our own:** we don't reinvent the wheel, we stick to standards, in the interface as well as in the technology. Interaction conventions and WCAG on one side, WebDAV, OpenID Connect, and S3 on the other: what is established, we don't rebuild.

## Collaboration without barriers

- **Sharing:** controlled shares with any recipient on the internet, human or machine, even without an account of their own.
- **Editing at the same time:** with people and AI agents, online or offline, without version chaos.
- **Traceable:** every change is visible and recoverable. You can't break anything.
