# 1903zfstudy
1903 项目
一个简单的弹出提示框
 	var obj={
			id:'duihuakuang',
			_w:"400",
			_h:"200",
			biaoti:"zhangfan",
			neirong:"hahh",
			yinyingyanse:"black",
			yinying_x:"2",
			yinying_y:"2",
			yingying_around:"10"
	}
    id:组件id名;
    _w:提示框宽度
    _h:提示框高度
    biaoti:提示框标题
    neirong:提示框内容
    yinyingyanse: 提示框外阴影颜色
    yinying_x:水平阴影的位置。允许负值。
    yinying_y:垂直阴影的位置。允许负值。
    yingying_around:模糊距离
    
  new Alert(obj);//实例
  元素默认隐藏,需要通过事件监听激活
  如:
  var tanchu =document.getElementById("tanchu");
		tanchu.onclick=function(){
			var duihuakuang=document.getElementById("duihuakuang");
			console.log(duihuakuang)
			duihuakuang.style.display="block";
		}
		
