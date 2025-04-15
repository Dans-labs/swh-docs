# swh-docs

Documentation repository for the DANS Dataverse SWH connector.

## Overview

This project provides documentation for the **DANS Dataverse SWH connector**, a tool designed to facilitate the deposit of software code and associated datasets into both the [Dataverse](https://dataverse.org/) repository and the [Software Heritage](https://www.softwareheritage.org/) (SWH) archive. The connector ensures that metadata and artifacts are properly archived and referenced across both platforms.

The documentation is divided into two main sections:

1. **[Researchers](docs/research_intro.md):** A user manual for researchers who want to archive software code, datasets, and metadata.
2. **[Developers](docs/develop_intro.md):** Technical documentation for developers working on the connector.

## Prerequisites

Before running the mkdocs server, ensure you have:

1.**Poetry version 2.x.x or higher installed.**
2.**Python version 3.12 or higher installed.**


## Installation

This mkdocs uses Python and `poetry` for dependency management. To set up the project locally:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd swh-docs# swh-docs
    ```
2. Install dependencies using Poetry:
    ```bash
   poetry install
   ```
3. Build the documentation:
   ```bash
   poetry run mkdocs build
   ```
## Usage
To serve the documentation locally, run:
   ```bash
  poetry run mkdocs serve --dev-addr=127.0.0.1:1945
   ```

Documentation repository for the DANS Dataverse SWH connector.
Open your browser and navigate to http://127.0.0.1:1945.
