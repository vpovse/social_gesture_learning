# Social gesture learning

GESRes dataset : https://osf.io/9zkfm/files and rename as GESRes_dataset.zip

Jester dataset : https://www.qualcomm.com/developer/software/jester-dataset/downloads
- Download the 3 files from with a another browser than firefox or chrome (use for exemple Brave)
- Concatenate the 3 files with : _cat 20bnjester-v1-00 20bnjester-v1-01 20bnjester-v1-02 > jester_full.tgz_
- Extract the main file then : _tar -xzf jester_full.tgz_

## GESRes dataset

The GESRes (Gesure Exploration and Synthesis Resource) dataset contains annotated gesture data with accompanying metadata. The dataset is designed to support gesture analysis in psychology, linguistics, and computer science.

To clean and filter GESRes dataset, use _filter_GESRes_dataset.ipynb_

Labels in _GESRes_filtered_gestures_ directory: 
- clasp
- cup
- finger
- hand
- hold
- knock
- one
- point
- present
- punch
- show
- soft
- wave

## Jester dataset

The Jester gesture recognition dataset includes 148,092 labeled video clips of humans performing basic, pre-defined hand gestures in front of a laptop camera or webcam. It is designed for training machine learning models to recognize human hand gestures like sliding two fingers down, swiping left or right and drumming fingers.

The clips cover 27 different classes of human hand gestures, split in the ratio of 8:1:1 for training, development and testing. The dataset also includes two “no gesture” classes to help the network distinguish between specific gestures and unknown hand movements.

To clean and filter GESRes dataset, use _filter_jester_dataset.ipynb_

Labels in _GESRes_filtered_gestures_ directory: 
- Drumming Fingers
- Pulling Hand In
- Pulling Two Fingers In
- Pushing Hand Away
- ...etc