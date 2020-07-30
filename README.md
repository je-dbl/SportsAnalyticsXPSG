# xPSG : Sports Analytics Challenge
This notebook presents excerpts of code used in the 2019 xPSG Sports Analytics Challenge. During the challenge, I had access to better computational resources: the version presented here is thus a 'lite' version of what I used. I did not qualify for the final round, but I still wanted to share insights learned during the process. A blog article about this experience can be read here: https://medium.com/@jeremi.debloisbeaucage/la-science-des-donn%C3%A9es-appliqu%C3%A9e-au-soccer-le-challenge-xpsg-2f35d8c4f940.

The task presented in this code is to predict which team will do the next event, using the preceding 10 events. An event can be anything related to soccer: a pass, shot, dribble, center, etc. and can be characterized by numerous qualifiers (long pass, chipped pass, etc.) Deep learning is used, via a Long Short-Memory (LSTM) Recurrent Neural Network (RNN).

This code has 3 different sections:
1. Extracting, cleaning and observing datasets
2. Creating training, validation and test sets
3. Training models and choosing the best
