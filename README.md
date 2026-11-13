# CV tailoring skill for Claude

**Give Claude a job advert and your master CV. Get back a tailored CV that shows the fit, and a score out of 10.**

This is a skill for Claude. It will:

1. **Read** the advert and build a scorecard of what the employer asks for, in their order.
2. **Map** each requirement to real evidence in your master CV, and list any gaps in plain words.
3. **Draft** a CV from your template: the same headings, two pages, and bullets that lead with the skills the employer named and show results.
4. **Score** the finished CV out of 10 against the advert, and save the breakdown so you can see why it got that mark.

It never adds a claim your master CV doesn't support.

---

## What it checks

- **Fit:** does page one show the job title, sector fit and two numbers within about seven seconds?
- **Coverage:** does each essential requirement have specific evidence? Requirements with no honest evidence are flagged, not hidden.
- **Wording:** does the CV use the employer's vocabulary where it is true, and avoid buzzwords and unsupported adjectives?
- **Bullets:** does each one name a skill, show what was done, give the scale, and end with a result?
- **Honesty:** would the employer feel misled if they knew the full story behind each line?
- **Format:** two pages, one column, no icons, skill bars or photos, and text that reads cleanly when parsed by applicant tracking systems.

## What you get

- **A tailored CV draft** in your template, ready to export as a PDF.
- **A scorecard and evidence map:** each requirement, the evidence used for it, and any gaps.
- **A score out of 10**, with the breakdown: essential criteria, desirable criteria, mirroring the advert, and specificity.
- **A short list of things to rewrite in your own words** before sending.

## How to use it

**Install**
- **Claude app / claude.ai:** download this repository as a ZIP (green **Code** button › **Download ZIP**), then upload it under **Settings › Capabilities › Skills**.
- **Claude Code:** run `git clone https://github.com/muhammad-karim/cv-tailoring ~/.claude/skills/cv-tailoring`

**Then just ask, for example:**
- "Tailor my CV to this job: [paste the advert]"
- "Score this CV against the job spec: [paste the CV and the spec]"
- "Which requirements in this advert does my CV not cover?"

## How it works

1. **Prepare:** read the full advert and any person spec, then build the scorecard and evidence map before any writing starts.
2. **Draft:** use the template, keep to its headings, and write the bullets in the four-part structure (skill, action, scale, result).
3. **Check and score:** run the honesty test, check the page count in the exported PDF, and score against the rubric in `SKILL.md`.

## What's in this repository

```
SKILL.md        The instructions Claude follows (with plain-English notes)
README.md       This file
```

## Set-up

The skill refers to "the candidate's master CV" and "the candidate's template". Before use, point it at your own:

1. Put your master CV in one document. Every fact, title, date and number in a tailored CV must come from it.
2. Make one CV template in your preferred layout, with the headings you want, and copy it for each application.
3. Tell Claude the links to both, once, at the start of a session.

## Good to know

- Scores are honest, not generous. A low score tells you where the gaps are.
- The score can't go above 7 if any essential requirement has no evidence.
- Always export the CV to PDF and check the page count before sending.

## Licence

MIT. Free to use and adapt.
