# Gene-Expression-Plots
Python scripts used to generate three plots: (A) Log2 Fold Change, (B) Heatmap, and (C) Venn diagram of overlap of significant upregulation for two genes in three cell lines. 

## Requirements

- Python 3.10+
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `matplotlib-venn`

Install with:

```bash
pip install numpy pandas matplotlib scipy matplotlib-venn
```

## Scripts

| Script | Description | Output |
|---|---|---|
| `PlotA_code.py` | Line plots of qRT-PCR Log2 fold change vs. concentration (dose-response), one panel per gene, across all three cell lines | `Plot A.png` |
| `PlotB_code.py` | Heatmap of mean Log2 fold change (qRT-PCR) across concentrations, grouped by cell line and gene | `Plot B.png` |
| `PlotC_code.py` | Three-way Venn diagram summarizing which concentration(s) produced significant upregulation (≥1.44-fold, Log2FC ≥ 0.53) shared across the three cell lines | `Plot C.png` |


## Citation

Diana Almahdawi, Jordan University of Science and Technology. Github: Gene Expression Plots. Available from: https://github.com/dlalmahdawi20/Gene-Expression-Plots

## License

Released under the [MIT License](LICENSE).
