# Projects

### Machine Learning - Sentence Pair Classification (Ranked 1/115 - private Kaggle competition for enrolled students) 

[Sentence Pair Classification (Kaggle)](https://www.kaggle.com/competitions/sentence-pair-classification-pml-2023)

[Documentation](https://github.com/IoanaLiviaPortfolio/Projects/blob/main/Machine_Learning_Sentence_Pair_Classification.pdf)

Sentence pair classification challenge focused on training classifiers using a dataset composed of Romanian sentences.

### Deep Learning - Image-Sentence Pair Matching (Ranked 1/68 - private Kaggle competition for enrolled students)

[Image Sentence Pair Matching (Kaggle)](https://www.kaggle.com/competitions/isp-match-dl-2024)

[Documentation](https://github.com/IoanaLiviaPortfolio/Projects/blob/main/Deep_Learning_Image_Sentence_Pair_Classification.pdf)

Binary classification of image + sentence pairs. The sentences are
interpreted as potential captions - they could either match the image (label 1) or not (label 0). Among
the rules, the use of additional data, pre-defined models or pre-trained models has been prohibited.

### Computer Vision - Mathable Solver

[Documentation](https://github.com/IoanaLiviaPortfolio/Projects/blob/main/Computer_Vision_Mathable_Solver.pdf)

Automatic scorer system for the game Mathable based on provided
images of the board corresponding to each move. The approach is based on object detection using the
hsv color space in order to extract the board. Afterwards, the additional border is removed and the
resulting board is divided in 196 equal square tiles, as the board size is known to have 14 tiles alongside
its width and height. Upon identifying the position and value of the placed token by using the created
token templates, the score for each move is computed with respect to the token’s numerical value and
the constraint, bonus and neighbours of the tile. The score of the turn is considered to be the sum of
the scores for each move made during the turn.

### Computer Vision - Visual surveillance of on-street parking

[Documentation](https://github.com/IoanaLiviaPortfolio/Projects/blob/main/Computer_Vision_Visual_surveillance_of_on-street_parking_spaces.pdf)

Automatic identification and tracking system for the surveillance
of on-street parking spaces. The approach for object detection and tracking is mainly based on the
Yolov8 implementation provided by Ultralytics and manual selection of desired areas to be analyzed,
adjusted based on the training data.

### RoReEmo - Romanian Reddit Emotion Dataset

[Documentation](https://github.com/IoanaLiviaPortfolio/Projects/blob/main/RoReEmo_Romanian_Reddit_Emotion_Dataset.pdf)

Introduces the novel ReRoEmo (Reddit Romanian Emotion) that contains romanian Reddit posts annotated with
one out of five potential emotions: fear, anger, joy, sadness, neutral - inspired from RED (Romanian Emotion Dataset) (Ciobotaru and Dinu, 2021) which contains tweets with the same potential labels. The dataset has been created as an aid in potential opinion mining tasks based on recent data. Moreover, it has been utilized as a potential extension of RED -
creating a larger corpus of emotion annotated romanian short texts.
