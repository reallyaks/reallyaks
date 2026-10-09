Small legal and agent tools. Not a firm, and not legal advice.

Open these three first. Each one has a sample already in the repo.

- [clause-diff](https://github.com/reallyaks/clause-diff) — two DOCX drafts in, a Word redline out, with moves and phrase comments. Open [the NDA redline](https://github.com/reallyaks/clause-diff/blob/main/samples/nda/redline.md).
- [agent-trace-eval](https://github.com/reallyaks/agent-trace-eval) — the model work. Twelve tasks against any OpenAI-compatible endpoint, and a dry-run scorecard you can read with no key. The citation-refusal task is the one that matters. Open [the scorecard](https://github.com/reallyaks/agent-trace-eval/blob/main/samples/scorecard.md).
- [citation-check](https://github.com/reallyaks/citation-check) — a memo in, a citation-form report out. Open [the report](https://github.com/reallyaks/citation-check/blob/main/samples/citation-report.md).

The rest, one line each.

- [hearing-timeline](https://github.com/reallyaks/hearing-timeline) — a timestamped hearing transcript turned into a timeline.
- [notice-window](https://github.com/reallyaks/notice-window) — notice periods pulled out of a contract.
- [defined-terms](https://github.com/reallyaks/defined-terms) — quoted definitions, as JSON.
- [signature-blocks](https://github.com/reallyaks/signature-blocks) — By / Name / Title blocks.
- [party-extract](https://github.com/reallyaks/party-extract) — the two parties named in a between-recital.
- [technical-curriculum](https://github.com/reallyaks/technical-curriculum) — a short Python script that prints file names and sizes.

Stack: Python, an OpenAI-compatible API when a key is set, sqlite or plain files. Clause Diff is Node.
