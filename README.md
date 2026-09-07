# AI-Scribe-Template
Template for rheumatology clinic visits

Click on [Rheumatology-Note.txt](https://github.com/psufka/AI-Scribe-Template/blob/main/Rheumatology-Note.txt) to access the current version of this template. 

**To use:**

Copy the entire document, and paste it in the template portion of the AI scribe of your choice. 

Feel free to edit and redistribute, as per standard [MIT License](https://github.com/psufka/AI-Scribe-Template/blob/main/LICENSE).

## Updates

**2026-09-07**
- Removed HPI instruction subheadings so studies and social/family details flow within the narrative; explicitly prohibited HPI category labels and missing-history statements.
- Added medication spelling references, including Systane, Bimzelx, TNF inhibitors, and selected biosimilars; retained dictated brand, formulation, and biosimilar identity.
- Changed ordered-lab wording to “See lab workup including…” with only explicitly named tests.
- Reorganized the HPI into concise implied-subject narrative, a separate prior-treatment paragraph, denials, studies, and social/family history; placed treatment discussions and decisions in Assessment & Plan.
- Put assessment paragraphs directly above their bullets, grouped continued medications, kept prednisone and each new medication on separate lines, and standardized follow-up spacing.
- Added the specified oral methotrexate tablet-to-mg conversion and conditional folic acid default, plus new-medication discussion wording.
- Added suggested outpatient ICD-10-CM codes after the task list.

**2026-07-30**
- Removed all markdown bold markers (`**`) from headers — scribes were copying the literal asterisks into note output
- Added explicit plain-text-only output rules (no asterisks, bold, underscores, hashtags, or backticks)
- Clarified that square brackets are placeholders to replace, never to output
- Standardized all bullets to hyphens

**2026-07-15**
- Rewrote the template for shorter, more structured rheumatology notes
- Strengthened explicit-only documentation rules to prevent invented findings, denials, tests, tolerance, or counseling
- Added labeled subjective, objective, injection, assessment/plan, and task-list fields with omit-if-empty behavior
- Corrected the longitudinal-care add-on label from `G5521` to `G2211`

**2026-02-07**
- Added `**Subjective:**` header for clean SOAP note structure
- Standardized all instructions to bracket notation (removed inconsistent parenthetical formatting)
- Expanded injection section: now prompts for medication/dose, anesthetic, guidance method (ultrasound vs landmark), and consent
- Cleaned up G5521 longitudinal care code section: separated instruction logic from boilerplate text, fixed typo
- Added medication adherence prompt (missed doses, difficulty obtaining medications, prior authorization issues)
- Expanded to-do list with specific categories: labs, imaging, referrals, prior authorizations, medication refills, patient education
- Expanded "Additionally" paragraph to capture medication tolerance, insurance/access barriers, and upcoming procedures affecting treatment
