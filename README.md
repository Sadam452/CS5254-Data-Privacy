# CS5254 Data Privacy Assignments

Welcome to the repository for the CS5254 Data Privacy course assignments. This repository contains various implementations and exercises focused on data privacy techniques, including K-anonymity, X-Y anonymity, X-Y linkability, L-diversity, recursive (c, l)-diversity, LKC-privacy, and the Laplace mechanism.

## Table of Contents

- [Overview](#overview)
- [Assignments](#assignments)
  - [K-Anonymity](#k-anonymity)
  - [X-Y Anonymity](#x-y-anonymity)
  - [X-Y Linkability](#x-y-linkability)
  - [L-Diversity](#l-diversity)
  - [Recursive (c, l)-Diversity](#recursive-c-l-diversity)
  - [LKC-Privacy](#lkc-privacy)
  - [Laplace Mechanism](#laplace-mechanism)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository includes various assignments related to data privacy. Each assignment covers different concepts and techniques used to ensure data privacy and protect sensitive information in datasets. The assignments are designed to help understand and implement these techniques through practical exercises.

## Assignments

### K-Anonymity

K-anonymity ensures that each record is indistinguishable from at least K-1 other records regarding certain identifying attributes. This technique prevents re-identification of individuals in a dataset.

### X-Y Anonymity

X-Y anonymity extends K-anonymity by considering relationships between quasi-identifiers and sensitive attributes, ensuring privacy against adversaries with background knowledge.

### X-Y Linkability

X-Y linkability measures the risk of linking anonymized data to external datasets. This technique evaluates the potential for re-identification when combining datasets.

### L-Diversity

L-diversity enhances K-anonymity by ensuring that each equivalence class of a dataset has at least L well-represented values for sensitive attributes, protecting against attribute disclosure.

### Recursive (c, l)-Diversity

Recursive (c, l)-diversity further refines L-diversity by considering the distribution of sensitive attributes within equivalence classes, providing stronger privacy guarantees.

### LKC-Privacy

LKC-privacy is a flexible privacy model that generalizes several privacy concepts, offering a comprehensive approach to prevent re-identification and attribute disclosure.

### Laplace Mechanism

The Laplace mechanism is used in differential privacy to add noise to data, ensuring that the output of a function does not significantly change when a single record in the dataset is modified.

## Download

To get started with these assignments, clone the repository:

```bash
git clone https://github.com/Sadam452/CS5254-Data-Privacy.git
cd CS5254-Data-Privacy
```


## Usage

Run the respective file.

## Contributing

Contributions are welcome! If you have improvements or new techniques to add, please fork the repository, create a new branch, and submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

Thank you for exploring the CS5254 Data Privacy assignments. We hope these exercises help you gain a deeper understanding of data privacy techniques and their implementation. If you have any questions or feedback, please feel free to reach out.