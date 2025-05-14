# Alcohol-Crime_ML_Analytics
This project is a Python pipeline that examines the relationship between per-capita alcohol consumption and homicide rates across European countries. It loads and cleans Excel and CSV data, generates descriptive stats and visualizations, fits linear, non-linear, spline and ML models, and compares their performance.


## 📁 Repository Structure

```text
├── AlcoHomicide-ML.ipynb                # Main Colab/Jupyter notebook with analysis code
├── Papier de Recherche - Alcool et Homicides.pdf   # Final research paper in French language (Thierry Hai Son ADAM)
├── Calcul Excel - Rapport Statistiques.xlsx         # Initial Excel statistics
└── README.md                             # Project overview and instructions
```

## 🛠️ Requirements

* Python 3.7+
* Google Colab or local Jupyter environment

### Python Libraries

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels python-dateutil
```

## 📂 Data Files

1. **Papier de Recherche - Alcool et Homicides.pdf**: Full research report outlining objectives, methodology, and results.
2. **Calcul Excel - Rapport Statistiques.xlsx**: Initial descriptive statistics and exploratory charts performed in Excel.

Make sure both files are in the working directory before running the analysis.

## 🚀 Usage

1. **Clone or download** this repository.
2. **Open** `AlcoHomicide-ML.ipynb` in Colab or Jupyter.
3. **Upload** the two data files when prompted.
4. **Run all cells** to reproduce the entire analysis:

   * Data ingestion and cleaning
   * Summary statistics and correlation matrices
   * Regression analyses (simple, multiple, polynomial, spline, piecewise)
   * Machine‑learning models (SVR, Random Forest, KNN)
   * Model comparison and visualizations
5. **Review** generated tables and saved plots (PNG) in the output folder.

## ⚙️ Customization

* **Data ranges** and **variable selection**: edit input file names or filter by year/country.
* **Model parameters**: tweak polynomial degrees, ML hyperparameters, or add new algorithms.
* **Visual style**: adjust Matplotlib/Seaborn settings for custom plots.

## 🤝 Contributing

Contributions are welcome! To propose improvements:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/my-change`)
3. Commit your changes (`git commit -m "Add feature"`)
4. Push (`git push origin feature/my-change`)
5. Open a Pull Request

## 📄 License

This project is licensed under MIT. See [LICENSE](LICENSE) for details.

---

*Reproduce, extend, and explore the complex dynamics between alcohol consumption and violence with ease!*

