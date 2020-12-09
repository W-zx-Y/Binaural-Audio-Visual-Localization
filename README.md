# Binaural Audio-Visual Localization

This repository contains the pixel-level ground-truth locations of the sound sources for FAIR-Play dataset and YT-MUSIC dataset.

The ground-truth localization maps of the FAIR-Play dataset can be downloaded [[here]](https://www.dropbox.com/s/xhec895hc9qubhx/gt-FAIR-Play.zip?dl=0).
The ground-truth localization maps of the YT-MUSIC dataset can be downloaded [[here]](https://www.dropbox.com/s/xhec895hc9qubhx/gt-FAIR-Play.zip?dl=0).

The videos and binaural sounds for these two dataset can been found at [[FAIR-Play]](https://github.com/facebookresearch/FAIR-Play) and [[YT-MUSIC]](https://pedro-morgado.github.io/spatialaudiogen/)

For each video in the FAIR-Play dataset, we extract 102 frames with a sampling rate of 10 and manually label the sound sources of the middle frame (the fiftieth one). While for the YT-MUSIC dataset, we label the 250th frames.

If you find these data useful in your research, please cite:

        @inproceedings{wu2021binaural,
          title={Binaural Audio-Visual Localization},
          author={Wu, Xinyi and Wu, Zhenyao and Ju, Lili and Wang, Song},
          booktitle={AAAI},
          year={2021}
        }
       
        @inproceedings{gao2019visualsound,
          title={2.5D Visual Sound},
          author={Gao, Ruohan and Grauman, Kristen},
          booktitle={CVPR},
          year={2019}
        }
        
        @inproceedings{morgado2018self,
          title={Self-supervised generation of spatial audio for 360 video},
          author={Morgado, Pedro and Nvasconcelos, Nuno and Langlois, Timothy and Wang, Oliver},
          booktitle={Advances in Neural Information Processing Systems},
          pages={362--372},
          year={2018}
        }

        
