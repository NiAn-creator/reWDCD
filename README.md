# Reimplementation of the Weakly Supervised Cloud Detection Network

In this project, we reproduce the weakly supervised deep learning-based cloud detection (WDCD) method [1].

The "train_WDCD.py" is used to train the classification model. In this work, we use the VGG16 as baseline following the WDCD paper setting. Specifically, we carefully reproduce the author produced global convolutional pooling module.

The "test_WDCD_clsAcc.py" is used to valid the classification performance.

The "test_WDCD_getCAM.py" is used to generate the cloud activation map (CAM) with the author proposed local pooling purnning (LPP) strategy.

The "test_WDCD_getoriCAM.py" is used to map the WDCD predictions to original spatial resolution.

The "test_WDCD_SegAcc.py" is used to valid the cloud detection accuracy.




[1] Li Y, Chen W, Zhang Y, et al., ?Accurate cloud detection in highresolution remote sensing imagery by weakly supervised deep learning,?
Remote Sensing of Environment, vol. 250, pp. 112045, 2020.

