# Memini

Memini is a free, offline-first multilingual flashcard application for creating vocabulary decks and studying languages.

Your decks, images, and learning progress are stored locally on your device. No account or subscription is required.

## Live app

[Open Memini](https://sdpabo.github.io/memini/)

## Features

- Create and customize flashcard decks
- Choose a color and symbol for each deck
- Add words, meanings, readings, notes, and parts of speech
- Add example sentences and translations
- Upload your own images
- Search for reusable images through Openverse
- Find translations and dictionary meanings online
- Browse cards individually or with the deck viewer
- Flip cards between the word and its meaning
- Study one or multiple decks
- Use several test modes:
  - Flashcards
  - Sentence → word
  - Image → word
  - Word → image
  - Meaning → word
  - Word → meaning
  - Mixed mode
- Review cards with spaced repetition
- Repeat a completed study session
- Export and restore backups
- Install the app as a PWA
- Continue using core features offline

## Supported interface languages

- English
- Ukrainian
- Japanese
- Chinese

Parts of speech, test modes, navigation, settings, and other interface elements are localized according to the selected interface language.

## Privacy and local storage

Memini is local-first.

Decks, cards, attached images, settings, review history, and learning progress are stored in the browser using IndexedDB.

The application does not currently provide accounts or cloud synchronization. Users should export backups regularly, especially before clearing browser data or changing devices.

External searches require an internet connection and may send the search term and selected language to the corresponding public provider.

## External services

Memini uses free or keyless providers where possible:

- [Openverse](https://openverse.org/) for reusable image search
- [MyMemory](https://mymemory.translated.net/) for translation suggestions
- [Free Dictionary API](https://dictionaryapi.dev/) for English dictionary results
- Wiktionary APIs for supported dictionary lookups

Selected images are downloaded and stored locally so they remain available offline.

Availability and request limits depend on the external providers.

## Technology

- React
- TypeScript
- Vite
- React Router
- Dexie and IndexedDB
- i18next
- Vite PWA
- Vitest
- Lucide icons
