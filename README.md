[![MBARI](https://www.mbari.org/wp-content/uploads/2014/11/logo-mbari-3b.png)](http://www.mbari.org)
 
## <div align="left">About</div>

Tutorials written in [Jupyter Notebooks](https://jupyter.org) to guide you through both accessing and 
using the data in the AWS [pacific-sound registry](https://registry.opendata.aws/pacific-sound).
 
<details open>
<summary>Tutorials</summary>
 
## Data Notebooks
 
* [2kHz Data](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/data/PacificSound2kHz.ipynb) ✨ Recommended first step to learn more about the low-frequency data
* [16kHz Data](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/data/PacificSound16kHz.ipynb) ✨ Recommended first step to learn more about the low-mid-frequency data
* [256kHz Data](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/data/PacificSound256kHz.ipynb) ✨ Recommended first step to learn more about the raw 10-minute data
* [256kHz to 2kHz Decimation](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/data/PacificSound256kHzTo2kHzDecimate.ipynb) ✨ Recommended to learn about how the raw 10-minute data is decimated from 256kHz to 2Khz

## Research and Machine Learning Notebooks
 
  * Blue Whales
      * [Blue B call index 🐳](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/bluewhales/classify/blueB/PacificSoundBlueBCallIndex.ipynb) Study song occurrence using a signal processing method
      * [Blue A call classification 🐳](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/bluewhales/classify/blueA/PacificSoundClassifyBlueA.ipynb) Classify blue whale song A calls with a neural network model
      * Training a model in SageMaker  🚧
  * Humpback Whales
      * [Humpback whale song detection 🐳](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/humpbackwhales/detect/PacificSoundDetectHumpbackSong.ipynb) Detect humpback song with a neural network model
  * Shipping Noise
    - [Quantify shipping noise in the soundscape](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/shippingnoise/PacificSoundShippingNoiseAnalysis.ipynb) 🛳️ Apply international standards to measure shipping noise and its temporal variations.
 
## Listen Up
* [Full access to 16 kHz audio](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/listen/PacificSoundListen.ipynb) 🐬  Listen to example recordings of dolphins and whales, then pick any time to listen and explore.

</details>

## <div align="left">Documentation</div> 

See [pacific-sound](http://docs.mbari.org/pacific-sound) for the official,documentation.

## <div align="left">Quick Start </div>
 
### [Install in SageMaker](https://docs.mbari.org/pacific-sound/installation/sagemaker/)

### [Install in Colab](https://docs.mbari.org/pacific-sound/installation/colab/)
 
### Install in your computer

[**Python>=3.6.0**](https://www.python.org/) is required with the 
[requirements.txt](https://github.com/mbari-org/pacific-sound-notebooks/blob/master/docs/notebooks/requirements.txt).
 
The recommended way to run the notebooks is using the [Anaconda](https://www.anaconda.com/) environment

```bash
git clone https://github.com/mbari-org/pacific-sound-notebooks
cd pacific-sound-notebooks
```

If using a Mac 
```
brew install sox
```

If using Linux
```
apt-get install libsox-fmt-all libsox-dev
```

```
conda env create 
conda activate pacific-sound-notebooks
pip install ipykernel
python -m ipykernel install --user --name=pacific-sound-notebooks
jupyter notebook
```
</details>
