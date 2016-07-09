# MinimaTetris ?

Last night, it was hard for me to sleep, so I created this little Tetris. My goal is to later add an Artificial Intelligence that will play alone.  

Game preview:  

![alt tag](https://github.com/JeremyPouyet/MinimaTetris/blob/master/imgs/preview.png)

## Install:

```
$> sudo apt-get install libsdl2-dev libsdl2-ttf-dev libsdl2-mixer-dev
$> git clone https://github.com/JeremyPouyet/MinimaTetris.git
$> cd MinimaTetris/ && make
$> ./MinimaTetris
```

## How to play:

The game start directly after the launch, then:  

* ← : move current tetromino left  
* → : move current tetromino right  
* ↓ : move current tetromino down  
* ↑ : rotate current tetromino  
* space: fast placing, current tetromino will move down until it encounter another tetromino  

After a game over, the game will be relaunched automatically.
