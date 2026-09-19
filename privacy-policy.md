# Releaf Privacy Policy

Effective September 19, 2026 · Releaf 1.4.1

## What stays on your device

Releaf stores imported works and their source links, saved works, likes, ratings, private reviews, reading positions (page and a character anchor), reading timestamps, hashed identities of seen poems, reflections, and preferences in Chrome’s local extension storage. This data is not synced, sold, shared, or sent to an analytics service. There are no accounts, ads, or trackers.

## Website access

Releaf uses access to X, Twitter, Instagram, TikTok, and YouTube to display its reading overlay and pause audio and video on the main page. Extra websites are optional and request Chrome permission when you add them. Releaf checks the current hostname; it does not collect the social page’s content or access Chrome’s browsing-history database. Source URLs and reading activity are retained only for your library, progress, and recommendations. Temporary tab and hostname information used to manage reading breaks lives in session storage and is removed when tabs close or Chrome restarts.

## Imports and external links

When you open a reading link, request an offline copy, or refresh the catalog, Releaf connects directly to the selected source. Automatic poem updates are enabled by default and contact PoetryDB for small batches as you reach the end of the queue and for updated title/author metadata when the unread index is exhausted. You can turn them off in Preferences; an existing explicit opt-out is preserved. This public API permits cross-origin requests without an additional Chrome host permission. Discovery searches run on local metadata, so search terms are not sent to a search service. Catalog refreshes contact Project Gutenberg and PoetryDB. That website receives an ordinary network request, including your IP address. Releaf omits credentials and referrer information and requests no HTTP caching on these requests. Link-only works retain their URL, title, author, reading progress, and a small text-feature profile when relevant; their full text stays in bounded temporary memory until evicted or the reader closes. The active book and paginated text also occupy temporary memory. Uploaded works and explicitly requested offline copies retain their extracted text locally. Opening a source link visits that website under its own privacy policy. No imported text is sent to Releaf’s developer. The starter library and an additional reserve of poems drawn from already-installed collections work offline. Reserve bookmarks store source boundaries and metadata without duplicating the source text.

## Read aloud

Releaf includes the SVOX Pico speech engine and English voice resources inside the extension. Narration is synthesized locally in a worker and played through Web Audio. It does not use system-installed voices, remote speech services, or voice downloads. Text is never uploaded for narration.

## PDF and EPUB uploads

Uploaded files are processed locally by the included PDF.js and EPUB ZIP parsers. Only extracted text and basic book metadata are saved. No file or reading content is sent to a document conversion or OCR service.

## Poem suggestions

Releaf ranks poems locally using your likes, star ratings, previously opened works, and text features such as recurring imagery and length. Already-seen poems are excluded from the automatic feed using local reading records and hashes of normalized title/author identities and poem text. Hashes persist even if a reading link is removed, and erasing local data clears them. The library still allows intentional rereading. Likes on previously read poems continue to inform recommendations; author variety also influences the order. Reviews and reflections are not sent to a model or analyzed to infer personal traits. Removing a like or changing a rating updates future suggestions; erasing your local data resets the ranking.

## Control and deletion

You can switch off the online poem feed, remove individual imports and reading links, export your data as JSON, or erase local data from Preferences. Chrome removes local extension storage when you uninstall the extension. Exported files stay wherever you save them and must be deleted separately. You can revoke optional website permissions in Chrome’s extension settings.

## Permissions

Storage saves your personal reading data. Scripting registers the reading overlay on custom websites you choose. Host access displays the overlay on supported websites. Optional host access enables additional sites and requested source reading and catalog refreshes that need additional cross-origin access. Releaf does not request browsing history, cookies, microphone, camera, or broad required access to every website.

## Limited Use

Releaf uses reading data and website access only to provide its reading, recommendation, and reflection features. Releaf’s use of information complies with the Chrome Web Store User Data Policy, including its Limited Use requirements. Reading data is not used for advertising, sold to data brokers, used for credit decisions, or made available to the developer for human review.

## Contact

For privacy questions, contact the developer using the support contact on Releaf’s Chrome Web Store listing.

Changes to Releaf’s data practices will be reflected in this policy with an updated effective date.
