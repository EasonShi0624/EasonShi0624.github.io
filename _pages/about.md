---
permalink: /
title: ""
excerpt: "Yuchen Shi is an undergraduate researcher at NYU Shanghai working on machine learning for chemical discovery, excited-state dynamics, and molecular modeling."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


# 😁 About Me
Hi, I'm Yuchen Shi—thanks for stopping by!

I am an undergraduate at **New York University Shanghai**, pursuing a B.S. in **Chemistry and Data Science (AI Concentration)**, with expected graduation in **May 2027**.

My research interests are **machine learning for chemical discovery**, **excited-state electronic structure and dynamics**, and **multiscale molecular modeling**. My projects span GFP photochemistry with [William J. Glover](https://wp.nyu.edu/glover/), quantum simulations of battery electrolytes with [Mark E. Tuckerman](https://wp.nyu.edu/tuckerman_group/), protein–ligand structure prediction with [Teresa Head-Gordon](https://thglab.berkeley.edu/research/), and molecular conformer generation with Shengjie Wang and Yingkai Zhang.

I am seeking PhD opportunities for **Fall 2027** in theoretical and computational chemistry, data science, and computer science.


<span class='anchor' id='research'></span>
# 📝 Research

## Research Experience

### Chemical Control of Excited-State Dynamics in GFP Chromophore Anions

*Feb 2024 – Present* · **Advisor:** William J. Glover

- I lead a computational study of how chemical substitution changes excited-state relaxation in anionic GFP chromophores, using **MRSF-TDDFT** and **fewest-switches surface hopping (FSSH)** in OpenQP/Newton-X.
- I developed a **natural transition orbital (NTO)** workflow to track diabatic state character and population transfer, elucidated the role of **nπ<sup>*</sup> states**, and proposed mechanism-guided substitution strategies to modulate chromophore photostability.

### Protein-Environment Effects on Neutral and Anionic GFP Photodynamics

*Jul 2024 – Present* · **Advisor:** William J. Glover

- I constructed explicitly solvated GFP models with Maestro, PyMOL, and AMBER, and performed **DW-CASSCF QM/MM nonadiabatic dynamics** using **ab initio multiple spawning (AIMS)** in TeraChem/FMS90.
- I implemented **configuration-interaction (CI) overlap calculations in TeraChem** to characterize diabatic excited-state populations, and analyzed how local electrostatics influence chromophore relaxation pathways.

### Solvent Effects on Uracil Photorelaxation

*Aug 2024 – Present* · **Advisor:** William J. Glover

- I used gas-phase **ab initio molecular dynamics (AIMD)** in TeraChem to calculate IR spectra of uracil and a proposed photorelaxation intermediate from dipole time-correlation functions.
- I mapped competing ground-state planarization pathways using **SVD-derived coordinates** and potential-energy scans, contributing to a collaboration with Suzuki’s group at Kyoto University to interpret experimental observations and evaluate the proposed intermediate.

### ML-Accelerated Quantum Simulations of Redox-Flow Battery Electrolytes

*Sep 2025 – Present* · **Advisor:** Mark E. Tuckerman

- I generated AIMD trajectories in **CP2K** and trained an **equivariant Transformer in TorchMD-NET** for anthraquinone in imidazoleacetic acid electrolytes, using transfer learning and query-by-committee active learning.
- I applied the learned potential to long-timescale classical MD and **path-integral molecular dynamics (PIMD)** to investigate nuclear quantum effects on proton transfer, solvation structure, and hydrogen-bond networks.
- I computed temperature-dependent vibrational spectra of imidazole–levulinic acid electrolytes to support Raman measurements with the Sangoro group at Ohio State University, and studied hydrogen-bond clusters and proton-transfer energetics in imidazole–acetic acid electrolytes using AIMD, umbrella sampling, and **nudged elastic band (NEB)** calculations.

### Co-folding Llama: Protein–Ligand Structure Prediction with LLMs

*Jun 2026 – Present* · **Advisor:** Teresa Head-Gordon

- I developed a data-curation pipeline combining structural repair, quality control, and leakage-aware splitting to assemble a **sub-million-scale dataset of protein–ligand complexes**.
- I post-trained LLMs for **3D protein–ligand structure generation** using supervised fine-tuning and **LoRA**, and proposed factorized **Z-matrix representations** that separate intramolecular geometry from the relative rigid-body pose, using quaternion or axis-angle parameterizations.

### StifFlow: Stiffness-Calibrated Flow Matching for Molecular Conformer Generation

*Apr 2026 – Present* · **Advisors:** Shengjie Wang and Yingkai Zhang

- I formulated a stiffness-aware flow-matching probability path using **precision-matrix interpolation** between graph-conditioned source and Hessian-informed conditional distributions.
- I designed conditional covariances that adapt deformation scales to stiff and soft molecular modes while preserving physically relevant degrees of freedom, targeting both geometric accuracy and ensemble coverage.


<span class='anchor' id='publications'></span>
# 📄 Publications & Presentations

## Manuscripts in Preparation

- **Chemical Substitution Redirects UV Photoresponse in Green Fluorescent Protein (GFP) Chromophore Anions.** <br>
  **Shi, Y.**, Shen, Y., Thongyod, W., Glover, W.<sup>*</sup>
- **A Tale of Two Pathways: Solvent Effects on the Photorelaxation of Uracil.** <br>
  Glover, W.<sup>*</sup>, Roy, R., **Shi, Y.**

## Poster Presentations

- *Aug 2026* · **ACS Fall 2026** <br>
  Tuning the Photo-oxidation of the Green Fluorescent Protein (GFP) Chromophore through Chemical Modification. <br>
  **Shi, Y.**, Shen, Y., Thongyod, W., Glover, W.<sup>*</sup>
- *Jun 2026* · **ChemAI NYC 2026** <br>
  Machine Learning-accelerated Quantum Simulations for Investigating Charge Transport in Candidate Redox-flow Battery Electrolytes. <br>
  **Shi, Y.**, Chen, M. S.<sup>*</sup>, Tuckerman, M.<sup>*</sup>
- *Jun 2026* · **18th International Congress on Quantum Chemistry** <br>
  Chemical Control of UV-Induced Dynamics in the Green Fluorescent Protein (GFP) Chromophore. <br>
  **Shi, Y.**, Shen, Y., Thongyod, W., Glover, W.<sup>*</sup>
- *Jun 2024* · **2024 International Symposium on Computational Molecular Science and Machine Learning** <br>
  Excited-state Dynamics of the Green Fluorescent Protein (GFP) Chromophore: Insights into Photo-oxidation. <br>
  Shen, Y.<sup>†</sup>, **Shi, Y.<sup>†</sup>**, Thongyod, W., Glover, W.<sup>*</sup>

<sup>*</sup> Corresponding author. <sup>†</sup> Equal contribution.

<span class='anchor' id='presentation'></span>
## Coursework Presentations

- *Dec 2025* · [Simulation of Grand-canonical Ensemble](/presentation/251209_Stat%20Mech%20Pitch%20Presentation.pptx) · CHEM-GA 2600 Statistical Mechanics Pitch Presentation
- *Dec 2025* · [Path Integral Formulation: Everything, everywhere, all at once](/presentation/251211_Path_integral.pptx) · CHEM-GA 2665 Quantum Mechanics Pitch Presentation

<span class='anchor' id='education'></span>
# 📖 Education

- *Aug 2023 – May 2027 (Expected)* · **New York University Shanghai** <br>
  B.S. in Chemistry and Data Science (AI Concentration) <br>
  **Cumulative GPA: 3.989/4.000**

**Graduate-level coursework:** Computational Chemistry; Statistical Mechanics; Quantum Mechanics; Optimization & Computational Linear Algebra; Machine Learning for Molecular Science.

## Training

- *Jul 14–18, 2025* · **2025 Summer School on Machine Learning and Artificial Intelligence for the Molecular Sciences** · NYU-ECNU Center for Computational Chemistry · [Course materials](https://github.com/EasonShi0624/25summer_school_ML_MolecularScience)

## Selected Coursework Project

**Representation Learning with a Lightweight Convolutional Neural Network** · Supervisor: Shengjie Wang <br>
I developed a CNN-based autoencoder for the CSCI-SHU 360 Machine Learning final competition, using batch normalization, residual connections, self-attention, and data augmentation. The project received a full score and ranked in the top 15%. [Code on GitHub](https://github.com/EasonShi0624/25Spring_Machine_Learning).


<span class='anchor' id='technical-skills'></span>
# 🛠 Technical Skills

- **Programming:** Python, C++, Shell.
- **Machine Learning:** PyTorch, TorchMD-NET, Hugging Face Transformers, PEFT, FlashAttention-2.
- **Electronic Structure & Dynamics:** TeraChem (contributor), OpenQP (beta-tester), FMS90, AMBER, CP2K, Newton-X, i-PI, BAGEL, eT, Molpro, Q-Chem, GAMESS-US, ORCA, OpenMolcas.
- **Cheminformatics & Modeling:** RDKit, Gemmi, Biopython, Maestro, PyMOL, VMD, Molden.

<span class='anchor' id='leadership'></span>
# 💻 Leadership & Activities

- *2023.09 – 2025.05* · **Athlete**, Co-Badminton Team, NYUSH Athletics & Fitness Department
- *2023.10 – 2025.05* · **Co-founder & Executive Board Member**, NYUSH Birdy
- *2024.05 – 2025.05* · **President**, NYUSH Society in Natural Sciences
 


<span class='anchor' id='honors-and-awards'></span>
# 🎖 Honors and Awards

- *Oct 2026* · **National Scholarship**, Ministry of Education, PRC
- *Jul 2026* · **Computational Resource Allocation (CIS261383)**, NSF ACCESS <br>
  Co-applicant with Curtis Wu; PI: Teresa Head-Gordon.
- *Jun 2026* · **Undergraduate Award in Physical Chemistry**, American Chemical Society
- *Jun 2024, 2025, 2026* · **Dean's Honors List**, NYU Shanghai
- *Jul 2025* · **NYU Shanghai 2025 Recognition Award**, NYU Shanghai
- *Jun 2025* · **Deans' Undergraduate Research Fund (DURF)**, NYU Shanghai <br>
  **Project:** Tuning the Photo-oxidation of the Green Fluorescent Protein (GFP) Chromophore Through Chemical Modifications
- *Apr 2025* · **Charting Your Path: Global Awards Leadership Program**, NYU Shanghai
- *May 2024* · **First-Year Fellowship**, NYU Shanghai
- *Sep 2023* · **Violet Scholarship**, NYU Shanghai



<span class='anchor' id='gallery'></span>
# 📸 Gallery
Beyond academics, I'm an enthusiast in photography and filming. Emotions and feelings fleet away easily, but images live.<br>
**"Photography is the simultaneous recognition, in a fraction of a second, of the significance of an event." ―― Henri Cartier-Bresson** <br> 
## Film
- *2021.06* · <strong style="color: #4b6aa1;"><a href="https://b23.tv/WfBtY3f" style="color: #4b6aa1; text-decoration: none;">Net</a></strong> (Microfilm) — Assistant Camera & Scriptwriter
- *2021.09* · <strong style="color: #4b6aa1;"><a href="https://b23.tv/UbzZp9l" style="color: #4b6aa1; text-decoration: none;">A Bite of Suzhou: the Clear and Refreshing Gift</a></strong> (Documentary) — Director of Photography
- *2022.06* · <strong style="color: #4b6aa1;"><a href="https://b23.tv/qwlfICM" style="color: #4b6aa1; text-decoration: none;">Bond with Promise</a></strong> (Music Video) — Director, Director of Photography, & Editor

## Photography
### Hong Kong, China. (2024.12)

<div class="photo-gallery">
  <p class="photo-gallery__title">Crossroad of the east and the west. The Queen's Rd. East under gloom of modernization.</p>
  <div class="photo-grid">
    <figure class="photo-card">
      <a href="/photography/hongkong/hk1.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk1.jpg" alt="Hong Kong scene 1">
      </a>
      <figcaption>Hong Kong · Frame 1 · Iron Curtain</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk2.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk2.jpg" alt="Hong Kong scene 2">
      </a>
      <figcaption>Hong Kong · Frame 2 · My Friend Rudolph</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk3.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk3.jpg" alt="Hong Kong scene 3">
      </a>
      <figcaption>Hong Kong · Frame 3</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk4.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk4.jpg" alt="Hong Kong scene 4">
      </a>
      <figcaption>Hong Kong · Frame 4</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk5.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk5.jpg" alt="Hong Kong scene 5">
      </a>
      <figcaption>Hong Kong · Frame 5</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk6.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk6.jpg" alt="Hong Kong scene 6">
      </a>
      <figcaption>Hong Kong · Frame 6</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk7.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk7.jpg" alt="Hong Kong scene 7">
      </a>
      <figcaption>Hong Kong · Frame 7</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk8.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk8.jpg" alt="Hong Kong scene 8">
      </a>
      <figcaption>Hong Kong · Frame 8</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk9.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk9.jpg" alt="Hong Kong scene 9">
      </a>
      <figcaption>Hong Kong · Frame 9</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk10.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk10.jpg" alt="Hong Kong scene 10">
      </a>
      <figcaption>Hong Kong · Frame 10</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk11.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk11.jpg" alt="Hong Kong scene 11">
      </a>
      <figcaption>Hong Kong · Frame 11</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk12.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk12.jpg" alt="Hong Kong scene 12">
      </a>
      <figcaption>Hong Kong · Frame 12</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk13.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk13.jpg" alt="Hong Kong scene 13">
      </a>
      <figcaption>Hong Kong · Frame 13</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk14.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk14.jpg" alt="Hong Kong scene 14">
      </a>
      <figcaption>Hong Kong · Frame 14</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk15.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk15.jpg" alt="Hong Kong scene 15">
      </a>
      <figcaption>Hong Kong · Frame 15</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk16.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk16.jpg" alt="Hong Kong scene 16">
      </a>
      <figcaption>Hong Kong · Frame 16</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk17.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk17.jpg" alt="Hong Kong scene 17">
      </a>
      <figcaption>Hong Kong · Frame 17</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk18.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk18.jpg" alt="Hong Kong scene 18">
      </a>
      <figcaption>Hong Kong · Frame 18</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk19.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk19.jpg" alt="Hong Kong scene 19">
      </a>
      <figcaption>Hong Kong · Frame 19</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk20.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk20.jpg" alt="Hong Kong scene 20">
      </a>
      <figcaption>Hong Kong · Frame 20</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/hongkong/hk21.jpg" class="photo-card__link">
        <img src="/photography/hongkong/hk21.jpg" alt="Hong Kong scene 21">
      </a>
      <figcaption>Hong Kong · Frame 21</figcaption>
    </figure>
  </div>
</div>

### Nanjing, Jiangsu, China. (2023.10)

<div class="photo-gallery">
  <p class="photo-gallery__title">One of the ancient capticals of China.</p>
  <div class="photo-grid">
    <figure class="photo-card">
      <a href="/photography/nanjing/nanjing_1.jpg" class="photo-card__link">
        <img src="/photography/nanjing/nanjing_1.jpg" alt="Nanjing city scene 1">
      </a>
      <figcaption>Nanjing · Frame 1</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/nanjing/nanjing_2.jpg" class="photo-card__link">
        <img src="/photography/nanjing/nanjing_2.jpg" alt="Nanjing city scene 2">
      </a>
      <figcaption>Nanjing · Frame 2</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/nanjing/nanjing_3.jpg" class="photo-card__link">
        <img src="/photography/nanjing/nanjing_3.jpg" alt="Nanjing city scene 3">
      </a>
      <figcaption>Nanjing · Frame 3</figcaption>
    </figure>
  </div>
</div>

### New York, United States. (2025.11)

<div class="photo-gallery">
  <p class="photo-gallery__title">Will be uploaded soon.</p>
</div>

### Dali, Yunan, China. (2025.3)

<div class="photo-gallery">
  <p class="photo-gallery__title"> A tranquil mountain city in southern China retaining traditional minority cultures. Famous for coffee and tea.</p>
  <div class="photo-grid">
    <figure class="photo-card">
      <a href="/photography/kunming&amp;dali/dali1.jpg" class="photo-card__link">
        <img src="/photography/kunming&amp;dali/dali1.jpg" alt="Kunming and Dali snapshot 1">
      </a>
      <figcaption> Dali · Frame 1</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/kunming&amp;dali/dali2.jpg" class="photo-card__link">
        <img src="/photography/kunming&amp;dali/dali2.jpg" alt="Kunming and Dali snapshot 2">
      </a>
      <figcaption> Dali · Frame 2 · Three Primary Colors</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/kunming&amp;dali/dali3.jpg" class="photo-card__link">
        <img src="/photography/kunming&amp;dali/dali3.jpg" alt="Kunming and Dali snapshot 3">
      </a>
      <figcaption> Dali · Frame 3</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/kunming&amp;dali/dali4.jpg" class="photo-card__link">
        <img src="/photography/kunming&amp;dali/dali4.jpg" alt="Kunming and Dali snapshot 4">
      </a>
      <figcaption> Dali · Frame 4</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/kunming&amp;dali/dali5.jpg" class="photo-card__link">
        <img src="/photography/kunming&amp;dali/dali5.jpg" alt="Kunming and Dali snapshot 5">
      </a>
      <figcaption> Dali · Frame 5</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/kunming&amp;dali/dali6.jpg" class="photo-card__link">
        <img src="/photography/kunming&amp;dali/dali6.jpg" alt="Kunming and Dali snapshot 6">
      </a>
      <figcaption> Dali · Frame 6</figcaption>
    </figure>
  </div>
</div>

### Qingdao &amp; Weihai, Shandong, China. (2023.7)

<div class="photo-gallery">
  <p class="photo-gallery__title">Two beautiful cities on the east coast of northern China. Sea breezes and coastal skylines.</p>
  <div class="photo-grid">
    <figure class="photo-card">
      <a href="/photography/qingdao&amp;weihai/qingdao_1.jpg" class="photo-card__link">
        <img src="/photography/qingdao&amp;weihai/qingdao_1.jpg" alt="Qingdao and Weihai coastal view 1">
      </a>
      <figcaption>Qingdao · Frame 1</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/qingdao&amp;weihai/qingdao_2.jpg" class="photo-card__link">
        <img src="/photography/qingdao&amp;weihai/qingdao_2.jpg" alt="Qingdao and Weihai coastal view 2">
      </a>
      <figcaption>Qingdao · Frame 2 · Wish You Were Here</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/qingdao&amp;weihai/qingdao_3.jpg" class="photo-card__link">
        <img src="/photography/qingdao&amp;weihai/qingdao_3.jpg" alt="Qingdao and Weihai coastal view 3">
      </a>
      <figcaption>Weihai · Frame 3</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/qingdao&amp;weihai/qingdao_4.jpg" class="photo-card__link">
        <img src="/photography/qingdao&amp;weihai/qingdao_4.jpg" alt="Qingdao and Weihai coastal view 4">
      </a>
      <figcaption>Weihai · Frame 4</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/qingdao&amp;weihai/qingdao_5.jpg" class="photo-card__link">
        <img src="/photography/qingdao&amp;weihai/qingdao_5.jpg" alt="Qingdao and Weihai coastal view 5">
      </a>
      <figcaption>Weihai · Frame 5</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/qingdao&amp;weihai/qingdao_6.jpg" class="photo-card__link">
        <img src="/photography/qingdao&amp;weihai/qingdao_6.jpg" alt="Qingdao and Weihai coastal view 6">
      </a>
      <figcaption>Weihai · Frame 6</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/qingdao&amp;weihai/qingdao_7.jpg" class="photo-card__link">
        <img src="/photography/qingdao&amp;weihai/qingdao_7.jpg" alt="Qingdao and Weihai coastal view 7">
      </a>
      <figcaption>Weihai · Frame 7</figcaption>
    </figure>
  </div>
</div>

### Shanghai, China. (2023.9)

<div class="photo-gallery">
  <p class="photo-gallery__title">Working people under the Oriental Pearl and iron skyline, and the friendship with the nature</p>
  <div class="photo-grid">
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_1.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_1.jpg" alt="Shanghai scene 1">
      </a>
      <figcaption>Shanghai · Omnipotent Youth Society · Frame 1 </figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_8.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_8.jpg" alt="Hong Kong scene 2">
      </a>
      <figcaption>Shanghai · Crack · Frame 2 </figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_3.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_3.jpg" alt="Hong Kong scene 3">
      </a>
      <figcaption>Shanghai · Red Light · Frame 3</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_4.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_4.jpg" alt="Hong Kong scene 4">
      </a>
      <figcaption>Shanghai · Frame 4</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_5.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_5.jpg" alt="Hong Kong scene 5">
      </a>
      <figcaption>Shanghai · Frame 5</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_6.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_6.jpg" alt="Hong Kong scene 6">
      </a>
      <figcaption>Shanghai · Frame 6</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_7.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_7.jpg" alt="Hong Kong scene 7">
      </a>
      <figcaption>Shanghai · Frame 7</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_2.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_2.jpg" alt="Hong Kong scene 8">
      </a>
      <figcaption>Shanghai · Frame 8</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_9.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_9.jpg" alt="Hong Kong scene 9">
      </a>
      <figcaption>Shanghai · Frame 9</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_10.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_10.jpg" alt="Hong Kong scene 10">
      </a>
      <figcaption>Shanghai · Frame 10</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_11.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_11.jpg" alt="Hong Kong scene 11">
      </a>
      <figcaption>Shanghai · Frame 11</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_12.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_12.jpg" alt="Hong Kong scene 12">
      </a>
      <figcaption>Shanghai · Frame 12</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_13.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_13.jpg" alt="Hong Kong scene 13">
      </a>
      <figcaption>Shanghai · Frame 13</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_14.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_14.jpg" alt="Hong Kong scene 14">
      </a>
      <figcaption>Shanghai · Frame 14</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/shanghai/Shanghai_15.jpg" class="photo-card__link">
        <img src="/photography/shanghai/Shanghai_15.jpg" alt="Hong Kong scene 15">
      </a>
      <figcaption>Shanghai · Frame 15</figcaption>
    </figure>
  </div>
</div>

### Suzhou, Jiangsu, China. (2021.3-2022.11)

<div class="photo-gallery">
  <p class="photo-gallery__title">My beloved hometown. <br> "沧浪之水清兮 可以濯吾缨"</p>
  <div class="photo-grid">
    <figure class="photo-card">
      <a href="/photography/suzhou/2021.3_1.jpg" class="photo-card__link">
        <img src="/photography/suzhou/2021.3_1.jpg" alt="Suzhou water town memory 1">
      </a>
      <figcaption>Suzhou · Memory 1</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/suzhou/2022.9_1.jpg" class="photo-card__link">
        <img src="/photography/suzhou/2022.9_1.jpg" alt="Suzhou water town memory 2">
      </a>
      <figcaption>Suzhou · Memory 2</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/suzhou/2022.9_2.jpg" class="photo-card__link">
        <img src="/photography/suzhou/2022.9_2.jpg" alt="Suzhou water town memory 3">
      </a>
      <figcaption>Suzhou · Memory 3</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/suzhou/2022.9_3.jpg" class="photo-card__link">
        <img src="/photography/suzhou/2022.9_3.jpg" alt="Suzhou water town memory 4">
      </a>
      <figcaption>Suzhou · Memory 4</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/suzhou/2022.9_4.jpg" class="photo-card__link">
        <img src="/photography/suzhou/2022.9_4.jpg" alt="Suzhou water town memory 5">
      </a>
      <figcaption>Suzhou · Memory 5</figcaption>
    </figure>
    <figure class="photo-card">
      <a href="/photography/suzhou/2022.10_1.jpg" class="photo-card__link">
        <img src="/photography/suzhou/2022.10_1.jpg" alt="Suzhou water town memory 6">
      </a>
      <figcaption>Suzhou · Memory 6</figcaption>
    </figure>
  </div>
</div>

### Zhoushan, Zhejiang, China. (2024.4)

<div class="photo-gallery">
  <p class="photo-gallery__title"> Archipelago in the East China Sea. <br> Experimental photography of Weirdcore. "You can go back, but there's nobody there anymore" :)</p>
  <div class="photo-grid">
      <figure class="photo-card">
        <a href="/photography/zhoushan/zhoushan_1.jpg" class="photo-card__link">
          <img src="/photography/zhoushan/zhoushan_1.jpg" alt="Zhoushan island breeze 1">
        </a>
        <figcaption>Zhoushan · Trail 1</figcaption>
      </figure>
      <figure class="photo-card">
        <a href="/photography/zhoushan/zhoushan_2.jpg" class="photo-card__link">
          <img src="/photography/zhoushan/zhoushan_2.jpg" alt="Zhoushan island breeze 2">
        </a>
        <figcaption>Zhoushan · Trail 2</figcaption>
      </figure>
      <figure class="photo-card">
        <a href="/photography/zhoushan/zhoushan_3.jpg" class="photo-card__link">
          <img src="/photography/zhoushan/zhoushan_3.jpg" alt="Zhoushan island breeze 3">
        </a>
        <figcaption>Zhoushan · Trail 3</figcaption>
      </figure>
  </div>
</div>






