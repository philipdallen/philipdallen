# Philip Allen

I am a technical project manager and a trained classical musician. I run an independent research program on representation: how ideas get encoded so that machines and people can both work with them. In plain terms, it asks one question in several materials: what form does an idea need to be in before someone, or something, can actually use it?

The program has three fronts. Maith builds machine-usable versions of formal mathematics. Ephapse reads the internal representations inside open-weight AI models. Idea Garden preserves human-legible representations: a capture-and-curation system for ideas. Rubato applies the same program to music, as an AI-native music format. PleaNP is formal-mathematics infrastructure alongside Maith, and HuB is the dashboard over all of it.

I direct the work; AI agents do most of the implementation; I specify, review, and verify. The discipline is the point: control tests that prove a detector works before its results are believed, failure tests written down in advance, append-only decision logs, and negative results kept on the record.

New here? Start with Rubato for the concrete version, or HuB for the live state of everything.

**Saratoga Springs, NY** · [LinkedIn](https://www.linkedin.com/in/allenpd) · philip.d.allen@gmail.com

---

## Public

### [Maith](https://github.com/philipdallen/Maith)

A pipeline in Lean 4 (a proof assistant: software that checks mathematical proofs mechanically) that converts mathematics from a large formal library into a structured form a language model can train on, and tests whether that helps the model prove theorems. The record keeps its own corrections: the retraction of the first accuracy results and a later reset, after data leakage was found, both stand in the README, not edited away. Current frontier: axiom discovery.

### [PleaNP](https://github.com/philipdallen/PleaNP)

Formal-mathematics infrastructure for the barriers around the P vs NP problem: the theorems showing which kinds of proof attempts provably cannot settle the question. The foundations are machine-checked with no admitted gaps. The main barrier result is written down exactly, with its two admitted gaps tracked openly; it is not claimed as proved.

### [ephapse](https://github.com/philipdallen/ephapse)

Looks inside open-weight AI models for an accident: two unrelated inputs switching on the same internal feature, which might point at a connection nobody was looking for. The results so far are honest nulls. The largest probe found nothing above the threshold set in advance, while its control test proved the detector worked. A second line closed on 2026-10-20 because its measuring instrument failed its own control test. Neither result is dressed up.

### [rubato](https://github.com/philipdallen/rubato)

An executable, AI-native music format: the score, plus a written brief for how it should be played, plus a plain-text record of who owns the rights. Format-first: musical decisions live in the specification, not in the tools. The sample library is served from a live CDN; no commercial sample library has been attained yet, and the log discloses that too.

### [HuB](https://github.com/philipdallen/HuB)

A read-only dashboard aggregating delivery status from the program's repos. The live state of everything above, in one place: the second click from this page.

---

## Private (available on request)

These repositories are private. Each claim below is dated; I open the repos to serious readers on request, so the claims are checkable, just not in public.

- **idea-garden**: the human-legible front of the program. A capture-and-curation system for ideas, with an AI curator (Tender) that proposes changes as pull requests. As of 2026-10-20 the live garden holds 49 inbox captures and 10 entries in its conservatory, the section for ideas chosen to keep.
- **rorschach**: how AI readings of ambiguous images diverge, and what the divergence carries. The headline result is stated with its uncertainty, and the record keeps the results it later retracted.
- **agent-method-experiment**: does a documented, structured multi-agent method beat a solo agent on identical frozen tasks? Two pilot pairs are complete; both returned the outcome registered in advance, `no_clear_effect`, with both sides scoring at the maximum. The confirmatory run has not been run.
- **recon-task, recon-task-b, recon-task-v2, recon-task-b-v2**: the frozen starting-point repos for that experiment, one pair per iteration. The two sides differ only by the method file under test.
- **well-tempered-model**: tests whether a language model's temperature setting (how random its answers are) behaves like a musical temperament, using prelude-and-fugue material as the test bed. A full trial (10 temperatures, 5 repetitions, 100 calls) is authorized in the repo's protocol and not yet run on main; pilot results are labeled probes, not claims.
- **memory-palace**: the visual arm of the program. Rooms and artifacts built as images in staged passes, all following one shared visual key, with checks that fail a pass which breaks the key.
- **logos**: an experiment in emergent communication: whether two AI agents invent a shared language. Designed and specified; not yet run.
- **wmfallen**: selected applied work outside the program: a headless inventory manager built for a family antiques business, live against the shop's existing website system, with phone photo upload and HTTP-level tests.

---

Open to music technology and systems/integration roles, research collaborations, and fellowships. Private repos open on request.
