# AI-rock-paper-scissor-with-Tensorflow

Requirements

    *Python 3
    *Keras
    *Tensorflow
    *OpenCV

Set up instructions

    1.Clone the repo.

$ git clone https://github.com/SouravJohar/rock-paper-scissors.git
$ cd rock-paper-scissors

   2. Install the dependencies

$ pip install -r requirements.txt

   3. Gather Images for each gesture (rock, paper and scissors and None): In this example, we gather 200 images for the "rock" gesture

$ python3 gather_images.py rock 200

    4.Train the model

$ python3 train.py

    5.Test the model on some images

$ python3 test.py <path_to_test_image>

  6.  Play the game with your computer!

$ python3 play.py
