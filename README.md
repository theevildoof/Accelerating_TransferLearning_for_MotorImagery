

## Absract 

Motor imagery (MI)-based brain-computer interfaces (BCIs) hold significant potential
for rehabilitation and assistive technologies. However, their widespread adoption is hin-
dered by high inter-subject variability in EEG signals, necessitating extensive calibration
for new users. Transfer learning (TL) methods overcome this by leveraging data from ex-
isting subjects to reduce the calibration time. However, the lack of standard evaluation
protocols in EEG-MI TL research makes it challenging to compare different approaches
fairly. Moreover, the lack of availability of codebases adds to the issue of reproducibility.
Our study employs a standardized evaluation protocol to compare key transfer learning
techniques across cross-session and cross-subject scenarios. We further conduct ablation
studies focusing on signal length and preprocessing parameters to quantify the sensitivity of
the algorithms to signal and noise variability. Finally, we present Python implementations
of the methods for reproducibility and to facilitate future research.

## Methods

We plan to evaluate the following methods:

1. Minimum Distance to Riemannian Mean(MDRM)
2. Riemannian Alignment(RA-MDRM)
3. Euclidean Alignment(EA)
4. Riemannian Procrustes Analysis(RPA)
5. Tangent Space Alignment(TSA)
6. Manifold Embedded Knowledge Transfer(MEKT)
7. CSP + LDA
8. Log-Euclidean Alignment

## References

- [IEEE Xplore: 6346529](https://ieeexplore.ieee.org/document/6346529)
- [AAAI: AAAI08-108](https://cdn.aaai.org/AAAI/2008/AAAI08-108.pdf)
- [KTH: Zadrozny](https://www.math.kth.se/matstat/gru/sf2935/zadrozny.pdf)
- [arXiv: 1503.06944](https://arxiv.org/pdf/1503.06944)
- [Wiley: 1683013](https://onlinelibrary.wiley.com/doi/10.1155/2020/1683013)
- [IEEE Xplore: 8624413](https://ieeexplore.ieee.org/document/8624413)
- [IEEE Xplore: 9905704](https://ieeexplore.ieee.org/document/9905704)
- [arXiv: 1807.00516](https://arxiv.org/abs/1807.00516)
- [Springer: 10.1007/s11571-022-09890-3](https://link.springer.com/article/10.1007/s11571-022-09890-3)
- [arXiv: 2006.08924](https://arxiv.org/abs/2006.08924)
- [ScienceDirect: S0031320323006933](https://www.sciencedirect.com/science/article/pii/S0031320323006933)
- [IEEE Xplore: 9782536](https://ieeexplore.ieee.org/document/9782536)
- [ACM: 10.1145/3494567](https://dl.acm.org/doi/10.1145/3494567)
- [arXiv: 1609.02907](https://arxiv.org/abs/1609.02907)
- [IEEE Xplore: 10285604](https://ieeexplore.ieee.org/document/10285604)
- [PubMed: 34310314](https://pubmed.ncbi.nlm.nih.gov/34310314/)
- [PubMed: 33395676](https://pubmed.ncbi.nlm.nih.gov/33395676/)
- [Springer: FITEE.1800083](https://link.springer.com/article/10.1631/FITEE.1800083)
- [IEEE Xplore: 4634130](https://ieeexplore.ieee.org/document/4634130)
- [SpringerOpen: 40537-016-0043-6](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-016-0043-6)
- [arXiv: 1802.03601](https://arxiv.org/abs/1802.03601)
- [IEEE Xplore: 8585027](https://ieeexplore.ieee.org/document/8585027)
- [arXiv: 1511.05547](https://arxiv.org/abs/1511.05547)
- [IEEE Xplore: 6247911](https://ieeexplore.ieee.org/document/6247911)
- [arXiv: 1705.05498](https://arxiv.org/abs/1705.05498)
- [IEEE Xplore: 6751384](https://ieeexplore.ieee.org/document/6751384)
- [JMLR: Gretton12a](https://jmlr.csail.mit.edu/papers/v13/gretton12a.html)
- [IEEE Xplore: 5640675](https://ieeexplore.ieee.org/document/5640675)
- [Springer: 10.1007/BF01129656](https://link.springer.com/article/10.1007/BF01129656)
- [arXiv: 1702.02897](https://arxiv.org/pdf/1702.02897)
- [Journal of Engineering Science: 4832](https://journal.esrgroups.org/jes/article/view/4832)
- [PMC: 9228168](https://pmc.ncbi.nlm.nih.gov/articles/PMC9228168/)
- [Frontiers: 10.3389/fnhum.2022.1068165](https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2022.1068165/full)
- [IEEE Xplore: 6046114](https://ieeexplore.ieee.org/document/6046114)
- [IEEE Xplore: 8013808](https://ieeexplore.ieee.org/document/8013808)
- [arXiv: 1808.05464](https://arxiv.org/abs/1808.05464)
- [IEEE Xplore: 8588384](https://ieeexplore.ieee.org/document/8588384)
- [Frontiers: 10.3389/fnhum.2022.1049985](https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2022.1049985/full)
- [IEEE Xplore: 9722771](https://ieeexplore.ieee.org/document/9722771)
- [IOP Science: 10.1088/1741-2552/ac4430](https://iopscience.iop.org/article/10.1088/1741-2552/ac4430)
- [arXiv: 1910.05878](https://arxiv.org/abs/1910.05878)
- [Wiley: 9871603](https://onlinelibrary.wiley.com/doi/10.1155/2018/9871603)
- [arXiv: 2302.04508](https://arxiv.org/abs/2302.04508)
- [PubMed: 38342784](https://pubmed.ncbi.nlm.nih.gov/38342784/)
- [arXiv: 1611.08024](https://arxiv.org/abs/1611.08024)
- [arXiv: 2311.17968v1](https://arxiv.org/pdf/2311.17968v1)
- [Springer: 10.1007/s11517-024-03032-z](https://link.springer.com/article/10.1007/s11517-024-03032-z)
- [PubMed: 34406935](https://pubmed.ncbi.nlm.nih.gov/34406935/)
- [HAL: 00602700](https://hal.science/hal-00602700/document)
- [IOP Science: 10.1088/1741-2552/aa61bb](https://iopscience.iop.org/article/10.1088/1741-2552/aa61bb/pdf?utm_source=sciencedirect_contenthosting&getft_integrator=sciencedirect_contenthosting)
- [Springer: 10.1007/s10916-018-1106-3](https://link.springer.com/article/10.1007/s10916-018-1106-3)
- [ScienceDirect: S095741742030110X](https://www.sciencedirect.com/science/article/pii/S095741742030110X)
- [PubMed: 29113518](https://pubmed.ncbi.nlm.nih.gov/29113518/)
- [IOP Science: 10.1088/1741-2552/ab405f](https://iopscience.iop.org/article/10.1088/1741-2552/ab405f)
- [Frontiers: 10.3389/fnhum.2020.00338](https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2020.00338/full)
