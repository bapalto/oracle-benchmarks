SUMMARY
===
| model | input size | param mem | feat. mem | flops  |
|-------|------------|--------------|----------------|-------------|
| resnet-50 | 224 x 224 | 98 MB | 103 MB | 4 BFLOPs |
| resnet-152 | 224 x 224 | 230 MB | 219 MB | 11 BFLOPs |
| inception-v3 | 299 x 299 | 91 MB | 89 MB | 6 BFLOPs |
| vgg-vd-19 | 224 x 224 | 548 MB | 63 MB | 20 BFLOPs |
| alexnet | 227 x 227 | 233 MB | 3 MB | 1.5 BFLOPs |
| ssd-300 | 300 x 300 | 100 MB | 116 MB | 31 GFLOPS |


**syn-replicated-fp32-2gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |649.42 |
resnet152 |223.11 |
inception3 |438.14 |
inception4 |158.11 |
vgg16 |434.51 |
alexnet |8214.27 |
ssd300 |329.62 |


**syn-parameter_server-fp32-2gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |661.47 |
resnet152 |217.46 |
inception3 |432.86 |
inception4 |152.39 |
vgg16 |438.06 |
alexnet |8423.94 |
ssd300 |331.02 |


**syn-replicated-fp16-2gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |1130.36 |
resnet152 |385.66 |
inception3 |720.13 |
inception4 |233.22 |
vgg16 |838.18 |
alexnet |13490.01 |
ssd300 |505.07 |


**syn-parameter_server-fp16-2gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |1159.61 |
resnet152 |384.21 |
inception3 |702.75 |
inception4 |237.46 |
vgg16 |800.26 |
alexnet |14011.10 |
ssd300 |532.36 |
