---
title: Research Sidebar Privacy Policy
---

# Research Sidebar Privacy Policy

Last updated: 27 October 2026

Research Sidebar ("the extension", "we") is a Chrome extension that helps you read and understand research papers. This policy explains what data the extension handles, why, and the choices you have.

## The short version

- The extension only reads a page or PDF when you ask it to.
- Your reading history, research focuses and settings stay on your device.
- Paper content you choose to read is sent to an AI provider to create summaries and evidence labels.
- We do not sell your data, use it for advertising, or use it for anything other than the extension's features.

## Data stored on your device

The following is saved in your browser's local extension storage and is not sent to us:

- Reading history: paper titles, authors, links, DOIs, summaries, evidence labels and favourites.
- Research focuses, optional "AI memory" details you enter (for example your research field), citation style and other settings.
- Your daily AI-action count.
- If you connect ChatGPT, the sign-in tokens OpenAI issues to the extension.

You can remove individual papers from the Reading History dashboard at any time. Uninstalling the extension deletes all of this data from your browser.

## Data sent for AI processing

When you click "Read this page", paste a link or DOI, choose a PDF, ask the assistant a question, or request a synthesis, the extension sends the following to an AI provider:

- The text of the paper or page you chose (and its link or DOI).
- Your question, your active research focus and any AI memory details you saved.
- Relevant saved paper summaries when you ask about your saved papers.

Which provider receives it depends on your setting in Options:

- **Default (Perplexity):** requests go through our server, a Cloudflare Worker, to the [Perplexity API](https://www.perplexity.ai/hub/legal/privacy-policy). Our server passes the request on and returns the answer. It does not store your content, keep a log of what you read, or create an account for you. Cloudflare, which runs the server, may process technical data such as IP addresses to deliver and secure the service ([Cloudflare privacy policy](https://www.cloudflare.com/privacypolicy/)).
- **ChatGPT (optional):** if you choose to connect your own ChatGPT account, requests go directly from your browser to OpenAI using your account. Our server is not involved. OpenAI's handling is covered by the [OpenAI privacy policy](https://openai.com/policies/privacy-policy/).

All data is sent over encrypted HTTPS connections. The extension does not read pages in the background or collect browsing activity you did not ask it to process.

## What we do not do

- We do not sell or transfer your data to third parties, except to the AI provider needed to perform the action you requested.
- We do not use or transfer your data for advertising, personalised ads, or to determine creditworthiness or for lending purposes.
- We do not allow humans to read your data, except where you ask us for support, where it is needed for security, or where the law requires it.

The use of information received from Google APIs and Chrome extension features follows the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/), including the Limited Use requirements.

## Permissions

- **Side panel**: shows the Research Sidebar next to the page.
- **Active tab, scripting and site access**: lets the extension read the paper page or link you choose. Research papers are hosted on many different websites, so access is not limited to specific sites, but nothing is read until you act.
- **Storage**: saves your history and settings on your device.
- **Identity**: used only if you choose to connect ChatGPT through OpenAI's sign-in page.

## Children

The extension is not directed at children under 13 and we do not knowingly collect their data.

## Changes

If we change how data is handled, we will update this page and the date above, and tell you in the extension before any new kind of data is used.

## Contact

Questions or requests: please open an issue at [github.com/anson215925-svg/research-sidebar-privacy/issues](https://github.com/anson215925-svg/research-sidebar-privacy/issues).
