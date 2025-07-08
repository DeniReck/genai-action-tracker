# genai-action-tracker
This tool uses GPT-4 to extract structured action items, owners, and due dates from messy, unstructured meeting transcripts.

## Why it Matters
Unlike basic Copilot summaries, this version:
- Infers action items from fragmented conversations
- Normalizes deadlines (e.g. "next Friday" → concrete date)
- Outputs a clean task table (CSV/Excel/Markdown)
- Can be integrated with Notion or Jira

## How it Works
1. Paste in a transcript (example provided)
2. Run prompt via ChatGPT or OpenAI API
3. Get:
   - Bullet-point summary
   - Action item table
   - Follow-up flags

## Sample Output
| Task | Owner | Due Date | Priority |
|------|-------|----------|----------|
| Talk to Legal | Sarah | 2025-07-12 | High |

## Files Included
- `sample_transcript.txt` – input
- `prompt_template.md` – optimized prompt
- `output_example.md` – example result

## Future Plans
- Integrate with Power Automate
- Export directly to Excel or Jira

## Author
Deniz Reckermann
