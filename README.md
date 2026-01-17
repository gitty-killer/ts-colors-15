# ts-colors-15

A small TypeScript tool that computes text statistics for colors.

## Goal
- Provide quick text metrics for colors documents.
- Report top word frequencies for fast inspection.

## Usage
ts-node index.ts data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Notes
- Only ASCII letters and digits are treated as word characters.
