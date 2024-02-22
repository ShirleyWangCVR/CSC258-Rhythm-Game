# CSC258-Rhythm-Game

My CSC258 final project. It's a rhythm game programmed in Verilog.  The initial screen is black with a white line near the bottom, and there are four columns that notes can come down in.  The goal is to press the corresponding key on the keyboard while the note is at the line to make the notes disappear and a song play.

There are three songs that can be played: Mary Had A Little Lamb, Fur Elise, and Unravel from Tokyo Ghoul.  There are four speeds that the song can come down in.  Upon starting up the game, press Key0 to reset and set up the screen and game.  Then use switches 0 and 1 to choose the song, and switches 2 and 3 to choose the speed the song should play at.  Then pressing Key1 will start the game.  The game is played on the keyboard keys A, S, D, F.

There are two types of notes: short and long.  Short ones will disappear once pressed, and play the corresponding sound.  Long ones need to be held for over 2/3rds while its over the white line for it to be a success and disappear.

Due to our particular implementation of the mif files and column and datapath module, we can only ever have one note crossing the white line at a time.  The way the notes are written in the mif file is also very specific and should be followed if used.



#### DEMO (Unravel from Tokyo Ghoul):

https://github.com/ShirleyWangCVR/CSC258-Rhythm-Game/assets/43547424/d9bc38b6-f06c-4b4c-9fbf-718fc602a7d2

