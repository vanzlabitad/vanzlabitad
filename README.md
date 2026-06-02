<!--
    If you're reading the raw markdown:
    Hello!
    🍎  Reveluv. Yes, this is intentional.
    Definitive albumn ranking: Perfect Velvet > Chill Kill > The Red
    Favourite songs: Kingdom Come, Automatic, Be Natural & Heaven.
    Listen to Red velvet, Trust me!
-->

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0000,50:8B0000,100:1a0000&height=220&section=header&text=Vanz%20Labitad&fontSize=56&fontColor=ffffff&fontAlignY=40&desc=Msci%20Neuroscience%20%E2%80%94%20University%20of%20Sussex&descAlignY=60&descColor=ff9999&animation=fadeIn" width="100%"/>
</div>

<br/>

<div align="center">

```
Neuroscience researcher who builds reproducible computational tools.
From EM connectomics to pharmacovigilance — say what the data actually shows.
```

</div>

<br/>

---

## 🔬 About

**3rd year MSci Neuroscience student** at the **University of Sussex** *(graduating Summer 2027)*, currently under the **Baden Lab** doing hands on zebrafish retinal connectomics. Right now, I'm actively reconstructing and comparing the 3D morphology of **monostratifying bipolar cell subtypes** across dorsal and ventral retinal regions using serial section electron microscopy, the kind of work where your unit of analysis is measured in nanometres and your sample size is hand-annotated.

Outside the lab, I build projects at the intersection of **neuroscience, pharmacology, and data engineering** — applying the same rigour to drug-safety signal detection and quantitative analysis as I do to nanometre-scale reconstruction. The throughline is being honest about what the numbers actually mean.

<br/>

---

## ⚙️ Stack

<div align="center">

**Languages & Analysis**

![Python](https://img.shields.io/badge/Python-8B0000?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-A00000?style=for-the-badge&logo=r&logoColor=white)

**Data & Visualisation**

![Pandas](https://img.shields.io/badge/Pandas-8B0000?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-A00000?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-B22222?style=for-the-badge&logo=scipy&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-A00000?style=for-the-badge&logo=r&logoColor=white)

**Data & Backend**

![SQL](https://img.shields.io/badge/SQL-8B0000?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-A00000?style=for-the-badge&logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-B22222?style=for-the-badge&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-A00000?style=for-the-badge&logoColor=white)

**ML & NLP**

![Hugging Face](https://img.shields.io/badge/Hugging%20Face-8B0000?style=for-the-badge&logo=huggingface&logoColor=white)
![FinBERT](https://img.shields.io/badge/FinBERT-B22222?style=for-the-badge&logoColor=white)

**Web & Deploy**

![Next.js](https://img.shields.io/badge/Next.js-A00000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-8B0000?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-B22222?style=for-the-badge&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-A00000?style=for-the-badge&logo=githubactions&logoColor=white)
![Quarto](https://img.shields.io/badge/Quarto-8B0000?style=for-the-badge&logo=quarto&logoColor=white)

**Imaging & EM Tools**

![ImageJ](https://img.shields.io/badge/FIJI%2FImageJ-B22222?style=for-the-badge&logoColor=white)
![WebKnossos](https://img.shields.io/badge/WebKnossos-8B0000?style=for-the-badge&logoColor=white)



</div>

<br/>

---

## 📂 Projects

### 🚧 In Progress

<table>
<tr>
<td width="50%" valign="top">

### 🧭 Pharos — Pharmacovigilance Signal Detection
*Flagship · 🔒 private (available on request)*

A platform that ingests OpenFDA FAERS adverse-event data, computes **ROR / PRR** disproportionality statistics, and flags drug-safety signals via the **EVANS criterion**. Next.js dashboard with interactive forest plots and Gemini-generated plain-language summaries; weekly refresh via GitHub Actions, static deploy on Vercel, Quarto methodology report.

`Python` `SQLAlchemy` `SciPy/statsmodels` `Next.js` `Vercel` `GitHub Actions`

</td>
<td width="50%" valign="top">

### 🐟 Zebrafish Retinal Connectomics
*Dissertation — Baden Lab, University of Sussex*

EM-based 3D morphometric analysis of monostratifying bipolar cells across dorsal and ventral retinal regions. Dual-annotator design. Key finding: **ventral S4 cells show significantly wider terminals**.

`Python` `SciPy` `WebKnossos` `STL mesh`

</td>
</tr>
</table>

### ✅ Completed

<table>
<tr>
<td width="50%" valign="top">

### 💊 [FDA FAERS — Antidepressant Safety Signals](https://github.com/Vanz23-23/fda-faers-neuro)
*Pharmacovigilance analysis*

Comparing neuropsychiatric adverse-event profiles across SSRIs, SNRIs and AEDs. SSRIs show more raw suicidal-ideation reports than SNRIs — but after adjusting for reporting volume the gap disappears (ROR 0.96, 95% CI [0.64–1.45]; χ² = 85.77, p ≈ 1.8×10⁻¹⁸; Fisher agrees). **Raw counts mislead. Rates don't.**

`Python` `SQLite` `SQL` `SciPy`

</td>
<td width="50%" valign="top">

### 📈 [Synk — Geopolitical Event-Driven Trading](https://github.com/Vanz23-23/Synk)
*Paper-trading research system*

A three-gate strategy that only enters when all three signals agree: **Regime** (GPR-index z-score), **Momentum** (ROC + SMA-20) and **Sentiment** (FinBERT over GDELT headlines). Quarter-Kelly sizing, Alpaca paper execution, in evaluation since April 2026.

`Python` `FinBERT` `Alpaca` `APScheduler`

</td>
</tr>
</table>

<br/>

---

## 📍 Currently

- 🔬 **3rd year** : actively reconstructing 3D morphology of bipolar cell subtypes in the Baden Lab & writing dissertation drafts
- 📝 Dissertation in progress : regional morphological specialisation of bipolar cells in larval zebrafish retina
- 🎓 Graduating **Summer 2027** : open to graduate R&D / data science roles *(pharma, biotech, neuroscience)*
- 🌍 Based in UK : open to London and beyond
- 🤝 **Hiring or want to collaborate?** Reach out below — particularly for quantitative analysis, imaging data, or scientific software.

<br/>

---

## 📬 Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-8B0000?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vanzlabitad/)
[![Instagram](https://img.shields.io/badge/Instagram-A00000?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/vanz.labitad/)
[![Email](https://img.shields.io/badge/Email-B22222?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vanzlabitad23@gmail.com)

</div>

<br/>
<div align="center">
"There were hard times and slumps, but I never avoided them. I believe that if I didn't go through those periods, I wouldn't be here right now." 
   <div align="center"> Kang Seulgi
   <div align="center">
   RV


<div align="center">
<sub>Powered by caffeine and Red Velvet b-sides.</sub>
</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0000,50:8B0000,100:0f0000&height=120&section=footer" width="100%"/>
</div>
