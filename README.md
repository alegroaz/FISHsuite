<p align="center">
  <img src="assets/banner.svg" alt="FISHsuite: whole-organism seqFISH+, from gene list to cell identity" width="100%">
</p>

<p align="center">
  <b>Open-source tools to design, run and analyse seqFISH+ experiments in whole, intact animals.</b><br>
  <sub>Caltech, Biology and Biological Engineering</sub>
</p>

<p align="center">
  <img alt="status" src="https://img.shields.io/badge/status-code%20coming%20soon-f26b3a">
  <img alt="organism" src="https://img.shields.io/badge/organism-C.%20elegans-2e9e5b">
  <img alt="method" src="https://img.shields.io/badge/method-seqFISH%2B-7b67c4">
</p>

---

Single-cell RNA-seq in small organisms means dissociating and pooling many animals, and the spatial
information is lost. Fluorescent reporters keep it, but only for a few genes. **FISHsuite** is a seqFISH+
platform that profiles **up to 600 genes at single-cell resolution in a single intact animal**, imaged in 3D.
We developed it in *C. elegans*, which is transparent and has a fully mapped nervous system. It should
carry over to other samples under ~100 µm thick, such as thick brain slices.

> 🚧 **This is a placeholder.** All code, CAD files and protocols will be released here.
> Watch or star the repo to get notified.

<p align="center">
  <img src="assets/pipeline.svg" alt="FISHencode → FISHflow → FISHmap" width="100%">
</p>

## 🧬 FISHencode: experiment design

Choose an imaging panel from single-cell RNA-seq, design error-correcting combinatorial barcodes, and
assemble the probe pool into an oligo order ready for synthesis.

<p align="center"><img src="assets/fishencode_barcoding.png" alt="seqFISH+ barcoding scheme" width="70%"></p>

## ⚙️ FISHflow: automation and hardware

A GUI that runs the fluidics and the microscope for unattended, multi-day hybridisation and imaging.
It comes with open CAD files for the physical setup, which you can laser-cut in acrylic, 3D-print in PLA
or machine in PEEK.

<table>
  <tr>
    <td width="50%"><img src="assets/fishflow_gui.png" alt="FISHflow GUI"></td>
    <td width="50%"><img src="assets/fishflow_device.png" alt="Laser-cuttable microfluidic device"></td>
  </tr>
  <tr>
    <td align="center"><sub>Protocol builder: reagents, probe plate, imaging</sub></td>
    <td align="center"><sub>A laser-cuttable microfluidic device</sub></td>
  </tr>
</table>

## 🔬 FISHmap: 3D image analysis

A GUI-driven pipeline with interactive previews at every step: registration, preprocessing, spot detection,
barcode decoding, nuclear segmentation, and assignment of transcripts to identified cells.

<table>
  <tr>
    <td width="45%"><img src="assets/fishmap_gui.png" alt="FISHmap step-by-step dashboard"></td>
    <td width="55%"><img src="assets/fishmap_cells3d.png" alt="Identified neurons in 3D"></td>
  </tr>
  <tr>
    <td align="center"><sub>Step-by-step dashboard with live previews</sub></td>
    <td align="center"><sub>Decoded transcripts assigned to identified neurons</sub></td>
  </tr>
</table>

## 🧪 Simulation

Synthetic image stacks with known ground truth, so you can benchmark detection and decoding without
a microscope.

<p align="center"><img src="assets/simulation.png" alt="Simulated barcoded seqFISH+ data" width="100%"></p>

## Applications

- **The "undead" nervous system.** Characterising surviving neuron-like cells in *ced-3* caspase mutants.
- **Novel model organisms.** Mapping the nervous system of the entomopathogenic nematode
  *Steinernema hermaphroditum*.

---

<p align="center"><sub>Sternberg Lab · California Institute of Technology</sub></p>
