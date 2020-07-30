可能报错的地方以及解决方案

旧版OpenCV：返回三个参数

image, contours, hierarchy = cv2.findContours(mask, cv2.RETR_TREE, cv2.CHAIN_APPROX_SIMPLE)
1
新版OpenCV：返回两个参数

contours,hierarchy = cv2.findContours(thresh,cv2.RETR_TREE,cv2.CHAIN_APPROX_SIMPLE)



# turtle_draw

python将图片进行边缘检测和轮廓提取进行turtle绘画

1. 你需要安装opencv，在cmd中输入：**pip3 install opencv-python**

2. 要使用需要将图片放置在和py同一个文件夹下，接着修改下面的pic后的参数为图片名字。

   ```
   if __name__ == "__main__":
    	pic = "image.jpg"
    	xy = array_pic(pic)
   	 draw(xy)
   ```

3. 效果如下图所示



![](https://gitee.com/hongcyu/image/raw/master/images/image.jpg)

变成

![2313S1](https://gitee.com/hongcyu/image/raw/master/images/2313S1.PNG)
