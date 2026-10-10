# Beginner-Friendly Project Ideas

These ideas are designed to help students connect AI, computing and biology. Start with public, non-sensitive data. Follow each dataset's licence and usage conditions, cite it, and do not present an educational model as a diagnostic or clinical tool.

## Beginner projects

### 1. DNA sequence statistics
**Question:** What patterns can be measured in a short DNA sequence?

- Count nucleotides and calculate GC content.
- Compare sequences using simple summary statistics.
- Visualise results.
- Explain why sequence statistics alone cannot establish biological function.

**Skills:** Python, strings, functions, plots and scientific explanation.

### 2. Protein sequence comparison
**Question:** How can two protein sequences be compared computationally?

- Use a public protein sequence source.
- Calculate simple sequence similarity or use a documented alignment tool.
- Explain what similarity can suggest and what it cannot prove.

**Skills:** data handling, sequence analysis and literature reading.

### 3. Microbial growth curve visualisation
**Question:** How does microbial population growth change over time in a provided educational dataset?

- Plot time against a growth measurement.
- Compare phases of growth where the data permit.
- Fit a simple curve only if assumptions are appropriate.
- Do not use the analysis to make unsupported claims about a real pathogen.

**Skills:** pandas, plotting, basic statistics and biology.

### 4. Public-health trend exploration
**Question:** What patterns appear in a public, aggregated epidemiological dataset?

- Cite the original source and its definitions.
- Plot changes over time or compare regions.
- Discuss missing data, reporting differences and confounding factors.
- Avoid causal claims unless the study design supports them.

**Skills:** data cleaning, visualisation and critical reasoning.

## Intermediate projects

### 5. Compare baseline and machine-learning models
Choose a permitted public biological dataset and a clearly defined prediction target.

- Create a simple baseline first.
- Split data correctly into training and evaluation sets.
- Avoid leakage between related samples.
- Report suitable metrics and limitations.
- Make clear that predictive performance is not the same as biological explanation.

### 6. Biomedical image classification demo
Use a public, appropriately licensed educational image dataset.

- Inspect class balance and data quality.
- Build a simple baseline before trying a neural network.
- Report precision/recall or other metrics appropriate to the task.
- Discuss dataset bias and why the demo is not a clinical diagnostic device.

### 7. Multi-omics exploration
Use a public tutorial dataset to explore how different biological measurement types can be represented and compared.

- Describe what each data layer measures.
- Check missingness and scale.
- Visualise samples and features.
- Avoid overinterpreting correlations.

### 8. Reproducible bioinformatics pipeline
Build a small, documented workflow that takes a public input file and produces a summary report.

- Separate code into reusable functions.
- Document software versions and input sources.
- Include example output and known limitations.
- Add tests for core functions.

## Recommended GitHub project structure

```text
project-name/
├── README.md
├── data/              # Keep large or restricted data out of Git if needed
├── notebooks/
├── src/
├── results/
├── figures/
├── requirements.txt
└── references.md
```

## Every project README should answer

1. What biological or biomedical question are you investigating?
2. Where did the data come from, and what licence applies?
3. What preprocessing was performed?
4. Which method was used, and why?
5. What were the results?
6. What are the limitations and possible sources of bias?
7. How can someone reproduce the analysis?
8. What should not be concluded from this project?

## Ethics and safety checklist

- Use public or properly authorised datasets.
- Do not upload personal, identifiable or confidential health data.
- Follow dataset terms and institutional rules.
- Cite sources and software.
- Do not describe a model as clinically validated without appropriate evidence.
- Treat AI-generated code and explanations as material to verify, not as unquestionable truth.
