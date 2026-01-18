# ts-colors-15

A small TypeScript tool that computes text statistics for colors.

## Objective
- Provide quick text metrics for colors documents.
- Report top word frequencies for fast inspection.

## Use cases
- Validate colors drafts for repeated terms before review.
- Summarize colors notes when preparing reports.

## Usage
npx ts-node index.ts data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Testing
- run `bash scripts/verify.sh`

## Notes
- Only ASCII letters and digits are treated as word characters.
