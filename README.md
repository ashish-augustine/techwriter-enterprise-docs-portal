# Technical Writing Portfolio
## Smart Infrastructure & Civil Engineering Documentation Portal


> **A **Docs-as-Code** technical writing portfolio** demonstrating documentation architecture, information architecture, documentation governance, Mermaid.js diagrams, and static site publishing through a simulated smart infrastructure knowledge portal.

Technical Writing · Docs-as-Code · Information Architecture · Documentation Governance · Smart Infrastructure

[![Built with MkDocs](https://img.shields.io/badge/Built%20with-MkDocs-blue.svg)](https://www.mkdocs.org/)
[![Theme: Material for MkDocs](https://img.shields.io/badge/Theme-Material%20for%20MkDocs-526CFE.svg)](https://squidfunk.github.io/mkdocs-material/)
[![Deployed on GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-brightgreen.svg)](https://pages.github.com/)
 

🔗 **[Explore the Live Documentation Portal](https://ashish-augustine.github.io/techwriter-enterprise-docs-portal/)**

## 📋 Overview

This project simulates an enterprise knowledge management portal designed to serve as a **Single Source of Truth (SSoT)** for a smart infrastructure organization.

It demonstrates how technical documentation can connect physical infrastructure assets—such as bridges, utilities, and rail systems—with digital engineering systems, including IoT sensors, APIs, and digital twin technologies.

Built using a **Docs-as-Code methodology**, the project treats documentation as a version-controlled, maintainable, and deployable product. Content is authored in Markdown, managed with Git and GitHub, and published as a static website using MkDocs with the Material theme.

The portfolio showcases both the technical implementation of a documentation portal and the information architecture and governance practices required to organize complex engineering knowledge.


## ✨ Key Features
* **Docs-as-Code Architecture:** Built using Markdown, Git, and MkDocs to treat documentation with the same rigor as software development.
* **Information Architecture (IA):** Features a strictly governed taxonomy, hierarchical navigation, and metadata standards for organizing complex engineering modules.
* **Visual Engineering (Mermaid.js):** Dynamic, code-generated diagrams mapping out cyber-physical architectures, operational workflows, and structural component taxonomies.
* **API Integration Strategy:** Architectural frameworks designed to ingest and render Swagger/OpenAPI schemas alongside standard operating procedures (SOPs).
* **CI/CD Deployment:** Configured for seamless, automated static site generation and hosting via GitHub Pages.



# Screenshots
 
<img width="1905" height="983" alt="Image" src="https://github.com/user-attachments/assets/3504136e-53be-42f8-a6ad-cc1ca154c310" />

<img width="1905" height="983" alt="Image" src="https://github.com/user-attachments/assets/e2de11ef-ed75-47bf-bbe1-2ece1e47561d" />

<img width="1905" height="983" alt="Image" src="https://github.com/user-attachments/assets/c02e1a53-4be0-43e1-acba-f66389e88a9f" /> 
<img width="1905" height="983" alt="Image" src="https://github.com/user-attachments/assets/433bfd5d-1914-40bd-8cc6-1b211306dfcc" />
 


<img width="1905" height="983" alt="Image" src="https://github.com/user-attachments/assets/f6d397ff-732e-4cc0-8557-9cf96d5966e4" />


 

<img width="1905" height="983" alt="Image" src="https://github.com/user-attachments/assets/42f25b23-ac62-440e-8cc5-e71872328508" />

 

 

## Visit this project live : 
## [https://ashish-augustine.github.io/techwriter-enterprise-docs-portal/](https://ashish-augustine.github.io/techwriter-enterprise-docs-portal/)



## 🗂️ Repository Structure
```text
├── docs/
│   ├── engineering/       # Cyber-physical architecture & asset modules
│   ├── quality/           # QA audits and continuous improvement frameworks
│   ├── standards/         # Enterprise metadata and taxonomy schemas
│   ├── strategy/          # Governance, vision, and lifecycle models
│   ├── index.md           # Portal homepage and executive summary
│   └── skills_summary.md  # Comprehensive breakdown of applied technical skills
├── mkdocs.yml             # Global configuration, theme, and navigation settings
└── README.md              # Project documentation



🚀 Getting Started (Local Development)
To run this documentation portal locally on your machine, follow these steps:

1. Prerequisites
Ensure you have Python 3 installed on your system.

2. Installation
Clone this repository and navigate into the project directory:
git clone [https://github.com/yourusername/smart-infra-docs.git](https://github.com/yourusername/smart-infra-docs.git)
cd smart-infra-docs



Set up a virtual environment and install the required dependencies (MkDocs and the Material theme):

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install mkdocs-material


3. Running the Local Server
Launch the live-reloading development server:
mkdocs serve
Open your browser and navigate to http://127.0.0.1:8000/ to view the site.


🌐 Live Deployment
This project is continuously deployed using GitHub Pages.
To manually trigger a build and deployment, use the following command:
mkdocs gh-deploy

Architected and maintained by [ASHISH AUGUSTINE / https://ashish-augustine.github.io/smart-infra-docs/].
```







# Comprehensive Skills & Tools Summary

## 🛠️ Technical Tools & Technologies Used

MkDocs: The core Python-based Static Site Generator (SSG) used to build the documentation portal.

Material for MkDocs: The enterprise-grade theme used for UI/UX, responsive design, and advanced navigation (integrated TOCs).

Mermaid.js: The JavaScript-based diagramming tool used to render dynamic flowcharts, sequence diagrams, and state diagrams directly from code.

Git: Used for local version control, branching, and committing changes.

GitHub & GitHub Pages: Used for remote repository hosting and automated CI/CD deployment of the live website.

Python (venv & pip): Used to create isolated virtual environments and manage project dependencies securely.

Markdown (MD): The core markup language used to author all technical content, SOPs, and manuals.

YAML: Used for global project configuration (mkdocs.yml) and document-level metadata (Frontmatter).

Visual Studio Code (VS Code): The Integrated Development Environment (IDE) used for authoring code and managing the built-in terminal.

Command Line Interface (CLI): Used extensively (Bash/Zsh) for environment setup, file manipulation, and Git operations.

Swagger/OpenAPI (Architectural): Integrated conceptually as the automated API schema generator for Systems Engineering modules.







## 🧠 Core Skills & Methodologies Demonstrated

Docs-as-Code Architecture: Treating documentation like software by writing in Markdown, tracking changes in Git, and deploying via automated pipelines.

Information Architecture (IA) & Governance: Designed scalable directory structures, enforced YAML metadata standards, and mapped out comprehensive document lifecycles (Creation, SME Review, Audit, Deprecation). Designing scalable folder structures, taxonomies, and deep-nested navigation for thousands of technical documents.

Visual Engineering: Utilized Mermaid.js to programmatically generate dynamic, code-based diagrams (flowcharts, state diagrams) representing complex cyber-physical architectures without relying on static images. Translating complex physical structures and operational workflows into code-based visual representations rather than relying on static images.

Metadata Standardization: Enforcing YAML frontmatter (Document IDs, Tiering, Review Dates) to ensure enterprise searchability and compliance.

Documentation Governance: Defining and mapping out strict document lifecycles (Creation, SME Review, Publication, Audit, Deprecation).

API Documentation Integration: Architecting frameworks to ingest dynamic software documentation (APIs) alongside static structural manuals.

CI/CD Deployment: Managing automated build processes to push documentation from local development branches to live production environments.

Cross-Disciplinary Integration: Bridging the gap between heavy Civil Engineering (CAD/Structural) and digital Systems Engineering (IoT/Telemetry) within a single source of truth.




 
