Tutorials written in [Juptyer Notebooks](https://jupyter.org) are available to guide you through both accessing and 
using the data in the pacific-sound registry. A live preview of these notebooks can be found by clicking any of the links 
below, or by navigating through the menus by topic, e.g. Data Access, Blue Whales, etc.

These notebooks can be used in [SageMaker](/docs/installation/sagemaker.md), [Colab](/docs/installation/colab.md) or [on your computer](/docs/installation/local.md).

All audio files in this archive use the UTC time standard.
Start time is encoded in the file names and included in the metadata for each daily decimated file.

## Data Access and Decimation Notebooks

---

* [2kHz Data](notebooks/data/PacificSound2kHz.ipynb) ✨ Recommended first step to learn more about the low-frequency data
* [16kHz Data](notebooks/data/PacificSound16kHz.ipynb) ✨ Recommended first step to learn more about the low-mid-frequency data
* [256kHz Data](notebooks/data/PacificSound256kHz.ipynb) ✨ Recommended first step to learn more about the raw 10-minute data
* [256kHz to 2kHz Decimation](notebooks/data/PacificSound256kHzTo2kHzDecimate.ipynb) ✨ Recommended to learn about how the raw 10-minute data is decimated from 256kHz to 2Khz

## Research and Machine Learning Notebooks

---

  * Blue Whales
      * [Blue B call index 🐳](notebooks/bluewhales/classify/blueB/PacificSoundBlueBCallIndex.ipynb) Study song occurrence using a signal processing method
      * [Blue A call classification 🐳](notebooks/bluewhales/classify/blueA/PacificSoundClassifyBlueA.ipynb) Classify blue whale song A calls with a neural network model
  * Humpback Whales
      * [Humpback whale song detection 🐳](notebooks/humpbackwhales/detect/PacificSoundDetectHumpbackSong.ipynb) Detect humpback song with a neural network model
  * Fin Whales
    * [Fin whale call index 🐳](notebooks/bluewhales/classify/blueB/PacificSoundBlueBCallIndex.ipynb) Fin whale song occurrence using a signal processing method
  * Shipping Noise
    - [Quantify shipping noise in the soundscape](notebooks/shippingnoise/PacificSoundShippingNoiseAnalysis.ipynb) 🛳️ Apply international standards to measure shipping noise and its temporal variations.

---

## Listen Up

* [Full access to 16 kHz audio](notebooks/listen/PacificSoundListen.ipynb) 🐬  Listen to example recordings of dolphins and whales, then pick any time to listen and explore.

