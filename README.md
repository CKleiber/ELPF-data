This repository provides an educational MNIST-style data set of the digits 0-9 and the 26 captial letters of the English alphabet as found on European car license plates. For this, the current (2025) fonts of the license plates of the countries listed below are sampled, resized to $28 \times 28$ pixels in the range [0, 1] and augmented with rotations, rescaling and blurring. 

Total number of samples: 76.032 (split into a train:test ratio of 80:20)

The .zip file contains the data in PyTorch .pt file format, split into train and test data, each containing the tuple (images, labels):
- images shape: (num_samples, 1, 28, 28)
- labels shape: (num_samples)

Countries included in the sampling:
- Andorra
- Austria (EU)
- Belgium (EU)
- Denmark (EU)
- Finland (EU)
- France (EU)
- Germany (EU)
- Italy (EU)
- Lithuania (EU)
- Netherlands (EU)
- Norway
- Poland (EU)
- Slovakia (EU)
- Spain (EU)
- Switzerland
- United Kingdom