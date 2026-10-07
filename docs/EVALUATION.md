# S.K. Velayutham School — Evaluation guide

Start with the smallest path that exercises the project. Distinguish source inspection,
syntax/build checks, functional behavior and domain validation when recording a result.

## Guided reading and demonstration

1. **Read the introduction.** Open the landing section and inspect school identity and the
English/Tamil strings attached to content.

2. **Explore education and campus.** Move through education stages, sports, academics, events and
facilities. Verify image meaning and content accuracy with the school.

3. **Review admissions.** Inspect the admissions date and enquiry controls. These are public
content and UI, not evidence that an admissions backend exists.

4. **Check both languages.** Test language switching, navigation, narrow screens and keyboard use.
Missing translations or focus behavior affect the actual reading path.

## Declared checks

These commands/checks describe the intended verification path. Their presence in this
guide does not claim that they passed. See the dated evidence below and the README for setup.

```text
python3 -m http.server 8080 --bind 127.0.0.1
```

## Evidence levels

| Level | What it establishes | What it does not establish |
| --- | --- | --- |
| Source review | A path exists in tracked code | Successful runtime behavior |
| Syntax/build | Parser/compiler accepts that path | End-to-end correctness |
| Behavioral check | A specific input/output case passed | Generalization beyond cases |
| Domain evaluation | Performance on a stated target setting | Other users/data/environments |

## What to record

- Commit, environment, dependency versions and date.
- Input provenance and whether data is synthetic, public or privately supplied.
- Absolute pass/fail/skip counts; keep failed cases and their root causes.
- Whether external services, hardware or a production deployment were actually exercised.
- Expected output and an artifact showing the observation.

## Review scenarios

- **Single-page structure:** Related school information stays within one navigation context.

- **Paired language strings:** English and Tamil content sit with the corresponding elements.

- **Content is separate from service:** A form presentation does not establish a delivered enquiry
workflow.

## Documentation inspection — 7 October 2026

The documentation was traced to committed source and checked for local links, balanced
code fences and supported implementation claims. Historical notebook outputs remain labeled
as historical. Live provider access, private databases and hardware behavior are not inferred
from configuration or dependency files. Any fresh run is recorded separately in the README.

## Next evidence to collect

- Validate admissions copy with the school.
- Test both language paths and enquiry actions.
- Record mobile and accessibility acceptance evidence.

## Fresh checks

The README records fresh checks on 7 October 2026, including commands and absolute results.
Those measured checks supersede an inspection-only description for the paths they cover.
