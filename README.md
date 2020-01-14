# Demo
13.##图片自适应
背景图片自适应：background-size:cover/contain   </br>
图片自适应：object-fit 属性值object-fit:fill/contain/cover/none/scale-down   </br>
fill:默认值，填满不保证保持原有比例   </br>
contain:保持原有比例，会留白  </br>
cover: 保持原有比例，拿中间部分，部分区域不可见   </br>
none:保持原有比例，同时保持替换内容原始尺寸大小   </br>
scale-down:保持原有尺寸比例，如果容器尺寸大于图片内容尺寸，保持图片原有尺寸，不会放大失真；容器尺寸小于图片内容尺寸，用法和contain一样  </br>
-----------------------------------------------------我是分割线---------------------------------------------------------- </br>
可以使用的一些示例

1.利用伪元素做的照片展示     </br>

2.类似下围棋的小Demo     </br>

![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/playchess.png)   </br>

3.HTML5利用Canvas模拟上下扫描动画实现     </br>

![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/san.png)   </br>

4.tab导航向左滑动切换页面     </br>

![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/mui-tab.png)   </br>

5.弹出框后加蒙版    </br>

![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/tanchumengban.png)   </br>

6.animate动画滑出侧边栏     </br>

![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/animate-siderbar.png)   </br>

7.日历签到打卡，转盘抽奖    </br>

![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/Attendance-Calendar1.png)   </br>

![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/Attendance-Calendar2.png)   </br>

8.日历插件使用            </br>    

![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/bootstrap-datetimepicker1.png)   </br>

9.div+css可以实现图片等比例缩放      </br>
div style="width:50px;height:40px"  div  </br>  
img{
 width:auto;
 height:auto;
 max-width:100%;
 max-height:100%;
}
根据上面4个css可以知道：    </br>
图片被缩放后在div的尺寸是：    </br>
width:50px;（因为图片的width:100%）    </br>
height:50px（这里height是在width:100%被缩放后的尺寸。）    </br>
我们可以发现这个50px的高度仍然超出了div的40px的高度,不符合max-height    </br>
这个时候，max-height:100%;就会发挥作用，    </br>
在max-height:100%;的作用下，图片被缩放后在div的尺寸是：    </br>
width:40px;    </br>
height:40px;    </br>
这个尺寸符合max-height和max-width    </br>

10.css显示图片中间区域</br>
![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/picturemode2.png)   </br>
![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/picturemode1.png)   </br>
![image](https://github.com/bellee/Demo/blob/master/readme_add_pic/picturemode3.png)   </br>


11.pullDemo
使用mui模版做的下拉刷新功能

12.几种常见的loading

