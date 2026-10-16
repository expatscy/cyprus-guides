# Contributing

Thank you for helping keep these guides accurate. Every pull request is read by the expats.cy editor before it is merged and published.

## What we accept

- **Corrections**: outdated fees, deadlines, addresses, office hours, links, rules.
- **Updates** when a law or procedure changes.
- **New guides** on living in Cyprus that aren't covered yet.
- **Translations** of existing guides into `en`, `ru`, `de`, `ar` or `he`.

## Rules

1. **Prove every fact.** For each fact you add or change, add a row to the evidence table in the pull request: claim → official source URL → date you checked it → value you saw there. Cite an official source: a Cyprus government site (`*.gov.cy`), an EU institution (`europa.eu`), legislation (`cylaw.org`), or the organisation's own official site. Put the link in the text or in the pull request description.
2. **No personal data about private people**: no names, phone numbers or emails of individuals. Public institutions and businesses' official contact details are fine.
3. **No advertising**: no affiliate links or promotion of your own business. Businesses can be listed in the [expats.cy directory](https://expats.cy/pricing/).
4. **Write in your own words.** Don't paste text from other websites or copyrighted material.
5. **One topic per pull request**, so it can be reviewed quickly.

## File format

Files live at `<language>/<section>/<article>.md`. The header between `---` lines:

| Field | Required | Notes |
|---|---|---|
| `title` | yes | |
| `description` | yes | one or two sentences, used in search results |
| `date` | yes | first publication, `YYYY-MM-DD` |
| `updated` | when you change facts | today's date, `YYYY-MM-DD` |
| `translationKey` | for translations | same value in every language version of a guide |
| `slug` | no | URL part; keep the existing one when editing |
| `tags`, `category` | no | |
| `faqSchema` | no | list of `question` / `answer` pairs |

When you change a fact, set `updated` to today's date.

## Licence of your contribution

Before your first pull request is merged, you sign the [Contributor License Agreement](CLA.md) (a bot asks you on the pull request). Under it you assign the copyright in your contribution to DailyMind LTD, the operator of expats.cy, and get a licence back to use your own text. expats.cy publishes merged changes under [CC BY-SA 4.0](LICENSE) and may also use them in its other products. The commit history credits every contributor. Details: [NOTICE](NOTICE).
