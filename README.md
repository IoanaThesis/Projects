# Projects

## Improving Romanian ASR for specific domains with TTS-based data augmentation (Master's Thesis)

[Documentation](https://github.com/IoanaLiviaPortfolio/Projects/blob/main/Master's_Thesis_Improving_Romanian_ASR_for_specific_domains_with_TTS_based_data_augmentation.pdf)

This thesis explores the use of text to-speech synthesis (TTS) as a data augmentation
method to improve the performance of Automatic Speech Recognition (ASR) systems
for low-resource languages in specialized domains. This study presents a novel dataset
of Romanian audio-transcript pairs sourced from astrology-related YouTube videos,
primarily designed for ASR but also applicable to other speech-related tasks such as
language identification. We generate synthetic speech from text prompts automatically
extracted from the horoscope section of ProTV, a major Romanian media TV channel.
The text is converted to audio using TTS systems developed by Google and Microsoft.
This synthetic data is then combined with the training data from our newly introduced
dataset to fine-tune the Whisper Small model, which was pre-trained on large-scale
multilingual data. Experimental results demonstrate improved performance on the test
set of the new dataset as well as on two other Romanian horoscope-related datasets.

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

### Machine Learning - Sentence Pair Classification (Ranked 1/115 - private Kaggle competition for enrolled students) 

[Sentence Pair Classification (Kaggle) - the link is added just for reference, as only participants can access private competition details](https://www.kaggle.com/competitions/sentence-pair-classification-pml-2023)

<img width="1880" height="1154" alt="image" src="https://github.com/user-attachments/assets/aa5f9f93-d3a8-48ae-9d34-82a5dc4a7343" />

[Documentation](https://github.com/IoanaLiviaPortfolio/Projects/blob/main/Machine_Learning_Sentence_Pair_Classification.pdf)

Sentence pair classification challenge focused on training classifiers using a dataset composed of Romanian sentences.

### Deep Learning - Image-Sentence Pair Matching (Ranked 1/68 - private Kaggle competition for enrolled students)

[Image Sentence Pair Matching (Kaggle) - the link is added just for reference, as only participants can access private competition details](https://www.kaggle.com/competitions/isp-match-dl-2024)

<img width="1926" height="1159" alt="image" src="https://github.com/user-attachments/assets/f702fb28-6bc2-4e1a-93ef-b493193f0e7b" />


[Documentation](https://github.com/IoanaLiviaPortfolio/Projects/blob/main/Deep_Learning_Image_Sentence_Pair_Classification.pdf)

Binary classification of image + sentence pairs. The sentences are
interpreted as potential captions - they could either match the image (label 1) or not (label 0). Among
the rules, the use of additional data, pre-defined models or pre-trained models has been prohibited.

### RoReEmo - Romanian Reddit Emotion Dataset

[Documentation](https://github.com/IoanaLiviaPortfolio/Projects/blob/main/RoReEmo_Romanian_Reddit_Emotion_Dataset.pdf)

Introduces the novel ReRoEmo (Reddit Romanian Emotion) that contains romanian Reddit posts annotated with
one out of five potential emotions: fear, anger, joy, sadness, neutral - inspired from RED (Romanian Emotion Dataset) (Ciobotaru and Dinu, 2021) which contains tweets with the same potential labels. The dataset has been created as an aid in potential opinion mining tasks based on recent data. Moreover, it has been utilized as a potential extension of RED -
creating a larger corpus of emotion annotated romanian short texts.
