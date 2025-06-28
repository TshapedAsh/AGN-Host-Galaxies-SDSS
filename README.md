# AGN-Host-Galaxies-SDSS

## 🔭 Project Summary
This project investigates the host galaxy properties of Active Galactic Nuclei (AGN) using spectroscopic data from the Sloan Digital Sky Survey (SDSS DR16). By comparing AGN-host galaxies with a control sample of non-AGN galaxies, we aim to explore differences in color, morphology, stellar mass, and redshift distribution.

This is part of a broader portfolio exploring supermassive black holes (SMBH), AGN feedback, and galaxy coevolution.

---

## 🎯 Goals
- Extract and compare galaxy properties (e.g., color, magnitude, redshift) from SDSS for AGN and non-AGN samples
- Visualize trends in host properties using clean data plots
- Quantify statistical differences using simple metrics (e.g., KS test, median shift)
- Build a lightweight, reproducible, portfolio-worthy project with potential to scale into a publication

---

## 📚 Data Source
- Sloan Digital Sky Survey (SDSS) Data Release 16
- Queried via `astroquery.sdss` and the CasJobs SQL interface

---

## 🧰 Tools Used
- Python 3
- `astroquery`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`
- Jupyter notebooks / modular scripts

---


Project Structure:
  - data/: SDSS AGN and non-AGN samples
  - notebooks/: Jupyter notebooks for analysis
  - scripts/: SDSS query scripts and helpers
  - outputs/: Visuals, plots, and tables
  - README.md: Project overview
  - LICENSE.md: MIT license for open reuse
  - requirements.txt: Python environment dependencies



---

## 📈 Early Results (coming soon)
- Color–magnitude diagrams for AGN vs. non-AGN hosts
- Morphology distribution comparison
- Stellar mass vs. redshift trends

---

## 🧠 Author
**Gaurav Gawade**  
Astrophysics MSc | Research interests: SMBHs, AGN feedback, galaxy evolution  
[CV](#) | [Portfolio](#) | [Email](#)

---

## 🔌 Reproducibility
To reproduce the project:
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run the query script in `scripts/` folder
4. Explore the analysis notebooks

---

## 🌌 Future Work
- Add AGN type (Seyfert, LINER, etc.) breakdown
- Extend to cross-match with morphology catalogs (Galaxy Zoo)
- Build a short research note or preprint

---

## 💡 License
MIT — feel free to use or adapt for educational and research purposes.
