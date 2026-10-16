# Research, skill discovery, and fallback

1. Identify the precise uncertainty that matters to the current decision.
2. Inspect relevant repository evidence if available. Prefer targeted searches and a small number of important files over a full repository crawl.
3. Discover relevant installed specialist skills/capabilities using the host's documented mechanism, **if available**. Do not assume a universal skill registry or invocation API.
4. Delegate a bounded task only when the specialist is demonstrably better suited and invocation is supported. Example: “Check whether the existing metrics exporter already exposes CPU pressure; report files, limitations, and evidence. Do not modify code.”
5. If no suitable skill exists, use built-in local file/search/shell tools, documentation access if provided, and ordinary reasoning. Do not fabricate access or evidence.
6. Separate findings into Verified / Inferred / Unknown, with source locations or links where available.
7. Return to the conversation with only decision-relevant findings, not a raw research dump.

Feasibility checklist (use selectively): compatibility, integration points, hidden dependencies, cost to build, migration, operations, maintenance, testing, security, rollback, and reversibility.

Prefer existing solution -> adapt existing solution -> custom solution -> novel architecture, unless the context supports another ordering. Research is for reducing decision risk, not for maximizing tool usage.
