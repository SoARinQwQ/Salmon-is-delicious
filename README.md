# Salmon-is-delicious
SAISK Created for Gamejam.
***I haven't learned programming systematically, just read about it in books and learned it online. Sorry if this causes any trouble.QwQ***

## 1.How to import scenes into unity?
Download **MAZE1.0.unitypackage** directly and then drag it directly into unity.
***But in addition to that, you need to add or change some settings.***

## 2.Camera settings.
First, we need to download *Cinemashine*.This is because I used the camera package that comes with unity.
The installation address is *Window-Package Manager*. Then make sure that the top left corner is under the selection *Unity Registry*.
Search for *Cinemashin* in the upper right corner.And install.

The camera will be changed automatically.

## 3.The player falls out of the picture.

Open *Project Settings* in *Edit*. Find *Gravity* in *Physics 2D*. Guaranteed XY is all 0.

## 4.Change the layer settings.

Enter three layers in *Sorting Layers* in *Add layer...*. They each correspond to the black background, MAP1, and player.
Then, change the *Sorting Layer* option in *Inspector-Additiona Settings* to the corresponding layer.(Example: MAP1--map layer.)

## 5.Water tag!!!

Please make sure all four Water *tags* are **Water**. the relevant code is in <Life.cs>.

## 6.TOUCH the VOID, and Jump to the next Scence!

In *Inspector* on **Void**, look for *Next Scenes(Script)* and change the Scene number of *Scene Build Index*. This will allow you to jump to that scenes when you _touch the Void_.
