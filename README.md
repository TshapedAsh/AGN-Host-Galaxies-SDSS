# 🌌 Galactic Homes of Hungry Black Holes
### An SDSS Deep Dive into AGN Host Galaxies

> What's the difference between a galaxy with a quiet supermassive black hole (SMBH) and one with a raging, luminous Active Galactic Nucleus (AGN) at its core? This project is all about answering that question.

We're jumping headfirst into the massive Sloan Digital Sky Survey (SDSS) dataset to figure out the tell-tale signs of a galaxy that hosts an AGN. Think of it as cosmic real estate analysis: what kind of galactic "neighborhoods" do these powerful black holes prefer?

This isn't just a one-off analysis; it's a core piece of my portfolio exploring the epic dance between SMBHs, AGN feedback, and how galaxies evolve.

---

## 🎯 The Mission

Our game plan is straightforward but ambitious:

* **Data Wrangling:** Dive into SDSS DR16, pull out two clean samples: one with AGNs, and a control group of their boring, non-AGN cousins.
* **Visualize Everything:** Go beyond basic plots. We're creating slick, publication-ready visualizations to spot trends in color, morphology, and stellar mass.
* **Statistical Smackdown:** Use robust stats (like the Kolmogorov-Smirnov test) to see if the differences we spot are legit or just cosmic chance.
* **Build a Legacy:** Craft a portfolio piece that’s clean, reproducible, and a solid launchpad for a future research paper. 🚀

---

## 🧰 The Tech Stack

This project is powered by Python 3 and some of the best open-source tools in the astro/data science world:

* **`astroquery`**: For talking directly to the SDSS CasJobs server.
* **`pandas`**: The undisputed champ for wrangling our data tables.
* **`matplotlib` & `seaborn`**: For crafting those eye-popping plots.
* **`scipy` & `scikit-learn`**: For the heavy lifting on the stats side.

---

## 📂 Project Blueprint

Everything you need is organized right here. No black boxes!

```
AGN-Host-Galaxies-SDSS/
├── data/             # 📡 Raw and processed SDSS data dumps
├── notebooks/        # 📓 Where the magic happens: Jupyter analysis notebooks
├── scripts/          # 🛠️ Reusable Python scripts for queries & data cleaning
├── outputs/          # 📊 The good stuff: plots, tables, and results
├── README.md         # 📘 You are here!
├── LICENSE.md        # ⚖️ The fine print (it's MIT, so go wild)
└── requirements.txt  # 📦 All the Python goodies you need to install
```

---

## 📈 First Light (Results Coming Soon!)

We're currently crunching the numbers. Here’s a sneak peek at the analyses in the pipeline:

* **Color-Magnitude Showdown:** Are AGN hosts bluer, redder, or just different?
* **Morphology Check:** Do AGNs prefer spirals, ellipticals, or something in between?
* **Mass vs. Redshift:** Uncovering how host properties have evolved across cosmic time.

Stay tuned for some awesome plots dropping here soon!

---

## 🧠 About Me

**Gaurav Gawade** An astrophysicist with a passion for the big questions: supermassive black holes, AGN feedback, and the co-evolution of galaxies. I build data-driven projects to explore the cosmos.

[CV](#) | [Portfolio](#) | [Say Hi!](#)

---

## 🚀 Get Your Hands Dirty (Reproducibility)

Wanna run this yourself? Easy.

1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/YourUsername/AGN-Host-Galaxies-SDSS.git](https://github.com/YourUsername/AGN-Host-Galaxies-SDSS.git)
    cd AGN-Host-Galaxies-SDSS
    ```

2.  **Set Up Your Environment:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Fetch the Data:**
    Run the primary query script in the `scripts/` folder to pull the latest data from SDSS.

4.  **Explore!**
    Fire up the Jupyter notebooks in the `notebooks/` directory and start exploring!

---

## 🗺️ The Roadmap

This project is just the beginning. Here's what's next:

* **AGN Subtypes:** Break it down: are Seyferts, LINERs, and Quasars living in different kinds of galaxies?
* **Galaxy Zoo Cross-Match:** Bring in human-powered morphological classifications for a much deeper look.
* **Preprint:** Polish these results into a short research note or a preprint for arXiv.

---

## 💡 License

This project is licensed under the **MIT License**. Feel free to use, remix, and adapt the code for your own research and educational projects. Just give credit where it's due!
