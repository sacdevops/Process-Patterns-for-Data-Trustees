# Designing Data Trustees: A Modular Process Pattern Approach

This repository contains the supplementary material for the research paper **"Designing Data Trustees: A Modular Process Pattern Approach for Data Trustees"** (submitted to the International Conference on Wirtschaftsinformatik). 

It provides a comprehensive collection of modular process patterns and technical documentation designed to help researchers and practitioners assemble adaptable, economically viable data trust architectures.

## 📦 Repository Contents

To overcome the rigid and monolithic structures of traditional data intermediaries, we decomposed complex trustee operations into reusable service components. 

This repository includes:
* **Process Patterns:** The executable workflow models for all identified service components.
  * `*.bpmn` files: Standardized Business Process Model and Notation files, ready to be imported and edited in any standard BPMN modeling tool (e.g., Camunda, Signavio, bpmn.io).
  * `*.svg` files: High-resolution vector graphics of each process pattern for quick viewing without specialized software.
* **Documentation:** Extended technical descriptions and contextual applicability conditions for each modular process pattern.

## 📂 Structure

```text
├── models/
│   ├── bpmn/       # Contains all process patterns in .bpmn format
│   └── svg/        # Contains all process pattern visualizations in .svg format
├── docs/           # Extended documentation for service components
└── README.md

## 🛠️ How to Use

* Viewing: Simply navigate to the process patterns directory to view the visual representations of the process patterns directly in your browser.
* Editing & Adapting: Download the .bpmn files from the process patterns directory. You can import these into your preferred low-code platform or BPMN editor to adapt the workflows to your specific domain requirements and legal frameworks (e.g., EU Data Act, DGA).

## 📝 Citation
If you use these process patterns or the accompanying documentation in your research or technical implementations, please cite our paper:
@inproceedings{Author2026DataTrustees,
  author    = {First Author and Second Author and Third Author and Fourth Author},
  title     = {Designing Data Trustees: A Modular Process Pattern Approach for Data Trustees},
  booktitle = {Proceedings of the International Conference on Wirtschaftsinformatik (WI)},
  year      = {2026},
  publisher = {AIS eLibrary},
  note      = {Forthcoming}
}
