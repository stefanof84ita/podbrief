# Privacy Policy — PodBrief

**Last updated:** April 6, 2026

## Overview

PodBrief is a Chrome browser extension that summarizes Spotify podcast episodes using AI. This privacy policy explains what data is collected, how it is used, stored, and shared.

## Data We Collect

### Data collected automatically

- **Anonymous usage events**: PodBrief uses Google Analytics 4 (via the Measurement Protocol) to collect anonymous usage events, including: extension installed, onboarding completed, and first summary generated. Each event is associated with a randomly generated client ID stored locally on your device. No personally identifiable information (name, email, IP address) is collected through analytics.

### Data you provide

- **API key**: When you configure PodBrief, you enter an API key for your chosen AI provider. This key is stored locally in your browser and is sent only to the AI provider you selected.
- **Settings and preferences**: Your chosen provider, model, and auto-open preference are stored locally in your browser.

### Data processed temporarily

- **Podcast transcripts**: When you analyze an episode, PodBrief reads the transcript from the Spotify web page. The transcript is sent to your chosen AI provider (e.g., Groq, OpenRouter, Anthropic) for summarization. PodBrief does not store transcripts on any server.
- **Episode metadata**: Title, show name, and duration are used to display information in the extension UI and are stored locally as part of cached analyses.

## How We Use Your Data

- **Podcast transcripts and metadata** are used solely to generate AI-powered summaries, highlights, takeaways, and chapters for the episodes you choose to analyze.
- **API keys** are used solely to authenticate requests to your chosen AI provider.
- **Anonymous analytics events** are used to understand how the extension is used in aggregate (e.g., how many people install and complete onboarding) to improve the product.
- **Cached analyses** are stored locally to avoid redundant API calls when revisiting the same episode.

## How We Store Your Data

All user data is stored locally on your device using Chrome's \`chrome.storage.local\` API:

- API keys and settings
- Cached episode analyses
- Daily usage counters
- Subscription status
- Anonymous analytics client ID

PodBrief does not operate any backend servers. No user data is stored on any server operated by PodBrief.

## How We Share Your Data

PodBrief shares data with third parties only in the following cases:

- **AI providers**: Podcast transcripts are sent to the AI provider you configure (e.g., Groq, OpenRouter, Anthropic) for summarization. This only happens when you explicitly request an analysis. Each provider has its own privacy policy:
  - [Groq Privacy Policy](https://groq.com/privacy-policy/)
  - [OpenRouter Privacy Policy](https://openrouter.ai/privacy)
  - [Anthropic Privacy Policy](https://www.anthropic.com/privacy)
- **Google Analytics**: Anonymous usage events (no personally identifiable information) are sent to Google Analytics for aggregate product analytics. See [Google's Privacy Policy](https://policies.google.com/privacy).
- **ExtensionPay / Stripe**: If you subscribe to PodBrief Pro, payment processing is handled by ExtensionPay and Stripe. See [ExtensionPay's Privacy Policy](https://extensionpay.com/privacy) and [Stripe's Privacy Policy](https://stripe.com/privacy).

PodBrief does **not** sell or transfer user data to any other third parties.

## Data Retention

- **Local data** (settings, cached analyses, usage counters) persists until you uninstall the extension or manually clear Chrome extension data.
- **Analytics data** is retained by Google Analytics according to Google's data retention policies.
- **AI providers** may retain transcripts according to their own privacy policies. PodBrief does not control third-party data retention.

## User Rights and Choices

- **Uninstall**: You can remove PodBrief at any time, which deletes all locally stored data.
- **Clear data**: You can clear cached analyses by reinstalling or using Chrome's extension data management.
- **Choose your provider**: You control which AI provider receives your transcript data.
- **Analytics**: Analytics events are anonymous and cannot be linked to your identity. No opt-out mechanism is currently provided, as no personally identifiable information is collected.

## Permissions Explained

- **storage**: Save your settings, cached analyses, and usage counters locally
- **sidePanel**: Display the analysis panel alongside Spotify
- **tabs**: Detect when you navigate to a new podcast episode
- **host_permissions (open.spotify.com, spclient.wg.spotify.com, api.spotify.com)**: Access Spotify pages and APIs to read podcast transcripts
- **host_permissions (AI API providers)**: Send transcripts to your chosen AI provider for summarization
- **host_permissions (google-analytics.com)**: Send anonymous usage events for product analytics

## Children's Privacy

PodBrief is not directed at children under 13. We do not knowingly collect data from children.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last updated" date above.

## Contact

For privacy questions or concerns, contact: stefanof84ita@gmail.com
