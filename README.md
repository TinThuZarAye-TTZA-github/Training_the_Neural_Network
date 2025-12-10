# Training the Neural Network 
#### The neural network is trained on 2 datasets
-**MINST Digits Dataset** 0-9
-**A-Z Handwritten Letter Dataset** A-Z

Each image is resized to **28x28**, normalized to **[0,1]** and one-hot encoded into **36 classes** 10 digits + 26 characters

Use a **Convolutional Neural Network - CNN** with data augmentation and trained for **20 epochs** with class blancing to improve accuracy.

Model is saved automatically to **custom_ocr.keras**
