A2----------------------------------
Forward time per example - 7ms
Backprop time per example -	11ms
Classification Loss	- 1.77403
L2 Weight Decay Loss - 0.00236
Training Accuracy - 0.36	
Validation Accuracy - 0.18
Examples Seen -	3024
Test Accuracy (last 200 images) - 0.26666666666666666

A3------------------------------------
conv (32x32x16)
filter size 5x5x3, stride 1
max activation: 0.88743, min: -1.83078
max gradient: 0.04183, min: -0.03696
parameters: 16x5x5x3+16 = 1216

relu (32x32x16)
max activation: 0.88743, min: 0
max gradient: 0.04714, min: -0.04741

pool (16x16x16)
pooling size 2x2, stride 2
max activation: 0.88743, min: 0
max gradient: 0.04714, min: -0.04741

conv (16x16x20)
filter size 5x5x16, stride 1
max activation: 2.29803, min: -2.67661
max gradient: 0.0443, min: -0.07596
parameters: 20x5x5x16+20 = 8020

relu (16x16x20)
max activation: 2.29803, min: 0
max gradient: 0.0443, min: -0.07596

pool (8x8x20)
pooling size 2x2, stride 2
max activation: 2.29803, min: 0
max gradient: 0.0443, min: -0.07596

conv (8x8x20)
filter size 5x5x20, stride 1
max activation: 1.19171, min: -6.04253
max gradient: 0.06818, min: -0.17644
parameters: 20x5x5x20+20 = 10020

relu (8x8x20)
max activation: 1.19171, min: 0
max gradient: 0.24404, min: -0.18414

pool (4x4x20)
pooling size 2x2, stride 2
max activation: 1.19171, min: 0
max gradient: 0.24404, min: -0.18414

fc (1x1x10)
max activation: 0.8704, min: -2.51126
max gradient: 0.17732, min: -0.72101
parameters: 10x320+10 = 3210

A4--------------------------------
1.
The first layer learns low-level features like edges, corners and color/brightness gradients.

2.
The network has features into more complex patterns: curves, shapes or object-parts.

3.
Yes, The CNN architecture does explode or vanish during backprop, making the training unstable.

4.
It learns patterns to the training data that don’t generalize to unseen validation data.

5.
This lowers spatial resolution, discards fine detail, but makes the model more efficient and robust to small translations