# AI Journey Companion

An interactive guidance and training tool from the **DCI AI Hub for Social Protection**. It helps social protection institutions plan, assess and govern AI systems, step by step, using the AI Hub knowledge products.

**Open the tool:** see the GitHub Pages link in the repository's About section (Settings → Pages).

## What it does

- **Nine stages, from first idea to monitoring and retirement.** Stages 1–3 (shared language, readiness, governance) are done once per institution. Stages 4–9 are done for each AI system, after a short triage that sets a light or full path.
- **Built on the AI Hub publications:** the Taxonomy, the Global Evidence Review, the Risk Assessment Framework and its four tools, the Data Sovereignty report, and the draft Governance Playbook, Procurement Toolkit, AI Register template and Model Card.
- **Comparable cases:** each system is matched against the cases in the [AI Hub Tracker](https://socialprotectionai.org/) (snapshot of 13 November 2026).
- **Documents filled as you go:** Model Card, risk assessment (Tools 1–4), Risk Register, AI Register entry, Sovereignty Schedule, gate decision record, and an institutional readiness report, downloadable as Word, Excel or CSV.
- **Facilitator pack:** workshop and gate meeting plans, and a presenter mode for the Governance & Readiness Walk.
- **Two worked examples, loaded on request:** a fictional multilingual benefits chatbot (Modern Standard Arabic, Lebanese Arabic, French, English) in a social assistance agency in Lebanon, and a fictional job matching assistant for employment counsellors in Morocco. The tool starts empty.

## Privacy

The tool is a single static page. Answers are stored only in the user's own browser (localStorage) and can be downloaded as a journey file to share or back up. Nothing is sent to a server. Word and Excel files are generated in the browser using the open-source [docx](https://github.com/dolanmiu/docx) and [SheetJS](https://sheetjs.com/) libraries, loaded from public CDNs.

## Status

Prototype. Several underlying AI Hub products are drafts; check the final published versions before relying on them. The tool is guidance, not legal advice.

## Updating

Everything is in `index.html`. Edit it and push to `main`; GitHub Pages republishes automatically.

## Licence

Apache License 2.0. See [LICENSE](LICENSE).
