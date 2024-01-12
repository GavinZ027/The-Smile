# 导入turtle模块
import turtle

# 创建一个画笔
pen = turtle.Turtle()

# 定义一个绘制眼睛的函数
def eye(col, rad):
    # 放下画笔
    pen.down()
    # 设置填充颜色
    pen.fillcolor(col)
    # 开始填充
    pen.begin_fill()
    # 画一个圆
    pen.circle(rad)
    # 结束填充
    pen.end_fill()
    # 抬起画笔
    pen.up()

# 绘制笑脸的轮廓
# 设置填充颜色为黄色
pen.fillcolor('yellow')
# 开始填充
pen.begin_fill()
# 画一个半径为100的圆
pen.circle(100)
# 结束填充
pen.end_fill()
# 抬起画笔
pen.up()

# 绘制笑脸的眼睛
# 移动到左眼的位置
pen.goto(-40, 120)
# 调用eye函数，绘制一个白色的圆，半径为15
eye('white', 15)
# 移动到左眼的中心
pen.goto(-37, 125)
# 调用eye函数，绘制一个黑色的圆，半径为5
eye('black', 5)
# 移动到右眼的位置
pen.goto(40, 120)
# 调用eye函数，绘制一个白色的圆，半径为15
eye('white', 15)
# 移动到右眼的中心
pen.goto(40, 125)
# 调用eye函数，绘制一个黑色的圆，半径为5
eye('black', 5)

# 绘制笑脸的鼻子
# 移动到鼻子的位置
pen.goto(0, 75)
# 调用eye函数，绘制一个黑色的圆，半径为8
eye('black', 8)

# 绘制笑脸的嘴巴
# 移动到嘴巴的左边
pen.goto(-40, 85)
# 放下画笔
pen.down()
# 设置画笔的方向为右
pen.right(90)
# 画一个半径为40，角度为180的弧线
pen.circle(40, 180)
# 抬起画笔
pen.up()

# 绘制笑脸的舌头
# 移动到舌头的位置
pen.goto(-10, 45)
# 放下画笔
pen.down()
# 设置画笔的方向为左
pen.right(180)
# 设置填充颜色为红色
pen.fillcolor('red')
# 开始填充
pen.begin_fill()
# 画一个半径为10，角度为180的弧线
pen.circle(10, 180)
# 结束填充
pen.end_fill()

# 隐藏画笔
pen.hideturtle()
