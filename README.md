### HELLO WORLD

```
void send_it_later_alligator();

for(a)
{
  while(crocodile){}
}
```

My [Resume](https://peterwaiiace.github.io/me.github.io/cv.html).

Reach me via [Discord](https://discord.com/users/691353309868458056) or walas.piotr@outlook.com.

## Announcements:

<a href="https://polar.sh/PeterWaIIace/posts"><picture><source media="(prefers-color-scheme: dark)" srcset="https://polar.sh/embed/posts.svg?org=PeterWaIIace&darkmode"><img alt="Posts on Polar" src="https://polar.sh/embed/posts.svg?org=PeterWaIIace"></picture></a>

## Support

<a href="https://polar.sh/PeterWaIIace"><picture><source media="(prefers-color-scheme: dark)" srcset="https://polar.sh/embed/subscribe.svg?org=PeterWaIIace&label=Subscribe&darkmode"><img alt="Subscribe on Polar" src="https://polar.sh/embed/subscribe.svg?org=PeterWaIIace&label=Subscribe"></picture></a>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y1SGTBV)

## My non-opensourced projects: 

### [WiP] [EyePilot](https://polar.sh/NativeSensors)

EyePilot is personal use app based on opensource [Eyegestures](https://github.com/NativeSensors/EyeGestures) python library. It is designed to deliver gaze driven interface for all who cannot use or do not want to use hand based input devices.

<p align="center">
  <img src="https://github.com/PeterWaIIace/PeterWaIIace/assets/40773550/3b38d73d-bb6f-4f31-b67d-231ac4cd04cb" width="300" height="150">
<img src="https://github.com/PeterWaIIace/PeterWaIIace/assets/40773550/9942794a-4d24-4f6c-8392-353546b6521b" width="300
" height="150">
</p>
<p align="center">
  <img src="https://github.com/PeterWaIIace/PeterWaIIace/assets/40773550/1715b4df-7ac3-479e-b51a-f6d800ea8ea5" width="300" height="150">
<img src="https://github.com/PeterWaIIace/PeterWaIIace/assets/40773550/fd9f66d4-6e62-4f6a-98e3-b16907993d24" width="300
" height="150">
</p>

### [Eyegestures](https://eyegestures.com/) ![status](https://img.shields.io/badge/status-up-green.svg)

Ad hoc (minimal calibration) Eye controlled cursor, detecting blinking, following your gaze move and working in web browser! 

Eyes are new mouse. Most people use laptops or smartphones, having easy access to built-in camera systems, and many research papers already shown that a web camera is enough to track gaze. Following that state of affair, I decided to develop this PoC for eye controlled tracker and it seems to work! (well do not expect too much though)

Demos:
1) [Cinema](https://eyegestures.com/cinema)
2) [Game](https://eyegestures.com/game)


<p align="center">
  <img src="https://github.com/PeterWaIIace/me.github.io/assets/40773550/df208ac9-e5f8-4603-8837-6a0791ee56eb" width="600" height="350">
</p>

<p align="center">
  <img src="https://github.com/PeterWaIIace/PeterWaIIace/assets/40773550/2ad25252-e96e-47d4-b25f-c47ba7f0f4f3" width="300" height="150">
<img src="https://github.com/PeterWaIIace/PeterWaIIace/assets/40773550/f3132843-063a-439a-8e1c-2385ddfdccda" width="300
" height="150">
</p>

### [WebSend](https://websend-app-eu.herokuapp.com/) (adhoc communication)![status](https://img.shields.io/badge/status-up-green.svg)

PnP adhoc messaging with file sending using webRTC! Allows for transfering files between to machines connected to internet, without sharing any email accounts, usb sticks, or links. Adhoc connection based on QR code or randomly generated passphrase.

### **Facejitsu** (done with [Emteq](https://www.emteqlabs.com/)) - Affective gaming PoC

Play games with your faces expressions, using Emteq facial sensing glasses! Affective gaming PoC built by me internally in Emteq. Games are experiments provided by [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) project.  

<p align="center">
  <img src=https://user-images.githubusercontent.com/40773550/228829034-e0a69858-92bb-4754-8993-1599176c7dfd.gif width="340" height="200">
  <img src=https://user-images.githubusercontent.com/40773550/228829964-80705b7e-74c8-4e3f-bffd-81c974013597.gif width="340" height="200">
</p>

(clearly I am not the best player ...)

## OpenSourced Projects: 

### [JAX-NEAT](https://github.com/PeterWaIIace/NEAT/tree/main)

This is implementation of Neural Evolution of Augmenting Topologies using JAX, based on paper of Kenneth O. Stanley and Risto Miikkulainen. I am huge fan of evolutionary techniques, so decided to design some tiny framework foR this.

Repository may be a bit of mess, but all main code is in neat.py.

Results roughly after **30 epochs/generations**:

<p align="center">
<img src="https://github.com/PeterWaIIace/NEAT/assets/40773550/bfd5e541-8f94-4f12-adaf-7091146ba21c" width="300" height="200">
<img src="https://github.com/PeterWaIIace/NEAT/assets/40773550/38fd8a25-ef47-48ff-a471-a37276515713" width="300" height="200">
</p>

### [JAX_vs_Numpy_vs_Loops](https://github.com/PeterWaIIace/benchmarking-matrices/tree/main)

Repo focused on benchmarking matrix operations, to find and document where JAX is outperforming Numpy.

### [ParticleLife](https://github.com/PeterWaIIace/ParticleLife)

Cpp and Python implementation of particle life algorithm. Pretty and beautiful simulation of emergent structures caused by simple interactions of attraction:

<p align="center">
  <img src=https://user-images.githubusercontent.com/40773550/234987226-72c52e8c-6991-4da5-bcae-75d3ea1086da.gif  width="300" height="300">
  <img src=https://user-images.githubusercontent.com/40773550/235330028-1cbec001-e376-451f-b626-23d3366c9347.gif  width="300" height="300">
</p>

### [Boids](https://github.com/PeterWaIIace/Boids)

Here is my take on implementation of 2D boids algorithm, case showing emergent behaviours based in systems based on simple building blocks.

<p align="center">
  <img src=https://user-images.githubusercontent.com/40773550/221363441-8afa31f7-3d15-4258-a417-1056fa4e333d.gif>
</p>

### [Genetic Painter](https://github.com/PeterWaIIace/GeneticPainter)

Evolutionary algorithms can make art (or at aleast reproduce it).

<p align="center">
  <img src=https://user-images.githubusercontent.com/40773550/228100220-3f8be211-896a-440f-9829-57247c1e3208.gif width="240" height="240">
  <img src=https://user-images.githubusercontent.com/40773550/228984764-37cecee3-1a10-46f2-9044-478daee041b1.gif width="240" height="240">
</p>

### [GPTConversatorium](https://github.com/PeterWaIIace/GPTConversatorium)

What will happen if you let two LLMs talk to each other? 

<p align="center">
  <img src=https://user-images.githubusercontent.com/40773550/221328004-4e8bc586-06d5-4a8e-b592-d6674d0d2e36.png width="644
" height="400">
</p>

### [GPTCodeProcessor](https://github.com/PeterWaIIace/GPTCodeProcessor)

LLM can generate code and test it! (feat. [BlackBoxTesting](https://github.com/PeterWaIIace/BlackBoxTesting) [WIP] Framework)

<p align="center">
  <img src=https://user-images.githubusercontent.com/40773550/218609556-b03af4a8-bbdd-4dc0-aa76-f0ffb5832244.png width="644
" height="400">
</p>


<!--
**PeterWaIIace/PeterWaIIace** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
