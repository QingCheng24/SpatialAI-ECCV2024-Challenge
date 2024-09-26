# SpatialAI-ECCV2024-Challenge

## Introduction
Our ECCV2024 workshop [SpatialAI](https://sites.google.com/view/spatial-ai-eccv24/home?authuser=0) opens a localization challenge.
We provide three different scenarios, each consisting of a reference map and a query sequence from the [4Seasons dataset](https://cvg.cit.tum.de/data/datasets/4seasons-dataset)


| scenarios       | reference map sequence              | query sequence                  |
| --------------- | ------------------------------- | ------------------------------- |
| neighborhood    | `recording_2020-10-07_14-53-52` | `recording_2021-05-10_18-26-26` |
| business_campus | `recording_2020-10-08_09-30-57` | `recording_2021-01-07_13-03-56` |
| countryside     | `recording_2020-06-12_11-26-43` | `recording_2021-01-07_14-03-57` |
  
 
Each reference map contains highly accurate reference poses. All sequences from the [4Seasons dataset](https://cvg.cit.tum.de/data/datasets/4seasons-dataset) can be used as training data.

## Dataset Download
### Reference map sequences 
- recording_2020-10-07_14-53-52
    - [imu_gnss](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-07_14-53-52/recording_2020-10-07_14-53-52_imu_gnss.zip)
    - [point_clouds](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-07_14-53-52/recording_2020-10-07_14-53-52_point_clouds.zip)
    - [reference_poses](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-07_14-53-52/recording_2020-10-07_14-53-52_reference_poses.zip)
    - [images_distorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-07_14-53-52/recording_2020-10-07_14-53-52_stereo_images_distorted.zip)
    - [images_undistorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-07_14-53-52/recording_2020-10-07_14-53-52_stereo_images_undistorted.zip)


- recording_2020-10-08_09-30-57
    - [imu_gnss](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-08_09-30-57/recording_2020-10-08_09-30-57_imu_gnss.zip)
    - [point_clouds](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-08_09-30-57/recording_2020-10-08_09-30-57_point_clouds.zip)
    - [reference_poses](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-08_09-30-57/recording_2020-10-08_09-30-57_reference_poses.zip)
    - [images_distorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-08_09-30-57/recording_2020-10-08_09-30-57_stereo_images_distorted.zip)
    - [images_undistorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-10-08_09-30-57/recording_2020-10-08_09-30-57_stereo_images_undistorted.zip)


- recording_2020-06-12_11-26-43

    - [imu_gnss](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-06-12_11-26-43/recording_2020-06-12_11-26-43_imu_gnss.zip)
    - [point_clouds](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-06-12_11-26-43/recording_2020-06-12_11-26-43_point_clouds.zip)
    - [reference_poses](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-06-12_11-26-43/recording_2020-06-12_11-26-43_reference_poses.zip)
    - [images_distorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-06-12_11-26-43/recording_2020-06-12_11-26-43_stereo_images_distorted.zip)
    - [images_undistorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2020-06-12_11-26-43/recording_2020-06-12_11-26-43_stereo_images_undistorted.zip)

### Query sequences     
- recording_2021-05-10_18-26-26
    - [imu](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2021-05-10_18-26-26/recording_2021-05-10_18-26-26_imu.zip)
    - [images_distorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2021-05-10_18-26-26/recording_2021-05-10_18-26-26_stereo_images_distorted.zip)
    - [images_undistorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2021-05-10_18-26-26/recording_2021-05-10_18-26-26_stereo_images_undistorted.zip)

- recording_2021-01-07_13-03-56
    - [imu](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2021-01-07_13-03-56/recording_2021-01-07_13-03-56_imu.zip)
    - [images_distorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2021-01-07_13-03-56/recording_2021-01-07_13-03-56_stereo_images_distorted.zip)
    - [images_undistorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2021-01-07_13-03-56/recording_2021-01-07_13-03-56_stereo_images_undistorted.zip)

- recording_2021-01-07_14-03-57

    - [imu](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2021-01-07_14-03-57/recording_2021-01-07_14-03-57_imu.zip)
    - [images_distorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2021-01-07_14-03-57/recording_2021-01-07_14-03-57_stereo_images_distorted.zip)
    - [images_undistorted](https://vision.cs.tum.edu/webshare/g/4seasons-dataset/dataset/recording_2021-01-07_14-03-57/recording_2021-01-07_14-03-57_stereo_images_undistorted.zip)


## Dataset Structure
For details on the dataset structure, we refer to the following [documentation](https://github.com/pmwenzel/mlad-eccv2020).

## Libartipy Python Library
In this [repository](https://github.com/Artisense-ai/libartipy), you will find a set of tools for working with the 4Seasons dataset.

## Task
Each `relocalizationFile_recording_source_to_recording_target.txt` contains a list of first the keyframe from the source (reference) sequence and the query keyframe. 
The task is to provide the relative pose between the source and the query frame. 
Note that the relative pose is from cam0 of the reference sequence to cam0 of the query sequence, respectively. 
The `6DOF` poses are specified as translation `(t_x, t_y, t_z)`, and quaternion `(q_x, q_y, q_z, q_w)`.

## Submission
The ground truth is withheld for the test sequences.
Please submit your results as a single zip file. The results for each re-localization file must be stored in a separate txt file in the archive's root folder. The file name must be exactly like the provided ones (case-sensitive).

The file format should be a text file containing one re-localization pair per line. Each line must contain 9 values:
`source_kf_id target_kf_id t_x t_y t_z q_x q_y q_z q_w`

To submit your results, you will have to send an email with a single zip file which contains the re-localization results for the 3 provided files.
Send to: spatialai-eccv2024@googlegroups.com.

## Deadlines
Challenge deadline: Extended to 24:00 (CEST) Nov. 30, 2024

For questions, please send an email to: spatialai-eccv2024@googlegroups.com.
