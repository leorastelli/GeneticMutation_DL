# GeneticMutation_DL
Repository per il progetto del corso di DeepLearning. Classificazione di immagini contenenti mutazioni genetiche attraverso varie ConvNet.
Contiene 4 jupyter notebook per le 4 reti create:
  - ConvNet_RGB.ipynb: Addestramento rete creata da noi con una sequenza di 2 strati convoluzionali con 2 di pooling e 1 layer fully-connected.
  - MobileNetV2_RGB.ipynb: Addestramento rete MobileNetV2 sulle immagini delle mutazioni di dati genetici a 3 canali colore (1000, 48, 3). La rete è pre-trained su 'imagenet'
  - ConvNet_Grayscale.ipynb: Addestramento rete creata da noi con una sequenza di 2 strati convoluzionali con 2 di pooling e 1 layer fully-connected.
  - MobileNetV2_Grayscale.ipynb: Addestramento rete MobileNetV2 sulle immagini delle mutazioni di dati genetici a 1 canale colore (1000, 48, 1). La rete utilizza dei pesi pre-addestrati dati da: https://github.com/NavodPeiris/MobileNet_96x96_greyscale_weights

### Metriche

  - ConvNet_RGB:
      - Validation Accuracy: 0.8061
      - Validation Loss: 0.4170
  - MobileNetV2_RGB:
      - Validation Accuracy: 0.8446
      - Validation Loss: 0.3469
  - ConvNet_Grayscale:
      - Validation Accuracy: 0.7949
      - Validation Loss: 0.4508
  - MobileNetV2_Grayscale:
      - Validation Accuracy: 
      - Validation Loss:
   


### Esecuzione
Per l'esecuzione aggiornare i path del drive presenti nei notebook




  
