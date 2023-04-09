# Ha-Tran
EE104-Lab 6

Reference: Laboratory Assignment 6

About this lab: In this project, there are four parts, the first two are about using the Convolutional Neural Network to train the AI to recognize the images. The second one is the Happy garden python game. The third one is Hello World to OpenAi. Finally, it is about Hello to ChatGPT

1)CNN - Baseline + Increasing Dropout + Data Augmentation + Batch Normalization + Your own method
In part one, we should download the CIFAR10 dataset online, and import some packages as below:
 
And this should be done in Google Colab, otherwise your computer may become overly weary while performing machine learning.
OR, you may simply execute my code. (because everything is set up already). However, remember to set the Epoch to at least 20 to increase the model's accuracy above 87 percent.
2)CNN - Challenge test
This part is just based on the previous one. If you train it well, the test result will be perfect.
To test different images, simply copy the URL and paste it into the code. After running it, you'll be surprised at how well the AI recognizes every ten different photos of objects.
 
3)Game Development – Happy garden

The game is a gardening game where the player controls a cow that must keep the garden happy by collecting wilted flowers before they die and avoiding mutated flowers that attack the cow. The game also features random rain events that will change the garden background and make the flowers grow faster.
The game consists of several functions that are called from the main Pygame Zero loop, including the draw function, which handles drawing the game world and UI; the new_flower function, which creates a new flower actor; the add_flowers function, which schedules the addition of new flowers to the game world at regular intervals; the check_wilt_times function, which checks how long each flower has been wilted and marks them as unhappy if they have been wilted too long; the wilt_flower function, which simulates flowers wilting over time; the check_flower_collision function, which checks if the cow has collided with a wilted flower and marks the flower as happy if it has; the check_fangflower_collision function, which checks if the cow has collided with a fangflower and ends the game if it has; the check_io_collision function, which checks if the cow has collided with an IO and ends the game if it has; the velocity function, which calculates a random velocity for the fangflowers and IOs; and the mutate and mutateIO functions, which handle the mutation of flowers into fangflowers and IOs, respectively.
Based on the slide, I just add more fangflowers, more enemies and rain in the garden
I also add some lines to add more flowers.

4)Hello to OpenAi

In this assignment, I need to download OPENAI_KEY from the website (Quickstart tutorial - OpenAI API) and copy the KEY. I would work on Window Powershell through out this assignment. After we run all the requirement, we will open browse and type localhost:5000 to get the screen window. At the box “Enter an animal”, type animal name such dog or cat, we will get four names for animal that is a superhero.
 
5)Hello to ChatGPT
To run this application, you will need the following:
An OpenAI API key (available from the OpenAI website)
A .env file containing your API key in the following format: OPENAI_API_KEY=<your_api_key_here>
Then, install all these below:
Clone this repository to your local machine.
Navigate to the directory where you cloned the repository.
Create a virtual environment: python -m venv env
Activate the virtual environment: env/bin/activate.bnat
Install the required dependencies: pip install -r requirements.txt

The application will prompt you for input. Enter your message and press Enter. The application will then generate a response using the OpenAI API and display it on the screen.
