# SoundClassification

# Background

The automatic classification of environmental sound is a growing research field with multiple applications to largescale, content-based multimedia indexing and retrieval. In particular, the sonic analysis of urban environments is the subject of increased interest, partly enabled by multimedia sensor networks, as well as by large quantities of online multimedia content depicting urban scenes.

# Challenges

There are primarily two major challenges with urban sound research namely:

- Lack of labeled audio data. Previous work has focused on audio from carefully produced movies or television tracks from specific environments such as elevators or office spaces and on commercial or proprietary datasets .

- Lack of common vocabulary when working on urban sounds.This means the classification of sounds into semantic groups may vary from study to study, making it hard to compare results so the objective of this notebook is to address the above two mentioned challenges.

# Dataset

The dataset is called UrbanSound and contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes. The dataset contains 8732 sound excerpts (<=4s) of urban sounds from 10 classes, namely: Air Conditioner, Car Horn, Children Playing, Dog bark, Drilling Engine, Idling, Gun Shot, Jackhammer, Siren, Street Music. The attributes of data are as follows: 
- ID: unique ID of sound excerpt,
- class,
- type of sound.

Please consult this site to have more information about the dataset: https://urbansounddataset.weebly.com/

# Objective

The objective of this project is train a CNN model that will automate classification Urban sounds.
