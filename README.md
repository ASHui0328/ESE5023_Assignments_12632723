# ESE5023\_Assignments\_12632723

1\.代码逻辑正确，建议补充注释

2\.当c1 != r2，代码打印报错信息，但是仍然返回预先初始化的零矩阵，容易造成误解。

改进：不应该返回无效零矩阵，可以用return None或者抛出异常。

np.zeros默认浮点数，结果会带.0。题目是整数矩阵，改成dtype=int。


3\.原代码公式的下标理解错误，浮点数除法会带小数，导入位置不合理；(-2分）


4\.代码逻辑正确，建议加上注释


5\.代码逻辑正确，但是多重for循环效率较低，可扩展性差。

建议作业独立完成，不要过度依赖AI工具


HW3 Comments from Yali 

Total: 45/50

1.1 Your plot is missing the colorbar, I don't know that the mean of different colors.(-1p) 
1.2 You don’t consider weighting by area(or latitude), and the pole area should has smaller weight. Also your unit is wrong! ppb reprents 1e-9, your data should multiply 1e9 to convert to ppb. (-4p)
1.3 Your consdiering about means with four grid is very careful. Good! (+1p), But your unit is still error...(-1p)

2.1. I  think plots may be more clear. Also you don’t print SST monthly climatology.(-1p)
2.2 Figure is very clear! (+1p)

3.Your figure is very nice! If there are some more detailed explanations, that’s would be better.



