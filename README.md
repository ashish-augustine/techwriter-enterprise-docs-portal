# smart-infra-docs


# Visit the deployed website live at : https://ashish-augustine.github.io/smart-infra-docs/




How to run locally
============
1. Create and Activate the Virtual Environment
Run these commands one by one in your VS Code terminal (ensure you are still inside the smart-infra-docs folder):
>
        python3 -m venv venv
        source venv/bin/activate


2. Install All Dependencies Inside the Sandbox
Now that we are safely inside the virtual environment, let's install MkDocs, the Material theme, and the missing extensions:
>
        pip install mkdocs mkdocs-material pymdown-extensions

3. Test the Server Again
Once the installation finishes successfully, run the serve command:
>
        mkdocs serve



============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================




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