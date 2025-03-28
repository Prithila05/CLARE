# CLARE

This study presents a novel multimodal dataset on Cognitive Load Assessment in REaltime (CLARE). The dataset contains physiological and gaze data from 24 participants with self-reported cognitive load scores as a ground-truth label. The dataset consists of four modalities, namely, Electrocardiography (ECG), Electrodermal Activity (EDA), Electroencephalogram (EEG), and Gaze tracking. To map diverse levels of mental load on participants during experiments, each participant completed four nine-minutes sessions on the MATB-II software with varying levels of complexity. During the experiment, the participants reported their cognitive load every 10-second.

# Sensor placement
This figure shows the placement of the sensors.
![Alt text](/Figures/sensor_placement_clare.JPG?raw=true "Optional Title")

# Download dataset

* Download the CLARE dataset from [here](https://borealisdata.ca/privateurl.xhtml?token=dcf15457-ea9e-41f6-b541-5ab22db4b26b).
* The structure of the dataset would be:

```    
CLARE
    |----EEG 
         |----participant_ID_1
                      |----eeg_data_exp_0
                      |----eeg_baseline_0
                      .
                      .
                      .
                      |----eeg_data_exp_3
                      |----eeg_baseline_3
         .
         .
         .
         |----participant_ID_21
    |----EDA
    |----ECG
    |----Gaze
    |----Labels
```
