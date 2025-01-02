---
layout: page
title: Academic
permalink: /academic/
image: /assets/img/ghc.jpg
caption: Attending the 2024 Grace Hopper Celebration with some fellow students from UChicago.
---

### Publications & Projects

#### CT-to-MRI Synthesis for High-dose-rate Brachytherapy Treatment Planning
<u>Rachel Gordon</u>, Hyejoo Kang, Alexander R. Podgorsak, Mohammed Abuhamad.
**Master's Thesis, Loyola University Chicago, 2024.**

<div style="display: flex; gap: 10px;">
  <button onclick="toggleAbstract('abstract1')">Abstract</button>
  <button onclick="openLink('https://drive.google.com/file/d/1DuzTBMaGBus1fUfEtWtcX2zE9R2PKcQv/view')">Paper</button>
  <button onclick="openLink('https://github.com/rachelngordon/gancm')">Code</button>
  <button onclick="openLink('https://drive.google.com/file/d/1_gaAzzrvJnPvSDqchlOCbfLcUmq_Wtyp/view')">Slides</button>
</div>


<div id="abstract1" style="display:none;">
  High-dose-rate (HDR) brachytherapy is a radiation treatment modality that places radioactive sources directly in cancerous regions. Radiation treatment planning for HDR prostate brachytherapy utilizes both CT and MRI to visualize the path of the radioactive source and the prostate gland, respectively. In this work, we propose GAN-CM, a method for conditional CT-to-MRI translation that is based on Generative Adversarial Networks (GANs). The proposed method uses the typical generator-discriminator design of GANs with a modified generator that incorporates semantic masks obtained from the domain image. The use of semantic masks allows GAN-CM to better capture the anatomical details and tissue characteristics present in CT scans, resulting in a more accurate and realistic MRI synthesis. Using “clinically-paired” CT and MRI datasets obtained from 78 patients with prostate cancer who were treated with HDR brachytherapy, we show the advantages of GAN-CM by demonstrating its ability to work effectively with heavy data augmentation and larger batch sizes, as well as its high performance for MRI synthesis. Exploring various experimental settings, we show that training GANs for this task requires careful considerations for preparing the data, such as normalizing and distributing the pixel values of input images. Using histogram equalization, GAN-CM achieves the best results when using the average of equalized and unequalized CTs.
</div>

<script>
  function toggleAbstract(id) {
    const abstract = document.getElementById(id);
    if (abstract.style.display === "none") {
      abstract.style.display = "block";
    } else {
      abstract.style.display = "none";
    }
  }

  function openLink(url) {
    window.open(url, '_blank');
  }
</script>



#### Identification and Analysis of the Spread of {Mis}information on Social Media. 
Muhammad T. Khan, <u>Rachel Gordon</u>, Nimra Khan, Madeline Moran, Mohammed Abuhamad, Loretta Stalans, Jeffrey Huntsinger, Jennifer Forestal, Eric Chan-Tin.
**Computational Data and Social Networks (CSoNet), 2023.**

<div style="display: flex; gap: 10px;">
  <button onclick="toggleAbstract('abstract2')">Abstract</button>
  <button onclick="openLink('https://link.springer.com/chapter/10.1007/978-981-97-0669-3_33')">Paper</button>
  <button onclick="openLink('https://drive.google.com/file/d/1YLiaL5guEJzFEY-AnMdFEMOwh_-uLsaO/view')">Slides</button>
</div>


<div id="abstract2" style="display:none;">
  With unfolding crises such as the COVID-19 pandemic, it is essential that factual information is dispersed at a rapid pace. One of the major setbacks to mitigating the effects of such crises is misinformation. Advancing technologies such as transformer-based architectures that can pick up underlying patterns and correlational information that constitutes information provide tools that can be used to identify what is misinformation/information. To identify and analyze the spread of misinformation, this work performs a quantitative analysis that uses X (previously Twitter) as the data source and a BERT-based model to identify misinformation. The information of the posts, users, and followers was collected based on hashtags and then processed and manually labeled. Furthermore, we tracked the spread of misinformation related to COVID-19 during the year 2021 and determined how communities that spread information and/or misinformation on social networks interact from an analytical perspective. Our findings suggest that users tend to post more misinformation than information, possibly intentionally spreading misinformation. Our model showed good performance in classifying tweets as information/misinformation, resulting in an accuracy of 86%.
</div>

***

{% include image.html url="/assets/img/hanoi.jpg" description="I got to present this work at the 2023 conference on Computational Data and Social Networks in Ha Noi, Viet Nam! Here is a photo of my dad and I getting dinner with some friends we met there." %}


#### Expressing Communal Joy on Social Media During Dark Times: Harnessing Natural Language Processing Methods to Characterize Linguistic Affective Data
<u>Rachel Gordon</u>, Corinne Steuk, Mohammed Abuhamad, Swarnali Banerjee, Rebecca L. Silton.
**Undergraduate Capstone Project, Loyola University Chicago, 2022.**

<div style="display: flex; gap: 10px;">
  <button onclick="toggleAbstract('abstract3')">Abstract</button>
  <button onclick="openLink('https://github.com/rachelngordon/Joy-Project')">Code</button>
</div>

<div id="abstract3" style="display:none;">
  With the recent increase in mental health problems facing humanity, it has become important for human survival to maximize adaptive emotion function through the use of positive emotions. This study seeks to identify how joy in particular can foster human resilience in the face of trauma. This research was conducted by looking at tweets around Chicago from September 2019 through January 2022. Several natural language processing techniques were employed to analyze these tweets in order to determine how the use of joy has changed with the occurrence of particular events over time and identify important topics and contexts pertaining to the experience of joy. The results of this analysis showed that joy is, in fact, often experienced communally in the context of shared identities, experiences, and goals, and thus the use of joy as an act of resistance is an important factor for the continued development and growth of humanity. 
</div>


***

### <a name="prof"></a> Short Professional Summary

For a full professional summary please see [my CV](https://drive.google.com/file/d/1dD4kfkNKCHcfA9JgnEpTU9Z4xMPm-bTQ/view?usp=sharing).

**EXPERIENCE**
* Graduate Research Assistant, Aug. 2024-Present
  - University of Chicago
* [Graduate Women in Computer Science](https://cs.uchicago.edu/diversity/women-in-computing/) co-chair, Sep. 2024-Present
  - University of Chicago
* Graduate Research Assistant, Aug. 2022-May. 2024
  - Loyola University Chicago, [Argonne National Laboratory](https://www.anl.gov/)
* Undergraduate Research Assistant, Oct. 2021—Aug. 2022.
  - Loyola University Chicago
* Python Tutor, Jan. 2022—May. 2022.
  - Loyola University Chicago
* Data Science Intern, Sep. 2021-May. 2022.
  - [Office of the Director of National Intelligence](https://www.dni.gov/)
* AI Research Associate, Sep. 2020-Jun. 2021.
  - [U.S. Department of State](https://www.state.gov/)

**EDUCATION**
* Ph.D. Computer Science, 2024—Present
  - University of Chicago
* M.S. Data Science, 2022—2024
  - Loyola University Chicago
* B.S. Statistics, Honors Summa Cum Laude, 2019-2022
  - Loyola University Chicago

**HONORS**
* Katherine Johnson Award for outstanding achievement in data science curriculum and research, Department of Computer Science at Loyola University Chicago, 2024.
* Best Paper Presentation in the Sciences, Loyola University Chicago Interdisciplinary Research Symposium, 2024.
* Defense of M.S. Thesis with Distinction, Loyola University Chicago, 2024.
* Father Rust. S.J. Memorial Award for outstanding achievement in mathematics and statistics courses, Department of Mathematics & Statistics at Loyola Unviersity Chicago, 2022.
* Departmental Honors, Department of Mathematics & Statistics at Loyola Unviersity Chicago, 2022.
* Presidential Scholar, Loyola University Chicago, 2019-2022.

***

{% include image.html url="/assets/img/drjoy.jpg" description="Meeting <a href='https://poetofcode.com/about/' target='_blank'>Dr. Joy Buolamwini</a>, the author of <a href='https://www.unmasking.ai/' target='_blank'>Unmasking AI</a>, which discusses issues of bias in computer vision and other AI technologies. This was my favorite nonfiction book I read in 2024, a must read!" %}

