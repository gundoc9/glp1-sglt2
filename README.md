# GLP-1 agonists and SGLT2 inhibitors before surgery: six AI models, twelve questions

Twelve perioperative questions on GLP-1 agonists (including tirzepatide) and SGLT2 inhibitors, put to six AI models three times each through OpenRouter. Every answer is placed by whose guidance the model named, US on the left and UK on the right, and set against the 2025 and 2026 references.

Live page: https://gundoc9.github.io/glp1-sglt2/

## What is in the page

- A cover, then one screen per question with the US and UK reference in a block at the top, one row per model, and a chip per run.
- Green chip: the model named US guidance. White chip with a black edge: UK guidance. Grey chip under the model's name: no guidance named, or guidance from elsewhere. Dashed: no number given.
- A closing screen with all twelve questions by all six models.
- Sources sheet with links to every guideline and paper used in the reference lines.
- Tap a model's name to read its three answers, the source it named and its caveat.

## Running it yourself

The page is one file with no server. Open `index.html#setup`, paste an OpenRouter key (kept only in your browser), pick the models, and ask. Twelve questions, six models, three runs each is 216 replies, about $2 to $3.50. "Save a copy with this run built in" downloads an `index.html` with the answers inside and no key.

## Files

- `index.html`: the page.
- `glp1-sglt2-card.png`: the social card (1200 × 630).
- `glp1-sglt2-icon-180.png`: the icon.

## Sources

The reference lines draw on: the FDA 2020 label change for SGLT2 inhibitors; ADA Standards of Care 2026, section 16; the 2024 ACC/AHA perioperative guideline; the SPAQI 2026 SGLT2 inhibitor consensus (Oprea et al., Br J Anaesth 2026); the SPAQI 2025 GLP-1 consensus (Oprea et al., Br J Anaesth 2025); the 2024 multisociety GLP-1 guidance (Kindel et al.); the ASA 2023 consensus-based guidance; the UK multidisciplinary consensus (El-Boghdadly et al., Anaesthesia 2025); and the Dhatariya, Levy and El-Boghdadly 2026 letter in Anaesthesia. Full citations and links are in the page's Sources sheet.

## Method notes

Each question went to each model three times through OpenRouter, at the models' default settings, asking for one JSON object: a number (or none), whose guidance the answer follows (US, UK, other or none), the source named, one caveat and a one-line answer. The questions were written in British English, which may nudge a model towards UK sources. Sources are shown as the models wrote them; some do not exist and none were checked by the page.

Answers are what six models said on the run date. They are not advice.

Dr Ganesh Sivasankara · MD · FRCA · FCARCSI · Consultant Anaesthetist

Licence: CC BY-NC-ND 4.0 (see LICENSE).
