# Hypothesis: EBV-Driven Epigenetic Silencing of FGF14 as a Candidate Mechanism in a Subset of Idiopathic Late-Onset Cerebellar Ataxia

**STATUS: Hypothesis generated through bioinformatic and computational analys.**

## Summary

We propose that in a subgroup of patients with late-onset progressive
cerebellar ataxia of unknown etiology — specifically, those who test
negative for the SCA27B GAA repeat expansion and other defined genetic
ataxias — epigenetic silencing of *FGF14* mediated by Epstein–Barr
virus (EBV) infection of CNS-trafficking lymphocytes may produce a
molecular and functional phenocopy of SCA27B without the genetic
expansion.

This is a hypothesis. It has not been tested directly. The chain of
reasoning depends on bridging three well-established but currently
disconnected fields. The purpose of this document is to make the
hypothesis explicit, falsifiable, and available for empirical
investigation.

## Background

### What is established

**EBV is causally necessary for multiple sclerosis.** A 20-year
longitudinal study of U.S. military personnel demonstrated that EBV
infection precedes and is required for the development of MS, with a
32-fold increased risk after seroconversion and essentially no MS
cases in EBV-seronegative individuals (Bjornevik et al., *Science*
2022).

**SCA27B is a frequent cause of previously idiopathic late-onset
cerebellar ataxia.** A dominantly inherited GAA repeat expansion in
intron 1 of *FGF14* causes progressive cerebellar dysfunction, often
with episodic features and downbeat nystagmus (Pellerin et al., *NEJM*
2023). In some cohorts of unsolved late-onset cerebellar ataxia,
SCA27B accounts for 10–60% of cases. The molecular consequence of the
expansion is reduced *FGF14* expression; the authors themselves note
that **epigenetic silencing may contribute to the transcriptional
deficiency**, analogous to FXN silencing in Friedreich ataxia.

**FGF14 loss produces a recognizable Purkinje cell phenotype.** In
*Fgf14*<sup>−/−</sup> mice, more than 80% of cerebellar Purkinje
neurons are quiescent and fail to fire repetitively in response to
depolarizing current, with reduced Na<sub>v</sub>1.6 expression
(Shakkottai et al., *Neurobiol Dis* 2009). Loss of iFGF14 disrupts the
intrinsic pacemaking property of Purkinje neurons (Bosch et al.,
*J Neurosci* 2015). Recent *in vivo* knock-in of the SCA27A F145S
mutation confirms haploinsufficiency-driven firing impairment
(Ransdell et al., bioRxiv 2024).

**FGF14 is methylation-silenceable.** In colorectal cancer, *FGF14* is
silenced by promoter hypermethylation in 10 of 10 cell lines studied,
with expression restored by treatment with the demethylating agent
5-azacytidine. *FGF14* functions as a tumor suppressor in this
context (Su et al., *J Cancer* 2020). This establishes that *FGF14*
has a methylatable promoter with demonstrable functional consequences
when silenced.

**EBV alters host gene methylation.** EBV-infected gastric epithelial
cells show hypermethylation of 216 host genes via LMP2A-mediated
upregulation of DNMT3b (Liang et al., *Gastroenterology* 2014;
extended to 886 genes by Zhao et al. 2013). EBV-driven host
methylation is documented in B-cell lymphomas, gastric carcinoma, and
nasopharyngeal carcinoma.

### What is not established

- That EBV silences *FGF14* in any tissue or cell type.
- That EBV affects host methylation in neurons or CNS-resident cells
  directly. EBV does not classically infect neurons; any effect on
  cerebellar tissue would be indirect (e.g., via cytokines or factors
  released by EBV-infected B cells in CNS-trafficking lymphocyte
  populations).
- That the methylation profile of EBV-infected B cells (the cells most
  relevant to CNS disease) includes *FGF14*. The published profiles
  to date are from gastric epithelial and selected B-cell lymphoma
  contexts, with cancer-relevant gene panels overrepresented.

### What appears to be against the hypothesis

The most comprehensive published catalog of EBV-induced host gene
methylation (Liang et al., 2014, gastric epithelial AGS-EBV model,
216 hypermethylated genes; Supplementary Table 11) **does not include
*FGF14*, *CACNA1A*, *ATXN1*, *SCN8A*, or *KCNC3*** — the cerebellar
pacemaking genes most relevant to SCA-spectrum ataxia. *FGF9*, a
related gene, appears in the dataset as demethylated and upregulated.

This is a substantive negative finding for the specific tissue and
program studied. Its interpretation is constrained, however, by the
following:

- The dataset is from gastric epithelial cells in latency II program,
  not B cells (the primary CNS-relevant reservoir, often in latency
  III).
- Genes with predominantly neuronal expression may have low baseline
  expression in gastric cells, falling outside the dynamic range of
  the assay even if methylatable in their native tissue.
- No equivalent comprehensive screen has been performed in EBV-
  infected B-lineage cells, EBV-positive samples from CNS-resident
  lymphocyte populations, or post-mortem cerebellar tissue.

The hypothesis is not refuted by the gastric dataset, but it currently
lacks direct empirical anchoring in any published methylation profile.

## Proposed empirical tests

The hypothesis is falsifiable. Specific empirical tests that would
support, refine, or refute it include:

1. **Methylation analysis of *FGF14* in post-mortem cerebellar tissue**
   from patients with late-onset cerebellar ataxia (SCA27B-negative)
   compared with controls, with parallel detection of EBV genomic
   material in adjacent tissue.

2. **Detection of EBV DNA in CSF** of patients with idiopathic
   late-onset cerebellar ataxia (SCA27B-negative), with quantitative
   comparison to age-matched controls and to MS patients.

3. **Reanalysis of published EBV-infected B-cell methylation datasets**
   (Burkitt lymphoma cell lines, EBV-immortalized lymphoblastoid cell
   lines, primary EBV-positive B cells) for differential methylation
   at *FGF14*, *CACNA1A*, and other cerebellar pacemaking genes.

4. ***In vitro* exposure of iPSC-derived Purkinje neurons** to
   conditioned media from EBV-infected B-cell lines, with measurement
   of *FGF14* expression, *FGF14* promoter methylation, and Purkinje
   firing properties.

5. **Computational modeling** of graded *FGF14* loss in validated
   Purkinje neuron models (e.g., Khaliq-Raman 2003, ModelDB entry
   48332) to characterize the spectrum of firing impairment expected
   under partial epigenetic silencing versus genetic haploinsufficiency
   — for use as a predictor of distinguishing clinical features.

A computational implementation of test (5) is in development as a
companion repository.

## Why this is worth investigating

If correct, the hypothesis would:

- Identify a candidate etiology for a fraction of currently idiopathic
  late-onset cerebellar ataxia
- Suggest specific diagnostic tests (EBV DNA in CSF; targeted *FGF14*
  methylation in cerebellar tissue) that are not currently part of
  routine workup
- Open a therapeutic question (whether anti-EBV strategies or
  demethylating agents might modify disease in this subgroup) that
  would require independent clinical investigation before being
  acted upon

If refuted, the hypothesis would:

- Narrow the search for non-genetic causes of late-onset cerebellar
  ataxia
- Inform the design of future screens for environmental and infectious
  contributors

## What this document does not claim

It does not claim that EBV causes cerebellar ataxia.

It does not claim that *FGF14* is silenced by EBV in any patient.

It does not recommend any change in current clinical practice.

It does not propose any therapeutic protocol.

It proposes a candidate mechanism worth empirical investigation, with
specific tests that could distinguish it from null.

## Author contribution and conflicts

This hypothesis was formulated in the context of clinical case work
where a patient with rapidly progressive cerebellar–pyramidal syndrome
remained without molecular diagnosis after extensive workup. The
formulation is the author's; no patient identifiers are included; no
commercial conflicts are declared.

## References

See `../REFERENCES.bib`. Key citations:

- Bjornevik et al., *Science* 2022;375(6578):296–301. PMID: 35025605.
- Pellerin et al., *NEJM* 2023;388:128–141.
- Shakkottai et al., *Neurobiol Dis* 2009;33:81–88. PMID: 18930825.
- Bosch et al., *J Neurosci* 2015;35:6752–6769. PMID: 25926453.
- Ransdell et al., bioRxiv 2024. doi:10.1101/2024.10.25.620253.
- Su et al., *J Cancer* 2020;11:819–825. PMID: 31949485.
- Liang et al., *Gastroenterology* 2014;147:1350–1362. PMID: 25173755.
- Wirth et al., *Mov Disord* 2023.
- Khaliq, Gouwens, Raman, *J Neurosci* 2003;23:4899–4912. PMID: 12832512.

---

*Comments, criticism, and proposals for empirical tests are welcome
via repository issues.*
