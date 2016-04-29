# Homework-6  
##摘要
炮弹的运行轨迹在没有空气阻力，不考虑科里奥利力及其它因素时会以一个抛物曲线运动，若考虑空气阻力，炮弹的运动比较复杂，我们来考虑在没有空气阻力和有空气阻力的情况下的数值解，拉描绘炮弹的运动曲线。  
给出一个简单的模型，炮弹在一个平面内运动，可视为质点，仅仅考虑重力和空气阻力的情况下给出解。
##正文
1.不考虑空气阻力  
d^2x/dt^2=0  
d^2y/dt^2=-g  
2.考虑空气阻力
d^2x/dt^2=-fx  
d^2y/dt^2=-fy-g  
同样可以用欧拉法来解决，因为是二阶微分方程，我们可以把二阶微分方程分解为两个一阶微分方程，参考书上给出的方程，进行在五空气阻力和有空气阻力时依据角度的不同进行对比。  
[程序](https://github.com/Wangzhengwhu/Homework-6/blob/master/1.py)  

给出在初速度为700m/s，发射角度在45°时，炮弹在有无空气阻力下的对比。  
![发射角度45°](https://github.com/Wangzhengwhu/Homework-6/blob/master/45.png)  

给出在初速度为700m/s，发射角度在35°时，炮弹在有无空气阻力下的对比。  
![发射角度35°](https://github.com/Wangzhengwhu/Homework-6/blob/master/35.png)  
给出在初速度为700m/s，发射角度在55°时，炮弹在有无空气阻力下的对比。  
![发射角度55°](https://github.com/Wangzhengwhu/Homework-6/blob/master/55.png)  





