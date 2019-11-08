# GrayscaleVideoColorization

## Introduction
In this project, we wish to build a system that automatically colorizes grayscale videos and historical films,
in an effort to restore videos to their original colors. We propose a system that deals with two issues in
particular: colorizing frames in a video, and optimizing this process across multiple frames. We wish to
implement this using a pre-trained CNN model with optimizations for performance over video.

## Running the notebooks
   Create two virtual environments, to avoid dependency mismatches.

### SceneDetect
   ```
   conda create -n sd3.7 python=3.7.4
   conda activate sd3.7
   ```

   Install dependencies from `scenedetection/scenedetectenv_reqts.txt`
   ```
   pip install -r scenedetection/scenedetectenv_reqts.txt
   ```

   Run the notebook : `scenedetection/SceneDetect.ipynb`
 
### Caffe-Colorization
   ```
   conda create -n cc3.6.3 python=3.6.3
   conda activate cc3.6
   ```

   Install dependencies from `colorization/working_colorization_reqts.txt`
   ```
   pip install -r colorization/working_colorization_reqts.txt
   ```
   Run the notebook : `colorization/Caffe_Colorization_Notebook.ipynb`

## Misc

   If you're having trouble viewing the notebooks, copy the link to the `.ipynb` file into [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/)!
