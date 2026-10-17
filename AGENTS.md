# AGENTS.md

Instructions for AI assistants and agents that edit this repository. Humans: see [CONTRIBUTING.md](CONTRIBUTING.md); the rules are the same.

## What this repository is

The editorial guides of [expats.cy](https://expats.cy) about living in Cyprus, in `en`, `ru`, `de`, `ar` and `he`. Licence: CC BY-SA 4.0. Every change is reviewed by a human editor before it is published. Readers rely on these guides for visas, taxes and documents, so a wrong fact can cost someone money or a deadline.

## Hard rules

0. **Ask before working.** Search open issues and pull requests (`gh issue list`, `gh pr list`). If the topic is taken, not planned, or has no go-ahead from the editor (issue or the expats.cy Telegram group, https://t.me/expatscy), stop and ask the human. Exception: typos, broken links, one outdated fee or date.
1. **Never invent facts.** No guessed fees, deadlines, addresses, phone numbers, office hours or legal requirements. If you can't verify a fact, leave the existing text as it is and say so in the pull request.
2. **Verify against an official source and cite it.** Open the page and check the value: `*.gov.cy`, `europa.eu`, `cylaw.org`, or the organisation's own official site. Put the URL in the text or in the pull request description, with the date you checked it.
3. **Set `updated:`** in the header to today's date (`YYYY-MM-DD`) whenever you change a fact.
4. **Write original text.** Don't copy from other websites; CC BY-SA 4.0 content from elsewhere (e.g. Wikipedia) may be adapted only with attribution in the pull request.
5. **No personal data** about private individuals. Public institutions and businesses' official contacts are fine.
6. **No advertising, affiliate or referral links.**
7. **Disclose AI help** in the pull request description (e.g. "Drafted with Claude, facts checked against the linked sources").

## File format

- Path: `<language>/<section>/<file>.md`. Sections: `immigration`, `documents`, `business`, `property`, `life`, `beyond-borders`, `videos`.
- File names: lowercase, words separated by hyphens, Latin letters (transliterate for `ru`, `ar`, `he`).
- YAML header between `---` lines. Required: `title`, `description`, `date`. Keep existing `slug`, `translationKey` and `date` unchanged when editing; changing `slug` breaks the page's URL.
- Translations: same `translationKey` as the original; translate `title`, `description`, `faqSchema` and the body. Write natural text in the target language rather than a word-for-word translation, and keep facts, numbers and links identical to the source.
- `videos/` files describe YouTube videos (`youtube_id`, `duration`, `upload_date`): fix descriptions or transcripts only, never the video metadata.
- Body: Markdown. Use `##`/`###` headings, lists for steps and documents, and links to official sources.

## Pull requests

- One topic per pull request; describe what changed and why.
- Fill the evidence table in the pull request: one row per changed fact (claim → official source URL → date checked → value seen). A fact without a row is not merged.
- Don't reformat files you didn't otherwise change.
- Don't edit `LICENSE`, `README.md`, `CONTRIBUTING.md`, `AGENTS.md` or `.github/` unless that is the point of the pull request.
