# Google Veo Software Tutorial Workflow

A creator-led software tutorial workflow for Google Veo. It combines a presenter, real screen recordings, generated Veo inserts, and an **example document pack** that is created before filming and reused consistently throughout the video.

## What changed in the production flow

The workflow now begins with realistic, internally consistent example documents. It defines the scenario, people, dates, figures, and source relationships first; creates polished source files and a finished example output; checks the pack for contradictions; and then plans the tutorial around those exact documents. The on-screen demonstration opens those files and uses them in the actual software being taught.

The documents should look like credible working materials—meeting minutes, survey summaries, budget notes, reports, briefs, forms, or other artifacts relevant to the lesson—with professional hierarchy, metadata, tables, realistic language, and complete content. They must remain clearly example documents for training use and must not imitate real people, companies, government agencies, credentials, or authentic official records.

## Reference style

The supplied reference is a 10:13, 16:9 software tutorial. A seated host speaks to camera, alternating with readable full-screen desktop demonstrations. The host introduces the goal, explains decisions and returns for recap; screen capture carries the exact steps. The edit uses occasional cursor emphasis, controlled crops/zooms, a title and a lower third. The style is practical and creator-led, not a cinematic short film.

## Veo production approach

Veo generates short illustrative clips and optional host segments. It does not replace the real product interface or the real example documents. Capture actual documents and software actions separately, with synthetic data only. Add titles and labels in the editor, not in generated imagery.

## Files

- `SYSTEM_PROMPT.md` — reusable Veo-specific production instructions, including document-pack creation.
- `sample/README.md` — sample concept, document-pack design, and scene plan.
- `sample/SCRIPT.md` — original tutorial narration.
- `sample/VEO_PROMPTS.md` — optional Veo insert prompts.
- `sample/DOCUMENT_PACK.md` — document facts, consistency ledger, and source relationships.
- `sample/documents/` — screen-ready HTML versions of the example documents that can be opened and captured on screen. Editable DOCX versions can also be generated as local assets.

## Start a production

1. Load `SYSTEM_PROMPT.md` into your production agent.
2. Supply topic, target viewer, ratio, runtime, Veo interface, host availability, and desired example-document formats.
3. The agent designs and creates the example document pack first, then checks the facts across files.
4. Use those exact documents in the actual software demonstration; capture the real app and real outputs.
5. Verify the selected Veo model's current settings before generating short inserts, record the host and screen steps, and assemble in a timeline editor.

## Model note

Veo product features and model names change. Google documentation distinguishes capabilities by model and interface. Check the active model settings and official docs linked from `SYSTEM_PROMPT.md` before production.

## Output status

The sample includes a script, storyboard, document-pack specification, screen-ready example documents, and Veo prompts. No generated Veo clips or finished tutorial video are included; rendering requires access to Veo and a timeline editor.

