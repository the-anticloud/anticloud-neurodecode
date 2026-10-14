# NEURODECODE

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-brain_computer_interface-lightgrey)

> Anticloud-hardened packaging of the upstream project `NEURODECODE` in category **BRAIN COMPUTER INTERFACE**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** BRAIN COMPUTER INTERFACE · **Upstream:** https://github.com/CheickDiakite-yikes/neurodecodekit · **Upstream pin:** `4e3be772f557b07ea8d4e220b1e3fe5e60d883cb` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# NeuroDecodeKit

Open-source, local-first, reproducible tools for turning EEG and MEG recordings
into small, inspectable neural language-decoding experiments without hiding
data access, split leakage, resource cost, or negative results.

NeuroDecodeKit is an independent research toolkit inspired by the access and
reproducibility problems around Brain2Qwerty-style decoding. It is not an
official Brain2Qwerty project, a medical device, or a demonstrated mind-reading
system.

```text
manifest -> selective download -> tiny shard -> event/sentence cache
         -> no-signal baseline -> neural baseline -> CER/WER report
```

The core thesis is practical: before another large model matters, a researcher
should be able to identify one legal dataset slice, inspect it locally, build a
bounded cache, preserve provenance, compare against a language-only control,
and explain exactly what the result does not prove.

Why the gates? Most routine engineering is reversible, but opening a held-out
target, reusing a consumed evaluation, or changing a rule after seeing the
outcome is not scientifically reversible. The approved
[Research Autonomy Charter](docs/RESEARCH_AUTONOMY_CHARTER_DRAFT.md) and its
[activation decision](docs/RESEARCH_AUTONOMY_CHARTER_DECISION.md) let
routine code, tests, synthetic work, bounded development experiments, commits,
pushes, and CI proceed autonomously while reserving exact approval for those
irreversible Tier C events.

## Scientific Operating Model

**Current result and priority (October 2, 2026):**
The [corrected session-2 temporal experiment](docs/INNER_SPEECH_TEMPORAL_ATTENTION_RESULT.md)
completed and scored once in **252 seconds**, retaining **1,994 trials**, all ten
people, three conditions and thirteen arms. **Primary, cue sensitivity and
progression all failed.** Inner-speech joint log-loss gain was **-0.006061 nats**
against peripheral/timing alone and **-0.008322 nats** against matched spectral
EEG; **0/10** people beat every control. Joint balanced accuracy was **22.15%**
versus 25% uniform. All nulls and secondary results remain in the
[aggregate](registries/inner_speech_temporal_attention_result.v0.json).
**Current blocker:** the approved three-file intracortical reference acquisition
stopped with an HTTP error after **1.062 seconds and zero archive bytes copied**.
No inventory, internal README, neural array, label, fit or score was opened.
The separately approved **0.61-second header-only diagnostic returned 403**,
with no redirect or body read. The [failure and next boundary](docs/THOUGHT_TO_TEXT_SCIENTIFIC_SWARM.md#approved-acquisition-stopped-at-http-transport)
preserve both attempts; the denial's cause is unknown. Next requires a normal
browser download or separately authorized authenticated API access, not an
anonymous retry. The scientific question remains attempted-speech transfer to
verbal versus visual rehearsal of the same arrows. No new decoding result is
claimed. Preserve session 3 and all consumed evidence.

The [scientific swarm review](docs/THOUGHT_TO_TEXT_SCIENTIFIC_SWARM.md) organizes
work around competing mechanisms, independent falsification and decisive data.
Its separate, parked candidate is a fixed beta-envelope trajectory test with
matched amplitude and circular-shift controls, unlike the completed raw-bin
comparison; no new experiment is authorized. The longer-term milestone is content
external cues cannot supply, with transfer to untouched words or days.

**Prior session-1 scientific result:**
The [completed ten-person imagined-word experiment](docs/INNER_SPEECH_OBSERVED_RESULT.md)
scored once in **245 seconds**, retaining 1,993 trials, all ten people, all three
conditions and all eight arms. The primary EEG increment **failed**: mean
inner-speech log-loss gain **-0.003282 nats**, only **1/10** people beating every
control (9/10 required). Joint inner-speech balanced accuracy was **24.58%**
against 25% uniform; peripheral/timing-only pronounced balanced accuracy was **83.69%**.
All negative and positive comparisons remain in the
[aggregate](registries/inner_speech_observed_result.v0.json). This is a scientific
negative result for the fixed model, not an execution failure or an EEG ceiling.
This motivated the fresh temporal test above, including EEG-only sensitivity
and matched peripheral/null controls. No tuning or rescoring of these consumed
session-1 trials; cue decoding alone is not thought decoding.

Earlier evidence remains relevant:
[SPEECH-REPRO-1 completed and scored once](docs/SPEECH_REPRODUCTION_RESULT.md).
The minimally overt EEGNet reference reached **52.49% balanced accuracy**, above
the 20% baseline in all three people. But auxiliary-only prediction reached
**84.83%**, and adding filtered EEG failed the registered conditional log-loss
test (mean log-loss gain **-0.022513**, only 1/3 people improved). Covert reference
BA was **18.13%**; the joint model also failed the full control conjunction.
All 341 trials, both conditions and all nine arms remain in the
[complete aggregate result](registries/speech_reproduction_result.v0.json).

The [nine-second calibration-only follow-up](docs/SPEECH_AUXILIARY_DISCOVERY_RESULT.md)
found **79.98% lip-only** and **66.22% EOG-only** balanced accuracy under
whole-trial blocked validation. Both beat all three controls in all three
minimally overt participants. DISPLAY, timing and microphone did not; no covert
arm passed consistently. This shifts the lead toward peripheral-channel
prediction, without establishing causal origin or new online performance.

The [67-second repetition-power comparison](docs/SPEECH_REPETITION_POWER_RESULT.md)
improved minimally overt adaptive EEG-derived BA from **37.73% to 46.38%**.
But adding it to N improved log loss in only **1/3 people** (mean gain
**+0.005820**), and **0/3 covert** (mean gain **-0.016323**). The registered
consistency test failed in both conditions. All 24 arms and both split schemes
remain in the [aggregate](registries/speech_repetition_po

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: pyproject.toml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `cache/`, `configs/`, `data/`, `fixtures/`, `notebooks/`, `products/`, `prompts/`, `registries/`, `scripts/`, `src/`, `tests/`
- Snapshot size: **2699 files**, **433056 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (1194), `.md` (749), `.json` (731), `.swift` (8), `(none)` (7), `.sh` (2)
- Upstream commit pinned for this packaging: `4e3be772f557b07ea8d4e220b1e3fe5e60d883cb`

---

## Installation

bounded cache, preserve provenance, compare against a language-only control,
and explain exactly what the result does not prove.

Why the gates? Most routine engineering is reversible, but opening a held-out
target, reusing a consumed evaluation, or changing a rule after seeing the
outcome is not scientifically reversible. The approved
[Research Autonomy Charter](docs/RESEARCH_AUTONOMY_CHARTER_DRAFT.md) and its
[activation decision](docs/RESEARCH_AUTONOMY_CHARTER_DECISION.md) let
routine code, tests, synthetic work, bounded development experiments, commits,
pushes, and CI proceed autonomously while reserving exact approval for those
irreversible Tier C events.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

browser download or separately authorized authenticated API access, not an
anonymous retry. The scientific question remains attempted-speech transfer to
verbal versus visual rehearsal of the same arrows. No new decoding result is
claimed. Preserve session 3 and all consumed evidence.

The [scientific swarm review](docs/THOUGHT_TO_TEXT_SCIENTIFIC_SWARM.md) organizes
work around competing mechanisms, independent falsification and decisive data.
Its separate, parked candidate is a fixed beta-envelope trajectory test with
matched amplitude and circular-shift controls, unlike the completed raw-bin
comparison; no new experiment is authorized. The longer-term milestone is content
external cues cannot supply, with transfer to untouched words or days.

**Prior session-1 scientific result:**
The [completed ten-person imagined-word experiment](docs/INNER_SPEECH_OBSERVED_RESULT.md)
scored once in **245 seconds**, retaining 1,993 trials, all ten people, all three
conditions and all eight arms. The primary EEG increment **failed**: mean
inner-speech log-loss gain **-0.003282 nats**, only **1/10** people beating every
control (9/10 required). Joint inner-speech balanced accuracy was **24.58%**
against 25% uniform; peripheral/timing-only pronounced balanced accuracy was **83.69%**.
All negative and positive comparisons remain in the
[aggregate](registries/inner_speech_observed_result.v0.json). This is a scientific
negative result for the fixed model, not an execution failure or an EEG ceiling.
This motivated the fresh temporal test above, including EEG-only sensitivity
and matched peripheral/null controls. No tuning or rescoring of these consumed
session-1 trials; cue decoding alone is not thought decoding.

Earlier evidence remains relevant:
[SPEECH-REPRO-1 completed and scored once](docs/SPEECH_REPRODUCTION_RESULT.md).
The minimally overt EEGNet reference reached **52.49% balanced accuracy**, above
the 20% baseline in all three people. But auxiliary-only prediction reached
**84.83%**, and adding filtered EEG failed the registered conditional log-loss
test (mean log-loss gain **-0.022513**, only 1/3 people improved). Covert reference
BA was **18.13%**; the joint model also failed the full control conjunction.
All 341 trials, both conditions and all nine arms remain in the
[complete aggregate result](registries/speech_reproduction_result.v0.json).

The [nine-second calibration-only follow-up](docs/SPEECH_AUXILIARY_DISCOVERY_RESULT.md)
found **79.98% lip-only** and **66.22% EOG-only** balanced accuracy under
whole-trial blocked validation. Both beat all three controls in all three
minimally overt participants. DISPLAY, timing and microphone did not; no covert
arm passed consistently. This shifts the lead toward peripheral-channel
prediction, without establishing causal origin or new online performance.

The [67-second repetition-power comparison](docs/SPEECH_REPETITION_POWER_RESULT.md)
improved minimally overt adaptive EEG-derived BA from **37.73% to 46.38%**.
But adding it to N improved log loss in only **1/3 people** (mean gain
**+0.005820**), and **0/3 covert** (mean gain **-0.016323**). The registered
consistency test failed in both conditions. All 24 arms and both split schemes
remain in the [aggregate](registries/speech_repetition_power_result.v0.json).
Better repetition features are useful; they do not establish independent neural
information. No online recording was opened.

**New belief-changing result:** the [83-second sham-input test](docs/SPEECH_ADAPTIVE_ATTRIBUTION_RESULT.md)
reached **49.72% minimally overt balanced accuracy without recorded EEG samples**
entering the features: one fixed synthetic waveform was processed with real
EOG/lip inputs. It beat all four primary controls in all three people under
blocked validation. This demonstrates an auxiliary-to-processed-feature pathway,
not that every real-EEG result is peripheral. Covert failed the primary consistency
rule; the real-EEG joint model failed its expanded control conjunction everywhere.
Simple normalization was competitive with the adaptive filter. All 29 arms,
600 trials and both split schemes remain in the
[aggregate](registries/speech_adaptive_attribution_result.v0.json).

The [159-second auxiliary-independent EEG comparison](docs/SPEECH_TIME_FREQUENCY_RESULT.md)
reached **89.75% minimally overt BA**, versus **85.62%** for repetition-enriched
auxiliary-only prediction under blocked validation. BA improved in all three
people with blocked folds (two with random folds), but the primary
log-loss increment improved in only **1/3** (mean gain **+0.003846**). Covert
also failed the all-person criterion. **None of nine preset EEG views passed
all controls in all three people**, under either split scheme. All 51 arms and
600 trials remain in the [aggregate](registries/speech_time_frequency_result.v0.json).
Better top-choice accuracy does not override the failed primary probability endpoint.

The [45-second nested confidence-calibration test](docs/SPEECH_PROBABILITY_CALIBRATION_RESULT.md)
identified a real probability-readout limitation: minimally overt joint log loss
fell **1.252182 → 0.369239**, with auxiliary-only A equally calibrated
**1.256028 → 0.489214**. Every chosen word and BA stayed unchanged. The conditional
EEG comparison now passed in **2/3 minimally overt people**, not all three;
covert passed in **1/3 blocked and 0/3 random**. The EEG all-person criterion
still failed in both conditions. All 20 arms, 600 trials and both schemes remain in the
[aggregate](registries/speech_probability_calibration_result.v0.json).

**Fresh-cohort rationale (now tested below):** close calibration/model/band searches on this reused
cohort and test imagined-word information on fresh people with strong peripheral
and cue controls. The [source decision](docs/SPEECH_NEXT_COHORT_DECISION.md)
reuses the existing ten-person Thinking Out Loud candidate for a fresh-cohort,
**same-day** study; no reviewed source supplies the complete new-day, cue-decoupled
design. Preserve both accuracy and probability-scoring endpoints, with roles fixed
before access and calibrators trained only on training data. The approved
[ten-person raw acquisition is complete](docs/INNER_SPEECH_ACQUISITION.md):
6.4304 GiB, first session, all EEG/eye/lip channels retained, verified in 347 seconds
and stored outside OneDrive. The [fixed four-word test](docs/INNER_SPEECH_TEST.md)
is now implemented with generated-only tests: all ten people, all three
conditions, eight matched arms, and a 20-minute/1-GiB cap. It requires mean
inner-speech log-loss gain of at least 0.02 nats and the same nine of ten people
beating every primary control. After the approved path fix, the sole corrected
run [stopped at event qualification](docs/INNER_SPEECH_QUALIFICATION_FAILURE.md):
all ten source hashes passed, but participant 01's event structure was refused.
No fitting or scoring occurred; this is not a biological null. The approved
[4.25-second structural audit](docs/INNER_SPEECH_EVENT_AUDIT.md) located the failure:
after three complete trials, the parser expected rest but saw the next trial
start. The decoded stream has 200 cues/actions/relax markers, but 199 rest
markers. The approved [missing-timing amendment](docs/INNER_SPEECH_MISSING_REST_AMENDMENT.md)
retains every trial and observed timing value, adds availability flags, and
changes the nuisance block from 85 to 87 features without inventing timestamps.
The [single amended run](docs/INNER_SPEECH_MISSING_REST_AMENDMENT.md)
qualified participant 01, then stopped after 12.27 seconds: participant 02 had
a direction cue where a trial-start marker was required after 72 complete
trials. No physiological windows, fits or scores followed. The approved
[whole-cohort census](docs/INNER_SPEECH_EVENT_CENSUS.md) then completed in 14.17
seconds: 50 intact run boundaries, but three absent direction cues and four
incomplete cue/action/relax sequences in the existing decoder's output.
It found 1,993 contiguous core sequences, not 2,000 qualified trials. The approved
[observed-anchor successor](docs/INNER_SPEECH_OBSERVED_RESULT.md) subsequently
confirmed exact independent decoder agreement for all ten people, accounted for
all 2,000 nominal slots and retained 1,993 eligible trials with seven predefined
structural exclusions. It completed training and one score; its primary failed.
No inferred words, timestamps, compressed chronology or post-score rescue were
used. Both earlier all-trial attempts and the census remain consumed history;
the [census aggregate](registries/inner_speech_event_census_result.v0.json) is unchanged.
Status events were read; labels cannot be called unopened. Consumed online recordings cannot be reused. The
low-channel peripheral interface remains a separate practical lead, not thought-to-text.
This consumed evaluation must not be retuned or rescored. We have evidence for
task-label prediction, not EEG-specific thought decoding, cortical origin,
clinical utility or unseen-person generalization. Both failed roots and the
successful one-shot evidence remain preserved. Earlier closeouts remain history.

The [Scientific Discovery and Invention Constitution](docs/SCIENTIFIC_DISCOVERY_AND_INVENTION_CONSTITUTION.md)
now governs research priorities. Its companion
[convergence plan](docs/SCIENTIFIC_CONVERGENCE_AND_INVENTION_PLAN.md) and
[machine knowledge ledger](registries/scientific_knowledge_ledger.v0.json)
separate what is supported, refuted, inconclusive, and still blocked; keep
discovery distinct from confirmation and translation; and score scientific
attribution separately from functional utility.

The frozen 60-person Dreyer nuisance-controlled unseen-person experiment was
the prior flagship confirmation route. Its one-file checkpoint stopped safely at
strict transport validation: one endpoint response opened, but no response
body byte or EDF header was read. The exact Dreyer lane is now consumed and
parked without a biological interpretation, and the 1.78 GB cohort was not
downloaded.

The latest prospective scientific source was the 15-person Ofner 2017
motor-imagery cohort. An exact metadata-only audit selected 150 original GDF
files totaling 13,748,417,608 bytes (`12.8042` GiB) with reported 61 EEG, three
EOG, and 32 hand/arm movement channels at 512 Hz. The tempting 4.58 GB BIDS
derivative was rejected because it omits the EOG and movement comparators
needed to distinguish central EEG from cheaper eye and overt-motion
explanations.

The sole `OFNER-C6R-1-HL-R0` range-header invocation is now consumed and
parked at `OFNER-H0-TRANSPORT`. The exact manifest passed identity selection,
but the first 256-byte GDF range produced zero accepted GDF body bytes, so no
real header, channel roster, geometry, signal, event, target, model, or score
was observed. This is a transport result, not a biological null. It cannot be
retried, rerun, repaired, resumed, substituted, or reinterpreted. No Tier C
packet is active. See the [result closeout](docs/OFNER_2017_MOTOR_IMAGERY_RANGE_HEADER_RESULT_CLOSEOUT.md)
and [proof closeout](docs/OFNER_2017_MOTOR_IMAGERY_RANGE_HEADER_RESULT_PROOF_CLOSEOUT.md).
The immutable machine frontier for that consumed result remains
[`registries/current_research_frontier.v6.json`](registries/current_research_frontier.v6.json).
The historical `registries/current_research_frontier.v10.json` and
`registries/current_research_frontier.v11.json` also remain immutable.
The proof passed Base Python `99174411928`, Optional Neuro Readers
`99174412006`, and CI `33280371097` on GitHub `main`.

The [artifact-only transport postmortem](docs/NEURAL_PAYLOAD_TRANSPORT_ADMISSION_POSTMORTEM_2026_08_29.md)
froze `NPA1-v0`: scientific source identity, expiring transport capability,
HTTP framing, bounded content identity, and semantic sensor eligibility are
separate gates. Generated-only `NPA1-G` is now remotely green at commit
`2e164ff`, Base Python `99184746988`, Optional Neuro Readers `99184747065`, and
CI `33284320443`. It accepted two deterministic seven-profile fixture replays
and 37 exact refusal families in 0.003375791013240814 seconds at 22,577,152-byte
peak RSS, with 4,162 generated input bytes, a 4,947-byte in-memory report, zero
network, and zero retained payload. The implementation contains no live
network opener or real execution command. Read the
[implementation](docs/NEURAL_PAYLOAD_ADMISSION_GENERATED_IMPLEMENTATION.md)
and [proof closeout](docs/NEURAL_PAYLOAD_ADMISSION_GENERATED_QUALIFICATION_PROOF_CLOSEOUT.md).
The proof closeout itself is green at exact commit `2ec3d4b`, Base Python
`99188620896`, Optional Neuro Readers `99188621003`, and CI `33285776358` on
GitHub `main`.

This closes a costly engineering uncertainty, not a scientific one. No fresh
source has been promoted, and no EEG was accessed. Independent review rejected
the pushed `FMSR1-v0` draft before acceptance or protected work. The additive
[`FMSR1-v1` successor](docs/FRESH_MOTOR_SOURCE_RESEARCH_PREREGISTRATION_AMENDMENT_1.md)
is exact-green at `e09f6cc`, Base Python `99197577034`, Optional Neuro Readers
`99197577007`, and CI `33289147031`. It freezes five official source indexes,
four exact queries, ordered
discovery-to-metadata routing, at least ten complete unseen participants,
synchronized EEG/EOG/EMG for every relevant effector, named geometry, and a
decisive central-EEG comparison against both joint nuisance-only and joint
nuisance plus deranged-central-EEG arms. Its exact 20 GiB partition is 12 GiB
payload, 2 GiB temporary files, 2 GiB derivatives, 1 GiB atomic publication,
and 3 GiB untouched reserve. `NO_QUALIFYING_SOURCE` remains valid. Every
current operation authority was false. The proof-only closeout and all-false
[`FMSR1-DISCOVERY-M0` request](docs/FRESH_MOTOR_SOURCE_DISCOVERY_AUTHORIZATION_PACKET.md)
are exact-green at `5c466efd`, Base Python `99204462828`, Optional Neuro
Readers `99204462714`, and CI `33291744779`. The maintainer's exact words are
recorded in the packet-bound
[decision](docs/FRESH_MOTOR_SOURCE_DISCOVERY_AUTHORIZATION_DECISION.md), which
is exact-green at `b66a3a1`, Base Python `99316322973`, Optional Neuro Readers
`99316322922`, and CI `33333549395` on GitHub `main`. The generated-only
[discovery implementation](docs/FRESH_MOTOR_SOURCE_DISCOVERY_IMPLEMENTATION.md)
is exact-green at `e92e9c2`, Base Python `99327605264`, Optional Neuro Readers
`99327605346`, and CI `33337741165`. It passes two deterministic 17-root
mock-HTTP replays and 25 adversarial
refusals with zero real network, payload, model, score, or claim operations.
Independent review also forced a park before live contact: the current packet
did not freeze actual official-index revisions, and a tracked local JSON
record cannot authenticate GitHub by
self-report. The implementation exposes no real transport. Its
[proof-only closeout](docs/FRESH_MOTOR_SOURCE_DISCOVERY_IMPLEMENTATION_PROOF_CLOSEOUT.md)
binds six exact artifacts / 162,295 bytes. Exact closeout `fac60bf` passed Base
Python `99330615390`, Optional Neuro Readers `99330615564`, and CI
`33338847448` on GitHub `main`; it does not activate live work. The new
[all-false admission correction](docs/FRESH_MOTOR_SOURCE_DISCOVERY_ADMISSION_CORRECTION.md)
keeps M0 non-armable and separates a future revision or complete opaque
snapshot witness, a fresh live GitHub CI verification before each
source-contact stage, and later candidate discovery. All five source profiles,
the exact CI profile, and every protected-operation authority remain null or
false. Any public discovery still requires separately witnessed evidence, a
fresh successor packet, and an exact-green decision.
The correction is exact-green at `8fe98df` with CI `33340527773`, and the
generated-only `FMSR1-R1-G-v0` registration is exact-green at `d53f3e8`, Base
`99339083749`, Optional `99339083636`, and CI `33341954248`. Its additive
[implementation](docs/FRESH_MOTOR_SOURCE_ADMISSION_GENERATED_QUALIFICATION_IMPLEMENTATION.md)
at `c3f536d` passed Base `99347978123`, Optional `99347978190`, and CI
`33345237136`, but a later independent durability review rejected activation:
the marker and attempt directory were fsynced while their newly created
directory ancestry was not, and pre-arm refusal had been described too broadly
as attempt consumption. Corrected successor `I1` reached GitHub `main` at
`d9229c1`, with Base `99358753480`, Optional `99358753302`, and CI
`33349080445` green. Activation `3de14c3` then passed Base `99361845630`,
Optional `99361845491`, and CI `33350175624` before the sole generated
qualification. That one-shot run is now consumed and passed: two identical
five-profile replays, all 82 refusals across 13 routes,
0.022029167041182518 seconds runtime, 21,397,504-byte peak RSS, 636 temporary
bytes, and zero network, real-source, neural, target, model, prediction, score,
release, or claim operations. It cannot be rerun. Read the
[measured result](docs/FRESH_MOTOR_SOURCE_ADMISSION_GENERATED_QUALIFICATION_RESULT.md).
The corrected result tree `9f5ff18` passed Base `99367259645`, Optional
`99367259785`, and CI `33352074929`; its
[proof-only closeout](docs/FRESH_MOTOR_SOURCE_ADMISSION_GENERATED_QUALIFICATION_PROOF_CLOSEOUT.md)
is exact-green at `dbfaf68`, Base `99369471021`, Optional `99369470875`, and
CI `33352882661`, with no rerun. The generated lane is closed. The next exact
artifact is the all-false
[`FMSR1-R1-W-v0` source-identity witness packet](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_AUTHORIZATION_PACKET.md).
It conservatively assigns all five indexes to opaque complete-snapshot replay,
binds all 17 initial requests in a canonical page/root/profile/global hash tree,
permits only exact typed pagination-control decoding, and grants no network or
implementation authority. The packet is exact-green at `d4ae388`, Base Python
`99381828165`, Optional Neuro Readers `99381828024`, and CI `33357313608` on
GitHub `main`. The maintainer's exact fresh words are preserved in the
[implementation-only decision](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_IMPLEMENTATION_DECISION.md),
which is exact-green at `e158e8c`, Base Python `99385124402`, Optional Neuro
Readers `99385124488`, and CI `33358495852`. The resulting
[generated witness implementation](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_GENERATED_IMPLEMENTATION.md)
passed one consumed qualification with two identical five-profile, 17-root,
34-page replays and 22 adversarial refusals in 0.035018666880205274 seconds at
21,364,736-byte peak RSS. It made zero network, candidate-semantic, neural,
target, model, prediction, score, or claim operations. Exact implementation
`ea37358` passed Base `99394572164`, Optional `99394572060`, and CI
`33361847146`. The additive live-adapter decision is exact-green at `0c50299`,
Base `99401989268`, Optional `99401989133`, and CI `33364407489`. Its sole
zero-network generated qualification is consumed and passed: two matching
five-profile / 17-root / 34-page replays, 76 generated transport calls, 16
refusals including six direct transport refusals, zero candidate semantic
accesses, 0.1274927919730544 seconds runtime, and 40,583,168-byte peak RSS.
The exact [live implementation](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_LIVE_IMPLEMENTATION.md)
is remotely green at `a2af6c4`, Base `99515316155`, Optional `99515315921`,
and CI `33400484765`. Its
[proof-only closeout](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_LIVE_IMPLEMENTATION_PROOF_CLOSEOUT.md)
binds 16 artifacts / 314,356 bytes and is pending its own commit and remote
proof. After that proof is green, fresh maintainer words and a separate
authority-bearing decision are required for one consumed live witness. Its
three-call CI gate compares clean local `main` with remote `main`, the two
unique successful checks on that exact commit, and the frozen workflow blob.
No official index or EEG has been accessed. `D1` remains behind its own later
packet, fresh words, decision, and green proof.
The [hard scientific decision tree](docs/SCIENTIFIC_RESULT_HARD_DECISION_TREE.md)
then routes one admitted source through sensitivity, confirmation,
independent replication, and only afterward causal/live translation. Its core
is a 3D spatial-temporal-physiological attribution cube inside a 5D evidence
map that adds task autonomy and population generalization; offline-to-live
operation is a separate sixth translation dimension. Live motor success does
not inherit a language claim. Communication retains its own preregistration
and independently scored LLM-only baseline. Within the cube, posterior EEG is
a neural spatial comparator, not part of the EOG/EMG/metadata nuisance bundle;
every neural comparator retains that identical nuisance bundle, and the central
motor-window condition must win every registered spatial, temporal, and
physiological edge rather than merely average well. Engineering may close only
the final immediate dependency of this experiment; the next substantive block
must produce real-data evidence or a measured blocker. See the
[additive evidence-map clarification](docs/FRESH_MOTOR_SOURCE_RESEARCH_EVIDENCE_MAP_CLARIFICATION.md)
and [current machine frontier](registries/current_research_frontier.v26.json).
Its immutable predecessor is `registries/current_research_frontier.v25.json`;
earlier predecessors are `registries/current_research_frontier.v24.json`,
`registries/current_research_frontier.v23.json`, and
`registries/current_research_frontier.v21.json`;
Earlier immutable predecessors: `registries/current_research_frontier.v20.json`,
`registries/current_research_frontier.v19.json`, `registries/current_research_frontier.v18.json`,
`registries/current_research_frontier.v17.json`, `registries/current_research_frontier.v16.json`,
`registries/current_research_frontier.v15.json`, `registries/current_research_frontier.v14.json`,
`registries/current_research_frontier.v13.json`, `registries/current_research_frontier.v12.json`,
and `registries/current_research_frontier.v11.json`.
The earlier predecessors `registries/current_research_frontier.v8.json`,
`registries/current_research_frontier.v7.json`, and
`registries/current_research_frontier.v6.json` remain immutable history.
COMM-P0 FS3 remains paused as an adjacent diagnostic.

The follow-on generated acquisition qualification now passes two complete
150-file fixture replays plus 20 adversarial refusals in 0.108829 seconds at
26,492,928-byte peak RSS, with zero network and zero retained payload. It
strictly separates stable path/size/SHA-256 identity from expiring signed
transport URLs and exposes no live-network or real-payload execution path.
This is engineering proof, not EEG evidence. Read the
[generated qualification closeout](docs/OFNER_2017_MOTOR_IMAGERY_ACQUISITION_GENERATED_QUALIFICATION.md).
That exact implementation and its proof are now green on GitHub `main`.

The historical Ofner generated milestone was remotely proven: a dependency-free GDF
2.x header parser and two-range transport firewall passed two 24,832-byte
header replays plus 41 adversarial refusals in 0.002138459 seconds at
26,214,400-byte peak RSS. It recovered the frozen synthetic 61 EEG + 3 EOG +
19 glove + 13 arm roster at 512 Hz, rejected trailing data bytes, and exposes
no network client, real execution command, event parser, signal parser, model,
or scorer. Read the
[header preregistration](docs/OFNER_2017_MOTOR_IMAGERY_FIXED_HEADER_PREREGISTRATION.md)
and [generated header result](docs/OFNER_2017_MOTOR_IMAGERY_FIXED_HEADER_GENERATED_QUALIFICATION.md).
This remains engineering proof, not EEG evidence. Its historical next
checkpoint was one separately governed range-only source-GDF header; that
checkpoint is consumed at transport H0, and bulk acquisition, signals, targets,
models, and scores remain closed.

The [`OFNER-C6R-1-HL` request](docs/OFNER_2017_MOTOR_IMAGERY_RANGE_HEADER_AUTHORIZATION_PACKET.md),
decision, implementation, and activation all became exact-green before the
one-shot execution. The attempt used one CPU thread, 48,021,504-byte peak RSS,
4,096 private allocated bytes, 2,340 public output bytes, and retained no
payload. It made one manifest GET and one first-range attempt, with zero
full-file requests and zero accepted GDF body bytes. The next reversible step
is artifact-only transport/source research, not another execution.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

stopped with an HTTP error after **1.062 seconds and zero archive bytes copied**.
No inventory, internal README, neural array, label, fit or score was opened.
The separately approved **0.61-second header-only diagnostic returned 403**,
with no redirect or body read. The [failure and next boundary](docs/THOUGHT_TO_TEXT_SCIENTIFIC_SWARM.md#approved-acquisition-stopped-at-http-transport)
preserve both attempts; the denial's cause is unknown. Next requires a normal
browser download or separately authorized authenticated API access, not an
anonymous retry. The scientific question remains attempted-speech transfer to
verbal versus visual rehearsal of the same arrows. No new decoding result is
claimed. Preserve session 3 and all consumed evidence.

The [scientific swarm review](docs/THOUGHT_TO_TEXT_SCIENTIFIC_SWARM.md) organizes
work around competing mechanisms, independent falsification and decisive data.
Its separate, parked candidate is a fixed beta-envelope trajectory test with
matched amplitude and circular-shift controls, unlike the completed raw-bin
comparison; no new experiment is authorized. The longer-term milestone is content
external cues cannot supply, with transfer to untouched words or days.

**Prior session-1 scientific result:**
The [completed ten-person imagined-word experiment](docs/INNER_SPEECH_OBSERVED_RESULT.md)
scored once in **245 seconds**, retaining 1,993 trials, all ten people, all three
conditions and all eight arms. The primary EEG increment **failed**: mean
inner-speech log-loss gain **-0.003282 nats**, only **1/10** people beating every
control (9/10 required). Joint inner-speech balanced accuracy was **24.58%**
against 25% uniform; peripheral/timing-only pronounced balanced accuracy was **83.69%**.
All negative and positive comparisons remain in the
[aggregate](registries/inner_speech_observed_result.v0.json). This is a scientific
negative result for the fixed model, not an execution failure or an EEG ceiling.
This motivated the fresh temporal test above, including EEG-only sensitivity
and matched peripheral/null controls. No tuning or rescoring of these consumed
session-1 trials; cue decoding alone is not thought decoding.

Earlier evidence remains relevant:
[SPEECH-REPRO-1 completed and scored once](docs/SPEECH_REPRODUCTION_RESULT.md).
The minimally overt EEGNet reference reached **52.49% balanced accuracy**, above
the 20% baseline in all three people. But auxiliary-only prediction reached
**84.83%**, and adding filtered EEG failed the registered conditional log-loss
test (mean log-loss gain **-0.022513**, only 1/3 people improved). Covert reference
BA was **18.13%**; the joint model also failed the full control conjunction.
All 341 trials, both conditions and all nine arms remain in the
[complete aggregate result](registries/speech_reproduction_result.v0.json).

The [nine-second calibration-only follow-up](docs/SPEECH_AUXILIARY_DISCOVERY_RESULT.md)
found **79.98% lip-only** and **66.22% EOG-only** balanced accuracy under
whole-trial blocked validation. Both beat all three controls in all three
minimally overt participants. DISPLAY, timing and microphone did not; no covert
arm passed consistently. This shifts the lead toward peripheral-channel
prediction, without establishing causal origin or new online performance.

The [67-second repetition-power comparison](docs/SPEECH_REPETITION_POWER_RESULT.md)
improved minimally overt adaptive EEG-derived BA from **37.73% to 46.38%**.
But adding it to N improved log loss in only **1/3 people** (mean gain
**+0.005820**), and **0/3 covert** (mean gain **-0.016323**). The registered
consistency test failed in both conditions. All 24 arms and both split schemes
remain in the [aggregate](registries/speech_repetition_power_result.v0.json).
Better repetition features are useful; they do not establish independent neural
information. No online recording was opened.

**New belief-changing result:** the [83-second sham-input test](docs/SPEECH_ADAPTIVE_ATTRIBUTION_RESULT.md)
reached **49.72% minimally overt balanced accuracy without recorded EEG samples**
entering the features: one fixed synthetic waveform was processed with real
EOG/lip inputs. It beat all four primary controls in all three people under
blocked validation. This demonstrates an auxiliary-to-processed-feature pathway,
not that every real-EEG result is peripheral. Covert failed the primary consistency
rule; the real-EEG joint model failed its expanded control conjunction everywhere.
Simple normalization was competitive with the adaptive filter. All 29 arms,
600 trials and both split schemes remain in the
[aggregate](registries/speech_adaptive_attribution_result.v0.json).

The [159-second auxiliary-independent EEG comparison](docs/SPEECH_TIME_FREQUENCY_RESULT.md)
reached **89.75% minimally overt BA**, versus **85.62%** for repetition-enriched
auxiliary-only prediction under blocked validation. BA improved in all three
people with blocked folds (two with random folds), but the primary
log-loss increment improved in only **1/3** (mean gain **+0.003846**). Covert
also failed the all-person criterion. **None of nine preset EEG views passed
all controls in all three people**, under either split scheme. All 51 arms and
600 trials remain in the [aggregate](registries/speech_time_frequency_result.v0.json).
Better top-choice accuracy does not override the failed primary probability endpoint.

The [45-second nested confidence-calibration test](docs/SPEECH_PROBABILITY_CALIBRATION_RESULT.md)
identified a real probability-readout limitation: minimally overt joint log loss
fell **1.252182 → 0.369239**, with auxiliary-only A equally calibrated
**1.256028 → 0.489214**. Every chosen word and BA stayed unchanged. The conditional
EEG comparison now passed in **2/3 minimally overt people**, not all three;
covert passed in **1/3 blocked and 0/3 random**. The EEG all-person criterion
still failed in both conditions. All 20 arms, 600 trials and both schemes remain in the
[aggregate](registries/speech_probability_calibration_result.v0.json).

**Fresh-cohort rationale (now tested below):** close calibration/model/band searches on this reused
cohort and test imagined-word information on fresh people with strong peripheral
and cue controls. The [source decision](docs/SPEECH_NEXT_COHORT_DECISION.md)
reuses the existing ten-person Thinking Out Loud candidate for a fresh-cohort,
**same-day** study; no reviewed source supplies the complete new-day, cue-decoupled
design. Preserve both accuracy and probability-scoring endpoints, with roles fixed
before access and calibrators trained only on training data. The approved
[ten-person raw acquisition is complete](docs/INNER_SPEECH_ACQUISITION.md):
6.4304 GiB, first session, all EEG/eye/lip channels retained, verified in 347 seconds
and stored outside OneDrive. The [fixed four-word test](docs/INNER_SPEECH_TEST.md)
is now implemented with generated-only tests: all ten people, all three
conditions, eight matched arms, and a 20-minute/1-GiB cap. It requires mean
inner-speech log-loss gain of at least 0.02 nats and the same nine of ten people
beating every primary control. After the approved path fix, the sole corrected
run [stopped at event qualification](docs/INNER_SPEECH_QUALIFICATION_FAILURE.md):
all ten source hashes passed, but participant 01's event structure was refused.
No fitting or scoring occurred; this is not a biological null. The approved
[4.25-second structural audit](docs/INNER_SPEECH_EVENT_AUDIT.md) located the failure:
after three complete trials, the parser expected rest but saw the next trial
start. The decoded stream has 200 cues/actions/relax markers, but 199 rest
markers. The approved [missing-timing amendment](docs/INNER_SPEECH_MISSING_REST_AMENDMENT.md)
retains every trial and observed timing value, adds availability flags, and
changes the nuisance block from 85 to 87 features without inventing timestamps.
The [single amended run](docs/INNER_SPEECH_MISSING_REST_AMENDMENT.md)
qualified participant 01, then stopped after 12.27 seconds: participant 02 had
a direction cue where a trial-start marker was required after 72 complete
trials. No physiological windows, fits or scores followed. The approved
[whole-cohort census](docs/INNER_SPEECH_EVENT_CENSUS.md) then completed in 14.17
seconds: 50 intact run boundaries, but three absent direction cues and four
incomplete cue/action/relax sequences in the existing decoder's output.
It found 1,993 contiguous core sequences, not 2,000 qualified trials. The approved
[observed-anchor successor](docs/INNER_SPEECH_OBSERVED_RESULT.md) subsequently
confirmed exact independent decoder agreement for all ten people, accounted for
all 2,000 nominal slots and retained 1,993 eligible trials with seven predefined
structural exclusions. It completed training and one score; its primary failed.
No inferred words, timestamps, compressed chronology or post-score rescue were
used. Both earlier all-trial attempts and the census remain consumed history;
the [census aggregate](registries/inner_speech_event_census_result.v0.json) is unchanged.
Status events were read; labels cannot be called unopened. Consumed online recordings cannot be reused. The
low-channel peripheral interface remains a separate practical lead, not thought-to-text.
This consumed evaluation must not be retuned or rescored. We have evidence for
task-label prediction, not EEG-specific thought decoding, cortical origin,
clinical utility or unseen-person generalization. Both failed roots and the
successful one-shot evidence remain preserved. Earlier closeouts remain history.

The [Scientific Discovery and Invention Constitution](docs/SCIENTIFIC_DISCOVERY_AND_INVENTION_CONSTITUTION.md)
now governs research priorities. Its companion
[convergence plan](docs/SCIENTIFIC_CONVERGENCE_AND_INVENTION_PLAN.md) and
[machine knowledge ledger](registries/scientific_knowledge_ledger.v0.json)
separate what is supported, refuted, inconclusive, and still blocked; keep
discovery distinct from confirmation and translation; and score scientific
attribution separately from functional utility.

The frozen 60-person Dreyer nuisance-controlled unseen-person experiment was
the prior flagship confirmation route. Its one-file checkpoint stopped safely at
strict transport validation: one endpoint response opened, but no response
body byte or EDF header was read. The exact Dreyer lane is now consumed and
parked without a biological interpretation, and the 1.78 GB cohort was not
downloaded.

The latest prospective scientific source was the 15-person Ofner 2017
motor-imagery cohort. An exact metadata-only audit selected 150 original GDF
files totaling 13,748,417,608 bytes (`12.8042` GiB) with reported 61 EEG, three
EOG, and 32 hand/arm movement channels at 512 Hz. The tempting 4.58 GB BIDS
derivative was rejected because it omits the EOG and movement comparators
needed to distinguish central EEG from cheaper eye and overt-motion
explanations.

The sole `OFNER-C6R-1-HL-R0` range-header invocation is now consumed and
parked at `OFNER-H0-TRANSPORT`. The exact manifest passed identity selection,
but the first 256-byte GDF range produced zero accepted GDF body bytes, so no
real header, channel roster, geometry, signal, event, target, model, or score
was observed. This is a transport result, not a biological null. It cannot be
retried, rerun, repaired, resumed, substituted, or reinterpreted. No Tier C
packet is active. See the [result closeout](docs/OFNER_2017_MOTOR_IMAGERY_RANGE_HEADER_RESULT_CLOSEOUT.md)
and [proof closeout](docs/OFNER_2017_MOTOR_IMAGERY_RANGE_HEADER_RESULT_PROOF_CLOSEOUT.md).
The immutable machine frontier for that consumed result remains
[`registries/current_research_frontier.v6.json`](registries/current_research_frontier.v6.json).
The historical `registries/current_research_frontier.v10.json` and
`registries/current_research_frontier.v11.json` also remain immutable.
The proof passed Base Python `99174411928`, Optional Neuro Readers
`99174412006`, and CI `33280371097` on GitHub `main`.

The [artifact-only transport postmortem](docs/NEURAL_PAYLOAD_TRANSPORT_ADMISSION_POSTMORTEM_2026_08_29.md)
froze `NPA1-v0`: scientific source identity, expiring transport capability,
HTTP framing, bounded content identity, and semantic sensor eligibility are
separate gates. Generated-only `NPA1-G` is now remotely green at commit
`2e164ff`, Base Python `99184746988`, Optional Neuro Readers `99184747065`, and
CI `33284320443`. It accepted two deterministic seven-profile fixture replays
and 37 exact refusal families in 0.003375791013240814 seconds at 22,577,152-byte
peak RSS, with 4,162 generated input bytes, a 4,947-byte in-memory report, zero
network, and zero retained payload. The implementation contains no live
network opener or real execution command. Read the
[implementation](docs/NEURAL_PAYLOAD_ADMISSION_GENERATED_IMPLEMENTATION.md)
and [proof closeout](docs/NEURAL_PAYLOAD_ADMISSION_GENERATED_QUALIFICATION_PROOF_CLOSEOUT.md).
The proof closeout itself is green at exact commit `2ec3d4b`, Base Python
`99188620896`, Optional Neuro Readers `99188621003`, and CI `33285776358` on
GitHub `main`.

This closes a costly engineering uncertainty, not a scientific one. No fresh
source has been promoted, and no EEG was accessed. Independent review rejected
the pushed `FMSR1-v0` draft before acceptance or protected work. The additive
[`FMSR1-v1` successor](docs/FRESH_MOTOR_SOURCE_RESEARCH_PREREGISTRATION_AMENDMENT_1.md)
is exact-green at `e09f6cc`, Base Python `99197577034`, Optional Neuro Readers
`99197577007`, and CI `33289147031`. It freezes five official source indexes,
four exact queries, ordered
discovery-to-metadata routing, at least ten complete unseen participants,
synchronized EEG/EOG/EMG for every relevant effector, named geometry, and a
decisive central-EEG comparison against both joint nuisance-only and joint
nuisance plus deranged-central-EEG arms. Its exact 20 GiB partition is 12 GiB
payload, 2 GiB temporary files, 2 GiB derivatives, 1 GiB atomic publication,
and 3 GiB untouched reserve. `NO_QUALIFYING_SOURCE` remains valid. Every
current operation authority was false. The proof-only closeout and all-false
[`FMSR1-DISCOVERY-M0` request](docs/FRESH_MOTOR_SOURCE_DISCOVERY_AUTHORIZATION_PACKET.md)
are exact-green at `5c466efd`, Base Python `99204462828`, Optional Neuro
Readers `99204462714`, and CI `33291744779`. The maintainer's exact words are
recorded in the packet-bound
[decision](docs/FRESH_MOTOR_SOURCE_DISCOVERY_AUTHORIZATION_DECISION.md), which
is exact-green at `b66a3a1`, Base Python `99316322973`, Optional Neuro Readers
`99316322922`, and CI `33333549395` on GitHub `main`. The generated-only
[discovery implementation](docs/FRESH_MOTOR_SOURCE_DISCOVERY_IMPLEMENTATION.md)
is exact-green at `e92e9c2`, Base Python `99327605264`, Optional Neuro Readers
`99327605346`, and CI `33337741165`. It passes two deterministic 17-root
mock-HTTP replays and 25 adversarial
refusals with zero real network, payload, model, score, or claim operations.
Independent review also forced a park before live contact: the current packet
did not freeze actual official-index revisions, and a tracked local JSON
record cannot authenticate GitHub by
self-report. The implementation exposes no real transport. Its
[proof-only closeout](docs/FRESH_MOTOR_SOURCE_DISCOVERY_IMPLEMENTATION_PROOF_CLOSEOUT.md)
binds six exact artifacts / 162,295 bytes. Exact closeout `fac60bf` passed Base
Python `99330615390`, Optional Neuro Readers `99330615564`, and CI
`33338847448` on GitHub `main`; it does not activate live work. The new
[all-false admission correction](docs/FRESH_MOTOR_SOURCE_DISCOVERY_ADMISSION_CORRECTION.md)
keeps M0 non-armable and separates a future revision or complete opaque
snapshot witness, a fresh live GitHub CI verification before each
source-contact stage, and later candidate discovery. All five source profiles,
the exact CI profile, and every protected-operation authority remain null or
false. Any public discovery still requires separately witnessed evidence, a
fresh successor packet, and an exact-green decision.
The correction is exact-green at `8fe98df` with CI `33340527773`, and the
generated-only `FMSR1-R1-G-v0` registration is exact-green at `d53f3e8`, Base
`99339083749`, Optional `99339083636`, and CI `33341954248`. Its additive
[implementation](docs/FRESH_MOTOR_SOURCE_ADMISSION_GENERATED_QUALIFICATION_IMPLEMENTATION.md)
at `c3f536d` passed Base `99347978123`, Optional `99347978190`, and CI
`33345237136`, but a later independent durability review rejected activation:
the marker and attempt directory were fsynced while their newly created
directory ancestry was not, and pre-arm refusal had been described too broadly
as attempt consumption. Corrected successor `I1` reached GitHub `main` at
`d9229c1`, with Base `99358753480`, Optional `99358753302`, and CI
`33349080445` green. Activation `3de14c3` then passed Base `99361845630`,
Optional `99361845491`, and CI `33350175624` before the sole generated
qualification. That one-shot run is now consumed and passed: two identical
five-profile replays, all 82 refusals across 13 routes,
0.022029167041182518 seconds runtime, 21,397,504-byte peak RSS, 636 temporary
bytes, and zero network, real-source, neural, target, model, prediction, score,
release, or claim operations. It cannot be rerun. Read the
[measured result](docs/FRESH_MOTOR_SOURCE_ADMISSION_GENERATED_QUALIFICATION_RESULT.md).
The corrected result tree `9f5ff18` passed Base `99367259645`, Optional
`99367259785`, and CI `33352074929`; its
[proof-only closeout](docs/FRESH_MOTOR_SOURCE_ADMISSION_GENERATED_QUALIFICATION_PROOF_CLOSEOUT.md)
is exact-green at `dbfaf68`, Base `99369471021`, Optional `99369470875`, and
CI `33352882661`, with no rerun. The generated lane is closed. The next exact
artifact is the all-false
[`FMSR1-R1-W-v0` source-identity witness packet](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_AUTHORIZATION_PACKET.md).
It conservatively assigns all five indexes to opaque complete-snapshot replay,
binds all 17 initial requests in a canonical page/root/profile/global hash tree,
permits only exact typed pagination-control decoding, and grants no network or
implementation authority. The packet is exact-green at `d4ae388`, Base Python
`99381828165`, Optional Neuro Readers `99381828024`, and CI `33357313608` on
GitHub `main`. The maintainer's exact fresh words are preserved in the
[implementation-only decision](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_IMPLEMENTATION_DECISION.md),
which is exact-green at `e158e8c`, Base Python `99385124402`, Optional Neuro
Readers `99385124488`, and CI `33358495852`. The resulting
[generated witness implementation](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_GENERATED_IMPLEMENTATION.md)
passed one consumed qualification with two identical five-profile, 17-root,
34-page replays and 22 adversarial refusals in 0.035018666880205274 seconds at
21,364,736-byte peak RSS. It made zero network, candidate-semantic, neural,
target, model, prediction, score, or claim operations. Exact implementation
`ea37358` passed Base `99394572164`, Optional `99394572060`, and CI
`33361847146`. The additive live-adapter decision is exact-green at `0c50299`,
Base `99401989268`, Optional `99401989133`, and CI `33364407489`. Its sole
zero-network generated qualification is consumed and passed: two matching
five-profile / 17-root / 34-page replays, 76 generated transport calls, 16
refusals including six direct transport refusals, zero candidate semantic
accesses, 0.1274927919730544 seconds runtime, and 40,583,168-byte peak RSS.
The exact [live implementation](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_LIVE_IMPLEMENTATION.md)
is remotely green at `a2af6c4`, Base `99515316155`, Optional `99515315921`,
and CI `33400484765`. Its
[proof-only closeout](docs/FRESH_MOTOR_SOURCE_IDENTITY_WITNESS_LIVE_IMPLEMENTATION_PROOF_CLOSEOUT.md)
binds 16 artifacts / 314,356 bytes and is pending its own commit and remote
proof. After that proof is green, fresh maintainer words and a separate
authority-bearing decision are required for one consumed live witness. Its
three-call CI gate compares clean local `main` with remote `main`, the two
unique successful checks on that exact commit, and the frozen workflow blob.
No official index or EEG has been accessed. `D1` remains behind its own later
packet, fresh words, decision, and green proof.
The [hard scientific decision tree](docs/SCIENTIFIC_RESULT_HARD_DECISION_TREE.md)
then routes one admitted source through sensitivity, confirmation,
independent replication, and only afterward causal/live translation. Its core
is a 3D spatial-temporal-physiological attribution cube inside a 5D evidence
map that adds task autonomy and population generalization; offline-to-live
operation is a separate sixth translation dimension. Live motor success does
not inherit a language claim. Communication retains its own preregistration
and independently scored LLM-only baseline. Within the cube, posterior EEG is
a neural spatial comparator, not part of the EOG/EMG/metadata nuisance bundle;
every neural comparator retains that identical nuisance bundle, and the central
motor-window condition must win every registered spatial, temporal, and
physiological edge rather than merely average well. Engineering may close only
the final immediate dependency of this experiment; the next substantive block
must produce real-data evidence or a measured blocker. See the
[additive evidence-map clarification](docs/FRESH_MOTOR_SOURCE_RESEARCH_EVIDENCE_MAP_CLARIFICATION.md)
and [current machine frontier](registries/current_research_frontier.v26.json).
Its immutable predecessor is `registries/current_research_frontier.v25.json`;
earlier predecessors are `registries/current_research_frontier.v24.json`,
`registries/current_research_frontier.v23.json`, and
`registries/current_research_frontier.v21.json`;
Earlier immutable predecessors: `registries/current_research_frontier.v20.json`,
`registries/current_research_frontier.v19.json`, `registries/current_research_frontier.v18.json`,
`registries/current_research_frontier.v17.json`, `registries/current_research_frontier.v16.json`,
`registries/current_research_frontier.v15.json`, `registries/current_research_frontier.v14.json`,
`registries/current_research_frontier.v13.json`, `registries/current_research_frontier.v12.json`,
and `registries/current_research_frontier.v11.json`.
The earlier predecessors `registries/current_research_frontier.v8.json`,
`registries/current_research_frontier.v7.json`, and
`registries/current_research_frontier.v6.json` remain immutable history.
COMM-P0 FS3 remains paused as an adjacent diagnostic.

The follow-on generated acquisition qualification now passes two complete
150-file fixture replays plus 20 adversarial refusals in 0.108829 seconds at
26,492,928-byte peak RSS, with zero network and zero retained payload. It
strictly separates stable path/size/SHA-256 identity from expiring signed
transport URLs and exposes no live-network or real-payload execution path.
This is engineering proof, not EEG evidence. Read the
[generated qualification closeout](docs/OFNER_2017_MOTOR_IMAGERY_ACQUISITION_GENERATED_QUALIFICATION.md).
That exact implementation and its proof are now green on GitHub `main`.

The historical Ofner generated milestone was remotely proven: a dependency-free GDF
2.x header parser and two-range transport firewall passed two 24,832-byte
header replays plus 41 adversarial refusals in 0.002138459 seconds at
26,214,400-byte peak RSS. It recovered the frozen synthetic 61 EEG + 3 EOG +
19 glove + 13 arm roster at 512 Hz, rejected trailing data bytes, and exposes
no network client, real execution command, event parser, signal parser, model,
or scorer. Read the
[header preregistration](docs/OFNER_2017_MOTOR_IMAGERY_FIXED_HEADER_PREREGISTRATION.md)
and [generated header result](docs/OFNER_2017_MOTOR_IMAGERY_FIXED_HEADER_GENERATED_QUALIFICATION.md).
This remains engineering proof, not EEG evidence. Its historical next
checkpoint was one separately governed range-only source-GDF header; that
checkpoint is consumed at transport H0, and bulk acquisition, signals, targets,
models, and scores remain closed.

The [`OFNER-C6R-1-HL` request](docs/OFNER_2017_MOTOR_IMAGERY_RANGE_HEADER_AUTHORIZATION_PACKET.md),
decision, implementation, and activation all became exact-green before the
one-shot execution. The attempt used one CPU thread, 48,021,504-byte peak RSS,
4,096 private allocated bytes, 2,340 public output bytes, and retained no
payload. It made one manifest GET and one first-range attempt, with zero
full-file requests and zero accepted GDF body bytes. The next reversible step
is artifact-only transport/source research, not another execution.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | pyproject.toml |
| Files in snapshot | 2699 |
| Lines of code | 433056 |
| Dependency references | 0 |
| Upstream license | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

| Edge-runtime packaging decision | Loop 40 research freezes 7 qualification levels, 6 package layers, 4 backend profiles, 20 identity fields, 24 fixtures, 30 gates, and 40 refusals around the retained 1,130-parameter float32 reference | Planning research is complete while the experiment is `Not Started` and unauthorized; ExecuTorch/XNNPACK is a research lead only, with no selected target, export, package, inference, simulator, or hardware result |
| One-device qualification decision | Loop 42 selects the exact OpenBCI Cyton base 8-channel USB-radio path and freezes 28 identity fields, 7 timing observables, 10 anomalies, 4 stages, 34 gates, and 46 refusals | Current evidence is Q0 official-specification eligibility only; no device is owned, purchased, connected, streamed, or qualified, and no signal or decoding claim exists |
| Independent reproduction decision | Loop 43 freezes a future target-free NeuroToken causal-replay challenge with 7 qualification levels, 16 independence fields, 28 packet fields, 34 submission fields, commit-reveal ordering, 36 gates, and 48 refusals | Planning research is complete while the challenge is `Not Started` and unauthorized; a local validator incident parsed 136 cache JSON files, including 11 known consumed session-2 report/metadata files, but no content was used for tuning, scoring, or claim selection |
| Claim and release decision | Loop 44 binds 16 claim cards to 7 evidence levels, 5 model cards, 4 dataset cards, 14 release gates, and 8 risks | Artifact review is complete; engineering release is held, scientific performance release is parked, and no tag, release, DOI, payload, or claim upgrade exists |
| Real predictive evidence | Both the same-person cross-session MEG model and the bounded S7 EEG classifier lose to no-signal controls | The current scientific result is negative, explicit, and frozen against post-hoc tuning |
| Local execution gate | Float16 preserved exact behavior but ran `1.170x` slower on the producer; qint8 cut payload to `47.1%` but changed behavior and ran `2.785x` slower | Float32 is retained, qualification stayed unopened, and Loop 24 is parked after the full run exceeded its 60-second cap |
| Next transport layer | Stage A is specified as 90 future schedule-by-fixture cases with 30 exact refusals under a 32 MiB cap | The decision packet is review-ready; no replay runtime, socket, board, or hardware path is authorized yet |

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing To NeuroDecodeKit

Thank you for helping make non-invasive neural language-decoding research more
accessible, reproducible, and honest. Contributions are welcome from software
engineers, neuroscientists, signal-processing researchers, dataset stewards,
EEG users, hardware builders, technical writers, designers, and people who are
new to the field.

You do not need access to a large MEG system or private dataset to contribute.
Many of the most useful improvements are pure-Python tests, synthetic fixtures,
format adapters, documentation, resource measurements, and better failure
messages.

## Read This First

NeuroDecodeKit is a research toolkit, not a medical device or a mind-reading
product. The current project has **not** demonstrated:

- neural decoding that beats its no-signal prior on the real evaluations run;
- unseen-person generalization;
- useful open-vocabulary EEG sentence decoding;
- an end-to-end real-time text system;
- compatibility with a consumer or portable device;
- arbitrary-thought decoding or clinical utility.

Those are proof boundaries, not marketing caveats. Contributions must preserve
them in code, reports, documentation, issue titles, and screenshots.

Before opening a pull request, read:

1. `README.md` for the product and engineering map.
2. `docs/RISK_AND_ETHICS.md` for privacy, licensing, and claim language.
3. `docs/DECISIONS.md` for frozen experimental decisions.
4. `AGENTS.md` if an automated coding agent will touch the project.
5. `THIRD_PARTY_NOTICES.md` before using Brain2Qwerty or SpanishBCBL material.
6. `docs/RW3_STAGE_A_AUTHORIZATION_PACKET.md` before proposing replay,
   streaming, or hardware work.
7. `docs/LOOP_24_LOCAL_PRECISION_RUNTIME.md` plus its preregistration before
   proposing model precision, quantization, local-runtime, memory, or energy
   benchmarks.

## Ways To Contribute

Good contribution lanes include:

| Lane | Examples | Real neural data required? |
|---|---|---:|
| Base Python | schemas, hashes, manifests, metrics, reports, error messages | No |
| Synthetic fixtures | malformed files, timing cases, cap tests, deterministic replay | No |
| Neuro formats | BrainVision, EDF/EDF+, BDF, EEGLAB, FIF, BIDS reader validation | No; synthetic first |
| EEG compatibility | metadata reports, reference/geometry documentation, bounded local validation | Not for the first gate |
| EEG hardware | offline replay adapters, timestamp audits, packet-loss reports, device descriptors | Usually n

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Apache-2.0** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text

                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Apache-2.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Apache-2.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `NEURODECODE` (category: BRAIN COMPUTER INTERFACE)
- **Upstream URL:** https://github.com/CheickDiakite-yikes/neurodecodekit
- **Pinned commit (SHA):** `4e3be772f557b07ea8d4e220b1e3fe5e60d883cb`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`e49fdd1bcd12bd9fae008cfa39e3775be60742da67b54838e12cb984641cc237`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

