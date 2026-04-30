---
permalink: /
title: ""
excerpt: ""
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

I am a rising junior at NYU Shanghai pursuing double majors in Chemistry and Data Science. I am honored to work as an undergraduate research assistant in computational chemistry with
<strong style="color: #4b6aa1;">
  <a href="https://wp.nyu.edu/glover/" style="color: #4b6aa1; text-decoration: none;">Professor William J. Glover's group</a>
</strong>
and
<strong style="color: #4b6aa1;">
  <a href="https://wp.nyu.edu/tuckerman_group/" style="color: #4b6aa1; text-decoration: none;">Professor Mark E. Tuckerman's group</a>
</strong>.

My current interests center on **applying and developing molecular dynamics (MD) techniques for complex systems** and **bridging molecular science with cutting-edge data science approaches**. I am also excited to explore neighboring areas including electronic structure, drug discovery, and quantum computing.

I am actively seeking a PhD position in theoretical/computational chemistry, data science, or computer science for Fall 2027. Fingers crossed!


<span class='anchor' id='research'></span>
# 📝 Research

## Research Experience

- *2025.10 – Present* · **Tuckerman Research Group** · NYU Department of Chemistry · PI: Mark E. Tuckerman
- *2024.02 – Present* · **Glover Group** · NYU Shanghai Department of Chemistry · PI: William J. Glover


## Selected Projects
### 1. Non-adiabatic Dynamics of Photo-response in Green Fluorescent Proteins (GFP)

**Supervisor:** William J. Glover <br>
**Keywords:** Photochemistry · Ab-initio Multiple Spawning (AIMS) · QM/MM <br>

Fluorescent proteins, first isolated from *A. victoria*, have become essential research tools across the life sciences. Their chromophores can undergo complex photochemical processes that change optical properties. We use non-adiabatic molecular dynamics to capture and interpret the excited-state behavior of GFP chromophores and to explore mutations that modulate photo-response, guiding the design and understanding of fluorescent proteins.

#### 1.1 Tuning the Photo-oxidation of the GFP Chromophore

The anionic chromophore is central to the GFP photocycle and mediates multiple photochemical pathways. By applying non-adiabatic dynamics, we resolved controversies surrounding the photodamage mechanism in the gas phase and proposed two chemical modification strategies to tune the UV response.

#### 1.2 UV Response of Neutral and Anionic GFP Chromophores

Building on the gas-phase study, we incorporated the protein environment and explicit solvent to simulate GFP excited-state dynamics more accurately. Comparing neutral and anionic chromophores revealed a promising mutation strategy that reshapes the local electrostatic environment to control photodamage.

### 2. Investigating Photo-relaxation of Uracil via Ab Initio Molecular Dynamics

**Supervisor:** William J. Glover <br>
**Keywords:** Spectroscopy · Ab-initio Molecular Dynamics (AIMD) · Enhanced Sampling <br>

Nucleotides are fundamental to DNA and RNA, yet prolonged UV exposure can trigger irreversible photodamage. We combine multiple computational techniques to complement experiments and shed light on the ultrafast dynamics of nucleotides.

#### 2.1 Theoretical Vibrational IR Spectra from Time-Correlation Functions

Time-correlation functions and ab initio molecular dynamics in both gas and condensed phases reveal the vibrational IR spectra of uracil and its photo-relaxation intermediates, highlighting the role of solvation effects in the process.

#### 2.2 Umbrella Sampling Free-Energy Study with a Planarity Descriptor

To explain the multiple relaxation timescales observed in uracil intermediates, Siyu Li (University of Oxford) and I worked on a molecular planarity descriptor and will employ umbrella sampling to construct the free-energy profile of the transition process.

### 3. Nuclear Quantum Effects in Anion Exchange Membrane Fuel Cells

**Supervisor:** Mark E. Tuckerman <br>
**Keywords:** Electrochemistry · Path Integral Molecular Dynamics (PIMD) · Machine Learning <br>

Redox flow batteries (RFBs) are a promising technology for grid-level storage of energy derived from intermittent renewable energy sources, however their wider adoption has been slow due to various drawbacks of existing technologies. As part of collaborative efforts between simulation and experiment, we are screening for alternative flow battery electrolytes that exhibit Grotthuss-accelerated proton transport mediated by extended hydrogen-bond networks.  
However, accurately modeling these systems remains challenging because it requires treating both electronic and nuclear quantum effects. To address these challenges, we have developed DFT-trained machine-learning interatomic potentials (MLIPs) to enable computationally efficient path integral molecular dynamics (PIMD) simulations for these electrolyte systems.

### 4. Representation Learning with a Lightweight Convolutional Neural Network

**Supervisor:** Shengjie Wang <br>
**Keywords:** Machine Learning · Computer Vision · Feature Extraction <br>

Modern vision systems depend on high-quality learned features, and convolutional neural networks (CNNs) provide a powerful way to extract hierarchical image structures. In this project, I developed a lightweight CNN-based autoencoder to learn representations from a fusion image dataset, evaluating performance using reconstruction loss and recognition accuracy. Techniques such as batch normalization, residual connections, self-attention, and data augmentation are included to enhanced the performance.

This work was for the final competition of CSCI-SHU 360 Machine Learning. It received a full score and ranked in the top 15%. Code is available on
<strong style="color: #4b6aa1;">
  <a href="https://github.com/EasonShi0624/25Spring_Machine_Learning" style="color: #4b6aa1; text-decoration: none;">GitHub</a>
</strong>.


<span class='anchor' id='education'></span>
# 📖 Education

- *2023.08 – Present* · B.S. in Chemistry with a second major in Data Science, New York University Shanghai <br>
  **Cumulative GPA: 3.984**

## Training

- *2025.07* · **2025 Summer School on Machine Learning and Artificial Intelligence for the Molecular Sciences** · NYU Shanghai

<span class='anchor' id='presentation'></span>
# 🎤 Presentation

- *2025.12* · <strong style="color: #4b6aa1;"><a href="/presentation/251209_Stat Mech Pitch Presentation.pptx" style="color: #4b6aa1; text-decoration: none;" download>Simulation of Grand-canonical Ensemble</a></strong> · CHEM-GA 2600 Statistical Mechanics Pitch Presentation
- *2025.12* · <strong style="color: #4b6aa1;"><a href="/presentation/251211_Path_integral.pptx" style="color: #4b6aa1; text-decoration: none;" download>Path Integral Formulation: Everything, everywhere, all at once</a></strong> · CHEM-GA 2665 Quantum Mechanics Pitch Presentation

<span class='anchor' id='leadership'></span>
# 💻 Leadership & Activities

- *2023.09 – 2025.05* · **Athlete**, Co-Badminton Team, NYUSH Athletics & Fitness Department
- *2023.10 – 2025.05* · **Co-founder & Executive Board Member**, NYUSH Birdy
- *2024.05 – 2025.05* · **President**, NYUSH Society in Natural Sciences
 


<span class='anchor' id='honors-and-awards'></span>
# 🎖 Honors and Awards

- *2023.09* · **Violet Scholarship**, NYU Shanghai
- *2024.05* · **First-Year Fellowship**, NYU Shanghai
- *2025.04* · **Charting Your Path: Global Awards Leadership Program**, NYU Shanghai
- *2025.06* · **Deans' Undergraduate Research Fund (DURF)**, NYU Shanghai  
  **Project:** Tuning the Photo-oxidation of the Green Fluorescence Protein (GFP) Chromophore Through Chemical Modifications
- *2024.06 & 2025.06* · **Dean's Honors List**, NYU Shanghai



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






