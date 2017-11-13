# Sound-recognition using Neural network

Fair Warnings :This code is hacked together in 48 hours for Energy hackathon project in Prague ( 3-5.11.2017)
Bugs may occur :)

Pitch :
Train Neural Network using public datasets to for sound recognition to recognize sound on the street. 
We are using Urban Sound and Mivia Audio Events Dataset.

{Pasquale Foggia, Nicolai Petkov, Alessia Saggese, Nicola Strisciuglio, Mario Vento, Reliable Detection of Audio Events in Highly Noisy Environments, Pattern Recognition Letters, Available online 9 July 2015, ISSN 0167-8655, http://dx.doi.org/10.1016/j.patrec.2015.06.026.}

{https://serv.cusp.nyu.edu/projects/urbansounddataset/}

## Contains

### Python parser for Mivia Audio Dataset
Simple Python parser that extracts exact points in the sound recordings where selected sound can be heard. (Very crude, but could be easily edited for your own usecase)

### IpythonNotebook for Neural Network training.
IpythonNotebook is based on https://github.com/aqibsaeed/Urban-Sound-Classification.

Contains slightly modified Python notebook for training on smaller number of categories. Different Neural network configurations were tried but the originaly mentioned were used for fast prototyping. ( For final presentation all data were used as a training :D )

### Server side
Server that recieves sound using websockets and classificate them.

### Android App
App that records sound and streams it to the server.
