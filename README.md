# Time Zone Converter

A glanceable React component that compares multiple time zones at once. Add favorite cities, see each zone's current local time side by side, with automatic daylight-saving adjustments.

## Features

- Compare multiple time zones in a single view
- Add and remove favorite cities
- Automatic daylight-saving time adjustments
- Clean card-based UI built on shadcn/ui

## Tech Stack

- React (hooks: `useState`, `useEffect`)
- shadcn/ui (`Button`, `Card`, `Input`)
- Lucide icons
- WorldTimeAPI

## Quick Start

The component lives in the `Time Zone Converter` file. Copy it into any React + TypeScript project that has shadcn/ui set up:

1. Copy the file contents into e.g. `src/components/TimeZoneConverter.tsx`
2. Make sure the `@/components/ui/*` imports resolve in your project
3. Render `<TimeZoneConverter />` where you want it

No auth or API keys needed — it uses device time settings plus WorldTimeAPI.

## Project Structure

```
.
├── Time Zone Converter   # The React component (TSX source)
├── README.md
└── LICENSE
```

---

Built by Girish Lade — https://ladestack.in
