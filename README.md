# Estimating Structural Gravity Model to Analyse a Potential Trading Opportunity between India and CPTPP

This repository contains the code and methodology used to estimate a structural gravity model to assess the trade impact if India were to join the CPTPP (Comprehensive and Progressive Agreement for Trans-Pacific Partnership).

## 📌 Objective

The primary research questions:
- How would India's bilateral trade with CPTPP countries change if it joined the agreement?
- What trade creation or diversion effects would this induce for both members and non-members?

## 🧪 Methodology

We estimate the structural gravity model using various approaches:

- Two-Way Fixed Effects Estimator
- Poisson Pseudo Maximum Likelihood (PPML)
- Gamma Pseudo Maximum Likelihood (GPML)
- Non-Linear Least Squares (NLS)
- Structural Iterated Least Squares (SILS)

The models include controls for:
- GDP of exporter/importer
- Bilateral distance
- Contiguity
- Common language
- Existing RTAs
- Year dummies
- Trade creation/diversion indicators
- Multilateral resistance terms via fixed effects

## 📊 Data Sources

Data was obtained from:
- [World Integrated Trade Solution (WITS)](https://wits.worldbank.org/)
- [CEPII](http://www.cepii.fr/)
- [UNCTAD](https://unctad.org/)
- [International Monetary Fund (IMF)](https://www.imf.org/)

## 📁 Repository Structure


## 📈 Key Findings

- Positive and significant trade creation effects observed under CPTPP+.
- Distance has a consistently negative impact across methods.
- Trade diversion effects are evident in NLS and PPML models.
- Heteroskedasticity was accounted for in multiplicative models like PPML and GPML.

## 📚 References

- Anderson, J. & van Wincoop, E. (2003). Gravity with Gravitas.
- Baier & Bergstrand (2007). Do Free Trade Agreements Actually Increase Members' International Trade?
- Silva & Tenreyro (2006). The Log of Gravity.
- WTO & UNESCAP (2016). An Advanced Guide to Trade Policy Analysis.

## ✍️ Author

**Nandita Gupta**  
Course Project — ECO342A (Econometrics-II)

---

> For academic or collaborative inquiries, feel free to open an issue or submit a pull request.



