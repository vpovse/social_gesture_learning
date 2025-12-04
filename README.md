# Social gesture learning

GESRes dataset : https://osf.io/9zkfm/files and rename as GESRes_dataset.zip

Jester dataset : https://www.qualcomm.com/developer/software/jester-dataset/downloads
- Download the 3 files from with a another browser than firefox or chrome (use for exemple Brave)
- Concatenate the 3 files with : _cat 20bnjester-v1-00 20bnjester-v1-01 20bnjester-v1-02 > jester_full.tgz_
- Extract the main file then : _tar -xzf jester_full.tgz_

## GESRes dataset
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
To clean and filter GESRes dataset, use _filter_jester_dataset.ipynb_

Labels in _GESRes_filtered_gestures_ directory: 
- Doing other things
- Drumming Fingers
- No gesture
- Pulling Hand In
- Pulling Two Fingers In
- Pushing Hand Away
- ...etc