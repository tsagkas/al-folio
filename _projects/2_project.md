---
layout: page
title: Hand-Gesture Recongnition
description: Real-time hand-gesture recongnition via sEMG signals with CNNs.
img: assets/img/thumbnails/semg_thumbnail.png
importance: 2
category: Research Projects
---


In the past few years, a great interest for the
classification of hand gestures with Deep Learning methods
based on surface electromyography (sEMG) signals has been
developed in the scientific community. In line with latest
works in the field, the objective of our work is to train
a novel CNN architecture, for the real-time
classification of hand-gestures. 

The classification accuracy on the MyoUP dataset, which we developed using a
commercial device (Myo Armband), was substantially higher
(approximately 24%) than on the Ninapro benchmark dataset
recorded with the same device.

<center>
    <iframe id="video" width="560" height="315" src="https://www.youtube.com/embed/w98PkUeSu20?autoplay=1&mute=1&enablejsapi=1" frameborder="0" allow="encrypted-media" allowfullscreen=""></iframe>
</center>



In order to contribute to the acquisition of sEMG data,
particularly from devices that do not require professional
calibration, we developed a sizeable sEMG dataset. Our
dataset, MyoUP, was inspired by the Ninapro dataset and
all of the recorded hand-gestures, are
identical to some of the [[Ninapro](http://ninaweb.hevs.ch)]. The recording device
we used was the Myo Armband, by Thalmic labs. The Myo
Armband is a relatively cheap and easy-to-wear device, with
a sampling frequency of 200Hz and 8 dry sEMG channels
that has been widely adopted in scientific research.

The MyoUP dataset contains recordings from 8 intact
subjects (3 females, 5 males; 1 left handed, 7 right handed;
age 22.38 ± 1.06 years). The acquisition process was
divided into three parts: 5 basic finger movements, 12
isotonic and isometric hand configurations and 5 grasping
hand-gestures. Volunteers became accustomed with the
procedure before performing each set of exercises. Subjects
were instructed to repeat each gesture 5 times, for a 5sec
period, interleaved with 5sec interruptions to avoid muscle
fatigue. A supervisor assisted the subjects in wearing the
Myo Armband to their dominant hand so that the device
would be placed in a comfortable position for the subject
and the device would detect the sEMG signals accurately.
The sEMG was visible to the subject on a screen along with
a picture of the hand-gesture that had to be performed.

---
## Downloads:

- Download dataset from: **[MyoUP dataset](https://github.com/tsagkas/MyoUP_dataset)**

- Download CNN and code from: **[code](https://github.com/tsagkas/sEMG-HandGestureRecognition)** 

- Download paper pdf from: **[pdf](http://www.ece.upatras.gr/skodras/data/uploads/pubs/ans-c117-prepress.pdf)** 

---
## Citation 

```
@INPROCEEDINGS{8900709,
    author={Tsagkas, Nikolaos and Tsinganos, Panagiotis and Skodras, Athanassios},
    booktitle={2019 10th International Conference on Information, Intelligence, Systems and Applications (IISA)}, 
    title={On the Use of Deeper CNNs in Hand Gesture Recognition Based on sEMG Signals}, 
    year={2019},
    pages={1-4},
    doi={10.1109/IISA.2019.8900709}}
```