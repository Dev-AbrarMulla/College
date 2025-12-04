Architecture 1 — Shallow Network
-------------------------------
Q1.
Lower accuracy, because the model cannot learn complex patterns due to limited capacity, it struggles with high-level features.

Q2.
Yes, a shallow CNN mostly learns edges, corners, simple textures.

Architecture 2 — Deeper Network with More Filters
-------------------------------------------------
Q1.
Yes, the deeper network with more filters generally achieves higher accuracy than the shallow model.

Q2.
Training time becomes longer due to the increased number of layers and parameters.

Q3.
Yes, deeper activations capture more complex and abstract patterns than earlier layers.

Architecture 3 — No Pooling
---------------------------
Q1.
Yes, removing pooling keeps full spatial detail and typically increases overfitting.

Q2.
Yes, without pooling the model passes more local variations, making gradients noisier and less stable.

Q3.
Yes, training becomes slower because feature maps remain large and computations increase.