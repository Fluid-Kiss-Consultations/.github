# Superdeterminism Application — Amendment Note

**Parent memo:** `superdeterminism-application-memo.md`
**Purpose:** Corrections and sharpenings from the dedicated reading pass on Donadi-Hossenfelder 2022 and the "Hossenfelder/Palmer/Price 2022" citation. Also answers the Price-cognitive-architecture question flagged in the handoff.
**Status:** Canonized. Decisions A, B, C, D ratified by mourne.
- (A) Corrections accepted: Lindblad-not-EPI; conference-not-paper; Price canonical is 2012.
- (B) Three-moves characterization of Donadi-Hossenfelder 2022 accepted as the application section's specific illustration.
- (C) Price gets a one-line seeded reference in the application section. No Archimedean-point engagement in this paper; the seed is preserved for potential later expansion.
- (D) Hossenfelder-specific characterization softened throughout. Framework framing emphasizes structural universality — the moves are rational, good-faith navigation of an inescapable architecture, not individual failings.

---

## Correction 1 — Donadi-Hossenfelder 2022 is not an "Extended Path Integral" model

The parent memo characterized the Donadi-Hossenfelder concrete model as an "Extended Path Integral" realization of superdeterminism. **This is wrong.** The actual technical structure is:

- **Lindblad-form master equation with future-input dependence.** The model modifies the standard density-matrix dynamics by adding Lindblad decay terms (Eqs. 4 and 15 in the paper) whose operators depend on the detector-setting eigenstates `|I⟩` at the time of detection.
- Hidden variables are complex numbers `λ_I` uniformly distributed in the unit circle, one per Hilbert-space dimension minus one.
- Bell's hidden variables are the **combined** specification `Λ = (λ_I, |I⟩)` — the λ's *and* the detector-setting basis together. This is the definitional move that secures violation of Statistical Independence: `p(Λ|a,b) ≠ p(Λ)`.
- When averaged over the λ's, the model reproduces Born's rule exactly. No fine-tuning of λ distributions is required.

The memo likely conflated this paper with a **separate** Donadi-Hossenfelder 2022 paper: *"A path integral over Hilbert space for quantum mechanics,"* Annals of Physics 440, 168827 (2022). The two papers are both from 2022 and both co-authored by Donadi and Hossenfelder, but the path-integral paper is a different mathematical framework addressing a different problem. The toy model that is the "concrete mathematical realization of superdeterminism" is the Lindblad paper, not the path-integral paper.

**Revised characterization for the application section:**
> Donadi and Hossenfelder (2022) provide a concrete mathematical realization of superdeterminism in the form of a Lindblad-type master equation with future-input dependence: the evolution of the prepared state depends on the detector-setting basis at the time of measurement. When averaged over uniformly-distributed hidden variables, the model reproduces Born's rule without fine-tuning.

---

## Correction 2 — "Superdeterminism and Retrocausality" (Hossenfelder/Palmer/Price 2022) is not a paper

It is the **2022 Bonn Workshop** co-organized by Hossenfelder, Palmer, and Price, held at the Center for Science and Thought, University of Bonn, and the associated MDPI *Entropy* Special Issue. No peer-reviewed paper by all three under this title exists.

Citations in the literature to "Hossenfelder, Palmer, & Price, Superdeterminism and Retrocausality, 2022" (e.g., Vissers 2023) refer to the **conference as an event**, not to a paper. This is a common shorthand but it is technically a non-citation. Using it as a source in a peer-reviewed paper would draw immediate reviewer objection.

**Peer-reviewed output that actually came from the workshop:**

1. **Adlam, E., Hance, J.R., Hossenfelder, S., & Palmer, T.N. (2024).** "Taxonomy for Physics Beyond Quantum Mechanics." *Proceedings of the Royal Society A* 480(2294): 20230779. DOI: 10.1098/rspa.2023.0779. arXiv:2309.12293.
   - The formal peer-reviewed synthesis from the Bonn Workshop. Classifies superdeterministic (strong/weak), retrocausal (with/without signalling, dynamical/non-dynamical), future-input-dependent, atemporal, and all-at-once models under a unified m-model framework.
   - Introduces distinctions between *deterministic* and *predictable* (Bohmian mechanics is deterministic but not predictable); between space-time causality and interventionist causality; and the term *retrotemporal* for future-input-dependent models that do not respect the light-cone structure.
   - **Note:** Price is **not** an author on this paper. The peer-reviewed physics output from the conference is Hossenfelder/Palmer-side, not Price-side.

2. **Hossenfelder, S. (2024).** "Quantum Confusions, Cleared Up (or so I hope)." arXiv:2309.12299. [Companion paper to Taxonomy; applies the taxonomy in an explicitly instrumentalist register.]
   - Framework-relevant: Hossenfelder opens by declaring her instrumentalist stance explicitly. The framework reads this as a rational and structurally expected response — an instrumentalist frame releases the theorist from realist commitments that cannot be adjudicated from within a causal-ceilinged observer's position, and is the kind of move the framework predicts any serious theorist working in this terrain to make. This is not a weakness of her position; it is a structural feature of any position occupying this epistemic location.

**Revised citation:** Replace "Hossenfelder, S., Palmer, T.N., & Price, H. (2022). 'Superdeterminism and Retrocausality.' *Entropy* special issue" (from the parent memo's new-citations list) with:

- **Adlam, Hance, Hossenfelder, Palmer (2024)** for the formal taxonomy
- **Hossenfelder (2024)** for the instrumentalist application
- **Bonn Workshop on Superdeterminism and Retrocausality, 2022** (organized by Hossenfelder, Palmer, Price) cited separately as the originating event if contextually useful, with URL pointer to the izph.de video archive
- **Price, H. (2012). "Does Time-Symmetry Imply Retrocausality? How the Quantum World Says 'Maybe'?"** *Studies in History and Philosophy of Modern Physics* 43(2): 75–83. arXiv:1002.0906. — Price's canonical single-authored statement of the TSAR argument (Time-Symmetry + Realism + Discreteness ⇒ Retrocausality), if Price's framing is to be cited

---

## Answer to the handoff question — does Price's retrocausal framing introduce cognitive-architecture claims?

**No.** Price's work in quantum foundations stays squarely in philosophy-of-time and formal quantum foundations. His TSAR argument is a formal implication from three explicit assumptions; his broader "Archimedean point" program (*Time's Arrow and Archimedes' Point*, 1996) argues for a perspective-transcendent view of time reachable through formal reasoning. He does not engage predictive processing, clinical delusion mechanisms, or the cognitive-architecture literature.

**Treatment in this paper (per decision C):** Price gets a single-line seeded reference in the application section, situating retrocausality as the neighboring framework on the foundations landscape (Price 2012, TSAR). The paper does not engage the Archimedean-point disagreement here; that engagement is a natural fit for a future paper and the seed is preserved for it.

**Priority claim status (re-confirmed):** The cross-disciplinary bridge from predictive-processing / BADE mechanisms to self-sealing reasoning in fundamental physics remains unoccupied. Neither the superdeterminism camp (Hossenfelder/Palmer) nor the retrocausality camp (Price/Wharton) crosses into cognitive-architecture terrain. The Taxonomy paper's scope explicitly excludes analysis of "the origin of this unease."

---

## New framework-relevant observations from the reading pass

The Donadi-Hossenfelder 2022 paper contains three explicit structural moves that the observer-constraint framework identifies. These are not errors or intellectual failings — they are exactly what the framework predicts **any** causal-ceilinged observer defending a theory in a domain detached from direct observation to do. They appear in a readable, traceable form in Donadi-Hossenfelder 2022 because the authors are unusually transparent about the shape of their argument; the same structural moves are present throughout the entire foundations-of-physics debate, on all sides, often less visibly. The observer-constraint framework treats these moves as skilled, good-faith navigation of an inescapable cognitive architecture. Citing them is diagnostic, not indicting.

### Move 1 — The assumption-protection move

When addressing the natural objection "how do the hidden variables at preparation 'know' the future detector settings?", the authors respond:

> "As for any scientific theory, we make assumptions to explain data. The assumptions of a theory are never explained within the theory itself (if they were, we wouldn't need them). Their scientific justification is that they allow one to make correct predictions."

This is structurally the same shape as BADE-maintained reasoning expressed at the philosophical level: the disconfirming query is routed out of the theory's scope rather than engaged. The authors are not wrong that theories rest on assumptions — every theory does, and every serious theorist will defend that position. The framework's observation is specifically about the kind of assumption being protected: a correlation between hidden variables and future detector settings that is stipulated to be underivable within the theory. That stipulation is reasonable given the authors' stated goal (a concrete toy model, not a fundamental theory), and the framework's point is not that they have erred but that the structural shape of the defense — irrespective of whether the defense is warranted in the local case — is the shape the framework identifies as characteristic of reasoning under deep underdetermination.

### Move 2 — The meta-physical/instrumental fine-tuning split

When fine-tuning objections are raised (Wood-Spekkens 2015; Sen-Valentini 2020), the authors respond by distinguishing "meta-physical" fine-tuning (analyses based on probability measures over parameters that cannot actually vary) from "instrumental" fine-tuning (the amount of input detail required to make a prediction). They then classify the critics' arguments as meta-physical — hence optional, not binding:

> "That an assumption is meta-physical does not make it wrong, but it means it is optional. Such assumptions are in many cases used out of tradition, not because of empirical necessity."

The distinction the authors draw is genuine and defensible on its own terms. The framework's observation is about the structural function the distinction performs in the dialectic: it reclassifies the ground of criticism as non-binding rather than engaging the criticism's object-level content. This is a normal and rational theoretical move under underdetermination — theories regularly need to distinguish binding from non-binding constraints, and the authors are entitled to make that case. The framework simply names the shape: under underdetermination, protective moves are available that neutralize objections by reframing the terrain on which they stand, and those moves are executed in good faith across the debate landscape.

### Move 3 — Testability-by-design

The authors explicitly state the model is "strictly speaking, untestable, because it does not specify where the distribution of hidden variables comes from." A more fundamental theory is required to make the model testable — a theory that has not yet been built. The model's predictive equivalence with QM is therefore absolute by construction.

The framework's observation here is pointed but not adversarial: the authors themselves name this limitation openly, which is scholarly honesty of a high order. Most theoretical constructs in the foundations-of-physics debate have the same property without their authors acknowledging it as directly. What the framework identifies is a general structural condition of the terrain — when a theory is constructed to be predictively equivalent to an existing framework in a domain where the underlying causal substrate is detached from observation, disconfirmation requires additional theoretical machinery that does not yet exist, and the theory is therefore protected from revision by the current evidence base. This is a feature of the terrain rather than a feature of any particular author's work.

---

## Implications for the application section

1. **The application does not portray any one camp as illustrating the framework.** The point is that **all** sides of the superdeterminism / retrocausality / standard-QM debate exhibit the same structural feature: each camp protects its prior (locality, time-symmetry, Statistical Independence) by deploying auxiliary machinery that becomes unfalsifiable within its own framework. The framework is diagnostic of the debate as a whole.

2. **Hossenfelder's community-pathology diagnosis is correct as far as it goes; the framework extends it universally.** She is right that SI-violation is misattributed to loss of free will, right that objections rely on classical-physics intuitions, right that most physicists don't realize Bell's theorem requires SI as a separate assumption from locality. The observer-constraint framework extends her diagnosis to apply symmetrically to the entire foundations-of-physics community, including proponents of every position — and including the observer-constraint framework's own author. The structural mechanism the framework identifies operates on the entire causal-ceilinged-observer set. This is extension, not opposition; agreement on the existence of a structural bias, with broader scope.

3. **Superdeterminism stays as an application case, not an advocacy.** The framework survives Hossenfelder being right about superdeterminism as cleanly as it survives her being wrong. The application section demonstrates that the framework's diagnostic lens does not require adjudicating the physics — it explains why the debate has the structure it has.

4. **Price engagement is a one-line seed only.** The application section cites Price 2012 (TSAR) once, as the pointer to the retrocausal alternative in the foundations landscape. No philosophical engagement with the Archimedean-point program in this paper. The seed is preserved for potential expansion in future work.

5. **Section weighting unchanged.** 15–20% of paper remains the right band. No indication from the reading pass that the application should be larger.

---

## Revised source list for the application section

Confirmed citations after the reading pass:

1. **Hossenfelder, S., & Palmer, T.N. (2020).** "Rethinking Superdeterminism." *Frontiers in Physics*, 8: 139. DOI: 10.3389/fphy.2020.00139. arXiv:1912.06462.
2. **Donadi, S., & Hossenfelder, S. (2022).** "A Toy Model for Local and Deterministic Wave-function Collapse." *Physical Review A*, 106, 022212. arXiv:2010.01327.
3. **Adlam, E., Hance, J.R., Hossenfelder, S., & Palmer, T.N. (2024).** "Taxonomy for Physics Beyond Quantum Mechanics." *Proceedings of the Royal Society A*, 480(2294): 20230779. arXiv:2309.12293. [Post-Bonn-Workshop synthesis.]
4. **Hossenfelder, S. (2024).** "Quantum Confusions, Cleared Up (or so I hope)." arXiv:2309.12299. [Instrumentalist application of the Taxonomy.]
5. **Price, H. (2012).** "Does Time-Symmetry Imply Retrocausality? How the Quantum World Says 'Maybe'?" *Studies in History and Philosophy of Modern Physics*, 43(2): 75–83. arXiv:1002.0906.
6. **Hossenfelder, S. (2024).** "Superdeterminism — The Forgotten Solution." PIRSA:24040080, Perimeter Institute, April 9, 2024.
7. **Hossenfelder, S. (2021).** "Does Superdeterminism save Quantum Mechanics? Or Does It Kill Free Will and Destroy Science?" *Backreaction* blog post. [For the SI-vs-free-will clarification; use as supporting, not load-bearing.]
8. **Hossenfelder, S. (March 2026).** YouTube video on Wolpert-Rovelli-Scharnhorst paper. [For the "science cannot justify the use of itself" framing; timestamped citation when used.]

Struck from the parent memo's list:
- "Hossenfelder, Palmer, Price (2022), *Superdeterminism and Retrocausality*, Entropy special issue" — this was not a paper. Replaced by Taxonomy (#3) above.

Added to the parent memo's list:
- Adlam/Hance/Hossenfelder/Palmer (2024), Taxonomy, peer-reviewed.
- Hossenfelder (2024), Quantum Confusions.
- Price (2012), TSAR argument.

---

## Ratification log

- (A) **Ratified.** Lindblad-not-EPI correction canonical. Conference-not-paper correction canonical. Price canonical is 2012 TSAR.
- (B) **Ratified.** Three-moves characterization is the application section's specific illustration.
- (C) **Ratified with convergent call.** Price gets a one-line seeded reference in the application section. No Archimedean-point engagement in this paper. Seed preserved for future expansion.
- (D) **Ratified.** Hossenfelder-specific framing softened throughout. Framework framing emphasizes structural universality applying to all causal-ceilinged observers including the framework's own author; the moves named are good-faith navigation of an inescapable architecture, not individual failings.

Amendment is canonized. Ready for mourne to signal the next gate.
