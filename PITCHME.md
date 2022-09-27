---
marp: true
title: ecoVAD
theme: gaia
paginate: true
author: Benjamin Cretois
footer:  Benjamin Cretois - Norwegian Institute for Nature Research
---

<!-- _class: lead invert -->

# ecoVAD :four_leaf_clover:

### An end to end pipeline for training and using Voice Activity Detection models in soundscape analysis.

Benjamin Cretois


---


![bg right width:500px height:500px](./assets/pic_twitter.jpg)

![width:80px height:80px](https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/twitter.svg) benjamincretois

![width:80px height:80px](https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg)  ssssss

![width:300px height:220px](./assets/NINA.png)





---

<!-- _class: lead invert -->

# Background


---

# Background

:sound: Eco-acoustic monitoring is **increasingly being used** to map biodiversity across large scales

<br>

:confused: Little thought is given to the **privacy concerns** and potential **scientific value** of inadvertently recorded human speech

<br>

:collision: We developed an end-to-end VAD pipeline and show how VAD models can be used for both!

---

<!-- _class: lead invert -->

# Method

---

# Method

We compare our pipeline with 2 state-of-the-art VAD models:

- [Pyannote](https://github.com/pyannote/pyannote-audio)
- [Google's WebRTC VAD](https://github.com/wiseman/py-webrtcvad)


<br>

:star: **Note** that in our repo we provided wrappers for using both models

--- 

# Method

<br>

**Training** :deciduous_tree: : We collected soundscape data that we mixed with human voices & other noises.


**Testing** :man: :woman: :child: : playback experiments with speech samples from a man, woman, and child at 1,5,10 and 20 meters.

**Using**: we collected soundscape from a recreational area to evaluate the ability of the models to detect human speech.

---

<!-- _class: lead invert -->

# Results

---

# Results

![bg right width:700px height:600px ](./assets/Figure_2.png)


- All model performed well on the playback data

<br>

- Our custom model performs better




---

# Results

![width:1200px height:500px ](./assets/Figure_3.png)


---

<!-- _class: lead invert -->

# Discussion

---

# Discussion

:star: Specificity vs state-of-the-art

:star:

:star: Speech detections as a direct measure of anthropogenic noise pollution and indirect proxy of human disturbance 




---

# Discussion


:arrow_right: Have a look at the [ecoVAD GitHub repo!](https://github.com/NINAnor/ecoVAD)

:arrow_right: And very soon the paper!



