# Revealing Typical Vulnerabilities

This project, titled **"Revealing Typical Vulnerabilities,"** was undertaken as part of the IS 734 (Data Analytics in Cybersecurity) course. It focuses on identifying and analyzing common vulnerabilities in computer systems to improve overall cybersecurity.

## Table of Contents
1. [Introduction](#introduction)
2. [Vision](#vision)
3. [Data & Visualization](#data--visualization)
4. [Data Analysis](#data-analysis)
5. [Ethical Issues](#ethical-issues)
6. [Future Scope](#future-scope)
7. [Installation](#installation)
8. [Usage](#usage)
9. [Conclusion](#conclusion)
10. [References](#references)
11. [Contact](#contact)

## Introduction

As technology continues to advance and our reliance on digital systems increases, cybersecurity dangers and vulnerabilities pose significant challenges. The consequences of cyberattacks can be devastating, including data breaches, financial losses, and reputational damage. This project focuses on identifying typical vulnerabilities and addressing these cybersecurity challenges to ensure the safety and security of our digital world.

## Vision

The project aims to improve the overall security of the digital world by identifying and exposing common vulnerabilities. By doing so, it helps cybersecurity professionals develop better security measures and patch security gaps before they are exploited by hackers. This proactive approach aims to prevent cyberattacks, data breaches, financial losses, and reputational damage.

## Data & Visualization

We utilized the Common Vulnerabilities and Exposures (CVE) dataset to identify typical software vulnerabilities. The CVE dataset categorizes each vulnerability with a unique identifier and provides details such as description, severity, and potential impact.

- **Visualization Techniques**: Data visualizations were used to explore the distribution and severity of vulnerabilities, enabling better understanding and prioritization of vulnerability management.

## Data Analysis

The project explored four different models to analyze vulnerabilities:
1. **Linear Regression**
2. **Decision Tree**
3. **Naïve Bayes**
4. **Random Forest**

### Results

- **Accuracy of Linear Regression (LR)**: 0.731039482
- **Accuracy of Decision Tree (DT)**: 0.786087494
- **Accuracy of Naïve Bayes (NB)**: 0.708902893
- **Accuracy of Random Forest (RF)**: 0.786582645

The Random Forest algorithm showed the highest accuracy, making it a preferable choice for predicting the criticality of cyberattacks.

## Ethical Issues

While the CVE dataset is valuable for identifying and fixing software vulnerabilities, ethical concerns must be addressed. Reporting vulnerabilities responsibly is crucial to avoid misuse by malicious actors and to protect sensitive information.

## Future Scope

As technology evolves, so do the tactics of cybercriminals. The project emphasizes the need for continuous adaptation in vulnerability management. By staying ahead of potential threats and proactively managing vulnerabilities, organizations can safeguard against cyber threats.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/jhasud00/Revealing-Typical-Vulnarability.git
   cd Revealing-Typical-Vulnarability
   pip install -r requirements.txt
   jupyter notebook RTV.ipynb
