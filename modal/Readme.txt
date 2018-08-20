1.使用该原件需要引入的文件有：animate.css  animate.js  modal.css  modal.js

2.该弹窗元件支持amd || commonjs || Global;


3.对外的两个API接口为show、hide;


4.实例化格式为：
var modal=new Modal({
content="内容"；

animation:{
	enter:'bounceIn',
	leave:'bounceOut'  //动画效果依赖css3动画库，若要更改请自行查看动画库说明
}
})

4.弹窗的样式（包括大小，颜色等可以重构），在modal.css中进行修改，重构可使用
modal.html，将注释部分的结构显示出来。