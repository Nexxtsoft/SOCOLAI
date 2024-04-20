# Knowledge-Base Project

## Overview

The Knowledge-Base project is the foundational effort in the SOCOLAI program aimed at creating a comprehensive and dynamic repository of knowledge on key topics related to AI and the software lifecycle. This project directly supports the development of Chapter 3 of the dissertation: "State of Research."

## Objectives

- **Data Collection**: Develop a bot/service that scans various public sources like RSS feeds from publication databases (Google Scholar, Microsoft Academic, etc.), and other accessible APIs to gather abstracts and relevant academic literature.
- **Data Categorization**: Utilize a dynamic keyword list, initially created with tools like Google and ChatGPT, to categorize abstracts. This list will expand as new relevant terms emerge from the data.
- **Network Analysis**: Apply algorithms like PageRank to rank articles, authors, and keywords to identify fundamental themes and terms, establishing a clear depiction of the research landscape.

## Implementation

### Data Collection

- **Sources**:
  - RSS feeds from major publication platforms.
  - Open APIs providing access to scholarly articles and their metadata.
- **Tools**:
  - Development of a custom bot or service capable of periodic scanning and data extraction.

### Data Categorization

- **Keyword Extraction**:
  - Analyze nouns and significant terms within titles and abstracts.
  - Implement a frequency threshold to elevate recurrent terms to 'keyword' status.
  - Compare and refine keywords against a comprehensive list of English nouns.
- **Dynamic List Management**:
  - Develop a system to add new keywords dynamically as new trends emerge in the dataset.

### Network Analysis

- **PageRank Application**:
  - Apply the PageRank algorithm to create a network graph of terms, authors, and publications.
  - Identify and rank foundational themes and contributors in the field.
- **Graph Database**:
  - Utilize a graph database to manage and visualize relationships between entities such as terms and authors.

## Future Work

- **Graph Expansion**: Expand the knowledge graph to include more entities and relationships as the project scales.
- **Machine Learning Integration**: Implement ML algorithms to predict emerging trends and recommend research directions.

## Contribution Guidelines

Contributors are encouraged to suggest improvements, add new sources, and help refine the keyword extraction algorithms. Please refer to [CONTRIBUTING.md](../CONTRIBUTING.md) for more detailed information on how to get involved.

## Contact

For more information or to get involved in the Knowledge-Base project, please email [info@socol.ai](mailto:info@socol.ai).

Thank you for your interest in advancing the field of AI in software lifecycle management through the Knowledge-Base project.
