# Risk Assessment Course Tool Support

This repository contains the source code for a **Risk Assessment Course Support Tool** (`Verktøystøtte for kurs i risikovurdering`). The tool provides a series of interactive tables and procedures to help users conduct risk assessments, organize risk matrices, and make informed decisions based on vulnerability and event likelihood data. The following screendump 

![Model](https://github.com/breibakk/RiskAssessmentCourseTool/blob/main/20241025-tool-pic.png)

The tool has been developed within the project "Network for Cybersecurity and Innovation" financed by the Viken County Municipality in Norway. The project aims to disseminate cybersecurity competence and infrastructure available at the Institute for Energy Technology and Østfold University College to companies and institutions in the local area. The business associations in Fredrikstad and Sarpsborg are project partners.


## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Risk Assessment Course Tool** is designed to assist users in following a systematic approach to risk evaluation, including determining the values at risk, assessing vulnerabilities, and working with risk matrices to evaluate and prioritize risks.

This tool is intended for educational purposes and can be utilized in risk assessment courses. It provides a straightforward way to organize data using interactive HTML content, making it easy for participants to navigate through different risk assessment phases.

## Features

- **Fremgangsmåte (Procedure):** Detailed guide on how to approach risk assessment.
- **Verditabell (Value Table):** A table for assessing the value of assets at risk.
- **Sårbarhetstabell (Vulnerability Table):** A table for evaluating potential vulnerabilities.
- **Uønskahendelsetabell (Undesirable Event Table):** Table for recording undesirable events and incidents.
- **Risikotabell (Risk Table):** Contains information about identified risks.
- **Risikomatrise (Risk Matrix):** A matrix to help prioritize risks based on severity and likelihood.
- **Behandlingstabell (Treatment Table):** Guidelines and strategies for treating risks.
- **Simple UI:** Easy-to-use tabbed navigation system.

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/risk-assessment-course-tool.git
    ```

2. Navigate to the directory:
    ```bash
    cd risk-assessment-course-tool
    ```

3. Open the `index.html` file in your web browser to start using the tool:
    ```bash
    open index.html
    ```

Alternatively, you can host this tool on a web server or use a tool like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) to preview it locally.

## Usage

1. Open the `index.html` file in a browser.
2. Navigate through the different tabs to access specific tools for risk assessment.
3. Each tab contains an embedded resource (HTML file) for different aspects of risk assessment (e.g., vulnerability tables, risk matrices).
4. Follow the guidelines provided in the `Fremgangsmåte` (Procedure) tab to conduct a risk assessment step by step.

## File Structure

The repository contains the following main files:

- `index.html`: The main HTML file with a tabbed interface.
- `Fremgangsmåte/`: Contains the HTML file for the procedure.
- `Verditabell/`: Contains the HTML file for the value table.
- `Sårbarhetstabell/`: Contains the HTML file for the vulnerability table.
- `Uønskahendelsetabell/`: Contains the HTML file for the undesirable event table.
- `Risikotabell/`: Contains the HTML file for the risk table.
- `Risikomatrise/`: Contains the HTML file for the risk matrix.
- `Behandlingstabell/`: Contains the HTML file for the treatment table.

## Contributing

Contributions are welcome! If you have suggestions, bug reports, or feature requests, please feel free to submit an issue or a pull request.

To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Last updated:** September 23, 2024
