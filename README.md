# ER Abdomen Companion

An indication-based reading checklist and reporting aid for emergency abdominal CT.

The radiologist selects the clinical question (for example RLQ pain, renal colic or blunt trauma). The tool then shows a tailored review checklist, a list of commonly missed diagnoses for that indication, and an every-scan sweep. Items marked normal become pertinent-negative sentences; items marked abnormal become prompts in a draft report. A grading module covers AAST 2018 liver, spleen and kidney injury, the modified CT severity index with revised Atlanta collection terms, and CT signs of closed-loop obstruction and ischaemia in small bowel obstruction.

**Live version:** https://ashnad235.github.io/ER-Abdomen-Companion/

## Author

Dr Ashraf Nadaf, MD, DNB, EDiR, FRCR
Specialist Radiologist, Abu Dhabi, UAE
ORCID: [0000-0003-1838-325X](https://orcid.org/0000-0003-1838-325X)

Clinical content and design by the author. Built with AI assistance (Claude, Anthropic).

## How to cite

Nadaf A. ER Abdomen Companion: an indication-based reading checklist and reporting aid for emergency abdominal CT [web application]. Version 1.0. 2026. Available from: https://ashnad235.github.io/ER-Abdomen-Companion/

GitHub also shows a "Cite this repository" button generated from `CITATION.cff`.

## Data and privacy

The tool runs entirely in the browser. It does not ask for or store patient identifiers, and no checklist content or report text ever leaves the browser. Checklist marks are saved only in the user's own browser.

The public site counts visits and a few anonymous actions (indication chosen, grade added, report copied) with [GoatCounter](https://www.goatcounter.com/), which uses no cookies and does not identify visitors.

## Scope and limitations

This is an educational and reporting aid, not a diagnostic device. Grading criteria are summarised from the published AAST Organ Injury Scale (2018 revision), the revised Atlanta classification (2012) and the modified CT severity index (Mortele 2004). Users should verify criteria against the source publications and apply their own clinical judgement.

## Publishing on GitHub Pages

1. Create a free account at github.com and a new public repository named `er-abdomen-companion`.
2. Upload all files in this folder (Add file → Upload files), then commit.
3. Open Settings → Pages. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/er-abdomen-companion/`.
5. Put that link in this README, in `CITATION.cff` (`url`), and in the `CREDITS.url` field near the top of the script in `index.html`.

## Changelog

- **1.0 (October 2026):** first release. Eleven indications, every-scan sweep, AAST liver/spleen/kidney, pancreatitis mCTSI + Atlanta, SBO risk signs, report draft with copy.

## Licence

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0). See `LICENSE`.
