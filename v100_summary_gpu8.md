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


**syn-replicated-fp32-8gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |1834.01 |
resnet152 |548.47 |
inception3 |1446.95 |
inception4 |384.92 |
vgg16 |592.56 |
alexnet |9184.29 |
ssd300 |1020.29 |


**syn-parameter_server-fp32-8gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |1912.38 |
resnet152 |503.49 |
inception3 |1373.01 |
inception4 |353.55 |
vgg16 |695.52 |
alexnet |11097.01 |
ssd300 |987.00 |


**syn-replicated-fp16-8gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |3444.67 |
resnet152 |990.91 |
inception3 |2462.67 |
inception4 |680.22 |
vgg16 |1080.10 |
alexnet |17751.75 |
ssd300 |1690.84 |


**syn-parameter_server-fp16-8gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |2471.12 |
resnet152 |724.56 |
inception3 |2039.57 |
inception4 |480.84 |
vgg16 |669.98 |
alexnet |11782.82 |
ssd300 |1330.54 |
