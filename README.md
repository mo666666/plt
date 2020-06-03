# plt
This repository is built to push me to learn matplotlib <br/>
### plt.scatter(x,y, c='purple', s=50, alpha=0.1, label='train')
绘制散点图：s是点的大小，size的简称；c是color的简称离散图的颜色；alpha是对比度<br/>
### plt.plot(x, y, 'r-', lw=3, label='no weight decay')
r、b是颜色，其后一根-还是--代表是拟合图还是虚线图，lw代表的是拟合线的宽度（linewidth）
### plt.text(-0.25, -1.5, 'no weight decay loss={:.6f}'.format(loss_normal.item(),fontdict={'size': 15, 'color': 'red'}))
编写文字说明，第一个参数是x参数，第二个参数是y参数，第二个是要写的文字，第三个是要表达的一些参数
### plt.ylim((-2.5, 2.5)) ，plt.xlim((-0.1, 0.1))
确定x轴，y轴坐标的范围
### plt.legend()
https://www.cnblogs.com/lfri/p/12248629.html
### plt.close()
没啥用，对于多个imshow
