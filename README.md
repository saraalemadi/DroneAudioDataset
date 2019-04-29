# DroneAudioDataset

This repo consists of drone audio dataset which has been recorded of drone propellers noise in an indoor environment by Sara Al-Emadi and artificially augmented with random noise clips. The drone audio dataset is part of 'Audio Based Drone Detection and Identification using Deep Learning' conference paper which can be found [here](https://www.researchgate.net/publication/332727775_Audio_Based_Drone_Detection_and_Identification_using_Deep_Learning?_iepl%5BviewId%5D=YyKGW9mH1GCJm0G3G9rvLrfM&_iepl%5BsingleItemViewId%5D=JVXYkvU0gGxrm0In7F3CGoIN&_iepl%5BpositionInFeed%5D=7&_iepl%5BhomeFeedVariantCode%5D=ncls&_iepl%5BactivityId%5D=1099278416220182&_iepl%5BactivityType%5D=person_add_publication&_iepl%5BactivityTimestamp%5D=1556529598&_iepl%5Bcontexts%5D%5B0%5D=homeFeed&_iepl%5BtargetEntityId%5D=PB%3A332727775&_iepl%5BinteractionType%5D=publicationTitle) . 

The noise clips that categorised as 'Unknown' in both binary and multiclass folders are used from the open-source project ESC: Dataset for Environmental Sound Classification by Karol J. Piczak (https://github.com/karoldvl/ESC-50) and the white noise from Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition by Pete Warden (https://arxiv.org/pdf/1804.03209.pdf and https://www.tensorflow.org/tutorials/sequences/audio_recognition). In addition, we have created our own silence audio clip to balance the dataset.

## Attribution ##

If you use this dataset in your research, cite via the following BibTeX:

@INPROCEEDINGS{AlEm1906:Audio,

AUTHOR=”Sara A Al-Emadi and Abdulla K Al-Ali and Abdulaziz Al-Ali and Amr Mohamed”,

TITLE=”Audio Based Drone Detection and Identification using Deep Learning”,

BOOKTITLE=”IWCMC 2019 Vehicular Symposium (IWCMC-VehicularCom 2019)”,

ADDRESS=”Tangier, Morocco”,

DAYS=23,

MONTH=jun,

YEAR=2019,
}

