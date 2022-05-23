## ResNet-50 Keras Implementation

### Reference: 
Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun
[Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)

### Implementation:
 
 ResNet50 architecture blocks from original ResNet paper are implemented with bottleneck design in Keras/Tensorflow-2.8. The implementation includes:

* Identity shortcut block
* Projection shortcut block
* ResNet initializer block
* ResNet50 Complete Keras Model
* Classification input pipeline from ResNet paper