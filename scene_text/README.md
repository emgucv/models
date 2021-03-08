Text Detection model (DB_TD500_resnet50.onnx) from https://drive.google.com/uc?export=dowload&id=19YWhArrNccaoSza0CfkXlA8im4-lAGsR
recommended parameter setting: -inputHeight=736, -inputWidth=736;
description: This model is trained on MSRA-TD500, so it can detect both English and Chinese text instances.

Text Recognition model (crnn_cs_CN.onnx) from https://drive.google.com/uc?export=dowload&id=1is4eYEUKH7HR7Gl37Sw4WPXx6Ir8oQEG
Vocabulary (alphabet_3944.txt) from: https://drive.google.com/uc?export=dowload&id=18IZUUdNzJ44heWTndDO6NNfIpJMmN-ul
parameter setting: -rgb=1;
description: The classification number of this model is 3944 (0~9 + a~z + A~Z + Chinese characters + special characters).
             The training dataset is ReCTS (https://rrc.cvc.uab.es/?ch=12).