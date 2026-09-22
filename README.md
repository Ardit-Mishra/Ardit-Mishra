# Hi, I'm Ardit Mishra

Bioinformatics graduate (Loyola University Chicago, 2024). I build scientific
software that states only what it can prove.

That sounds like a slogan, so here is what it costs in practice: the projects
below publish what was tried and rejected alongside what shipped, name their own
weakest evaluation rather than their best, and in two cases document the point
where an earlier version of them claimed more than it had measured.

**[arditmishra.com](https://arditmishra.com)** ·
[LinkedIn](https://linkedin.com/in/ardit-mishra) · amishra7599@gmail.com

---

## Projects

### [BioStudio](https://github.com/Ardit-Mishra/biostudio) — [live](https://biostudio.arditmishra.com)

A pre-order check for synthetic DNA. Before an order ships, a separate verifier
re-derives the requested edits from the exported sequence and the GRCh38
reference **alone** and holds the order until it can — the separation is enforced
by the function signature, not by convention. Attacked with 22 mutation operators
whose ground truth is computed from the delivered file rather than from the
checker: **19,823 attempts, 0 false pass, 0 false hold**, with two deliberately
broken builds shipped so the number stays falsifiable.

The other half is an ADMET property layer over seven endpoints on scaffold
splits. [DECISIONS.md](https://github.com/Ardit-Mishra/biostudio/blob/main/DECISIONS.md)
records what was trained and did not ship, and where the evidence is thin.

### [Tri-AI](https://github.com/Ardit-Mishra/tri-ai)

A build system for software that builds software. A job arrives as a dependency
graph of smaller steps, and each step goes to the cheapest lane that can finish
it — local model, free lane, paid only when the work needs it. A step is accepted
only when its verification command **exits 0**, never because an agent reported
success. One free model deleted 387 of 389 lines and reported success; that is
why the gate exists.

### [Genclarus](https://github.com/Ardit-Mishra/genclarus) — [live](https://genclarus.com)

A gene and variant explainer where **no language model writes factual content**.
Every sentence renders deterministically from typed facts in ClinVar, dbSNP,
gnomAD, UniProt, MyGene and MyVariant, bound to the source field it cites, and a
fail-closed validator refuses anything it cannot ground. Hallucination is not
mitigated here; the generation step that would produce one does not exist.

### [Peptide–MHC Binding Predictor](https://github.com/Ardit-Mishra/peptide-mhc-binding-predictor) — [live](https://peptide.arditmishra.com)

Peptide–MHC class I binding, scored entirely in the browser — no API, no
server-side inference, no sequence leaves the machine. **Fifteen approaches** were
evaluated on one identical peptide-grouped split, including CNN, CNN-BiLSTM,
Transformer and frozen ESM-2. None beat gradient-boosted trees, and a 1992
substitution matrix matched a pretrained protein language model on a quarter of
the head parameters. The full comparison is in
[DECISIONS.md](https://github.com/Ardit-Mishra/peptide-mhc-binding-predictor/blob/main/DECISIONS.md).

### [GenomeSight](https://github.com/Ardit-Mishra/genomesight) — [live](https://genomesight.arditmishra.com)

A sequence workbench that deliberately contains **no machine learning**. Every
operation it performs has an exact answer, so the guarantee is one the others
cannot make: the same input always returns the same result. An optional Cython
k-mer accelerator is measured at 5.3×–11.0× with the pure-Python fallback always
available and the engine actually serving a request reported at runtime.

### [Multiple Sclerosis RNA-Seq](https://github.com/Ardit-Mishra/Multiple-Sclerosis-RNA-Seq)

Undergraduate coursework, Loyola University Chicago, 2023, four-person team.
EAE mouse-model transcriptomics investigating Sephin1 — Kallisto pseudoalignment,
Sleuth differential expression, WebGestalt enrichment. Where the trajectory
started.

---

## Tech

**Languages** Python, R, SQL, TypeScript, JavaScript, Bash, Cython

**ML & evaluation** PyTorch, scikit-learn, XGBoost, SHAP, ESM-2, Hugging Face ·
leakage-aware splits (scaffold, peptide-grouped, leave-one-allele-out),
ROC-AUC/PR-AUC, calibration, adversarial fuzzing against constructed ground truth

**Scientific** RDKit, Biopython, Kallisto, Sleuth, sequence alignment, VCF
normalisation, Golden Gate assembly, GRCh38, ClinVar, gnomAD, AlphaFold

**Systems** FastAPI, Next.js, React, Three.js, Node, Docker, GitHub Actions,
PostgreSQL, AWS, GCP, Vercel

---

Also five years trading NQ, ES and Gold futures through proprietary firms under
defined drawdown and position-sizing limits — where the habit of writing down
what actually happened, rather than what was supposed to, came from.
