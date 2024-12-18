# PSP Neoadjuvant vs Upfront Markov Cohort Analysis

This repository contains analyses comparing neoadjuvant and upfront treatment strategies using Markov cohort models. The analyses include Monte Carlo sensitivity analyses and reference materials.

## Table of Contents

- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Key Implementations](#key-implementations)
- [References](#references)
- [License](#license)

## Project Overview

The project aims to evaluate and compare the effectiveness of neoadjuvant versus upfront treatment strategies using Markov cohort analysis. The analyses involve Monte Carlo simulations to assess sensitivity and robustness of the results.

## Repository Structure

- `SB11/`: Contains Jupyter Notebook files with the main analyses.
- `MDP_Final.amua`: Data file used in the analyses.
- `Monte carlo 2-way sensitivity analysis.26`: Script for performing two-way sensitivity analysis using Monte Carlo simulations.
- `Reference article and other IMP info.docx`: Document with reference articles and important information related to the project.
- `Transformations related to the angular and the square root.pdf`: PDF discussing mathematical transformations used in the analysis.
- `sb11_base_article_H.pdf`: Base article providing foundational information for the project.
- `terminal node.png`: Image depicting the terminal node structure used in the Markov model.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/klsavaj/PSP-Neoadjuvant-v-s-Upfront-Markov-Cohort-Analysis.git
   cd PSP-Neoadjuvant-v-s-Upfront-Markov-Cohort-Analysis
   ```

2. **Set Up the Environment**:

   - Ensure you have Python installed.
   - Install the required packages:

     ```bash
     pip install -r requirements.txt
     ```

## Usage

1. **Run the Jupyter Notebooks**:

   - Navigate to the `SB11/` directory.
   - Open and execute the notebooks to perform the analyses.

2. **Perform Sensitivity Analysis**:

   - Execute the `Monte carlo 2-way sensitivity analysis.26` script to conduct two-way sensitivity analyses.

## Key Implementations

- **Markov Cohort Model**: Utilized to simulate patient transitions between health states over time, comparing neoadjuvant and upfront treatment strategies.

- **Monte Carlo Simulations**: Applied to assess the uncertainty and variability in model parameters, enhancing the robustness of the analysis.

- **Sensitivity Analyses**: Conducted to determine the influence of key parameters on the outcomes, identifying critical factors affecting treatment effectiveness.

## References

- Refer to `Reference article and other IMP info.docx` for detailed references and important information related to the analyses.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
