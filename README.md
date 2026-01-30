# Oral Cancer Therapeutic Gene Analysis

A Python pipeline that analyzes mutation and expression data to identify cancer genes and recommend treatments for oral cancer.

## What it does

1. **Loads genomic data** from CSV files (mutations + gene expression)
2. **Identifies cancer genes** using Gene Ontology API + known cancer gene database
3. **Finds treatments** by searching scientific literature for drug therapies
4. **Generates reports** with therapeutic recommendations for each gene

## Files needed

- `mutation.csv` - Gene mutation data
- `expression.csv` - Gene expression data

## Quick start

```bash
pip install pandas requests google-generativeai
```

Open `oral_cancer_therapeutic_gene_analysis.ipynb` and run all cells.

## Output

Detailed therapeutic reports for each cancer gene including:
- Gene function in oral cancer
- Available drug treatments
- Clinical trial recommendations
- Literature evidence with DOIs

## APIs used

- Gene Ontology (gene annotation)
- Europe PMC (literature search)
- Google Gemini (report generation)

---

*Bioinformatics pipeline for precision oncology*
