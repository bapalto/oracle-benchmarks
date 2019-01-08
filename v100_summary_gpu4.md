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


**syn-replicated-fp32-4gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |1156.48 |
resnet152 |382.41 |
inception3 |737.50 |
inception4 |237.86 |
vgg16 |819.34 |
alexnet |15273.02 |
ssd300 |559.69 |


**syn-parameter_server-fp32-4gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 | |
resnet152 |355.28 |
inception3 |726.18 |
inception4 |236.34 |
vgg16 |858.57 |
alexnet |15531.73 |
ssd300 |580.26 |


**syn-replicated-fp16-4gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |1855.67 |
resnet152 |642.68 |
inception3 |1129.31 |
inception4 |403.30 |
vgg16 |1596.30 |
alexnet |26346.00 |
ssd300 |826.35 |


**syn-parameter_server-fp16-4gpus**

Config | 8167M-Tesla_V100-SXM2-16GB |
:------:|:------:|
resnet50 |1905.39 |
resnet152 |666.99 |
inception3 |1178.99 |
inception4 |406.51 |
vgg16 |1546.83 |
alexnet |24977.06 |
ssd300 |874.71 |
