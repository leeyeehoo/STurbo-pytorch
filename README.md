# SiamVGG

SiamVGG adopts SiamFC as the baseline approach. It applies a fully-convolutional Siamese network to allocate the target in the search region. SiamVGG uses modified VGG-16 network as the backbone. The network is trained offline on both ILSVRC VID dataset and Youtube-BB dataset end-to-end. The model SiamVGG gets significant improvements when compare to the original SiamFC.

## Getting Started

### Hardware Environment

* System: ubuntu 14.04 LTS

* Memory: 15.6 GiB

* Processor: Intel Core i7-7700K CPU @4.20GHz * 8

* Graphics: GeForce GTX 1080 Ti/PCle/SSE2

* OS type: 64-bit

### Prerequisites

* CUDA compilation tools version: release 8.0, V8.0.61

* NVIDIA driver version: 390.59

* MATLAB version: 9.3.0.713579 (R2017b)

* Please use Anaconda environment for the test
  
  * python                    2.7.13
  
  * pytorch                   0.2.0
  
  * torchvision               0.1.8
  
  * pillow                    4.1.1
  
  * numpy                     1.12.1
  
  * hdf5                      1.8.17
  
