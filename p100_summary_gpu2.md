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

Config | 5120-Tesla_P100-SXM2-16GB |
:------:|:------:|
resnet50 |475.05 |
resnet152 |175.85 |
inception3 |297.33 |
inception4 |111.18 |
vgg16 |257.45 |
alexnet |4831.39 |
ssd300 |235.17 |


**syn-parameter_server-fp32-2gpus**

Config | 5120-Tesla_P100-SXM2-16GB |
:------:|:------:|
resnet50 |477.10 |
resnet152 |168.07 |
inception3 |293.36 |
inception4 |109.62 |
vgg16 |255.26 |
alexnet |5197.74 |
ssd300 |232.04 |


**syn-replicated-fp16-2gpus**

Config | 5120-Tesla_P100-SXM2-16GB |
:------:|:------:|
resnet50 |551.11 |
resnet152 |197.43 |
inception3 |320.62 |
inception4 |115.07 |
vgg16 |304.53 |
alexnet |5623.62 |
ssd300 |255.80 |


**syn-parameter_server-fp16-2gpus**

Config | 5120-Tesla_P100-SXM2-16GB |
:------:|:------:|
resnet50 |541.45 |
resnet152 |190.99 |
inception3 |300.77 |
inception4 |111.77 |
vgg16 |268.84 |
alexnet |5356.96 |
ssd300 |252.46 |
