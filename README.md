# Black-Mesa-Blue-Shift-Launcher
A simple launcher for Black Mesa: Blue Shift to launch through Steam.
Includes an optional variant with a Black Mesa inspired starting sequence.

[The original Reddit post](https://www.reddit.com/r/BlackMesaSource/comments/102ih19/ive_made_a_launcher_for_black_mesa_blue_shift/)
## About the file names (Important)
Note that in the names of the files, v2 denotes a version with the aforementioned starting sequence, while oldUI launches an alternate version of Black Mesa: Blue Shift with a UI resembling that of the classic gold_src engine games.

## To install, move the chosen executable to either:

**steamapps\workshop\content\362890\2424633574** if you used the symbolic link install method

Or **steamapps\common\Black Mesa** if you used the file browswer install method

Multiple executables can coexist within these folders.

## The opening sequence

Since it takes so long for Black Mesa: Blue Shift to load for me, I decided to make the starting sequence I mentioned before. It doesn't fully cover the load time, but it's something to look at. The starting sequence comprises of a terminal window with a blue background and white text (Inspired by the BMOS systems seen in Black Mesa) and an ASCII art of the Black Mesa logo (Maybe only *partially* insprired by Portal's credit sequence). It then goes on to a user named barney.calhoun logging on (I've created a simple function to simulate typing) and executing a file named bshift.bat (Or bshift_oldUI.bat if you're using the alternate version). Afterward, the user is given a mysterious warning and the screen is cleared to show text announcing the success of the program's launch.

## Distribution information
Feel free to distribute this wherever and to whomever you wish. 
If modifying and distributing, credit me if and where possible.

No external libraries were used in the making of this project.
