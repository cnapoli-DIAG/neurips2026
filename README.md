# MLP Learning-Regime Plot Galleries

This repository provides supplementary visual material for the analysis of learning-regime dynamics in shallow multilayer perceptron (MLP) training.

It contains HTML galleries for browsing PNG plots generated during the experimental analysis. The plots summarize training dynamics observed for different optimizers, datasets, network configurations, learning rates, and batch sizes.

The material is intended to support visual inspection, reproducibility, and verification of the learning-regime assignments discussed in the related manuscript.

---

## Repository contents

The main repository contains two HTML gallery files:

- `spearman_plots_gallery.html` — gallery of the main training-dynamics plots, including loss, gradient norms, rolling-window Spearman coefficients, and related coupling indicators;
- `derivatives_plots_gallery.html` — gallery of derivative-based dynamic plots, including quantities derived from the temporal evolution of the Spearman-based discrepancy signal.

The complete PNG plot archive is not stored directly in the repository because of its large size. Instead, the full image archive is provided as downloadable assets in the **Releases** section.

---

## Complete PNG archive

The full set of PNG files is available in the latest GitHub Release.

Download the following archives from the **Releases** section:

- `Adam.zip`
- `Momentum.zip`
- `SGD.zip`

After downloading, extract the archives into the same directory as the HTML gallery files.

The expected local structure is:

```text
project_directory/
├── Adam/
├── Momentum/
├── SGD/
├── spearman_plots_gallery.html
└── derivatives_plots_gallery.html
