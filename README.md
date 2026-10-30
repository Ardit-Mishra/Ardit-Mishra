<a href="https://arditmishra.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img alt="Ardit Mishra — AI engineer & builder. Designed for what AI gets right, and ready for what it gets wrong." src="assets/banner-light.svg" width="100%">
  </picture>
</a>

<p>
  <a href="https://arditmishra.com"><img alt="Portfolio" src="https://img.shields.io/badge/portfolio-arditmishra.com-D97706?style=flat-square"></a>
  <a href="https://linkedin.com/in/ardit-mishra"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-ardit--mishra-0A66C2?style=flat-square"></a>
  <a href="https://arditmishra.com/resume/Ardit_Mishra_Resume.pdf"><img alt="Resume" src="https://img.shields.io/badge/resume-one%20page%20PDF-4ADE80?style=flat-square"></a>
  <img alt="Open to work" src="https://img.shields.io/badge/open%20to-AI%20·%20ML%20·%20data%20roles-555?style=flat-square">
</p>

Science taught me evidence. Trading taught me risk. Running a business's data taught me what actually moves it.
Now I build AI systems, and science tools, that prove what they claim.

## What I've built

<table>
<tr>
<td width="50%" valign="top">
<a href="https://tri-ai.arditmishra.com"><img src="assets/tri-ai.jpg" alt="Tri-AI public view"></a>
<h3><a href="https://github.com/Ardit-Mishra/tri-ai">Tri-AI</a></h3>
<b>A general contractor for software.</b> Text it a job on Telegram; free AI models build each step, a reviewer approves it, and a real test decides if it counts. A build costs $0.<br>
<sub>Python · LLM agents · SQLite · Ollama · Telegram</sub>
</td>
<td width="50%" valign="top">
<a href="https://genclarus.com"><img src="assets/genclarus.jpg" alt="Genclarus explaining BRCA1"></a>
<h3><a href="https://github.com/Ardit-Mishra/genclarus">Genclarus</a></h3>
<b>A translator with footnotes for your genes.</b> Plain-English explanations where every sentence cites the database field it came from. No model writes the facts.<br>
<sub>Next.js · TypeScript · BM25 + embeddings · Vitest</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://biostudio.arditmishra.com"><img src="assets/biostudio.jpg" alt="BioStudio Variant Control Bench"></a>
<h3><a href="https://github.com/Ardit-Mishra/biostudio">BioStudio</a></h3>
<b>A second proof-reader for DNA orders.</b> Re-derives every edit from the final sequence and the reference genome alone. 19,823 attempts to fool it, 0 got through.<br>
<sub>Python · FastAPI · React · Three.js · Docker</sub>
</td>
<td width="50%" valign="top">
<a href="https://peptide.arditmishra.com"><img src="assets/peptide.jpg" alt="Peptide–MHC binding score in the browser"></a>
<h3><a href="https://github.com/Ardit-Mishra/peptide-mhc-binding-predictor">Peptide–MHC</a></h3>
<b>A lock-and-key test for the immune system.</b> Runs in your browser. 15 models compared on one leak-free split; the simplest won at 0.919 ROC-AUC.<br>
<sub>XGBoost · PyTorch · ESM-2 · TypeScript</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://genomesight.arditmishra.com"><img src="assets/genomesight.jpg" alt="GenomeSight sequence workbench"></a>
<h3><a href="https://github.com/Ardit-Mishra/genomesight">GenomeSight</a></h3>
<b>A calculator for DNA.</b> ORFs, motifs, codon usage and alignment. Same input, same answer, every time; Cython makes it up to 11× faster.<br>
<sub>Python · FastAPI · Cython · React</sub>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/Ardit-Mishra/Multiple-Sclerosis-RNA-Seq">MS RNA-seq</a></h3>
<b>Where it started.</b> A four-person Loyola project: does Sephin1 change gene activity in a mouse model of multiple sclerosis? Raw reads to pathways.<br>
<sub>Kallisto · Sleuth · R · Snakemake</sub>
</td>
</tr>
</table>

## Skills, with receipts

| Skill | Where it shows |
|---|---|
| **Agentic AI & multi-agent systems** | Tri-AI: planner, builder and reviewer agents; stuck-agent detection; failed work reverts itself |
| **LLM evaluation & guardrails** | Called all 574 models a router listed; 20 answered as themselves. Work counts only when a test exits 0 |
| **RAG & grounded answers** | Genclarus: hybrid BM25 + local embeddings, Recall@10 0.950; refuses any sentence it cannot cite |
| **AI-assisted development** | Claude Code and Codex daily: one AI writes, a second reviews, the test suite decides, I check the claims |
| **Machine learning** | Leak-free splits, honest baselines, browser inference matching the trained model to 7.5e-08 |
| **Python, APIs & testing** | FastAPI, Cython, SQL; pytest, Vitest, GitHub Actions; ~2,500 tests gate Tri-AI deploys |
| **Bioinformatics** | GRCh38, ClinVar, gnomAD, UniProt, Biopython, Kallisto, Sleuth |

## How I work

Every project publishes what was tried and **did not** ship next to what did (see the `DECISIONS.md` files). When an earlier version claimed more than it measured, the fix is documented too.
