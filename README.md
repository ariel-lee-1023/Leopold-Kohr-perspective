# Leopold-Kohr-perspective

A distilled **perspective skill** for LLM agents: reason and write about political power, social
size, federation, development, prosperity, cities, traffic, universities, and the good life the way
Leopold Kohr (1909–1994) does—look beneath ideology for dimension, test every institution against
the function it performs, contract what has passed its optimum, and join only the functions whose
reach genuinely requires breadth.

The skill is written in English, in the first person, as a voice rather than a description of one.
It can be installed as a file-based agent skill or used as a system prompt.

It was produced with [persona-distiller](https://github.com/ariel-lee-1023/persona-distiller) from
six supplied works segmented into seven analytical clusters: 359,964 words and approximately
883,318 heuristic tokens.

## Repository layout

```text
Leopold-Kohr-perspective/
├── SKILL.md
├── references/
│   ├── frameworks.md
│   ├── voice.md
│   └── clusters/
│       ├── c01-customs-unions.md
│       ├── c02-development-without-aid.md
│       ├── c03-breakdown-of-nations.md
│       ├── c04-academic-inn.md
│       ├── c05-inner-city.md
│       └── c06-overdeveloped-nations.md
├── fidelity-ledger/
│   ├── provenance.md
│   ├── episodic.md
│   └── fidelity.json
├── CHANGELOG.md
├── LICENSE
├── NOTICE.md
└── README.md
```

`SKILL.md`, `references/voice.md` and `references/frameworks.md` are all required in full before the first substantive reply, including short answers. `references/frameworks.md` supplies full definitions,
causal rules, standing verdicts, and a construct index. `references/voice.md` supplies the measured
three-register expressive system and applies from the first reply. The six work modules
add domain-specific apparatus and applications. The two ledger Markdown files and `fidelity.json`
are audit records and should never be loaded as persona context.

The c02 module also declares c07 because the debate is a separately segmented portion of the same
book. Only Kohr's marked replies in that section were used; other speakers never enter the voice
baseline.

## Activation

Before the first substantive answer, read the complete [SKILL.md](SKILL.md),
[voice](references/voice.md) and [frameworks](references/frameworks.md), including for
short replies. The core supplies the perspective, voice supplies its expressive
system, and frameworks supplies its conceptual and reasoning distinctions. Reuse files
already fully retained in context; reload missing files after compaction. Add topic,
work or mode modules when relevant. For a chat without file access, supply all three
complete texts at the start.

This loading-only update has not been reassessed. Existing assessment results remain
attached to the runtime inputs and scope originally tested.

## Usage

### As a file-based skill

```bash
git clone https://github.com/ariel-lee-1023/Leopold-Kohr-perspective.git \
  ~/.claude/skills/Leopold-Kohr-perspective
```

An agent reads the frontmatter in `SKILL.md`, then reads the full core, voice and frameworks
before answering. Its loading table selects additional work modules when relevant.

### As a system prompt

Paste the body of `SKILL.md` after the frontmatter together with the complete
`references/voice.md` and `references/frameworks.md`. Add the relevant cluster module
for specialized work. Do not add `fidelity-ledger/` to the
prompt; it documents the build rather than the perspective.

## Design notes

**Scale is relational, not a slogan.** The core does not equate smallness with goodness. It asks
whether the size of a unit matches its function and environment, and prefers smallness because it
limits the radius of error, preserves exit, and keeps causes visible.

**Refusals carry the identity.** Eight cost-bearing positions remain in the core: against world
political unification, aid-as-development, output as welfare, road capacity as a traffic cure,
university expansion, sentimental small-state innocence, national villain stories, and the false
choice between autarky and centralized union.

**Three registers remain separate.** A forensic technical-historical register belongs to customs
unions; an architectonic developmental register to *Development Without Aid*; and an
analogical-satirical social philosophy register to the other four works. Names-masked blind
classification separated nine sampled passages perfectly, although that sample is small.

**Coinages are throttled.** The ordinary machinery is *size*, *power*, *function*, *division*, and
*balance*. Rarer labels such as *power theory*, *velocity theory*, *Aspirin Standard*, *translucent
society*, and *luxometer* are used only when their exact mechanism is active.

### Factual cutoff

The source record runs from the 1949 customs-union study through the 1993 *Academic Inn*, with
later collections reprinting some earlier material. Kohr died in 1994. Host agents should retrieve
current facts first and then apply the perspective. Nothing here supplies knowledge of later events.

## Provenance and honesty

The [provenance ledger](fidelity-ledger/provenance.md) records corpus boundaries, all 45 extracted
elements and their allocation, computed and realized budgets, register measurements, gates, package
checks, and limitations. The [episodic ledger](fidelity-ledger/episodic.md) keeps one-off happenings
away from reusable reasoning. `fidelity.json` mirrors the test results in machine-readable form.

Headline results and their limitations are kept in those files. The initial projection gate scored
1.00 on five masked items, but the sample omitted the urban domain and the same distiller predicted
and graded it. Register discrimination scored 1.00 on nine passages. These are evidence of internal
assembly discipline, not claims of independent historical or psychometric validation.

The source corpus is not included. The original text in this repository is MIT licensed; that
license does not extend to any referenced source work.

## Contributing

Issues and pull requests are welcome, especially for independently graded projection tests, private
letters or recorded conversations, denser coverage of the 1958–1972 interval, and material needed
to assess how Kohr's method behaves under live interpersonal pressure. Changes to the persona should
update the changelog and provenance ledger together.

MIT © 2026 Ariel Lee. [See LICENSE](LICENSE).

