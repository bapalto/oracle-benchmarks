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

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |371.74 |
resnet152 |130.95 |
inception3 |244.11 |
inception4 |92.15 |
vgg16 |239.26 |
alexnet | |
ssd300 |183.84 |


**syn-parameter_server-fp32-1gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |367.02 |
resnet152 |129.90 |
inception3 |241.71 |
inception4 |91.57 |
vgg16 |237.26 |
alexnet |4500.92 |
ssd300 |183.79 |


**syn-replicated-fp16-1gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |681.17 |
resnet152 |241.52 |
inception3 |424.68 |
inception4 |152.17 |
vgg16 |466.53 |
alexnet |7709.26 |
ssd300 |318.36 |


**syn-parameter_server-fp16-1gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |690.76 |
resnet152 |247.51 |
inception3 |429.36 |
inception4 |157.84 |
vgg16 |474.13 |
alexnet |7833.40 |
ssd300 |324.79 |
