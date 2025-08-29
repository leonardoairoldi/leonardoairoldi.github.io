---
title: "Electronics Engineering - Master Thesis"

categories:
  - Blog

tags:
  - Engineering
  - Politecnico di Milano
  - University

header:
  teaser: /assets/master-thesis/frontespizio-AIROLDI-color.jpg

gallery-diff-images:
  - url: /assets/master-thesis/frontespizio-AIROLDI-color.jpg
    image_path: /assets/master-thesis/frontespizio-AIROLDI-color.jpg
  - url: /assets/master-thesis/abstract-eng.jpg
    image_path: /assets/master-thesis/abstract-eng.jpg

---

On July 22nd, I successfully defended my Master’s Thesis in Electronics Engineering at Politecnico di Milano.
In my final year I joined [ARPLab](https://arplab.deib.polimi.it/), a research group dedicated to advancing Integrated Circuits.

My thesis, developed within the Analog-to-Digital Converter (ADC) team, focused on analyzing the impact of non-idealities in Time-Interleaved (TI) converters, a key component in modern wireless digital radio receivers such as Wi-Fi 7 and 5G.

It was a long journey, full of challenges, but also very rewarding. I got to dive into something new, contribute (even in a small way) to state-of-the-art ICs, and most importantly, learn from some truly brilliant engineers along the way.

Thanks everyone who made this dream possible.


{% include gallery layout="half" id="gallery-diff-images" caption="Front page and abstract of the thesis." %}

## Analysis of Calibration and Randomization Techniques in TI ADCs for Wireless Applications
> Analog-to-Digital Converters (ADC) are a key component in a digital radio receiver. Modern wireless standards, such as Wi-Fi and 5G, push the limits for the resolution and bandwidth of ADCs to achieve higher data-rates. Time Interleaving (TI) becomes the dominant architecture at high sampling speeds, needed to match the requirements set by the standards. This thesis presents an in-depth analysis on TI ADCs and the impact on their non idealities on a wireless receiver performance. Calibrations are conventionally used in TI ADCs to enhance their performance but, as demonstrated in this work, they are not enough to guarantee a good performance when decoding a wireless signal. Randomization techniques are shown to be a solution, and the study focuses on both pseudo-random chopping-aided offset calibration and channel-order randomization. The two techniques are compared, analyzing both their advantages and disadvantages considering also the implementation non idealities. Channel-order randomization is found to be the most suitable solution, and an implementation of the key block to this technique, the phase generator, is proposed for the adaption on a 4 channel TI ADC with a sampling frequency of 2GHz using the 28nm TSMC technology node. Finally, a new timing skew mismatch calibration is proposed, which improves existing State-of-the-Art techniques for correcting sampling time errors when the channel order is randomized.