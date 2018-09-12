# tetris-game

> Tetris WinAPI Win32 C/C++

Win32程序，使用WinAPI，主要代码在 [TetrisGame_zjy.cpp](https://github.com/VincentJYZhang/tetris-game/blob/master/Source%20Code/TetrisGame_zjy.cpp) 和 [Shapes.h](https://github.com/VincentJYZhang/tetris-game/blob/master/Source%20Code/Shapes.h) 中。

## 形状存储

使用二维数组存储七种形状，遍历填充，通过矩阵的旋转算法进行变换。

```
static int shapes[7][4][4] = {
  {
      { 0, 0, 0, 0 },
      ( 0, 1, 0, 0 },
      { 1, 1, 1, 0 },
      { 0, 0, 0, 0 },
  },
  
  ......

}

```

## demo展示

![demo](./demo.png)
