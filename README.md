# YoLoV7_Torch

Ning Xu, Timothy Guo, and Oliver Hahn

## the paper can be found at : TBA
## the video can be found at : https://www.youtube.com/c/isaac2math

* **Re: Chris Huge's folking request : Github DOES NOT allow folking all 5 packages simultaneously (open MM, EricSheng, WongKinYiu, AlexeyAB, and his). Since he insists of folking, to be fair with all sources, we have rewritten the package to make sure that there is 0% of code and data cited from his pacakge.**

* This package is based on YoLov7 by https://github.com/WongKinYiu/yolov7 and directly modified from several packages including YoLov5 by Open MM lab, YoLov4 by AlexeyAB, and YoLov7 by https://github.com/WongKinYiu/yolov7, and the CudaCpp training module from Eric Sheng.
* This package is for the purpose of deep learning education, research demostration, and proof of idea/value only;
* For production, the CUDA C++ is always the first recommendation. 
  * Benchmark : the repo is tested using 24G Nvidia 3090ti and 64G RAM for 4K image obj detection. When the training size reaches 5 millions and test size reaches 0.2 million, the VRAM and RAM usage quickly increase linearly.
  * If you are looking for packages for serious production, see my other repo https://github.com/isaac2math/YoLoV7_CudaCpp

