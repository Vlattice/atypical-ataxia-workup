# Atypical Progressive Ataxia: An Open Diagnostic Framework

An open, community-maintained resource for clinicians and researchers
encountering rapidly or atypically progressive ataxia syndromes that resist
standard molecular diagnosis.

## Motivation

A meaningful fraction of late-onset progressive cerebellar and
cerebellar–pyramidal syndromes remain classified as "idiopathic" after
extensive workup. Several recent advances have changed what *should* be on
the differential, but uptake in routine clinical practice is uneven across
regions and centers:

- **SCA27B** (GAA repeat expansion in *FGF14*) was identified in 2023 as a
  frequent cause of previously idiopathic late-onset cerebellar ataxia
  (Pellerin et al., *NEJM* 2023; Wirth et al., *Mov Disord* 2023). In some
  cohorts it accounts for 10–60% of unsolved late-onset ataxias.
- **EBV** was established in 2022 as a causally necessary factor for
  multiple sclerosis (Bjornevik et al., *Science* 2022), reopening
  questions about its role in other inflammatory CNS conditions.
- Adult-onset **leukoencephalopathies** with progressive corticospinal
  involvement (CSF1R-related, GFAP/Alexander adult-onset, hereditary
  spastic paraplegias with complicated features) have expanding
  diagnostic panels.
- Regionally relevant **infectious causes** (HTLV-1 in parts of South
  America, Africa, and the Caribbean) remain underdiagnosed when not
  specifically requested.

This repository compiles, in open and contributable form:

1. A structured differential for atypical progressive ataxia and
   cerebellar–pyramidal syndromes
2. Specific tests, their indications, and notes on availability and cost
   by region where information is available
3. Clinical, imaging, and CSF patterns that inform diagnostic priority
4. Hypotheses worth empirical investigation that are not yet established
   but biologically plausible and testable

The intent is **not** to replace clinical judgment, and **not** to
substitute for specialist evaluation. It exists to reduce the chance that
an accessible diagnostic test is overlooked because a clinician or center
is unaware that it exists, or that a recently described entity is
overlooked because it postdates standard training.

## Structure

```
.
├── README.md                 ← this file
├── CASE-PATTERNS.md          ← recognized clinical patterns
├── ALGORITHM.md              ← suggested workup order [in progress]
├── DIFFERENTIAL/
│   ├── infectious/           ← HTLV-1, syphilis, Whipple, EBV-CNS, etc.
│   ├── metabolic/            ← X-ALD, Wilson, B12/copper, mitochondrial
│   ├── genetic/              ← SCA27B, SCA1-3, FRDA, HSP, leukodystrophies
│   ├── autoimmune/           ← cerebellar Ab+, GAD-Ab, MOG, AQP4
│   └── paraneoplastic/
├── HYPOTHESES/
│   └── EBV-FGF14-silencing.md  ← proposed mechanism, explicitly hypothesis
├── REFERENCES.bib            ← bibliography
├── CONTRIBUTING.md           ← how to contribute
└── LICENSE                   ← CC-BY 4.0
```

## What "atypical" means here

This resource focuses on presentations that share one or more of these
features:

- Rapid progression (months to a few years)
- Cerebellar ataxia with prominent corticospinal involvement
- Intrathecal IgG synthesis (oligoclonal bands) without typical
  MS-pattern lesions
- Symmetric or bilateral white matter changes in corticospinal tracts
- Lack of response to first-line immunotherapy (steroids, IVIg)
- No identified mutation on standard ataxia panels

If you are working through such a case, this resource is meant to help
you ensure that accessible tests are not missed.

## Contributing

Pull requests are welcome from clinicians, researchers, patient
advocates, and anyone with relevant expertise. The standard for
inclusion is:

- **Established entities**: peer-reviewed primary source
- **Hypotheses**: explicit framing as hypothesis, with cited reasoning,
  acknowledged limitations, and proposed empirical tests
- **Regional or cost information**: source documented

See `CONTRIBUTING.md`.

## License

- **Content** (markdown files, documentation): CC-BY 4.0
- **Code** (if any added): MIT

## Citation

If this resource is useful in your work, please cite the Zenodo DOI
DOI 10.5281/zenodo.20431333.

## Acknowledgments

This project was initiated in response to a clinical case in which
several potentially diagnostic tests, accessible but not requested
at the time of workup, were identified retrospectively. The patient
is not named; the contribution offered here is the recognition that
such gaps exist and can be reduced.

## Disclaimer

This is an open educational resource. It does not constitute medical
advice. Clinical decisions remain the responsibility of treating
physicians evaluating individual patients.
