# Rock, Paper, Scissors
Image recognition and machine learning project that can detects hand shape from video feed and keeps score in a Rock, Paper, Scissors game. 

## Video Demo
Click on the image below to be redirected to a YouTube video!
[![Video](https://img.youtube.com/vi/NvAWEgTGzkg/0.jpg)](http://www.youtube.com/watch?v=NvAWEgTGzkg)

## Project description
This project can detect hand symbols of between two players simultaneously from a video feed and update the score accordingly. The system was implemented using an OMAP L138 Development Kit and the vpif_lcd_loopback framework provided in the C6748 LCDK Starterware library. The video feed of the hand signals was processed to facilitate the extraction of feature vectors. The features were then used to train a single-hidden-layer neural net, whose coefficient would later allow for fast real-time detection of the hand symbols. The system is able to successfully identify and display the corresponding hand symbol and update the score in real time. The whole process was implemented without the use of filters and is therefore efficient and expeditious.

## Implementation
![alt text][pipeline]

[pipeline]: pipeline.png
