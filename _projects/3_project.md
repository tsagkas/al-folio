---
layout: page
title: MyoUP dataset
description: Dataset of sEMG signals, recorded with the Myo armband.
img: assets/img/thumbnails/myo_thumbnail.jpg
importance: 3
category: Research Projects
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/MyoUP.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In order to contribute to the acquisition of sEMG data, particularly from devices that do not require professional calibration, we developed a sizeable sEMG database. Our dataset, MyoUP, was inspired by the Ninapro database and all of the recorded hand-gestures, presented in: 
[[here](/assets/pdf/MyoUP.pdf)]. The recording device we used was the Myo Armband, by Thalmic labs. The Myo Armband is a relatively cheap and easy-to-wear device, with a sampling frequency of 200Hz and 8 dry sEMG channels that has been widely adopted in scientific research.


---
## Dataset Info

The MyoUP database contains recordings from 8 intact subjects (3 females, 5 males; 1 left handed, 7 right handed; age 22.38 ± 1.06 years). The acquisition process was divided into three parts: 5 basic finger movements, 12 isotonic and isometric hand configurations and 5 grasping hand-gestures. Volunteers became accustomed with the procedure before performing each set of exercises. Subjects were instructed to repeat each gesture 5 times, for a 5sec period, interleaved with 5sec interruptions to avoid muscle fatigue. A supervisor assisted the subjects in wearing the Myo Armband to their dominant hand so that the device would be placed in a comfortable position for the subject and the device would detect the sEMG signals accurately. The sEMG was visible to the subject on a screen along with a picture of the hand-gesture that had to be performed.


<center>
<iframe id="video" width="560" height="315" src="https://www.youtube.com/embed/iJyF1SP5_r4?autoplay=1&mute=1&enablejsapi=1" frameborder="0" allow="encrypted-media" allowfullscreen=""></iframe>
</center>

---
## Hand Gesture Recognition via sEMG signals 

Since the results of this research where rather promising, a real-time hand gesture recognition model was developed, by designing a CNN and training it with the MyoUP dataset. More information regarding the implementation can be found here: <a href="https://github.com/tsagkas/sEMG-HandGestureRecognition">here</a>


<center>
<iframe id="video" width="560" height="315" src="https://www.youtube.com/embed/w98PkUeSu20?autoplay=1&mute=1&enablejsapi=1" frameborder="0" allow="encrypted-media" allowfullscreen=""></iframe>
</center>

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