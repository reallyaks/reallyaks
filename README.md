English-law drafting tools.

- [clause-diff](https://github.com/reallyaks/clause-diff) — two DOCX drafts in, a Word redline out. [NDA sample](https://github.com/reallyaks/clause-diff/blob/main/samples/nda/redline.md)
- [citation-check](https://github.com/reallyaks/citation-check) — neutral citations, law reports, and ibid. [Sample report](https://github.com/reallyaks/citation-check/blob/main/samples/citation-report.md)
- [agent-trace-eval](https://github.com/reallyaks/agent-trace-eval) — twelve tasks for an OpenAI-compatible model. Refusing an invented citation is the one that matters. [Scorecard](https://github.com/reallyaks/agent-trace-eval/blob/main/samples/scorecard.md)
- [hearing-timeline](https://github.com/reallyaks/hearing-timeline) — a planning-committee transcript turned into a timeline. [Sample](https://github.com/reallyaks/hearing-timeline/blob/main/samples/timeline.md)
- [notice-window](https://github.com/reallyaks/notice-window) — notice periods in a contract.
- [defined-terms](https://github.com/reallyaks/defined-terms) — quoted definitions.
- [signature-blocks](https://github.com/reallyaks/signature-blocks) — By / Name / Title blocks.
- [party-extract](https://github.com/reallyaks/party-extract) — the two parties in a between-recital.

Clause Diff is Node. The rest are Python. A model is called only when both `OPENAI_BASE_URL` and `OPENAI_API_KEY` are set.
