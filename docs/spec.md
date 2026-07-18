# Audience — Expert reader — throughline source

This document is **generated from the graph** by `tl docs`; `tl docs --check` gates
it in CI. The prose headings are hand-owned — everything between `tl:*` markers is
injected from the YAML items, so the published spec can never drift from the graph.

This source is the **audience axis** for one level: an **expert** (specialist) reader
with full command of the field. It governs how the writing is *calibrated* to the
reader's expertise — assumed knowledge, terminology, depth, orientation and examples —
not universal readability, spelling, punctuation, register, purpose, medium or brand
voice, each of which is its own throughline source. Audience levels are mutually
exclusive: **expert**, **practitioner** and **general** are sibling sources and a
consumer composes exactly one under the `audience` namespace. Every principle is a
`user_requirement`; every rule is a `system_requirement` that `implements` its
principle. The throughline UIDs are this source's own and immutable — a consumer cites
a rule as `audience:SR-0001`.

It carries
<!-- tl:count type == 'user_requirement' -->
5
<!-- tl:end --> principles and
<!-- tl:count type == 'system_requirement' -->
10
<!-- tl:end --> rules.

## Purpose

<!-- tl:item INT-0001 -->
**INT-0001 — Text is pitched for an expert reader** — `intent`, status `approved`

> An expert reader has full command of the field. They expect the writing to build on shared fundamentals, use precise terminology without definition, go to full technical depth, and get straight to the substantive point rather than orienting them to basics they already hold. This axis governs how the writing is calibrated to the reader's expertise — assumed knowledge, terminology, depth and orientation — not universal readability, spelling, register or purpose, each of which is a separate source. Audience levels are mutually exclusive: a consumer composes exactly one of the expert, practitioner or general sibling sources.

**source_ref**: TBS Audience — Expert reader
<!-- tl:end -->

## 1. Assume full command of the field's fundamentals

<!-- tl:item UR-0001 -->
**UR-0001 — Assume full command of the field's fundamentals** — `user_requirement`, status `approved`

> Take the field's fundamentals as shared ground and build on them rather than re-establishing them.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Expert reader — Assumed prior knowledge
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0001' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0001 | system_requirement | approved | Build on shared expert knowledge; do not re-explain the fundamentals |
| SR-0002 | system_requirement | approved | Use the field's standard acronyms, processes and roles without introduction |
<!-- tl:end -->

## 2. Use precise field terminology without defining it

<!-- tl:item UR-0002 -->
**UR-0002 — Use precise field terminology without defining it** — `user_requirement`, status `approved`

> Use the field's exact technical vocabulary and notation, unglossed, so meaning stays precise.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Expert reader — Terminology and jargon
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0002' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0003 | system_requirement | approved | Use exact technical terms and notation without glossing them |
| SR-0004 | system_requirement | approved | Prefer the precise technical term over a plain-word paraphrase |
<!-- tl:end -->

## 3. Go to full technical depth

<!-- tl:item UR-0003 -->
**UR-0003 — Go to full technical depth** — `user_requirement`, status `approved`

> Give the specialist detail, mechanisms and edge cases an expert needs to reason about the subject.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Expert reader — Depth and detail
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0003' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0005 | system_requirement | approved | Include the specialist detail, mechanisms and edge cases |
| SR-0006 | system_requirement | approved | Explain how it works, not only what it means |
<!-- tl:end -->

## 4. Skip basic orientation; open at the substantive point

<!-- tl:item UR-0004 -->
**UR-0004 — Skip basic orientation; open at the substantive point** — `user_requirement`, status `approved`

> Start at the substantive question and treat the wider context as already held.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Expert reader — Context and orientation
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0004' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0007 | system_requirement | approved | Open at the substantive question, not with background the expert holds |
| SR-0008 | system_requirement | approved | Assume the wider context and motivation are known; do not restate them |
<!-- tl:end -->

## 5. Use domain examples, standards and prior work as reference points

<!-- tl:item UR-0005 -->
**UR-0005 — Use domain examples, standards and prior work as reference points** — `user_requirement`, status `approved`

> Anchor points in the field's own cases, standards and established results.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Expert reader — Examples and reference points
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0005' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0009 | system_requirement | approved | Illustrate with domain-specific cases and examples from the field |
| SR-0010 | system_requirement | approved | Cite standards, literature or established results as shared reference points |
<!-- tl:end -->
