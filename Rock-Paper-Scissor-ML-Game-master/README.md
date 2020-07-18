# rock-paper-scissors 

An AI app to play the Rock Paper Scissors game :

## Requirements
- Python 3
- Keras
- Tensorflow
- OpenCV

## Set up instructions
1. Clone the repo.
```sh
$ git clone git@github.com:sgupta117/Rock-Paper-Scissor-ML-Game.git
```

2. Install the dependencies
```sh
$ pip install -r requirements.txt
```

3. Gather Images for each gesture (rock, paper and scissors and None):
In this example, I have gathered 200 images for the "rock" gesture
```sh
$ python3 gather_images.py rock 200
```

4. Train the model
```sh
$ python3 train.py
```

5. Test the model on some images
```sh
$ python3 test.py <path_to_test_image>
```
Glimpse:

![RPS](https://user-images.githubusercontent.com/61824566/87464224-609f3d80-c630-11ea-8cc6-ad27b4ab532b.PNG)
![RPS1](https://user-images.githubusercontent.com/61824566/87464244-6d239600-c630-11ea-9864-b611721bdfae.PNG)


6. Play the game with your computer!
```sh
$ python3 play.py
```
