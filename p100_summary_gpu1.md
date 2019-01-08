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


**syn-replicated-fp32-1gpus**

Config | 5120-Tesla_P100-SXM2-16GB |
:------:|:------:|
resnet50 |246.06 |
resnet152 |90.82 |
inception3 |151.59 |
inception4 |58.73 |
vgg16 |161.18 |
alexnet |3106.73 |
ssd300 |121.50 |


**syn-parameter_server-fp32-1gpus**

Config | 5120-Tesla_P100-SXM2-16GB |
:------:|:------:|
resnet50 |246.04 |
resnet152 |90.72 |
inception3 |151.66 |
inception4 |58.66 |
vgg16 |161.18 |
alexnet |3105.65 |
ssd300 |121.51 |


**syn-replicated-fp16-1gpus**

Config | 5120-Tesla_P100-SXM2-16GB |
:------:|:------:|
resnet50 |280.53 |
resnet152 |100.81 |
inception3 |161.33 |
inception4 |58.93 |
vgg16 |169.47 |
alexnet |3195.83 |
ssd300 |130.47 |


**syn-parameter_server-fp16-1gpus**

Config | 5120-Tesla_P100-SXM2-16GB |
:------:|:------:|
resnet50 |283.52 |
resnet152 |102.45 |
inception3 |163.07 |
inception4 |59.64 |
vgg16 |171.12 |
alexnet |3226.30 |
ssd300 |132.17 |
