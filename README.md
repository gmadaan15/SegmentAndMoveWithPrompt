# SegmentAndMoveWithPrompt
small application for segmenting an object from an image through text prompt and moving it in x and y direction by number of pixels.

# First Task: Segment using command prompt.
This is done using the SegmentThroughPrompt Notebook. This can be directly run by uploading in colab. Can be run using only cpu but takes time.

# Second Task : Remove, and overlay on the new image at a new position.
This is done with the RemoveAndMove Notebook. There are errors there because the gpu quota on colab was over. But hae made sure that the whole notebook generates output with available gpu. One extra point to note here is that we downgrade the python version to 3.9 because the model used was not working with the default 3.10 version. Could be corrected if manual download and uploading of packages are done. But because was running on colab so preferred to change the version.
