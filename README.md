# GrayscaleVideoColorization

## Introduction
In this project, we wish to build a system that automatically colorizes grayscale videos and historical films,
in an effort to restore videos to their original colors. We propose a system that deals with two issues in
particular: colorizing frames in a video, and optimizing this process across multiple frames. We wish to
implement this using a pre-trained CNN model with optimizations for performance over video.

## Proposed Solution
Our initial plan was to build on the approach taken by Zhang et.al. to solve the problem of video
colorization by:
- Adaptively clustering similar frames in the video, find a representative frame and generate its color
map.
- Using an LSTM network to propagate color information across successive frames within a cluster.
- Processing individual clusters in parallel and stitching the results together to generate a fully colored
output video.

## Results
We have obtained the following results on different frames of a video:
![Alt text](/data/images/Cheetah.png?raw=true "Figure 1: Sample frames extracted from video and the colored output from our model")


