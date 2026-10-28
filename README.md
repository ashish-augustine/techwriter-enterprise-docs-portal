# Technical Writing Portfolio
# A Docs-as-Code portfolio for smart infrastructure. 
A technical writing portfolio showcasing Docs-as-Code, technical documentation, information architecture, documentation governance, Mermaid.js diagrams, and MkDocs through a simulated smart infrastructure documentation portal.

# Project Summary

This project simulates an enterprise-grade Knowledge Management portal designed to serve as the Single Source of Truth (SSoT) for a multibillion-dollar Smart Infrastructure division. The scope encompasses bridging the documentation gap between physical Civil Engineering assets (bridges, utilities, rail) and digital Systems Engineering telemetry (IoT sensors, API endpoints) to support the maintenance of live Digital Twins.



Built from scratch using a modern Docs-as-Code methodology, this portfolio demonstrates the ability to treat documentation like software. It was authored in Markdown, version-controlled via Git/GitHub, and statically generated using MkDocs (Material Theme).







# Smart Infrastructure & Civil Engineering Documentation Portfolio

[![Built with MkDocs](https://img.shields.io/badge/Built_with-MkDocs-blue.svg)](https://www.mkdocs.org/)
[![Theme: Material](https://img.shields.io/badge/Theme-Material-526DD.svg)](https://squidfunk.github.io/mkdocs-material/)
[![Deployment: GitHub Pages](https://img.shields.io/badge/Deployed_on-GitHub_Pages-brightgreen.svg)](https://pages.github.com/)

## 📖 Overview
This repository contains a comprehensive, enterprise-grade **Docs-as-Code** portfolio demonstrating modern Technical Writing and Documentation Architecture skills. 

The project simulates a centralized Knowledge Management portal for a multibillion-dollar Smart Infrastructure and Civil Engineering enterprise. It serves as the Single Source of Truth (SSoT) for integrating physical asset documentation (Civil/Structural) with digital system telemetry (Systems/IoT).

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







1111111
# Technical Writing Portfolio
## Smart Infrastructure & Civil Engineering Documentation Portal

[![Built with MkDocs](https://img.shields.io/badge/Built%20with-MkDocs-blue.svg)](https://www.mkdocs.org/)
[![Theme: Material for MkDocs](https://img.shields.io/badge/Theme-Material%20for%20MkDocs-526CFE.svg)](https://squidfunk.github.io/mkdocs-material/)
[![Deployed on GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-brightgreen.svg)](https://pages.github.com/)

A **Docs-as-Code technical writing portfolio** demonstrating documentation architecture, information architecture, documentation governance, Mermaid.js diagrams, and static site publishing through a simulated smart infrastructure knowledge portal.

**[Explore the Live Documentation Portal](https://ashish-augustine.github.io/techwriter-enterprise-docs-portal/)**

## Overview

This project simulates an enterprise knowledge management portal designed to serve as a **Single Source of Truth (SSoT)** for a smart infrastructure organization.

It demonstrates how technical documentation can connect physical infrastructure assets—such as bridges, utilities, and rail systems—with digital engineering systems, including IoT sensors, APIs, and digital twin technologies.

Built using a **Docs-as-Code methodology**, the project treats documentation as a version-controlled, maintainable, and deployable product. Content is authored in Markdown, managed with Git and GitHub, and published as a static website using MkDocs with the Material theme.

The portfolio showcases both the technical implementation of a documentation portal and the information architecture and governance practices required to organize complex engineering knowledge.

## Key Features

- **Docs-as-Code workflow:** Authoring in Markdown, version control with Git, and static site generation with MkDocs.
- **Information architecture:** Structured content hierarchies, taxonomy design, and navigation for complex engineering documentation.
- **Documentation governance:** Documentation standards, metadata conventions, review workflows, and lifecycle management.
- **Mermaid.js diagrams:** Code-based visualizations of engineering architectures, operational workflows, and system relationships.
- **Engineering knowledge integration:** A documentation model connecting civil and structural engineering information with systems engineering and IoT concepts.
- **API documentation strategy:** Exploration of how Swagger/OpenAPI specifications can complement technical manuals and standard operating procedures.
- **Static site deployment:** GitHub Pages publishing for accessible, web-based technical documentation.

## Screenshots

The following screenshots showcase the documentation portal's interface, navigation, and content.

<img width="1905" height="983" alt="Smart infrastructure documentation portal homepage" src="https://github.com/user-attachments/assets/3504136e-53be-42f8-a6ad-cc1ca154c310" />

<img width="1905" height="983" alt="Documentation portal interface and navigation" src="https://github.com/user-attachments/assets/e2de11ef-ed75-47bf-bbe1-2ece1e47561d" />

<img width="1905" height="983" alt="Engineering documentation portal view" src="https://github.com/user-attachments/assets/c02e1a53-4be0-43e1-acba-f66389e88a9f" />

<img width="1905" height="983" alt="Smart infrastructure technical documentation interface" src="https://github.com/user-attachments/assets/433bfd5d-1914-40bd-8cc6-1b211306dfcc" />

<img width="1905" height="983" alt="Engineering knowledge and documentation content" src="https://github.com/user-attachments/assets/f6d397ff-732e-4cc0-8557-9cf96d5966e4" />

<img width="1905" height="983" alt="Technical documentation portal content view" src="https://github.com/user-attachments/assets/42f25b23-ac62-440e-8cc5-e71872328508" />

## Repository Structure

```text
.
├── docs/
│   ├── engineering/       # Engineering architecture and asset documentation
│   ├── quality/           # Quality assurance and continuous improvement
│   ├── standards/         # Metadata, taxonomy, and documentation standards
│   ├── strategy/          # Documentation governance and lifecycle models
│   ├── index.md           # Portal homepage and project overview
│   └── skills_summary.md  # Technical skills and methodologies
├── mkdocs.yml             # MkDocs configuration, theme, and navigation
└── README.md              # Repository overview and setup instructions
```

## Getting Started

Follow these steps to run the documentation portal locally.

### Prerequisites

- Python 3
- Git
- pip, Python's package installer

### 1. Clone the Repository

```bash
git clone https://github.com/ashish-augustine/techwriter-enterprise-docs-portal.git
cd techwriter-enterprise-docs-portal
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment:

**Windows (Command Prompt):**

```bat
.venv\Scripts\activate
```

**Windows (PowerShell):**

```powershell
.\.venv\Scripts\Activate.ps1
```

**macOS / Linux:**

```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
python -m pip install mkdocs-material
```

### 4. Run the Local Development Server

```bash
mkdocs serve
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser to preview the documentation site. The development server automatically rebuilds the site when you make changes to the source files.

## Deployment

The documentation portal is published using **GitHub Pages**.

To build and deploy the site manually, run:

```bash
mkdocs gh-deploy
```

This command builds the documentation and publishes the generated site to the configured GitHub Pages branch. Ensure that your GitHub repository permissions and Pages settings are configured appropriately before deploying.

## Technical Skills & Tools

| Tool / Technology | Application |
|---|---|
| **Markdown** | Authoring technical documentation, manuals, and SOPs |
| **MkDocs** | Generating a static documentation website |
| **Material for MkDocs** | Theming, responsive layouts, navigation, and table of contents |
| **Mermaid.js** | Creating code-based flowcharts and engineering diagrams |
| **Git & GitHub** | Version control, change tracking, and repository management |
| **GitHub Pages** | Hosting and publishing the documentation portal |
| **Python, venv & pip** | Managing the local development environment and dependencies |
| **YAML** | Configuring the documentation site and defining metadata conventions |
| **Visual Studio Code** | Authoring content and managing development workflows |
| **Command-line tools** | Running build commands, managing files, and performing Git operations |
| **Swagger/OpenAPI concepts** | Exploring API specification integration within technical documentation |

## Core Competencies Demonstrated

### Technical Writing & Docs-as-Code

- Writing structured, maintainable documentation in Markdown.
- Applying version control and software development practices to documentation.
- Organizing content for readability, consistency, and long-term maintenance.

### Information Architecture & Governance

- Designing documentation hierarchies, taxonomies, and navigation structures.
- Defining metadata conventions and document classification approaches.
- Modeling documentation lifecycles, including creation, subject matter expert (SME) review, publication, audit, and deprecation.

### Visual & Systems Documentation

- Representing engineering systems, operational workflows, and relationships through Mermaid.js.
- Structuring documentation around physical infrastructure and digital engineering systems.
- Exploring documentation patterns for APIs, IoT systems, and digital twin environments.

### Quality & Deployment

- Applying documentation standards and quality assurance practices.
- Managing source content through Git-based workflows.
- Building and publishing static documentation sites using MkDocs and GitHub Pages.

## Project Goals

This portfolio demonstrates how a structured documentation system can improve the discoverability, consistency, maintainability, and governance of technical knowledge in a complex engineering environment.

It also serves as a practical demonstration of technical writing capabilities across content architecture, documentation tooling, visual communication, and web-based publishing.

## Author

**Ashish Augustine**

- **Portfolio / Live Project:** [Smart Infrastructure Documentation Portal](https://ashish-augustine.github.io/techwriter-enterprise-docs-portal/)
- **GitHub Repository:** [techwriter-enterprise-docs-portal](https://github.com/ashish-augustine/techwriter-enterprise-docs-portal)


 
