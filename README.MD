# Image Encryption
## Goal of the Project:
  The goal of this project was to create a terminal-based software that would be able to encrypt an image so that no sensitive information is available. The software should also have the capabilities to decrypt the image by using a key that is saved to a .txt file. 
  
## Tools Used: 
- Visual Studio Code
- imcrypt library


## Methodology:
  In order for this project to work, first imcrypt has to be downloaded using the "npm i -g imcrypt" command. After download this, the coding process can begin. In VS code, a file must first be created called CLI.js. In this file all of the different flags/commands must be entered so that the computer can recognize when to encrypt and decrypt. For example, if "impcrypt -e image.png" is typed in, this "-e" flag will encrypt the image. "-d" will decrypt and there are many more different flags. Once these flags are declared, a file called encrypt.js must be made which actually encrypts the image once the user uses the "-e" flag. This file encrypts the image where only RGB pixels are seen and also changes the new images name to image_encrypted.png. After the encryption file was made the decryption file was made so that users could access to original image. Once the image is encrypted, a document called key.txt is made which has the decryption key in it. The decrypt.js file uses this key as input from the user and the "-d" flag to decrypt the image and present the original image to the user. 
  
## Challenges Faced: 
The main challenge that I faced was actually encrypting the image because this required high-level knowledge of encrypting using keys and then being able to use this key to decrypt the image. This process took a while but eventually the project was successful and the user can efficiently encrypt and decrypt images. 
