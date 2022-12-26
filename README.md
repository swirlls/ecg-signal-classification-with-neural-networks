## Overview

Developed two models with residual connection for ECG signal classification; One implemented MLP, and the other implemented CNN.

`Keras` for both models

## Procedure

* **For normalization layers**, a feasible normalization method from GroupNorm, InstanceNorm, BatchNorm, and LayerNorm was selected.

* **For average pooling**, the pooling window size was fixed to 2 and the stride was fixed to 2 as well with optional padding if necessary. 

* Overall accuracy should be greater than 85% - accuracy on the test set is about ~90%

Diagram of layout for MLP:

![image](https://user-images.githubusercontent.com/98493736/209571937-a643e370-2458-4d38-91ae-5fdab3464ca0.png)

Diagram of layout for CNN:

![image](https://user-images.githubusercontent.com/98493736/209571955-32f8f88d-ae76-4d30-a2cf-27ec70b89db1.png)
