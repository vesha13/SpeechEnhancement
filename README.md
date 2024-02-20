This code's aim is Speech Enhancement and Denoising Audio For Hard-of-Hearing People In Universities.
-
The main idea is to fine tune existing pre-trained MetricGAN+ model from speechbrain (https://speechbrain.github.io/; https://github.com/speechbrain/speechbrain).

Fine tunning is made on custom data.
Main methods/instruments are: 
-  PyTorch
-  Metric Generative adversarial networks (MetricGAN)
-  Spectral Masking
-  Bidirectional Long short term memory (BLSTM)

Process of fine-tunning and testing pre-trained model on the data could be found in experiment.ipynb

Plots of results could be found plots.ipynb
