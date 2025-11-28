# CISC101-KattieTan-Group2-PaperSummarizer

# Paper Summarizer

This project is a modular LLM-based tool to summarize academic papers. It produces section-wise summaries, unified summaries, and a glossary, following strict spec-based constraints.

## Repository Structure

- `system_prompt.md` — Contains the main system instructions for the LLM.
- `modules/` — Contains modular prompt files:
  - `intake&setup_module.md`
  - `sectionloop_module.md`
  - `guardrails_module.md`
  - `render&refine_module.md`
  - `citationextractorandnormalizer_module.md`
  - `equationandconceptexplainer_module.md`
- `README.md` — Project overview and documentation.

## Usage

1. Open `system_prompt.md` in an LLM environment.
2. Feed the paper and required inputs as described in the modules.
3. Receive structured summaries according to the PS2 specification.
