# Privacy Policy

Last updated: June 17, 2026

Read it 1000 Years Later is a Chrome extension that extracts readable content from the current web page and helps users generate summaries, translations, follow-up answers, and optional deep-read notes.

## Data the extension handles

When you use the extension on a web page, it may process the current page URL, title, description, favicon, and readable text content. This data is used only to provide the extension's user-facing features: summarization, translation, page-grounded Q&A, deep-read README generation, blocked-domain checks, and optional GitHub sync.

The extension may store your settings locally in Chrome extension storage, including LLM endpoint, model names, default language, blocked domains, local cache preference, GitHub repository settings, and authentication tokens required for optional GitHub sync.

If local article cache is enabled, the extension stores summaries, deep-read drafts, and recent Ask history in Chrome extension local storage on your device. The cache is capped at 6 MB and can be cleared from the extension settings.

## How data is used

Page content and related context are sent to the LLM endpoint you configure in order to generate summaries, translations, answers, and deep-read drafts. The extension does not send page content to a developer-operated server unless you configure such a server as your LLM endpoint.

If you enable GitHub sync, the extension uses GitHub OAuth Device Flow and the GitHub API to save generated deep-read README files to the repository you configure. Summary and Ask conversations are not synced to GitHub by default.

## Data sharing

The extension does not sell user data and does not use user data for advertising, retargeting, or user profiling.

Data may be transmitted to:

- The HTTPS LLM API endpoint configured by the user.
- GitHub, only when the user connects GitHub and chooses to save generated deep-read notes.

## Security

API keys and tokens are stored in Chrome extension local storage on your device. The extension requires LLM endpoints to use HTTPS. GitHub API requests are sent over HTTPS.

Do not enter secrets that you do not want stored in Chrome extension local storage. You can remove stored GitHub tokens by disconnecting GitHub in the extension settings.

## Data retention and deletion

Settings, optional cached article data, and GitHub tokens remain on your device until you clear them, disconnect GitHub, remove the extension, or clear Chrome extension data.

You can clear cached article data from the extension settings. You can also remove all extension data through Chrome's extension management and browser data controls.
