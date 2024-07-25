---------Project Summary: Audio-Based Instruction Classification for Robots---------
This project involves creating a system that can listen to audio instructions, convert them into text, and classify the instructions for a robot to follow. 
The given code includes an example where an audio file named audio5.wav is processed. This audio file can be changed too to test the code. Numerous other audio files are also attached along with the code.
The audio file path is provided, and the program then converts it into a text file and then processes the file to extract, classify, and print the instructions.
A predefined dictionary of instructions is present which contains certain keywords on the basis of which instruction segmentation is done.
Instruction are mainly classified on the basis of their movement and distance of movement, for ex -
Extracted Text: 'move up and then go down 5 metres and then move diagonally backward by 10 m'
Instruction: move up
Instruction: move down, Value: 5 meters
Instruction: diagonal movement, Value: 10 meters
