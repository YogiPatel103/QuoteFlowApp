# QuoteFlow

QuoteFlow is a colourful motivational quotes mobile app built with Expo and React Native.
It shows famous motivational quotes in a swipeable short-form feed, similar to a TikTok-style experience.

Made by Yogi Halai 2026.

## Screenshots

| Quotes Feed | Library |
| --- | --- |
| <img src="docs/screenshots/quotes-feed.jpeg" width="220" alt="QuoteFlow quotes feed screen" /> | <img src="docs/screenshots/library.jpeg" width="220" alt="QuoteFlow library screen" /> |

| Saved Quotes | About |
| --- | --- |
| <img src="docs/screenshots/saved-quotes.jpeg" width="220" alt="QuoteFlow saved quotes screen" /> | <img src="docs/screenshots/about.jpeg" width="220" alt="QuoteFlow about screen" /> |

## Features

- Animated opening screen
- Colourful QuoteFlow logo
- Vertical swipe quote feed
- Famous quotes with author names and context
- Searchable quote library
- Saved quotes page
- Share quote button
- Bright colourful mobile UI
- Expo Go support

## Tech Stack

- Expo
- React Native
- Expo Router
- TypeScript
- React Native Animated API
- Material Icons from `@expo/vector-icons`

## Getting Started

Install dependencies:

```bash
npm install
```

Start the Expo development server:

```bash
npm.cmd start
```

Then open the app using Expo Go:

1. Install Expo Go on your phone.
2. Make sure your phone and computer are on the same Wi-Fi.
3. Scan the QR code shown in the terminal.

## Useful Commands

Start the app:

```bash
npm.cmd start
```

Run on Android:

```bash
npm.cmd run android
```

Run on web:

```bash
npm.cmd run web
```

Check the project:

```bash
npm.cmd run lint
npx.cmd tsc --noEmit
```

## Project Structure

```text
app/
  index.tsx              Animated opening screen
  _layout.tsx            Root app layout
  (tabs)/
    index.tsx            Swipe quote feed
    explore.tsx          Quote library
    saved.tsx            Saved quotes page
    settings.tsx         About page
    _layout.tsx          Tab navigation

components/
  quote-logo.tsx         Colourful QuoteFlow logo

constants/
  quotes.ts              Famous motivational quotes

hooks/
  use-saved-quotes.tsx   Shared saved quotes state
```

## App Pages

### Quotes

The main swipe feed. Users can swipe up and down through quotes, save quotes, and share them.

### Library

A searchable list of all quotes in the app.

### Saved

Shows all quotes the user has bookmarked.

### About

Shows app information, quote stats, the logo, and the credit.

## Credit

Made by Yogi Halai 2026.

