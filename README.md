# TrackUtils
A collection of usefull scripts for detecting and tracking things

How to:
1. Frames are extracted using ffmpeg (.png format). See here for more help [ffmpeg tutorial](https://amor.cms.hu-berlin.de/~francisf/assets/content/pdf/ffmpeg_tutorial_02042020.pdf)
2. Images are uploaded and keypoint annotations are done using [makesense.ai](https://www.makesense.ai/)
3. Small alteration are done to adjust for class identity (keypointCSV2COCO.ipynb)
4. Keypoints are converted to COCO format (keypointCSV2COCO.ipynb)
5. COCO dataset is uploaded to Google Colab, where detectron2 is trained on the custom dataset and applied to new images.

Directory overview:

- notebooks
-- keypointCSV2COCO.ipynb 
-- keypoint_detectron2.ipynb
