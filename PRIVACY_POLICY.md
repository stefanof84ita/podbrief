# Privacy Policy — PodBrief

**Last updated:** March 27, 2026

## Overview

PodBrief is a browser extension that summarizes Spotify podcast episodes using AI. We are committed to protecting your privacy and being transparent about how data is handled.

## Data Collection

PodBrief does **not** collect, store, or transmit any personal data to our servers. We do not operate any backend servers.

## What Data is Processed

When you use PodBrief, the following data is processed **locally in your browser**:

- **Podcast transcripts**: Read directly from Spotify's website to generate summaries. Transcripts are sent to your chosen AI provider (e.g., Groq, OpenRouter) for analysis and are not stored by PodBrief.
- **Episode metadata**: Title, show name, and duration are used to display information in the extension UI.
- **API keys**: Your AI provider API key is stored locally in Chrome's extension storage and is only sent to the AI provider you configure.
- **Usage counter**: A daily count of analyses is stored locally to enforce free tier limits.
- **Cached analyses**: Previously generated summaries are cached locally in your browser to avoid redundant API calls.

## Third-Party Services

PodBrief sends podcast transcripts to third-party AI providers for analysis. Which provider is used depends on your settings:

- **Groq** (api.groq.com) — [Privacy Policy](https://groq.com/privacy-policy/)
- **OpenRouter** (openrouter.ai) — [Privacy Policy](https://openrouter.ai/privacy)
- **Anthropic** (api.anthropic.com) — [Privacy Policy](https://www.anthropic.com/privacy)
- **Custom providers** — as configured by you

PodBrief also uses **ExtensionPay** (extensionpay.com) for Pro subscription management, which processes payments through Stripe. See [ExtensionPay's Privacy Policy](https://extensionpay.com/privacy) and [Stripe's Privacy Policy](https://stripe.com/privacy).

## Data Storage

All data is stored locally using Chrome's `chrome.storage.local` API:

- API keys and settings
- Cached episode analyses
- Daily usage counters
- Subscription status

No data is stored on any external server operated by PodBrief.

## Data Sharing

PodBrief does **not** sell, share, or transfer your data to any third party, except as described above (sending transcripts to your chosen AI provider for analysis, and subscription management through ExtensionPay/Stripe).

## Permissions Explained

- **storage**: Save your settings and cached analyses locally
- **sidePanel**: Display the analysis panel alongside Spotify
- **tabs**: Detect when you switch podcast episodes
- **scripting**: Read podcast transcripts from Spotify pages
- **host_permissions (open.spotify.com)**: Access Spotify pages to read transcripts
- **host_permissions (API providers)**: Send transcripts to your chosen AI provider

## Children's Privacy

PodBrief is not directed at children under 13. We do not knowingly collect data from children.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last updated" date above.

## Contact

For privacy questions or concerns, contact: stefanof84ita@gmail.com
