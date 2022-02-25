# Maldataset-2021
Maldataset2021 is a malware dataset that consists of 28 classes of malware, in which each class represents a malware family, and each sample gives a RGB 224x224 PNG file. The PNG files are transformed from the original binary malware files. The motivation of image transformation is to identify malware on the raw bytes of entire executable files (i.e., image), so that deep learning technologies such as CNN can be applied to malware classification, since CNN model has been demonstrated with its outstanding capability on image classification. In this view, we provide here a new dataset that contains the latest malware samples. The entire PNG files are split as, 70% for training and the remaining 30% for testing.
Maldataset2021 is a malware dataset that consists of 28 classes of malware, in which each class represents a malware family, and each sample gives a RGB 224x224 PNG file. The PNG files are transformed from the original binary malware files. The motivation of image transformation is to identify malware on the raw bytes of entire executable files (i.e., image), so that deep learning technologies such as CNN can be applied to malware classification, since CNN model has been demonstrated with its outstanding capability on image classification. In this view, we provide here a new dataset that contains the latest malware samples. The entire PNG files are split as, 70% for training and the remaining 30% for testing.

Malware Classes	Number of Samples
Training Set	Testing Set
Agent	350	120
Agenttesla	85	35
Androm	350	147
Andromeda	85	35
Autorun	350	147
Autorun.k	80	25
Azorult	35	10
Cerber	70	30
Darkcomet	45	25
Dridex	30	15
Dyre	41	18
Emotet	68	26
Grandcrab	73	21
Hawkeye	70	21
Heyodo	69	30
IceID	69	20
Limerat	10	6
Loki	138	40
Nanocore	157	42
Neshta	350	147
Nymaim	73	30
QuasarRat	92	35
Regrun	350	147
Remcosrat	155	70
Robot!gen	140	18
Sality	350	147
Shifu	31	12
Trickbot	141	69
Total Number	3604	1365
The PNG files are of type 3D, therefore, it was saved as a NumPy .npy (RGB) and a .csv (Gray Scale) file, respectively. You can use either or both types of files for the classification. 

 https://www.csmining.org/cdmc2021/index.php?id=5

Citation:
Chaalan Tarek Maldataset 2021: Maldataset as png images, June 2021
