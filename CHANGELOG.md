# Read it 1000 Years Later Changelog

Public release notes for the Chrome extension.

<!-- read-it-1000-years-later:v1.2.1:start -->
## Version 1.2.1

This release adds a reading trail to summaries for easier navigation and updates the DeepSeek V4 integration to use the Responses API for more reliable performance.

## Highlights

- Added a reading trail to summary results, making it easier to locate the source text behind each summary point.
- Switched DeepSeek V4 models to the Responses API for improved stability and accuracy.
<!-- read-it-1000-years-later:v1.2.1:end -->

<!-- read-it-1000-years-later:v1.2.0:start -->
## Version 1.2.0

This release adds a new web research provider powered by DeepSeek Responses, improves localization and sidepanel behavior, and refactors the extension internals for cleaner, more maintainable code.

## Highlights

- Added DeepSeek Responses support for web research, with a new research mode and refined output handling.
- Improved sidepanel state and web research supplements, making research results more stable and localized.
- Refactored the sidepanel into focused, modular components, reducing complexity and improving performance.
- Updated documentation and packaging for the extension and repository.
<!-- read-it-1000-years-later:v1.2.0:end -->

<!-- read-it-1000-years-later:v1.1.6:start -->
## Version 1.1.6

This release adds a new Tencent Token Plan for accessing token-based services and simplifies the reading workflow in the side panel.

## Highlights

- Added Tencent Token Plan support for users who need token-based authentication.
- Simplified the side panel reading flow with a cleaner and more direct interface.
- Updated user-facing text across all supported languages.
- Streamlined background processing to make the extension faster and more reliable.
<!-- read-it-1000-years-later:v1.1.6:end -->

<!-- read-it-1000-years-later:v1.1.5:start -->
## Version 1.1.5

This release adds the ability to archive original articles with atomic GitHub synchronization and improves the empty-state experience after using Deep Read.

## Highlights

- Archive original articles directly to a GitHub repository with atomic sync
- Improved empty-state display in the Summary panel after performing a Deep Read
- Enhanced background and content scripts for more reliable synchronization
- Refreshed side panel interface with better handling of archived content
<!-- read-it-1000-years-later:v1.1.5:end -->

<!-- read-it-1000-years-later:v1.1.4:start -->
## Version 1.1.4

This release switches the npm registry to the official one, improving the reliability and consistency of dependency resolution during builds.

## Highlights

- Updated npm registry source for improved build consistency
<!-- read-it-1000-years-later:v1.1.4:end -->

<!-- read-it-1000-years-later:v1.1.2:start -->
## Version 1.1.2

Fixed an issue where the OpenRouter model catalog was not refreshing correctly, ensuring the latest models are always available in the side panel.

## Highlights

- Updated model catalog refresh logic for OpenRouter
- Ensures new and updated models appear promptly
- Improves reliability when selecting models in the side panel
<!-- read-it-1000-years-later:v1.1.2:end -->

<!-- read-it-1000-years-later:v1.1.1:start -->
## Version 1.1.1

This release redesigns the changelog display inside the extension, now rendering entries with Markdown for better readability. The changelog entry has also been moved into the settings header for easier access.

## Highlights

- Redesigned changelog with Markdown rendering for improved formatting
- Moved changelog entry to the settings header area
- Internal CI improvements for version synchronization
<!-- read-it-1000-years-later:v1.1.1:end -->

<!-- read-it-1000-years-later:v1.1.0:start -->
## Version 1.1.0

This release adds OpenRouter provider settings and introduces a public changelog sync feature, along with various UI updates and workflow improvements.

## Highlights

- Added OpenRouter provider settings, enabling new AI model access options
- New public update changelog sync for better visibility of release changes
- Enhanced sidepanel UI with significant interface updates
- Improved packaging workflow for extension releases
<!-- read-it-1000-years-later:v1.1.0:end -->