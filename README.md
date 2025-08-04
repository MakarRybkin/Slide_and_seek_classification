### The solution to the competition https://zindi.africa/competitions/classification-for-landslide-detection demonstrates the process of creating and training a deep learning model for binary classification of landslides based on multispectral data and Sentinel-2.
### Competition metric - f1
### Key methods:

#### Several CV methods were explored from simple CNNs to different transformers. In the end, the best results were shown by ensembles of EfficientNetB5, DenseNet169, ResNet50 and cross-validated eva_large_patch14_196.in22k_ft_in22k_in1k and beitv2_large_patch16_224.in1k_ft_in22k_in1k

#### Experiment tracking: Integration with Comet ML ensured transparent tracking, comparison and reproducibility of all experiments. Experiments with transformers https://www.comet.com/makar-rybkin/classification-for-landslide-detection-ensamble-pytorch. Experiments with CNN https://www.comet.com/makar-rybkin/classification-for-landslide-detection-ensamble

### Thanks to the applied strategies, it was possible to achieve F1 = 0.9 on public and F1 = 0.8711 on private leaderboard. This result allowed to take 30th place in the overall competition rating.
