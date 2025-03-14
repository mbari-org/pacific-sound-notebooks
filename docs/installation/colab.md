**Colaboratory** is also known as Colab. It is a Google Research product that allows one to write code in a web browser.
Colab is free with limitations in compute and memory. 
Upgrading to [Colab Pro/Pro+](https://colab.research.google.com/signup) allows for more compute and memory for a fee. 
Some, but not all of these notebooks may run in the Colab environment. 

To use Colab

1. Setup a gmail account if you don't already have one.
2. Launch the notebook by clicking on one of the links below:

| Notebook                                                                                                                                                                                       | Description                                                                                   |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------
| [PacificSound2kHz.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/data/PacificSound2kHz.ipynb)	                                   | Low-frequency data access and spectrogram calibration                                         |
| [PacificSound16kHz.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/data/PacificSound16kHz.ipynb)                                  | Low-mid-frequency data access and spectrogram calibration                                     |
| [PacificSound256kHz.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/data/PacificSound256kHz.ipynb)                                | Raw recording data access and spectrogram calibration                                         |
| [PacificSoundListen.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/listen/PacificSoundListen.ipynb)                              | Listen to example recordings of dolphins and whales, then pick any time to listen and explore |
| [PacificSound256kHzTo2kHzDecimate.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/data/PacificSound256kHzTo2kHzDecimate.ipynb)    | Recommended to learn about how the raw 10-minute data is decimated from 256kHz to 2Khz        | |
| [PacificSoundClassifyBlueA.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/bluewhales/classify/blueA/PacificSoundClassifyBlueA.ipynb) | Blue whale A call classification using a trained neural network model                         |
| [PacificSoundBlueBCallIndex.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/bluewhales/classify/blueB/PacificSoundBlueBCallIndex.ipynb) | Signal processing method for computing Blue whale B call index                           |
| [PacificSound_FinCallindex.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/finwhales/PacificSound_FinCallindex.ipynb)        | Signal processing method for computing Fin whale call index                            |
| [PacificSoundShippingNoiseAnalysis.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/shippingnoise/PacificSoundShippingNoiseAnalysis.ipynb) | Signal processing methods for studying temporal variations in shipping noise                  |
| [PacificSoundDetectHumpbackSong.ipynb](https://colab.research.google.com/github/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/humpbackwhales/detect/PacificSoundDetectHumpbackSong.ipynb) | Humpback song detection using a trained neural network model                                  ||

**Important**  - there is a 24-hour runtime limit for Colab. This can be an issue for some applications
such as training deep-learning models for sound detection and/or classification. 