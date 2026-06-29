# Read it 1000 Years Later Legal

This public repository hosts privacy, legal, and support documentation for **Read it 1000 Years Later**, a Chrome side panel extension for summarizing, translating, asking questions about, and generating deep-read notes from web pages.

The main extension source repository may be private, but the Chrome Web Store requires a publicly accessible privacy policy. This repository provides that public policy URL and a public contact channel for privacy or support questions.

## Install

<a href="https://chromewebstore.google.com/detail/read-it-1000-years-later/bpdledepfcohbimofppegfpdnadhabij"><img src="https://storage.googleapis.com/web-dev-uploads/image/WlD8wC6g8khYIiJ_MSB1dHMvNv42/x2SfGFKnc0yEZ0mMKOgL.svg" alt="Available in the Chrome Web Store" height="48"></a>

> Requires Google Chrome latest stable version and a compatible LLM API key (OpenAI Chat Completions format).

## Product Overview

Read it 1000 Years Later helps users process long web pages from a Chrome side panel. It extracts readable page content, generates summaries, translates on demand, answers follow-up questions grounded in the current page, and can optionally create deep-read notes for later research. Deep-read notes can be synced to GitHub via Device Flow.

| Dark mode | Light mode |
|:----:|:------:|
| <img width="369" height="916" alt="dark mode screenshot" src="https://github.com/user-attachments/assets/f9fec3f5-bc83-4086-a194-8f20bd1173db" /> | <img width="369" height="916" alt="light mode screenshot" src="https://github.com/user-attachments/assets/15f1258a-c89f-4b5e-a4fc-48299039c42c" /> |

### Core Features

1. **Side Panel Content Extraction**: Click `Summarize` on any web page and the extension uses Mozilla Readability to extract the main content from articles, blog posts, documentation, and more.
2. **Summary View**: Generates streaming summaries with a quick overview, detailed breakdown, key concepts, and extended references, helping you decide whether a page is worth a deeper read.
3. **Language Switching and On-Demand Translation**: Default summary language can follow your browser locale, or be set to English or Chinese. The initial summary is generated in one language; switching languages triggers a translation based on the existing summary.
4. **Ask Mode**: Ask follow-up questions grounded in the current page. Answers combine the generated summary, relevant source text snippets, recent conversation history, and compressed chat context.
5. **Deep Read**: Generates a standalone single-file research README that can be copied, regenerated, and — importantly — is kept separate from Summary, Ask, and original page content when syncing to GitHub.
6. **GitHub Vibe Research Sync**: Connect a GitHub repository via GitHub App Device Flow to save generated deep-read README files under a configured owner, repo, branch, and path prefix.

    <img width="345" height="624" alt="github vibe research screenshot" src="https://github.com/user-attachments/assets/4a500c57-045c-4d60-9e09-8c5f93d75d30" />

7. **AI Settings**: Configure LLM provider (DeepSeek or OpenRouter), API key, endpoint URL, default summary language, and separate model selections for Summary/Ask and Deep Read.

    <img width="344" height="635" alt="ai settings screenshot" src="https://github.com/user-attachments/assets/4b0d7c47-6d74-452e-b9ba-3105f38a6229" />

8. **Local Article Cache and Domain Blocking**: Optionally store summaries, deep-read drafts, and recent Ask history in extension local storage (6 MB cap). Block specific domains in the settings to skip processing on unwanted pages.

### Usage Flow

1. Open a readable web page.
2. Click the extension icon to open the side panel.
3. Click `Summarize` to generate a summary and tags.
4. Switch languages in the `Summary` view, or enter `Ask` mode to ask follow-up questions.
5. When you need a more complete research note, use `Deep Read` to generate a README.
6. After connecting GitHub, sync deep-read README files to your configured repository path.
7. To regenerate a summary, click `Regenerate Summary` in `Summary` mode.

## Privacy and Data Handling

User data handling is described in the [Privacy Policy](./PRIVACY.md). Key points:

- Page content extraction happens locally in the browser.
- Summary, translation, and Q&A requests are sent only to the HTTPS LLM endpoint you configure.
- API keys and tokens are stored in Chrome extension local storage on your device.
- Local article cache is opt-in and stored only on your device (6 MB cap).
- The extension does not sell user data or use it for advertising, profiling, or retargeting.

## Documents

- [Privacy Policy](./PRIVACY.md)

## Contact

For privacy questions, data handling questions, or support requests, please open an issue in this repository:

https://github.com/KrabsWong/read-it-1000-years-later-legal/issues
