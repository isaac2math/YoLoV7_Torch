# YoLoV7_Torch

Ning Xu, Timothy Guo, Oliver Hahn, and Adam Roff

## the research paper can be found at : TBA
## the intro video can be found at : TBA

# IP justice warriors, if you plan to pin any accusation, please note that :

* **All packages have been properly cited in the paper**.
* This repo is a university public research project and not for any commercial profits purpose;
* We currently can only show the base, raw results, and a ipynb demo before the acceptence.
* The full packages will be revealed right after the acceptence.
* ~~The data adaptors, front/demo ipynb, traning/testing/validation scripts are directly modified from Chris Hughe~~ 
* The data adaptors, front/demo ipynb, traning/testing/validation scripts are directly modified from WongKinYiu and open MM lab. The core are coded by us.
* At the current stage, the original core from WongKinYiu and open MM lab are shown as a place holder **for baseline reproduction ONLY**. 

# If you do not wish your code to be a part of the uni research project, please let us know and I am more than happy to purge it out.

* **Re: Chris Hughes' folking request : Github DOES NOT allow folking all 5 packages simultaneously (open MM, EricSheng, WongKinYiu, AlexeyAB, and his). To be fair with all sources, we have rewritten the package to make sure that there is 0% of code (data adaptors, front/demo ipynb, a training script) and data cited from his pacakge.**

---

* This package is based on YoLov7 by https://github.com/WongKinYiu/yolov7 and directly modified from several packages including YoLov5 by Open MM lab, YoLov4 by AlexeyAB, and YoLov7 by https://github.com/WongKinYiu/yolov7, and the CudaCpp training module from Eric Sheng.
* This package is for the purpose of deep learning education, research demostration, and proof of idea/value only;
* For production, the CUDA C++ is always the first recommendation. 
  * Benchmark : the repo is tested using 24G Nvidia 3090ti and 64G RAM for 4K image obj detection. When the training size reaches 5 millions and test size reaches 0.2 million, the VRAM and RAM usage quickly increase linearly.
  * If you are looking for packages for serious production, see my other repo https://github.com/isaac2math/YoLoV7_CudaCpp

