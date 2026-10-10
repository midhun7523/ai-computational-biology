# Identifying an Unknown DNA Sequence Using BLAST

**Project:** A Beginner's Study of Identifying an Unknown DNA Sequence Using BLAST  
**Course:** Programming with Generative AI

This folder organizes the coding and practical work described in the accompanying practical record. It includes:
- a local-alignment demonstration against five short representative sequences;
- experiments showing the effect of mismatches, query length and database size;
- a simple multi-metric decision rule;
- a CSV results-table generator;
- an optional live NCBI BLAST request;
- an offline random-sequence demonstration.

## 1. Requirements

Python 3.10 or later is recommended.

```bash
python -m venv .venv
# Windows:
.venv\\Scripts\\activate
# macOS/Linux:
source .venv/bin/activate

pip install -r requirements.txt
```

## 2. Run the project

Run commands from this project folder:

```bash
python src/pairwise_species_alignment.py
python src/experiments.py
python src/decision_rule.py
python src/make_results_csv.py
python src/offline_demo.py
```

The live NCBI query is optional and requires internet access:

```bash
python src/ncbi_blast.py
```

Results are written to `results/`; plots are written to `figures/`.

## 3. Important interpretation note

The small species strings in `pairwise_species_alignment.py` are **illustrative fragments**, not a validated reference database. The E-values calculated in the experiments use a simplified demonstration formula with chosen constants. They are **not official BLAST E-values** and must not be used for clinical diagnosis. For real sequence identification, submit an appropriate sequence to NCBI BLAST and review the database, alignment, query coverage, percent identity and E-value together.

## 4. Data

The offline experiment creates its own reproducible simulated sequences. The optional online example uses a short sample DNA sequence included in the script. No external dataset is required for the offline scripts.

## 5. Folder guide

- `src/` — Python scripts
- `results/` — generated CSV/text/JSON outputs
- `figures/` — generated plots
- `data/` — reserved for input data you add later
- `requirements.txt` — Python dependencies
