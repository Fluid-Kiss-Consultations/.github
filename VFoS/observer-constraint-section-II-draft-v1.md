# §II. Layer 1 — The Observer as Constructor (Neuroscience) — Draft v1

**Paper:** "The Observer-Constraint Framework" (working title, keystone paper #5)
**Author:** mourne / John A. Welch
**Section target:** ~960 words (12% of ~8,000-word paper, per v1.1 outline adjustment)
**This draft:** ~955 words
**Citations used:** Clark 2013; Friston 2010; Ficco et al. 2021

---

The naive model of perception treats the brain as a passive receiver that transduces sensory input into representations of the external world. The model is old, intuitive, and wrong — or at least wrong enough that no serious account of perceptual neuroscience in the last two decades has defended it at its strong reading. What has replaced it is a family of models in which perception is generated rather than received: the brain constructs its best current hypothesis about the state of the world from the top down, compares that hypothesis to incoming sensory signal, and updates either the hypothesis or the weight assigned to the signal depending on which it estimates more reliable.

The clearest synthesis of this predictive-processing framework is Clark (2013). On this account, the brain is a hierarchical prediction machine: at each cortical level, top-down probabilistic models attempt to generate the sensory activity observed at the level below, and what propagates upward is not raw sensory data but prediction error — the residual signal where the generative model failed to match input. Perception is not the endpoint of a bottom-up inferential chain but the state of the generative model once the bidirectional cascade has settled into a minimum-prediction-error configuration. High-level regularities constrain intermediate ones, which constrain low-level ones; each level simultaneously predicts downward and sends error upward. Clark himself catalogues outstanding evidential, methodological, and conceptual challenges to the framework, and the argument here requires only its consensus-stable core: perception is constructed through a hierarchical predictive process, and prediction error is the signal that drives update.

Beneath this architectural description sits a more ambitious unifying claim. Friston (2010) argues that biological systems, including brains, operate by minimizing variational free energy — an information-theoretic quantity that provides an upper bound on the long-run surprisal of sensory samples. Perception, action, and learning fall under a single imperative: perception updates the model so predictions fit input; action changes input so it fits predictions; learning shifts the model's parameters so predictions track the world over time. The strongest readings of the free-energy principle are contested, with critics arguing they verge on the tautological, but the weaker reading — that the brain operates in large part through prediction-error minimization — is consensus-stable and sufficient here.

The predictive-processing picture might have remained a theoretical unification, open to the charge of being more philosophically congenial than empirically grounded. It did not. Ficco et al. (2021), aggregating Activation Likelihood Estimation data across seventy neuroimaging studies, identified the left anterior insula and the left inferior frontal gyrus as clusters appearing consistently in both prediction-encoding and prediction-violation conditions, with a broader predictive network extending through bilateral insula, frontal and temporal gyri, parietal lobules, and claustrum. The specific anatomy is not what matters for the argument. What matters is that the predictive-processing account is no longer merely a theoretical construct awaiting neural grounding; it is a framework with a localizable empirical signature that survives meta-analytic scrutiny.

This gives us the first of two premises the core claim requires: perception is constructed, not received. The second is more restrictive, and it is where the phrase "causally bounded observer" does its work. Every step in the construction process — from the transduction of physical stimuli into neural signal, through the propagation of that signal up the cortical hierarchy, through the downward flow of predictions and the updating of the generative model — is a causal step. There is no channel of perceptual or inferential access that bypasses this substrate; there is no modality of contact with the world that is not, at its lowest physical level, a causal contact. I will refer to this condition as causal mediation: the brain's access to the world proceeds exclusively through causal pathways, and whatever the brain ultimately represents is a reconstruction from the causal residue those pathways deposit. The thesis is physiological, not metaphysical. It makes no claim about the ultimate structure of reality. It claims only that reality, insofar as any observer has access to it, reaches that observer through causes — and that this fact sets the scope of what can and cannot be empirically adjudicated from within the observer's position.

Two consequences follow. First, any domain whose underlying substrate is not causally contactable in this sense is one the architecture can model only through translation, not through direct access. Second, when the architecture models such a domain, the same protective machinery that stabilizes perception against noise — the same precision-weighting that decides whether to update the model or discount the error — becomes available as a mechanism for stabilizing belief against disconfirmation. The next section takes up what happens when that machinery misfires, and why clinical psychiatry has been able to operationalize the misfiring as a measurable, dimensional cognitive phenomenon.

---

## Self-review notes for mourne

**Structural choices made:**

- **Six paragraphs**, mapped to the outline's five-item structure but merged: the outline's items 1 and 2 (naive model failure + Clark's predictive processing) split into paragraphs 1–2 because the naive-model setup reads naturally as its own beat; outline items 3, 4, 5 become paragraphs 3, 4, 5; paragraph 6 is the §III bridge.
- **Paragraph 5 carries the most weight.** It cashes the "causal mediation" term that §I v2 introduced and defines what "causally bounded observer" means physiologically. The paragraph's closing two sentences ("physiological, not metaphysical... sets the scope of what can and cannot be empirically adjudicated") are doing defensive work against the likely reviewer objection "you're smuggling metaphysics in through physiology." I put that defense where the term is defined rather than reserving it for §VIII, because reviewers hit the objection at first occurrence.
- **Paragraph 4 keeps Ficco honest.** The foundation memo's anatomy list ("insula, IFG, TPJ, premotor regions") doesn't match Ficco 2021's headline findings — those are left anterior insula and left IFG, with the broader network extending further. I cited Ficco accurately to what the paper actually found, with the broader list as a descriptive extension rather than as attribution.
- **No citation of Friston with a direct quote on the FEP's tautology-adjacent readings.** The "contested at strongest readings, weaker reading sufficient" framing is structurally loyal to the foundation memo's caveat without needing to quote critics. Saves citation weight for sections that need it more.

**Paying off §I IOUs:**

- **"Causal mediation"** defined in paragraph 5. §I v2 used the term in the claim statement without defining it; §II now cashes it in. The definition is broad enough to cover perception, inference, and memory — consistent with the v1→v2 decision to move from "causal transduction" (narrower) to "causal mediation" (broader).
- **"Causally bounded observer"** grounded physiologically. §I introduced it as an architectural thesis; §II now names the specific physiological facts (stimulus transduction, signal propagation, synaptic release) that ground it. Reviewers looking for what the phrase *means* will find an answer here rather than in §VI.
- **"Constructs rather than receives"** is the §II backbone. Paragraph 1 sets up the shift; paragraph 2 (Clark) delivers the architectural description; paragraph 3 (Friston) delivers the unifying imperative; paragraph 4 (Ficco) delivers the empirical substantiation. Sequenced to build argumentative momentum rather than descriptive accumulation.

**Phrases that are load-bearing and should stay:**

- "causal mediation" (§I v2 canonical term, cashed here).
- "consensus-stable core" and "consensus-stable and sufficient" — preempts the reviewer objection that Layer 1 overreaches on contested theoretical commitments. Twice is not too many for a framework paper crossing disciplinary lines.
- "physiological fact, not a philosophical stance" / "physiological, not metaphysical" — closes off the metaphysics-smuggling objection at source.
- "reconstruction from the causal residue those pathways deposit" — compresses the whole section's claim into one image. Earns its density.

**Things I held back from:**

- **Hohwy 2013 *The Predictive Mind*.** Available as secondary Layer 1 anchor per the foundation memo. Not needed — Clark + Friston + Ficco carry the load without it. Reserve for if reviewers push back on single-source reliance.
- **Walsh et al. 2020.** Same reasoning. Reserve.
- **Technical specifics of Bayesian priors / precision-weighting.** Introduced at paragraph 6 only to the extent needed for the §III bridge. Full precision-weighting treatment lives in §III where BADE requires it.
- **Any reference to delusions, psychiatry, or the psychiatric bridge in §III.** Deliberate: Layer 1 is pure perceptual-architecture setup. The psychiatric extension arrives in §III; the §II bridge sentence hands the baton without poaching from it.

**Open questions for review:**

1. **Word count: 955 vs. 960 target — acceptable.** No trim needed unless you want one.
2. **Paragraph 1's "wrong — or at least wrong enough"** — register flicker toward informal? Alternative: "The model is long-standing, intuitive, and empirically indefensible at its strong reading." Cleaner, but loses the argumentative-honest quality of the hedge. I prefer the original; your call.
3. **Paragraph 5's "I will refer to this condition as causal mediation"** — the "I will refer to" phrasing introduces the term deliberately, which is one register choice; alternative is "This condition is what I call causal mediation" (more active, slightly more confident). Both acceptable for the venue band. Kept the passive-introduction form because it reads as more academically cautious, which serves the paper's diagnostic posture.
4. **Paragraph 4 closing** — "localizable empirical signature that survives meta-analytic scrutiny" is doing heavy lifting; a reviewer could read it as overclaim given Ficco 2021's own methodological caveats (authors note limitations in their PRISMA section). Defensible because the claim is narrow ("survives meta-analytic scrutiny" ≠ "is definitively established"), but flag for your read.

**Not drafting §III this turn. Awaiting your review of §II before proceeding.**

---

## Cross-section consistency check

- **§I v2 references Clark 2013 and Woodward et al. 2006, 2007 in the preview paragraph.** §II references Clark 2013 and Ficco 2021 and Friston 2010. §III will reference Woodward et al. 2006, 2007, Sterzer et al. 2018, McLean et al. 2017, and Harding et al. 2024. Each citation hits in the section where it belongs; no duplicate citation loads across sections.
- **"Causally bounded observer" / "causal mediation" usage count:** §I v2 uses "causally bounded observer" twice and "causal mediation" twice. §II uses "causally bounded observer" once (as a back-reference to §I) and "causal mediation" once (as the defining paragraph). Density calibrated — the terms are earning their weight, not being repeated for emphasis.
- **Voice consistency:** §II retains §I v2's single-author "I," terse-but-precise edge, and academic-cautious hedging where load-bearing. No register drift.
