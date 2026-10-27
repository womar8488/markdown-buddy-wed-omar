# BDA400 Assignment 1 - Reflection Questions

## 1. How does structuring an R project with an .Rproj file and README enhance reproducibility?
Using an `.Rproj` file automatically anchors the working directory to the project folder root, avoiding brittle hardcoded absolute file paths. Paired with a structured `README.md`, any collaborator or reviewer can open the project in RStudio, understand dependencies, and re-run the analysis without manual path reconfigurations.

## 2. What role does AI play in drafting project documentation, and why is human review necessary?
AI tools accelerate documentation setup by generating structured Markdown headers, templates, and formatting syntax. However, human review is essential because AI can hallucinate incorrect environment versions, misidentify script names, or output overly generic disclosures. Human validation guarantees technical accuracy and maintains academic integrity standards.

## 3. How do standard Markdown headers and formatting improve the readability of data science documentation?
Markdown headers (`#`, `##`), lists, and fenced code blocks establish clear visual hierarchy. This enables technical readers to scan directly to essential sections—such as installation steps, setup code, or output descriptions—without navigating dense, unformatted blocks of text.