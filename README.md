# CS8395_Project_3
## Overview
The project will use Unity and Vuforia to create an AR labyrinth game. The executable will be able to be installed and run on Android smartphones. The game is inspired by the famous game “Labyrinth 2” and the combination of AR will bring a brand-new vision to this game. 

## Basic Idea
The idea is from an old game I have played called “Labyrinth 2” (https://apps.apple.com/us/app/labyrinth-2/id307758884). Labyrinth 2 is a game created by Illusion Labs on Dec.1, 2009. The game is supported for the iPod Touch, iPhone, and Android smartphones. The HD edition is also designed for the iPad. To beat the levels, the player needs to move the metal ball to the destination while avoiding other obstacles. The core of the game is based on the gravity sensor of the smart devices, combined with the gyroscope and accelerometer. This allows players to tilt the device to control the movement of the ball. In the era of smartphones, this game has brought a great impression to people and received many positive reviews.
<img src=https://user-images.githubusercontent.com/72234409/160718461-707c5a0e-4ea1-4e7c-bcb5-44ce36c66bd1.jpg width="200" height="300">

## Reasons
Since this remarkable game does not have an AR version, I think it would be fun to combine the AR component into the game. For the original version of the game, the entire game window can only fit on the screen of the smart device. If the game can be explored with AR technology, the size and the texture of the game components can be more realistic, which brings a more stereoscopic impression to the players. Besides, more ways to play are possible be found when combined with AR technology.

## Tools and Expectations
Unity and Vuforia will be used to create this application. As the concept of the project, the user will use the camera of their Android device to scan the image target provided. There will be a virtual labyrinth on the screen, a destination sign, and a ball inside of the labyrinth. The user needs to find a way to roll the ball all the way to the destination.

## Instructions
To interact with the code, download and save the "front_cover.jpg" and "back_cover_1.jpg" in the Image/ as the target images. Use the link in the README.md to download AR_book_cover.apk to your Android smartphone and open it. The application will be installed by itself. The application will open your camera to scan the target image. Please note you need to allow camera access first. Once you scan the "front_cover.jpg", you will see the title of the book and the author name in the form of AR texts and an AR model on the front cover. For "back_cover_1.jpg", you will see the brief information of the book. Once you cover your hand or other objects on the back cover, you will see a paragraph of AR text which is a short review of the book.

## Limitations
* The original back cover of the book is unable to be used as an image target for too many repetitive patterns. Therefore a movie poster is used instead as the "back cover" of the book.
* The virtual button feature for the back cover works more unstable on the smartphone camera than the laptop camera.
* The Unity Project is too large to be pushed up to Github. The scene file and the C# script are committed instead as works.
