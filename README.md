# Plan Mock Data

Mock data for spiritual practice plans in multiple languages and sprints.

## Structure

- `data/` - Source Dart files with plan data
- `mock-data/` - Generated JSON files organized by sprint
- `plan_listing.json` - Main plan listing format file

## Languages

- **Tibetan (bo)** - Traditional Tibetan Buddhist practices
- **English (en)** - English translations and teachings
- **Chinese (zh)** - Chinese Buddhist texts and practices

## Sprints

- Sprint 13: Mind Training practices
- Sprint 14: Vajrasattva purification practices
- Sprint 15: Tara practice (Green Tara prayers)
- Sprint 16: Bodhisattva's Way of Life teachings
- Sprint 17: Anger management practices
- Sprint 18: Medicine Buddha healing practices

## Data Format

Each sprint contains structured JSON with:

- Plan metadata (title, description, duration)
- Daily tasks (verses, teachings, meditation, practice)
- Unique UUID4 identifiers
- Content types: TEXT, VIDEO, AUDIO, IMAGE

Generated from Dart map objects with consistent formatting across all languages.
