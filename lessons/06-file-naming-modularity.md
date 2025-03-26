# File Naming and Modularity Matter

## Summary
Since tools like Cursor/Windsurf don't include all files in context (to reduce their costs), accurate file naming prevents code duplication. Make sure filenames clearly describe their responsibility.

## Detailed Explanation
AI tools work with limited context to manage costs and performance. Clear file names help AI understand where code should go and what it does, preventing it from recreating existing functionality. Good modularity also makes it easier for AI to focus on specific parts of your code.

## Tips
- Give files descriptive, purpose-indicating names
- Keep related functionality together
- Structure code in logical, focused modules
- Make file responsibilities clear from their names

## Common Mistakes
- Using generic file names
- Spreading related code across multiple files
- Having files with mixed responsibilities
