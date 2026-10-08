# HumanBrain Scientific Papers

Publication roadmap and materials for **HumanBrain: GPU-Accelerated Whole-Brain Simulator with Anatomical Connectivity and Adaptive Feedback Control**.

## Repository Structure

## Publication Roadmap

### Phase 1: Preprint (Week 1-2)
- [x] arXiv submission (q-bio.NC - Neurons and Cognition)
- [x] Zenodo DOI generation
- [ ] bioRxiv submission (optional)

**Target Date**: December 2025
**Status**: LaTeX source ready for Overleaf compilation

### Phase 2: Nature Neuroscience (Week 2-8)
- [ ] Manuscript submission
- [ ] Peer review process
- [ ] Revisions and resubmission

**Target Date**: January-March 2026
**Estimated Probability**: 5-10%
**Status**: Preparing submission materials

### Phase 3: PLOS Computational Biology (Week 8-12)
- [ ] Fallback submission if Nature rejects
- [ ] Open peer review
- [ ] Publication

**Target Date**: March-May 2026
**Estimated Probability**: 30-40%
**Status**: Backup option

## Main Repository

Source code: [github.com/Yatrogenesis/HumanBrain](https://github.com/Yatrogenesis/HumanBrain)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17720778.svg)](https://doi.org/10.5281/zenodo.17720778)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC--BY--4.0-lightgrey.svg)](LICENSE)

## arXiv Submission

The arXiv preprint is located in \ with:

- \ - Full LaTeX source
- \ - All figures in PDF/EPS/PNG format
- Compilation tested on Overleaf with pdfLaTeX

**Category**: q-bio.NC (Neurons and Cognition)
**Secondary**: cs.NE (Neural and Evolutionary Computing)

## Key Contributions

1. **GPU Cable Equation Integration**: 152 compartments/neuron, 1.52M total compartments for 10K neurons
2. **Anatomical Connectivity**: 8 biologically validated pathways
3. **Adaptive Feedback Loop**: Real-time attractor analysis
4. **Performance**: Near real-time (50-80 FPS) on consumer GPU (RTX 3050)

## Figures

All figures generated using Python (matplotlib/seaborn) in Google Colab:

1. figure1_voltage_trace - Adaptive control voltage transition
2. figure2_attractor_analysis - D2 and lambda1 evolution
3. figure3_architecture - System architecture diagram
4. figure4_performance - Benchmark comparison charts

Formats: PDF (vector), EPS (vector), PNG (600 DPI raster)

## Citation

## License

Papers, figures and text in this repository: **CC-BY-4.0** (see `LICENSE`). The simulator source code is not in this repository; it lives in [Yatrogenesis/HumanBrain](https://github.com/Yatrogenesis/HumanBrain) and is licensed under AGPL-3.0-or-later.

## Contact

Francisco Molina Burgos | pako.molina@gmail.com | ORCID: 0009-0008-6093-8267

---

Yatrogenesis Research | 2025
