# Covid-19-detection-through-chest-x-ray-using-transfer-learning

This project is a comparative study for COVID-19 detection through posteroanterior (PA) view of the chest x-ray between three models: the first one is simple Convolution neural network architecture from scratch, the second one is transfer learning from pre-trained model VGG-16 as feature extractor and third is transfer learning from pre-trained model VGG-16 by fine-tuning some blocks of it while training. The project achieved 99% accuracy through transfer learning that outperformed simple convolution neural network architecture with 81% accuracy.

Dataset used for training the model are extracted from the following references:
1. https://github.com/ieee8023/covid-chestxray-dataset
2. https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
