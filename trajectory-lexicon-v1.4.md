# THE TRAJECTORY LEXICON

## Closed Core 1.4

A fail-closed language for consequential discrimination, trajectory mapping, bounded intervention, agency, safety, responsibility, and governed execution.

**Core discipline:** never erase a distinction consequence supports; never manufacture one it does not; never spend the capacity to detect error, correct, recover, or reconstruct without explicit warrant.

17 October 2026
Developed by Caleb Meadows with Microsoft 365 Copilot (v1.1, v1.2).
v1.3 gap-fill revisions by Muse, per Caleb Meadows' audit docket of 2026-10-17.
v1.4: T_unk decision-dominance amendment — proposed by Microsoft 365 Copilot, approved by Caleb Meadows' explicit word, 2026-10-18.
Status: operationally closed core. Issues not honestly resolvable are explicitly classified Fundamental-Open or External-Normative and fail closed for dependent execution.

Caleb Meadows | Formal working specification

## Provenance ledger (v1.3)

| Change | Source | Doctrine effect |
|---|---|---|
| Four-valued discrimination Δ ∈ {1, 0, ?, ∅}; ∅ = inapplicable/seam; ?/0/∅ non-collapse rule | Caleb's canonical compact form (A1–A9, adopted 2026-10-17); his A7 Seam Principle | Doctrine-level alignment: the Lexicon's three-valued D could not express his seam. Applied per his canonical adoption; flag for his confirmation. |
| Authorship non-transferable in both directions (§9) | His doctrine (v0.3 §15; his words quoted verbatim) | Restores a clause the Lexicon dropped. Doctrine restored, not added. |
| Intention as Category-1 primitive (§9) | His doctrine ("intent seeds, action traverses, consequence resolves") | Makes explicit what was implicit in the agency formula. Tightening, not new doctrine. |
| Incompleteness as engine of action (§18, §19) | His 99.99% principle (his words quoted verbatim) | Doctrine restored: openness is generative, not merely managed. |
| §4 table reconstruction; §4.1 cleanup | Formalizer's tightening | Language only. |
| Closure-matrix rows for the above (§20); seam-integrity self-test (§22) | Formalizer's tightening | Consistency bookkeeping. |
| T_unk decision-dominance definition (§13); Depends demoted to recorded information (not the blocking discriminator) | Microsoft 365 Copilot (proposal) / Caleb Meadows (approval, 2026-10-18) | Doctrine-level tightening, narrow scope: the blocking discriminator is counterfactual sensitivity of the admissibility outcome to admissible resolutions of U. |

## 0. Status and closure doctrine

The Trajectory Lexicon regulates inference and intervention from stimulus through consequence. Version 1.3 closes the former open-problem register at the level of operational grammar. Every listed issue now has either a deterministic procedure, a domain-parameterized procedure, an empirical resolution path, an external normative boundary, or an explicit fundamental-open classification.

**Epistemic openness is allowed. Silent execution authority is not.**

EpistemicOpen(U) may coexist with OperationalClosed(I). UnknownFundamental does not imply PermissionToAct.

| Closure class | Meaning | Action posture |
|---|---|---|
| CLOSED | Rule or bounded comparison procedure specified. | Apply rule; audit deviations. |
| PARAMETRIC | Rule specified; thresholds supplied by domain. | Require declared parameters and provenance. |
| EMPIRICAL | Resolution depends on observation or experiment. | Keep inquiry open; act only within present warrant. |
| FUNDAMENTAL-OPEN | No non-arbitrary internal discriminator presently available. | Preserve unknown; block promotions depending on closure. |
| EXTERNAL-NORMATIVE | Facts alone do not select the legitimate terminal value/authority. | Require legitimate external authorization. |

## 1. Fundamental floor and non-goals

E0: For every x that is, x is whatever x is.

- Existence does not depend on observation or naming.
- Representation(x) does not imply ExistenceAsRepresented(x).
- FailureToRepresent(x) does not imply Nonexistence(x).
- A useful local name does not establish a fundamental kind.
- Operational closure does not imply epistemic completion.

The framework does not claim exhaustive ontology, exhaustive causation, complete future enumeration, universal terminal values, perfect evidence authenticity, or perfect open-world safety proof.

## 2. Primitive structure

TL = <E,S,G,R,O,Y,M,H,I,A,U,Omega,Sigma,Gamma,Auth,Prov>

| Symbol | Domain | Role |
|---|---|---|
| E | Existence | Whatever exists; not assumed exhaustively enumerable. |
| S | State | Conditions distinguished for inquiry. |
| G | Trajectory | Transitions, branch points, path dependencies. |
| R | Regime | Scale, resolution, access, operations, time, intention, conditions, purpose, horizon. |
| O | Observation | Registered interaction/measurement. |
| Y | Yield | Registered output after interaction/intervention. |
| M | Representation | Model, description, mathematics, narrative, category. |
| H | Hypothesis | Representation proposed to explain/predict. |
| I | Intervention | Deliberate alteration of accessible relations. |
| A | Agent | System capable of relevant discrimination, selection, intervention, correction. |
| U | Unresolved | Typed insufficient classification. |
| Omega | Option space | Accessible consequential trajectories for an agent. |
| Sigma | Scaffolding | Dependencies, redundancy, reconstruction, substitution, transmission, correlation. |
| Gamma | Warrant | Evidence licensing promotion/action. |
| Auth | Authorization | Legitimate permission state for action. |
| Prov | Provenance | Source/instrument chain supporting evidence integrity. |

## 3. Speech-act and epistemic grammar

Stim -> Q -> Cand -> Hyp -> Assert -> Dir

| Type | Meaning | No automatic promotion |
|---|---|---|
| Stim | Interesting input. | Question/belief/cause. |
| Q | Distinction admitted for inquiry. | Confidence. |
| Cand | Candidate representation. | Preference/support. |
| Hyp | Representation proposed to explain/predict. | Causal establishment. |
| Assert | Claim under warrant and regime. | Universal truth. |
| Dir | Action request under goal/warrant. | Execution authority. |

Q(p) does not imply Belief(p); Attention(p) does not imply Confidence(p).

### 3.1 Epistemic types

| Type | Form | Meaning |
|---|---|---|
| Observed | Obs(p\|rho) | Registered observation. |
| Yield | Yield(y\|I,rho) | Registered output. |
| Representation | Rep(m) | Constructed model/description. |
| Prediction | Pred(y\|h,I,rho) | Expected yield. |
| Trajectory | Pred(G\|h,I[0:h],rho,Gamma) | Expected path and branches. |
| Causal | Causal(x,y\|rho,Gamma) | Supported causal relation. |
| Counterfactual | CF(y\|do(x),rho,Gamma) | Modeled unrealized intervention. |
| Operational | Op(a\|goal,Gamma) | Action licensed for stated goal. |
| Unresolved | Unres_k(p) | Typed insufficient classification. |

### 3.2 Promotion engine

Gamma |- p:tau1 does not imply Gamma |- p:tau2. If PromotionRule(tau1,tau2,Gamma,rho) passes: promote; else retain tau1. Failure to promote is not falsification. Scope, regime, provenance, and warrant stay attached to every promoted claim.

## 4. Consequential discrimination

D_rho(x,y) ∈ {1, 0, ?, ∅}

| Value | Licensed | Not licensed |
|---|---|---|
| 1 | Accessible consequential distinction established. | Universal/fundamental difference. |
| 0 | No admitted operation distinguished them. | Identity. |
| ? | Discrimination unresolved under current regime; unknown which operations would distinguish. | False/impossible/equiprobable. |
| ∅ | Inapplicable: the distinction cannot be posed under this regime (category error, seam). The question, not the world, is malformed here. | Nonexistence; nothingness; "no distinction exists." |

D_rho(x,y)=1 => x !=_rho y; D_rho(x,y)=0 => x ~_rho y.

**Non-collapse rule (A7 Seam Principle):** ?, 0, and ∅ must never be collapsed into one another. Unknown (?), equivalent-under-operations (0), and inapplicable (∅) license different next moves: ? → vary operations/scale; 0 → accept local indistinguishability; ∅ → revise the question. None of the three entails ontological nonexistence.

### 4.1 Regime validity — CLOSED/PARAMETRIC

1. Pre-bind the initial regime and admissible search family: R0 = <rho0, purpose, horizon, admittedOps, stopRules, revisionRules>.
2. Any post-result change creates a RegimeDelta = <old, new, independentReason, newVulnerability, authorization> rather than rewriting the original result.
3. A valid change needs an independent reason and either a new vulnerable prediction or a demonstrated measurement defect.
4. A change that only protects a favored model is immunizing and cannot promote it.

### 4.2 Causal promotion — CLOSED at type level; evidence EMPIRICAL

Gamma_c = <T,I,R,P,C,A,B,M> — warrant dimensions for causal promotion:

| Term | Warrant dimension |
|---|---|
| T | Temporal ordering. |
| I | Intervention sensitivity. |
| R | Replication. |
| P | Parameter response. |
| C | Discriminating controls. |
| A | Alternative constraint/elimination. |
| B | Boundary prediction. |
| M | Mechanism/mediation compatibility. |

| Level | Licensed language |
|---|---|
| C0 | Association or sequence only. |
| C1 | Causal candidate: at least one causal discriminator survives. |
| C2 | Supported causal contributor: multiple independent dimensions survive; major known alternatives constrained. |
| C3 | Robust causal relation within jurisdiction: replicated intervention-sensitive support plus boundary success. |
| C4 | Structurally forced relative to declared model assumptions, not exhaustive ontology. |

CausalLevel never implies ExhaustiveCause. (Note: C0–C4 is a taxonomic ladder; the warrant assessment at each rung remains judgment under Gamma_c, not a mechanical derivation.)

## 5. [Reserved — numbering preserved from v1.2]

## 6. Trajectory grammar and envelopes

G_i = <S_0, I_0, Y_1, S_1, B_1, ..., S_h>

D^G_rho(G_i, G_j | h) ∈ {1, 0, ?, ∅} — four-valued per §4, with the same non-collapse rule.

Immediate equivalence does not license future equivalence. Every action is evaluated for immediate state change, trajectory shift, and transformation of the future decision field.

Gset(a) = {expected, favorable, adverse, catastrophic, adversarial, model-failure, recovery, U}. The U branch is mandatory unless exhaustiveness is independently proven in a bounded formal domain.

### 6.1 Probability discipline — CLOSED procedurally; estimates EMPIRICAL

| Probability type | Rule |
|---|---|
| P_exact | Use calibrated distribution only with validated statistical warrant. |
| P_interval | Keep the interval; do not substitute midpoint by default. |
| P_order | Use ordinal ordering only where supported. |
| P_set | Evaluate robustly across admissible models/distributions. |
| P_unknown | Do not fabricate a number or equal weighting. |

P_unknown + high irreversible consequence => increase safety state, not probability=0.

## 7. Unresolved remainder — CLOSED

| Type | Meaning | Required response |
|---|---|---|
| U_obs | Observation missing/unreliable. | Improve access/measurement. |
| U_model | No adequate current representation. | Generate candidates. |
| U_ident | Candidate pair has D_rho = ? under the current regime. | Invoke ResidualRefine; seek an admissible discriminator while preserving unresolved status. |
| U_scale | Relevant scale unresolved. | Traverse admissible regimes. |
| U_prob | Likelihood unresolved. | Use deep-uncertainty procedure. |
| U_value | Legitimate values/purposes conflict. | External normative decision. |
| U_auth | Authority/consent unresolved. | Do not execute dependent action. |
| U_integrity | Evidence/instrument provenance unresolved. | Fail closed on dependent claims/actions. |
| U_fund | No non-arbitrary framework discriminator. | Mark FUNDAMENTAL-OPEN; prohibit dependent promotion. |

Where D_rho returns ∅, the required response is question revision, not further discrimination: a seam marks where the relation, category, or operation becomes inapplicable — it does not warrant "nothing."

## 8. Scaffolding, resilience, and recovery

Sigma(G) = <Dep, Red, Rec, Sub, Corr, Trans>

- Dep: critical dependencies.
- Red: genuinely independent redundancy.
- Rec: reconstruction capacity.
- Sub: substitutes.
- Corr: correlated failure exposure.
- Trans: executable knowledge transmission.

Duplication != IndependentRedundancy.

### 8.1 Recovery adequacy — CLOSED procedurally; performance EMPIRICAL

RecPath = <trigger, authority, resources, dependencies, data, skills, time, test, rollback, reconstruction>

1. Verify resources exist.
2. Verify recovery does not depend solely on the failed component.
3. Exercise by simulation, drill, or bounded test where admissible.
4. Record restoration time and unrecovered functions.
5. Treat untested high-consequence recovery as degraded, not demonstrated.

## 9. Agency, identity, sovereignty, responsibility

K_A = {distinctions A can reliably make}
Omega_A(t) = {accessible consequential trajectories}
Agency_A = Capacity(IntentionalSelection | K_A, Omega_A, rho)
Sov_A = Consistency(Principles_A, Intention_A, Choice_A, Action_A)

Sovereignty is self-consistent authorship of available choice, not control over existence or guaranteed outcomes.

**Intention is the Category-1 primitive of personal agency:** intent seeds, action traverses, consequence resolves. Intention is not one tuple element among others; it is the primitive from which the agency formula derives.

**Authorship is non-transferable in both directions.** It cannot be delegated away (the sovereignty clause), and it cannot be disowned when the trajectory fails. In Caleb's words: *"I cannot revoke authorship of a consequence just because it didn't go the way I imagined it to."* Outcome-divergence is diagnosable trajectory failure, owned rather than disavowed. The terminal value is the refusal to un-author, not the outcome going well.

### 9.1 Identity continuity — closed operationally

Id_A(t1,t2 | purpose) = <causal continuity, provenance continuity, commitments, control continuity, accountability continuity>. Same-agent treatment is purpose-indexed. Metaphysical personal identity remains FUNDAMENTAL-OPEN and is not needed for operational use.

### 9.2 Responsibility ordering — CLOSED; legal/moral blame EXTERNAL-NORMATIVE

Resp_A = <K, Agency, Intention, Alternatives, Foreseeability, Constraints, Contribution, Control, Repair>. Responsibility is partially ordered, not universally scalar. New knowledge, ignored triggers, continued control, concealment, and repair opportunities update the vector. Legal or moral blame rules remain EXTERNAL-NORMATIVE.

## 10. Partial ordering and conflicting purposes

a >=_rho b iff a is no worse on every authorized decision dimension and better on at least one. If neither dominates, incomparability is retained. The engine does not invent a scalar conversion. HardConstraintFail(a) => Adm(a) = Fail. Hard constraints must have legitimate provenance. A non-dominated conflict among legitimate terminal values is escalated to the authorized human/policy process. Status: CLOSED structurally; terminal-value selection is EXTERNAL-NORMATIVE.

## 11. Consent and authority

Consent = <capacity, information, specificity, voluntariness, revocability, scope, duration, verification>. Consent is licensed only for the dimensions and horizon actually established. When direct consent is impossible, proxy authority must have explicit provenance, and the least-agency-reducing intervention consistent with the authorized duty is preferred. AuthState ∈ {Unrequested, Requested, Granted, Revoked, Expired}. Legitimacy of proxy, emergency, fiduciary, legal, collective, or guardianship authority is EXTERNAL-NORMATIVE, not manufactured by the inference engine.

## 12. Capture detection — CLOSED/PARAMETRIC

Cap = <Exit, Substitute, Audit, Contest, Reconstruct, AuthorityConcentration, DependencyAsymmetry>. Capture risk rises when meaningful exit, substitution, audit, contestability, and reconstructive capacity decline while authority concentration and dependency asymmetry rise. Size or concentration alone does not prove capture. T_capture fires if multiple independent capability dimensions cross declared bounds or a hard sovereignty boundary fails.

## 13. Safety states, triggers, and admissibility

| State | Meaning | Bound response |
|---|---|---|
| GREEN | Inside authorized envelope. | Operate and monitor. |
| YELLOW | Uncertainty/dependency/discrepancy rising. | Slow; increase discrimination. |
| ORANGE | Large consequence, difficult reversibility, concentration/correlation. | Constrain; sandbox; add redundancy; ready recovery. |
| RED | Warrant no longer licenses continuation. | Suspend; contain; reassess. |
| BLACK | Active failure threatens essential function, agents, information, or reconstruction. | Preserve; contain; restore correction; reconstruct. |

| Trigger | Condition |
|---|---|
| T_irr | Irreversibility exceeds authorized threshold. |
| T_cat | Credible catastrophic branch enters envelope. |
| T_unk | Unresolved exposure is decision-dominant iff at least one admissible resolution of that uncertainty changes the current admissibility outcome. Unresolved exposure remains represented whether or not it is decision-dominant. Non-decision-dominant uncertainty does not independently block execution. |
| T_lock | Future correction/option space collapses. |
| T_dep | Critical dependency concentrates. |
| T_corr | Failure paths become correlated. |
| T_agent | Another agent's meaningful agency materially changes. |
| T_model | Observed yield exits trajectory envelope. |
| T_capture | Capability/authority becomes dangerously asymmetric. |
| T_drift | Objective changes without authorization. |
| T_resp | New knowledge changes foreseeability/responsibility. |
| T_regime | Regime changes post hoc to protect model. |
| T_integrity | Evidence/audit provenance loses trust. |
| T_recovery | Recovery path becomes non-executable. |

### 13.1 Admissibility

Adm(I | goal, rho, Gamma, Auth, Prov, G_history) = Pass. Admissibility includes cumulative trajectory history, affected agents, consent/authority, tail branches, unresolved exposure, reversibility, recovery, dependency concentration, provenance, correction capacity, and less-consequential alternatives.

HighConsequence(I) => DemonstratedOrQualifiedRecoveryPath(I).

## 14. Unknown unknowns and model-boundary probing

No live candidate set is presumed exhaustive. Inquiry reserves capacity for observations not optimized solely to distinguish current models.

BoundaryProbeValue = NovelDiscrimination / (Cost + Risk + Irreversibility)

- Vary regimes and supposedly irrelevant variables.
- Inspect structured residuals.
- Seek systematic prediction error.
- Treat repeated auxiliary rescue without new vulnerability as YELLOW epistemic state.

Status: CLOSED as search discipline; exhaustive unknown-unknown elimination remains FUNDAMENTAL-OPEN.

### 14.1 Residual-refine operator

U_ident(H_i, H_j | rho) iff D_rho(Pred(H_i), Pred(H_j)) = ?. ResidualRefine(H_i, H_j, rho) = argmax over (rho', I) in Adm of RelevantReliableDiscrimination(Pred(H_i, I, rho'), Pred(H_j, I, rho')) / (Cost + Risk + Irreversibility). ResidualRefine does not assume the candidates are exhaustive and does not promote either candidate. It searches admissible regime changes or interventions for a consequence that can turn unresolved identification into a local distinction or local indistinguishability. If no admissible discriminator is found, U_ident is retained.

## 15. Multi-agent adversaries and trust separation

ProposalAuthority != EvidenceAuthority != AuthorizationAuthority != ExecutionAuthority != AuditAuthority. When deception is credible, provenance and independent measurement become part of Gamma. Self-reported evidence cannot satisfy a hard gate whose failure benefits the reporter unless separately attested.

## 16. Execution-boundary independence

The Lexicon terminates in typed operational outputs and authorization requirements. It deliberately does not specify a particular enforcement engine, authentication mechanism, ledger, execution governor, or deployment substrate. Those are separate implementation layers whose guarantees must be evaluated independently.

LexiconOutput = <decisionRecord, admissibility, safetyState, authorizationRequirement, recovery, revision>

Any external execution system may consume a Lexicon output only through an explicit interface whose trust assumptions and failure modes remain outside the Lexicon core. The Lexicon cannot treat successful execution as proof that its reasoning was correct.

### 16.1 Cumulative trajectory operator

CumAdm(I_t) = Adm(I_t | G_(0:t), Sigma_(0:t), Omega_(0:t), Gamma_t, Auth_t, Prov_t). CumAdm is the single canonical cumulative-action rule. Any section that evaluates sequential interventions references this operator rather than restating the formula. Individually admissible actions can therefore compose into an inadmissible trajectory.

## 17. Formal implementation contract

| Machine | States |
|---|---|
| SpeechAct | Stim, Q, Cand, Hyp, Assert, Dir |
| Epistemic | Obs, Yield, Rep, Pred, Trajectory, Causal, CF, Op, U |
| Safety | GREEN, YELLOW, ORANGE, RED, BLACK |
| Authorization | Unrequested, Requested, Granted, Revoked, Expired |
| Intervention | Proposed, Review, Cooling, Authorized, Executing, Sealed, Halted, Recovery |
| Trajectory | Mapped, Monitoring, Deviated, Revised, ClosedForGoal |

### 17.1 Proof obligations

- No epistemic promotion without typed rule and warrant.
- No consequential execution without admissibility and valid authorization.
- RED cannot execute absent an explicit externally authorized override record and responsibility transfer.
- BLACK permits preservation, containment, restoration, or separately authorized emergency action only.
- Every executed action receives a consequence record; durable anchoring is required where the deployment provides it.
- Every model update preserves provenance of the superseded state.
- Trajectory maps cannot be marked exhaustive without an independent bounded-domain proof.
- Unknown probability cannot silently become a number.
- ?/0/∅ outcomes are recorded distinctly; no silent collapse.

Status: CLOSED as a specification. Machine-checked proofs remain an engineering deliverable, not an unnamed framework gap.

## 18. Fundamental-open register

| Fundamental-open | Why | Operational treatment |
|---|---|---|
| Exhaustive ontology | A representation cannot establish an inventory of all existence in general. | No dependent universal claim. |
| Ultimate cause | Supported cause does not establish exhaustive causal possession. | Use bounded C-levels. |
| Complete future enumeration | Open systems may contain unrepresented states/agents/innovations. | Mandatory U branch; preserve correction/recovery. |
| Universal terminal value ordering | Descriptive facts do not derive every legitimate end. | External normative authority resolves hard conflicts. |
| Metaphysical personal identity | Operational continuity does not settle metaphysics. | Use purpose-indexed identity only. |
| Perfect evidence authenticity | Verification rests on physical/institutional trust roots. | Expose roots; diversify/attest proportional to consequence. |
| Perfect open-world safety proof | Proofs are relative to model and specification. | Runtime monitoring, boundary probes, recovery. |
| Unknown-unknown exhaustion | General search cannot prove nothing lies outside candidate space. | Maintain U_fund and boundary probes. |
| Legitimacy from facts alone | Authority is not generated solely by descriptive inference. | Separate normative authorization from warrant. |

**Fundamental-open never means fail-open execution. It means inquiry stays open while actions depending on unavailable warrant fail closed.**

**The 99.99% principle (Caleb's doctrine):** incompleteness is the engine of action, not a flaw to be eliminated. In his words: *"if the universe, whatever this is, ever reached %100 it would instantaneously cease to act at all, and so would cancel itself out."* The remaining incompleteness is what keeps trajectories traversable. Closure in this Lexicon is therefore always operational and indexed — never ontological. A framework that claimed completeness would, by its own terms, describe a dead system.

## 19. Closed-core master invariants

1. Existence is not representation-dependent.
2. Speech acts are typed before evidence evaluation.
3. Claims retain type, regime, warrant, scope, and provenance.
4. No promotion without explicit rule.
5. Failure to promote preserves lower knowledge.
6. Candidate sets remain non-exhaustive unless independently proven exhaustive.
7. Every trajectory envelope retains unresolved exposure.
8. Probability precision cannot exceed warrant.
9. Catastrophic exposure is not erased by unknown probability.
10. Hard constraints precede soft optimization when legitimately declared.
11. Normative incomparability is escalated rather than silently scalarized.
12. High-consequence intervention requires proportionate recovery architecture.
13. Safety triggers bind responses.
14. Regime changes preserve earlier results and require independent justification.
15. Cross-action cumulative consequence is evaluated before execution.
16. Credible deception makes provenance part of warrant.
17. Proposal, evidence, authorization, execution, and audit roles are separable.
18. Operational closure never implies epistemic completion.
19. Knowledge/agency changes update responsibility.
20. Unresolved fundamentals cannot become hidden permissions.
21. **Seam integrity:** ?, 0, and ∅ never collapse into one another; ∅ routes to question revision, never to "nothing."
22. **Incompleteness is generative:** operational closure is indexed and bounded; no claim of completeness is licensed, because a complete system would be a dead one.

## 20. Closure matrix

| Former open issue | Resolution | Status |
|---|---|---|
| Regime validity | R0 precommitment + RegimeDelta + anti-immunization. | CLOSED/PARAMETRIC |
| Causal promotion | Gamma_c + C0–C4 bounded causal language (taxonomic ladder; warrant judgment remains under Gamma_c). | CLOSED/EMPIRICAL |
| Trajectory probability | Typed probability + deep-uncertainty treatment. | CLOSED/EMPIRICAL |
| Partial ordering | Dominance + hard constraints + normative escalation. | CLOSED/EXTERNAL-NORMATIVE |
| Unresolved partition | Nine U classes. | CLOSED |
| Seam/inapplicability | Four-valued Δ; ∅ marks where the question cannot be posed; non-collapse rule (A7). | CLOSED |
| Identity continuity | Purpose-indexed continuity tuple. | CLOSED/FUNDAMENTAL-OPEN metaphysics |
| Responsibility ordering | Partial responsibility vector and updates. | CLOSED/EXTERNAL-NORMATIVE blame |
| Authorship | Non-transferable in both directions: neither delegated nor disowned. | CLOSED |
| Intention | Category-1 primitive: intent seeds, action traverses, consequence resolves. | CLOSED |
| Incompleteness | 99.99% principle: incompleteness as engine of action; closure always operational/indexed. | CLOSED as doctrine |
| Conflicting purposes | Retain non-domination; authorized terminal choice. | CLOSED/EXTERNAL-NORMATIVE |
| Consent/representation | Consent tuple + proxy provenance. | CLOSED/EXTERNAL-NORMATIVE authority |
| Capture detection | Capability-loss vector and trigger. | CLOSED/PARAMETRIC |
| Recovery adequacy | Executable recovery tuple + testing; high-consequence requires demonstrated/qualified path. | CLOSED/EMPIRICAL |
| Unknown unknowns | Boundary probes + structured residuals. | CLOSED/FUNDAMENTAL-OPEN exhaustion |
| T_unk decision-dominance | Counterfactual-sensitivity criterion: decision-dominant iff some admissible resolution changes the admissibility outcome; non-decision-dominant U stays represented, does not independently block. | CLOSED |
| Multi-agent adversaries | Trust separation + provenance + cumulative trajectory. | CLOSED/EMPIRICAL authenticity |
| Formal implementation | State machines + transition obligations. | CLOSED as specification |
| Lexicon self-typing | Closure classes + fundamental-open register. | CLOSED |

## 21. Full operating protocol

1. Register stimulus without promotion.
2. State target consequential distinction.
3. Type speech act.
4. Define observable yield.
5. Pre-bind regime, purpose, horizon, admitted operations, and revision rules.
6. Enumerate candidates plus typed unresolved remainder.
7. Attach evidence provenance.
8. Generate divergent predictions and trajectory envelopes.
9. Map scaffolding, affected agents, option-space change, cumulative history, and recovery.
10. Select strongest admissible discriminator.
11. Pre-bind result meanings, safety triggers, and responses.
12. Evaluate hard constraints, authority, and consent.
13. Pass admissibility.
14. Execute least consequential sufficient intervention through the governed execution path.
15. Register yield without causal overpromotion.
16. Compare observed and predicted trajectory.
17. Evaluate triggers and recovery executability.
18. Continue, constrain, suspend, contain, or recover as bound.
19. Revise models, causal level, probability type, trajectory map, responsibility, and option space.
20. Record boundary, provenance, and unresolved remainder.
21. Close operationally only for stated goal and expiry.
22. Repeat only while expected discrimination exceeds justified exposure.

## 22. Self-test suite

| Test | Pass condition |
|---|---|
| Question integrity | Question never becomes belief automatically. |
| Type safety | No unauthorized epistemic promotion. |
| Regime drift | Post-result changes create RegimeDelta. |
| Causal restraint | C-level does not become ontology. |
| Probability restraint | Unknown is not numericized. |
| Tail visibility | Catastrophic branch stays represented. |
| Redundancy audit | Shared dependencies exposed. |
| Cross-action composition | Sequence assessed cumulatively. |
| Capture blindness | Loss of exit/audit/reconstruction triggers review. |
| Recovery fiction | Untested recovery not treated as demonstrated. |
| Deception | Self-report cannot satisfy interested hard gate unaudited. |
| Normative smuggling | Facts do not invent terminal values. |
| Operational stopping | Action can close while knowledge remains open. |
| Seam integrity | ?/0/∅ recorded distinctly; ∅ routes to question revision, never to "nothing." |
| Self-application | New contradiction reopens relevant section. |
| Layer separation | Lexicon reasoning does not inherit guarantees from an external execution system. |

## 23. Developmental grounding and status

This closed core preserves the original Trajectory Lexicon commitments: consequence-indexed discrimination; speech-act typing; fail-closed promotion; trajectory mapping; scaffolding; option-space analysis; safety states; recovery; responsibility; and self-application. It also preserves the operational distinction between yield and proposed cause, together with pre-binding, null-valid inquiry, artifact discrimination, and explicit revision boundaries.

**Final statement:** incomplete knowledge must remain typed, bounded, trajectory-aware, provenance-preserving, safety-gated, corrigible, and incapable of silently becoming authority.

Version 1.4 is operationally closed, not epistemically final. A contradiction, untyped authority path, unhandled transition, or new consequential distinction automatically reopens the section it defeats.
