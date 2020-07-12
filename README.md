# TensorFlow int8 Inference
This code example provides a sample code to run ResNet50, IneptionV4 & ResNet101 low precision inference on Intel's pretrained int8 model

## Key implementation details
The example uses Intel's pretrained model published as part of Intel Model Zoo. The example also illustrates how to utilize TensorFlow and MKL run time settings to maximize CPU performance on ResNet50, IneptionV4 & ResNet101 workload

## Pre-requirement

TensorFlow is ready for use once you finish the Intel AI Analytics Toolkit installation, and have run post installation script.

You can refer to the oneAPI [main page](https://software.intel.com/en-us/oneapi) for toolkit installation, and the Toolkit [Getting Started Guide for Linux](https://software.intel.com/en-us/get-started-with-intel-oneapi-linux-get-started-with-the-intel-ai-analytics-toolkit) for post-installation steps and scripts.

## Activate the Enviornment

1. Make an account at [oneAPI](https://inteliotgnew.secure.force.com/devcloudsignup).
2. Launch the jupyter notebook in browser.
3. Select Kernel-> 'TensorFlow AI'.
4. Git Clone this Repository and run the Notebook.

## License  
This code sample is licensed under MIT license. \n
Credits: Intel Model Zoo