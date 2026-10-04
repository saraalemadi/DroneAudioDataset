# DroneAudioDataset

This repo consists of drone audio dataset which has been recorded of drone propellers noise in an indoor environment by Sara Al-Emadi and artificially augmented with random noise clips. The drone audio dataset is part of 'Audio Based Drone Detection and Identification using Deep Learning' conference paper which can be found [here](https://www.researchgate.net/publication/332727775_Audio_Based_Drone_Detection_and_Identification_using_Deep_Learning?_iepl%5BviewId%5D=YyKGW9mH1GCJm0G3G9rvLrfM&_iepl%5BsingleItemViewId%5D=JVXYkvU0gGxrm0In7F3CGoIN&_iepl%5BpositionInFeed%5D=7&_iepl%5BhomeFeedVariantCode%5D=ncls&_iepl%5BactivityId%5D=1099278416220182&_iepl%5BactivityType%5D=person_add_publication&_iepl%5BactivityTimestamp%5D=1556529598&_iepl%5Bcontexts%5D%5B0%5D=homeFeed&_iepl%5BtargetEntityId%5D=PB%3A332727775&_iepl%5BinteractionType%5D=publicationTitle) . 

The noise clips that categorised as 'Unknown' in both binary and multiclass folders are used from the open-source project ESC: Dataset for Environmental Sound Classification by Karol J. Piczak (https://github.com/karoldvl/ESC-50) and the white noise from Speech Commands: A Dataset for Limited-Vocabulary Speech Recognition by Pete Warden (https://arxiv.org/pdf/1804.03209.pdf and https://www.tensorflow.org/tutorials/sequences/audio_recognition). In addition, we have created our own silence audio clip to balance the dataset.

### Licence

This dataset is provided **solely for educational and non-commercial academic research purposes**.

**The dataset may not be used, directly or indirectly, for military, defence, intelligence, security, weapons, surveillance, targeting, or other defence-related applications, regardless of whether the use is commercial or non-commercial.**

Commercial use requires prior written permission from the copyright holder. See [`LICENSE.md`](LICENSE.md) for the complete terms and conditions.

### Third-Party Materials

This repository contains audio material originating from third-party datasets, including **ESC-50** and **Speech Commands**. These materials are not covered by this licence and remain subject to their respective licences.

Users are responsible for identifying and complying with the applicable terms of those third-party datasets.

If you require permission for a use not covered by this licence, please contact the copyright holder.


### Citation

If you use this dataset in your research, please cite the following publication:

```bibtex
@INPROCEEDINGS{AlEmadi2019Audio,
  author    = {Sara A. Al-Emadi and Abdulla K. Al-Ali and Abdulaziz Al-Ali and Amr Mohamed},
  title     = {Audio Based Drone Detection and Identification Using Deep Learning},
  booktitle = {2019 International Wireless Communications and Mobile Computing Conference (IWCMC)},
  address   = {Tangier, Morocco},
  month     = jun,
  year      = {2019}
}
```


