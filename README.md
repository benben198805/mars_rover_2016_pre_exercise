#Mars Rovers thoughtworks puzzles
#ThoughtWrorks 火星漫游者号 题目

一小队机器人探测器将由NASA送上火星高原，探测器将在这个奇特的矩形高原上行驶。用它们携带的照相机将周围的全景地势图发回到地球。每个探测器的方向和位置将由一个x, y系坐标图和一个表示地理方向的字母表示出来。为了方便导航，平原将被划分为网格状。位置坐标示例：0，0，N，表示探测器在坐标图的左下角，且面朝北方。为控制探测器，NASA会传送一串简单的字母。可能传送的字母为：'L','R'和 'M'。'L',和 'R'分别表示使探测器向左、向右旋转90度，但不离开他所在地点。'M'表示向前开进一个网格的距离，且保持方向不变。假设以广场（高原）的直北方向为y轴的指向。
输入

首先输入的line是坐标图的右上方，假定左下方顶点的坐标为0，0。剩下的要输入的是被分布好的探测器的信息。每个探测器需要输入wo lines。第一条line 提供探测器的位置，第二条是关于这个探测器怎样进行高原探测的一系列说明。位置是由两个整数和一个区分方向的字母组成，对应了探测器的（x,y）坐标和方向。每个探测器的移动将按序完成，即后一个探测器不能在前一个探测器完成移动之前开始移动。
输出

每个探测器的输出应该为它行进到的最终位置坐标和方向。
#输入和输出
##期待的输入:

5 5

1 2 N
LMLMLMLMM
3 3 E
MMRMMRMRRM 

##期待的输出

1 3 N
5 1 E

