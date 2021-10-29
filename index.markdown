---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


| ![](/assets/images/main.png)|
|:--:|
| *The eye contact detection for autonomous agents is a crucial and non-trivial task - Image taken from: https://jooinn.com/people-walking-on-pedestrian-lane-during-daytime.html - Image under Creative Commons Licence* |

# Introduction

---

<p></p>
To the best of our knowledge, the *eye contact classification* task applied to autonomous agents is underestimated in the current literature. This task can be crucial for a large variety of autnomous agents including autonomous vehicles and social robots interacting with humans. These agents should change their behaviour depeding on this modality, for e.g. an autonomous car should rapidly take an action if several pedestrians are looking at it, or a social robot should change its behaviour when somebody is looking at it. 


| ![](/assets/images/looking_gif.gif)|
|:--:|
| *Predictions from our model on the JRDB test set* |


# LOOK Dataset
---

<p></p>
The dataset consists of a set of selected scenes from different opensource autonomous driving dataset. We use the following datasets and annotate them:
* [JRDB](https://jrdb.stanford.edu/) 
* [Nuscenes](https://www.nuscenes.org/)
* [Kitti](http://www.cvlibs.net/datasets/kitti/)

Find more information at the [dataset](/dataset/) section. 

# Annotations
---
<p></p>

The human annotations have been done using Amazon Mechanical Turk, we aggregate the results from several human annotators. Find more information about the annotation process at the [dataset](/dataset/) section.
