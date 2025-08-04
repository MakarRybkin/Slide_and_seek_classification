### Решение соревнования https://zindi.africa/competitions/classification-for-landslide-detection демонстрирует процесс создания и обучения модели глубокого обучения для бинарной классификации оползней на основе мультиспектральных данных и Sentinel-2.
### Метрика соревнования - f1
### Ключевые методы :

#### Было исследовано несколько методов CV от простых CNN до разных трансформеров. В итоге лучшие результаты показали ансамбли из EfficientNetB5, DenseNet169, ResNet50 и кросс-валидированный eva_large_patch14_196.in22k_ft_in22k_in1k и beitv2_large_patch16_224.in1k_ft_in22k_in1k

#### Отслеживание экспериментов: Интеграция с Comet ML обеспечила прозрачное отслеживание, сравнение и воспроизводимость всех экспериментов. Эксперементы с трансформерами https://www.comet.com/makar-rybkin/classification-for-landslide-detection-ensamble-pytorch. Эксперементы с CNN https://www.comet.com/makar-rybkin/classification-for-landslide-detection-ensamble

### Благодаря примененным стратегиям,  удалось достичь F1 = 0.9 на public и F1 = 0.8711 на private leaderboard. Этот результат позволил занять 30-е место в общем рейтинге соревнования.
