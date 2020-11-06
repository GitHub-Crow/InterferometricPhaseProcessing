# 平地相位去除

### Idea

- 通过相位信息重建时间序列
- 分别对方位向和距离向进行平地相位去除
- 选取平地相位去除后的相位图像

### result

![image-20200720131400493](C:\Users\sfpotato\AppData\Roaming\Typora\typora-user-images\image-20200720131400493.png)

# 定位

### idea

- 利用主图像和辅图像斜距方程以及主图像的多普勒方程解出PT的位置
- 然后利用初始值找到距离初始值最近的解作为PT的定位位置

### result

- $PT = [884608.50 \ \ -4306564.21 \ \  4606004.50]$
