# Iron-Man-Voice-Image-Search

This application is my take on recreating the web search done by Tony Stark as Iron Man. The search is done via voice commands and the results are displayed in Augmented reality.

Future extension: Will try to incorporate the feature into HoloLens or Magic Leap.


Let us meet the President

![Say "Donald Trump"](https://github.com/adityaiiitv/Iron-Man-Voice-Image-Search/blob/master/4.PNG)

Say out loud "Donald Trump"


![The President is here](https://github.com/adityaiiitv/Iron-Man-Voice-Image-Search/blob/master/5.PNG)

The President is here!!


Working:

(1) Call the microphone to listen for speech

(2) Process speech using IBM Watson Unity plugin

(3) Create a google search query and get the resulting JSON using Google Custom Search API

(4) Use Vuforia's ground plane detection

(5) Augment the images in the image prefab, display the prefab over the ground plane

Tools: Unity, C#, IBM Watson, Google Custom Search API

![Pressing the button after saying "Hello"](https://github.com/adityaiiitv/Iron-Man-Voice-Image-Search/blob/master/1.PNG)

Say out loud "Hello" and press the button for magic


![Resulting images augmented in the reality](https://github.com/adityaiiitv/Iron-Man-Voice-Image-Search/blob/master/2.PNG)

Viola!


![Resulting images augmented in the reality](https://github.com/adityaiiitv/Iron-Man-Voice-Image-Search/blob/master/3.PNG)
