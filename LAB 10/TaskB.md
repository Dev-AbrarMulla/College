B1----------------------------------

1.
0.05 causes unstable or diverging loss.

2.
0.9 gives faster convergence than 0.5.

3.
Yes. For speed larger batch size trains faster than smaller batch per epoch & for accuracy, smaller batches usually generalize better; large batches may reduce accuracy slightly.

4.
Yes, With weight decay = 0, the model is more likely to overfit and the gap between training and validation accuracy increases.