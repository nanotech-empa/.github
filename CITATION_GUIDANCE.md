# Licensing, software attribution and scientific credit

This guide helps people and coding agents preserve credit when using software
from nanotech@surfaces and its collaborators. Each project retains its own
identity, authorship, licence, contributor credits and funding acknowledgements.
Acknowledging a dependency does not transfer authorship or imply endorsement.

## Licence compliance

Read the licence and source-specific notices for the exact code being reused.
For MIT-licensed code, retain the applicable copyright and permission notices
in copies or substantial portions of the software. A person's name, repository
link or scientific citation does not replace these notices.

Preserve third-party notices for copied, adapted or vendored code. A repository's
main licence must not be presented as replacing separately licensed components.
This guide grants no additional licence and does not resolve a missing licence.

Scientific citation requests below are separate from licence conditions. They
are not additional terms of the MIT licence.

## Software attribution

Credit the originating software and its relevant contributors or team. Record:

- the original repository URL and, for a particular implementation, its source path;
- the release version and/or immutable commit actually used;
- the project's existing software citation and verified DOI, where available;
- the applicable licence and notices when code is copied or distributed.

A contribution by one person may build on substantial work by others. Preserve
that context instead of attributing an entire implementation to a single PR
author. An index or code corpus should retain source revision and licence/notice
information alongside contributor attribution.

Use a release DOI only for the release it identifies. A project/concept DOI
identifies the software across archived releases; it does not establish which
revision was used or prove that unreleased changes are archived. Identify the
exact commit for development code.

A project's CITATION.cff should describe that project's software using verified
existing authorship metadata. Preserve established contributor and funding
acknowledgements. Resolve ambiguous author lists with the maintainers; do not
infer authorship or ownership from commit counts, copyright alone or a dependency.
Upstream papers are related scientific references, not automatically the
preferred citation of the dependent software.

## Scientific acknowledgements: choose by actual use

### AiiDA

When AiiDA helped the research, acknowledge the AiiDA team and follow the
[official AiiDA citation guidance](https://aiida.net/acknowledgements/), which
lists the three papers below:

- **A1 — Main paper:** S. P. Huber et al., *AiiDA 1.0, a scalable computational
  infrastructure for automated reproducible workflows and data provenance.*
  Scientific Data **7**, 300 (2020).
  [DOI:10.1038/s41597-020-00638-4](https://doi.org/10.1038/s41597-020-00638-4)
- **A2 — Workflow engine:** M. Uhrin, S. P. Huber, J. Yu, N. Marzari and G. Pizzi,
  *Workflows in AiiDA: Engineering a high-throughput, event-based engine for
  robust and modular computational workflows.* Computational Materials Science
  **187**, 110086 (2021).
  [DOI:10.1016/j.commatsci.2020.110086](https://doi.org/10.1016/j.commatsci.2020.110086)
- **A3 — First paper / ADES model:** G. Pizzi, A. Cepellotti, R. Sabatini,
  N. Marzari and B. Kozinsky, *AiiDA: automated interactive infrastructure and
  database for computational science.* Computational Materials Science **111**,
  218–230 (2016).
  [DOI:10.1016/j.commatsci.2015.09.013](https://doi.org/10.1016/j.commatsci.2015.09.013)

### AiiDAlab

When AiiDAlab was used, acknowledge the AiiDAlab team and cite both platform
papers, as listed on the [official AiiDAlab website](https://www.aiidalab.net/about/):

- **L1 — Original platform paper:** A. V. Yakutovich et al., *AiiDAlab – an
  ecosystem for developing, executing, and sharing scientific workflows.*
  Computational Materials Science **188**, 110165 (2021).
  [DOI:10.1016/j.commatsci.2020.110165](https://doi.org/10.1016/j.commatsci.2020.110165)
- **L2 — Updated platform paper:** A. V. Yakutovich, D. Hollas, E. Bainglass,
  J. Yu et al., *Accelerating discovery across scientific disciplines through
  reproducible workflows with AiiDAlab.* Digital Discovery **5**, 2310–2324 (2026).
  [DOI:10.1039/D5DD00567A](https://doi.org/10.1039/D5DD00567A)

### AiiDAlab Quantum ESPRESSO app

When the AiiDAlab Quantum ESPRESSO app, or relevant work derived from that app,
was used, also cite its paper:

- **L3 — QE app:** X. Wang, E. Bainglass, M. Bonacci, A. Ortega-Guerrero et al.,
  *Making atomistic materials calculations accessible with the AiiDAlab Quantum
  ESPRESSO app.* npj Computational Materials **12**, 72 (2026).
  [DOI:10.1038/s41524-025-01936-4](https://doi.org/10.1038/s41524-025-01936-4)

Using Quantum ESPRESSO or aiida-quantumespresso alone does not imply use of the
AiiDAlab QE app. A standalone library or generic code snippet does not call for
all six papers simply because it is hosted in this organisation.

### Other software and methods

These references complement citations to the software, simulation codes,
plugins, numerical methods and original implementations actually used. Preserve
their own citation and acknowledgement instructions. For example, a standalone
meqpy calculation or cp2k-spm-tools command should credit its own software and
methods; platform references become relevant when those platforms were used.

## Keeping citation metadata accurate

Use published articles rather than superseded preprints. Verify titles,
authors, journal details and DOIs against the publisher or authoritative DOI
metadata. Obtain full author lists there when exporting BibTeX or other
machine-readable publication references.

Check software creator metadata against existing package declarations and
published software records before adding CITATION.cff. In development branches,
do not copy an older release's version, date or release DOI onto newer code.
Keep links and actual-use guidance consistent when updating an app, its backend
or shared development instructions.
