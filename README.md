# SpatialAI-ECCV2024-Challenge

## Introduction
Our ECCV2024 workshop [SpatialAI](https://sites.google.com/view/spatial-ai-eccv24/home?authuser=0) opens a localization challenge.
We provide three different scenarios, each consisting of a reference map and a query sequence from the [4Seasons dataset](https://www.4seasons-dataset.com/)


| scenarios       | reference sequence              | query sequence                  |
| --------------- | ------------------------------- | ------------------------------- |
| neighborhood    | `recording_2020-10-07_14-53-52` | `recording_2021-05-10_18-26-26` |
| business_campus | `recording_2020-10-08_09-30-57` | `recording_2021-01-07_13-03-56` |
| countryside     | `recording_2020-06-12_11-26-43` | `recording_2021-01-07_14-03-57` |
  
 
Each reference map contains highly accurate reference poses. All sequences from the [4Seasons dataset](https://www.4seasons-dataset.com/) can be used as training data.

## Dataset Download
To download the challenge data and other sequences from the dataset, we refer to the [download page](https://www.4seasons-dataset.com/dataset).

## Dataset Structure
For details on the dataset structure, we refer to the following [documentation](https://www.4seasons-dataset.com/documentation).

## Libartipy Python Library
In this [repository](https://github.com/Artisense-ai/libartipy), you will find a set of tools for working with the 4Seasons dataset.

## Task
Each `relocalizationFile_recording_source_to_recording_target.txt` contains a list of first the keyframe from the source (reference) sequence and the query keyframe. 
The task is to provide the relative pose between the source and the query frame. 
Note that the relative pose is from cam0 of the reference sequence to cam0 of the query sequence, respectively. 
The `6DOF` poses are specified as translation `(t_x, t_y, t_z)`, and quaternion `(q_x, q_y, q_z, q_w)`.

## Submission
The ground truth is withheld for the test sequences.
To submit your results, please refer to the steps described on the [challenge webpage](https://sites.google.com/view/spatial-ai-eccv24/challenge_1?authuser=0).
