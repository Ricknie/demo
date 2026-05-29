# Timestamp Converter

A lightweight bilingual timestamp utility site built as a single static HTML page. It runs fully in the browser and does not upload user input.

## What Was Added

### Layer 1: Core Timestamp Converter

- Unix timestamp to date conversion.
- Date to Unix timestamp conversion.
- Automatic input detection for:
  - Unix seconds
  - Unix milliseconds
  - Unix microseconds
  - Unix nanoseconds
  - ISO/date strings
- Current live Unix timestamp.
- UTC, local time, selected timezone, RFC 2822, and relative time output.
- One-click copy for each result.
- English and Chinese UI switching with local preference storage.

### Layer 2: Advanced Tools

- Batch timestamp converter for logs, CSV exports, database rows, and analytics data.
- CSV copy output for batch conversion results.
- Time difference calculator for two dates in the selected timezone.
- Cron schedule preview for five-field cron expressions.
- Cron support includes `*`, numbers, ranges, lists, and step expressions such as `*/15`.

### Layer 3: SEO And Shareability

- Real static URL pages for long-tail search intents:
  - `/unix-timestamp-converter`
  - `/timestamp-to-date`
  - `/date-to-timestamp`
  - `/milliseconds-to-date`
  - `/batch-timestamp-converter`
  - `/time-difference-calculator`
  - `/cron-expression-preview`
  - `/current-unix-timestamp`
- URL lookup support through query values:
  - `?t=1713528896`
  - `?t=now`
- FAQ content for common timestamp questions.
- Bilingual metadata and UI copy.
- Default language is English, with Chinese available from the language switcher.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `Intl.DateTimeFormat`
- Browser `Intl.RelativeTimeFormat`
- Browser `localStorage`
- Browser Clipboard API

## Local Preview

Open `index.html` directly in a browser, or serve the folder with any static server.

Example:

```bash
npx serve .
```

The project has no build step and no runtime dependencies.
