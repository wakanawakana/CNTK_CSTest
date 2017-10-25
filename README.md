# CNTK_CSTest
Use CNTK from C #

This code is for checking whether various DeepLearning can be executed with CNTK CPU and GPU version

##Build Staps

- nuget CNTK.CPUONLY
- nuget CNTK.GPU

##Execute Staps
- run CNTKAccess.Test() <- foward
- run CNTKAccess.TrainTest() <- training

<img src="log.jpg">

##Pretraind data
If you need pretraining data for resnet download from here

https://github.com/Microsoft/CNTK/blob/master/PretrainedModels/Image.md#resnet

How to use the training side is unknown


