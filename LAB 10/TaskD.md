*Effect of each hyperparameter
-----------------------------
Learning rate: Controls how fast the model learns.

Momentum: Smooths updates and speeds convergence; higher momentum reduces oscillations.

Batch size: Larger batches train faster but may reduce generalization & smaller batches give noisier but often better gradients.

Weight decay (L2): Reduces overfitting by penalizing large weights.

*Comparison of models
--------------------------
Architecture 1 (Shallow): Fastest but because it learns only simple edge-level features.

Architecture 2 (Deep with More Filters): Best accuracy due to deeper layers and richer features.

Architecture 3 (No Pooling): More detailed feature maps but slower training.

*Which architecture performed best and why?
-------------------------------------------
Architecture 2 performed best because its deeper layers and larger number of filters capture more complex patterns, leading to stronger feature representations and higher accuracy.

Short Answers
------------------------------------------
Why do deeper CNNs learn more complex patterns?
    - Allows the network to form hierarchical and more abstract representations.

Why does test accuracy lag behind training accuracy?
    - The model overfits the training data and cannot fully generalize to unseen samples.

Why is pooling important?
    - Pooling reduces spatial size, lowers computation, and increases robustness.

What happens if stride is too large?
    - A large stride skips important details, causing loss of information and lower accuracy.

What design principles did you learn today?
    - Deeper layers improve representation, pooling helps with generalization, and parameters must be balanced for accuracy & speed.