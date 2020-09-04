# jxnx
Jetson Xavier NX
Jetson Xavier NX Developer Kit
Key Features:
384 CUDA cores (parallel processors, single value multiplication per GPU clock), 48 Tensor cores(specialised for matrix operations, less precision, matrix multiplication per GPU clock), 2 Deep Learning Accelerators.
RAM:8GB 128-bit LPDDR4x	51.2GB/s
Power: 10 – 15 Watts
Storage: MicroSD, can add external NVMe SSD


Really nice for detecting usage of face mask, image processing -> taking images as input. Average RGB image provides around 1000 x 1000 pixels resulting to 3 million input features (just for the first layer of CNN), considering all the layers it will require a lot of operations. Using this device, capable of doing up to 21 TOPs, CNN would be faster and more efficient.
Jetson Xavier enables us to run several NN in parallel (faster processing can run different models at the same time), and process data from multiple high-resolution sensors.
Cloud Native Development (container-based environment, each part of the app is packaged in its own container), individual applications and services can be packaged as Docker containers and individually distributed and updated via the cloud.


JetPack 4.4 SDK 
cuDNN
provides high-performance primitives for deep learning frameworks. It provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers.
TensorRT
high performance deep learning inference runtime for image classification, segmentation, and object detection neural networks. It includes a deep learning inference optimizer and runtime that delivers low latency and high-throughput for deep learning inference applications.	
DeepStream
delivers a complete streaming analytics toolkit for AI-based multi-sensor processing, video and image understanding.
Isaac SDK
accelerate robot development by making it easier to add artificial intelligence (AI) for perception and navigation into robots.
