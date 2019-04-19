# 40LayoutExercise

## 简述

共40个练习，每个练习具体要求见后文。练习成对，即奇数为需要掌握的知识点，偶数只需简单改动布局顺序即可。

所有练习以如下HTML结构为基础（千万不要改动，否则失去练习的意义）

	<div id="container">
		<div id="header">Header</div>
  		<div id="wrapper">
    		<div id="content">Content</div>
  		</div>
  		<div id="navigation">Navigation</div>
  		<div id="extra">Extra stuff</div>
  		<div id="footer">Footer</div>
	</div> 


目前完成了1-40的文档。

使用须知:
1. 使用  templates/index.html 做为导航页
2. 点击左侧 标记顺序码,可以动态加载 相应的的CSS, 同时改变页面的布局。
3. 自行练习只需 修改 templates/css/co{id}.css 文件,点击对应的按钮{id}即可加载结果。

#### 示例图

![image](https://github.com/dodoru/40LayoutExercise/blob/master/templates/img/sp_12.png?raw=true)


## 练习

### 1. Three percentage columns(n.1)  

#### 要求

1. wrapper 居中且占据50%宽度
2. navigation、extra 宽度25%，分居content两侧，左侧navigation，右侧extra

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc71c465.png)

### 2. Three percentage columns(n.2)

#### 要求

1. 在1的基础上，调换navigation和extra

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc11e4bb.png)

### 3. Three percentage columns(n.3)  

#### 要求

1. wrapper 左对齐且占据50%宽度
2. extra、navigation宽度25%，依次位于content右侧

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc1248de.png)

### 4. Three percentage columns(n.4)
 
#### 要求

1. 在3的基础上，调换navigation和extra

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc135b22.png)
	

### 5. Three percentage columns(n.5)  

#### 要求

1. wrapper 右对齐且占据50%宽度
2. navigation、extra 宽度25%，依次位于content左侧

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc20cbf1.png)
	

### 6. Three percentage columns(n.6)

#### 要求

1. 在5的基础上，调换navigation和extra
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc216818.png)	
	
### 7. Three fixed columns(n.7)

#### 要求

1. container 宽度700px且居中
2. wrapper 居中且宽度400px
3. extra、navigation 150px，依次位于content两侧

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc5c6615.png)
	

### 8. Three fixed columns(n.8) 
 
#### 要求

1. 在7的基础上，调换navigation和extra
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc5c6e98.png)	
	
### 9. Three fixed columns(n.9)
  
#### 要求

1. container 宽度700px且居中
2. wrapper 左对齐且宽度400px
3. extra、navigation 150px，依次位于content右侧
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc59af23.png)	
	
### 10. Three fixed columns(n.10)
  
#### 要求

1. 在9的基础上，调换navigation和extra

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9bc61c7e7.png)
	
### 11. Three fixed columns(n.11)
  
#### 要求

1. container 宽度700px且居中
2. wrapper 右对齐且宽度400px
3. navigation、extra 150px，依次位于content左侧
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9e0937d7a.png)	
	
### 12. Three fixed columns(n.12) 

#### 要求

1. 在11的基础上，调换navigation和extra
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9df563d0f.png)	
	
### 13. Liquid, secondary columns fixed-width (n.13)
 
#### 要求

1. wrapper 居中且宽度自适应，margin-left及margin-right为200px
2. extra、navigation 宽度200px，分别位于content两侧
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9dfa34cd4.png)	
	
### 14. Liquid, secondary columns fixed-width (n.14)

#### 要求

1. 在13的基础上，调换navigation和extra
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9dfb1a944.png)	
	
### 15. Liquid, secondary columns fixed-width (n.15)  

#### 要求

1. wrapper 左对齐且宽度自适应，margin-right为400px
2. navigation、extra 宽度200px，依次位于content右侧
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9df634e8e.png)	
	
### 16. Liquid, secondary columns fixed-width (n.16) 

#### 要求

1. 在15的基础上，调换navigation和extra

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9dfcb4d2c.png)

### 17. Liquid, secondary columns fixed-width (n.17)（开始float：right）  

#### 要求

1. wrapper 右对齐(float:right)且宽度自适应，margin-left为400px
2. extra、navigation 宽度200px，依次位于content左侧

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9df840ea1.png)
	

### 18. Liquid, secondary columns fixed-width (n.18) 

#### 要求

1. 在17基础上，调换navigation和extra

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9dfd8cbd3.png)
	

### 19. Liquid, three columns, hybrid widths (n.19)(混合宽度)
  
#### 要求

1. navigation 宽度200px，位于content左侧
2. content margin-left:200px margin-right: 33%
3. extra 宽度33%，位于content右侧

#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9dfcbb973.png)

### 20. Liquid, three columns, hybrid widths (n.19)(混合宽度)

#### 要求

1. navigation 宽度33%，位于content左侧
2. content margin-left:33% margin-right: 200px
3. extra 宽度200px，位于content右侧
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/14/55cd9dfe13b6b.png)	
	
### 21. Liquid, three columns, hybrid widths (n.21)  

#### 要求

1. wrapper margin-left:-25%为extra留出空间 width:100%不能省
2. content margin-left:25% margin-right: 200px为navigation留出空间
3. navigation 宽度200px，位于content右侧
4. extra 宽度25%，位于content右侧

#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d1924ba72bb.png)	

### 22. Liquid, three columns, hybrid widths (n.22) 

#### 要求

1. wrapper margin-left:-200px为extra留出空间
2. content margin-left:200px margin-right: 25%为navigation留出空间
3. navigation 宽度25%，位于content右侧
4. extra 宽度200px，位于content右侧

#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d1924cb6ce6.png)
	

### 23. Two columns liquid, side fixed (n.23)(flaot left|right)

#### 要求

1. wrapper margin-left:-200px为navigation、extra留出空间 width:100%不能省 
2. content margin-left:200px 
3. navigation 宽度200px，位于content右侧 float:right
4. extra 宽度200px，位于content右侧、navigation底部 float:right; clear: right

#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d1924e0e616.png)

### 24. Two columns liquid, side fixed (n.24)(flaot left|right)

#### 要求

1. wrapper margin-right:-200px为navigation、extra留出空间 width:100%不能省 
2. content margin-right:200px 
3. navigation 宽度200px，位于content左侧 float:left
4. extra 宽度200px，位于content左侧、navigation底部 float:left; clear: right
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d1924e5621d.png)	
	
### 25. Two percentage columns (n.25)（float left|right）

#### 要求

1. 23基础上将固定宽度200px换成百分比30%
2. wrapper margin-left:-30%为navigation、extra留出空间 width:100%不能省 
3. content margin-left:30% 
4. navigation 宽度30%，位于content右侧 float:right
5. extra 宽度30%，位于content右侧 float:right clear: right
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d1924d3b9ac.png)	
	
### 26. Two percentage columns (n.25)（float left|right）

#### 要求

1. 24基础上将固定宽度200px换成百分比30%
2. wrapper margin-right:-30%为navigation、extra留出空间 width:100%不能省 
3. content margin-right:30% 
4. navigation 宽度30%，位于content左侧 float:left
5. extra 宽度30%，位于content左侧 float:left clear: left
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d192502d195.png)	
	
### 27. One column liquid and two halves (n.27)

#### 要求

1. wrapper 占满一行 
2. navigation 宽度50%，位于content底部偏左 
3. extra 宽度50%，位于content底部偏右

#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d192505131e.png)
	
### 28. One column liquid and two halves (n.27)

#### 要求
	
1. wrapper 占满一行 
2. navigation 宽度50%，位于content底部偏右
3. extra 宽度50%，位于content底部偏左

#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d19250bd9c5.png)

### 29. Two percentage columns and one larger (n.29)  

#### 要求

1. wrapper margin-right:-30%为navigation留出空间 width:100%不能省 
2. content margin-right:30% 
3. navigation 宽度30%，位于content左侧
4. extra 宽度100%，位于content底部 
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d19251d132a.png)	
	
### 30. Two percentage columns and one larger (n.29)  

#### 要求

1. 在29的基础上，调换wrapper和navigation
1. wrapper margin-left:-30%为navigation留出空间 width:100%不能省 
2. content margin-left:30% 
3. navigation 宽度30%，位于content右侧
4. extra 宽度100%，位于content底部 

#### 图示

![image](https://ooo.0o0.ooo/2015/08/17/55d192538bd5b.png)

---
	
### 31. Two columns liquid, fixed side and large one (n.31)
  
#### 要求
	
1. 在29基础上，把百分比宽度30%换成固定200px
2. wrapper margin-right:-200px为navigation留出空间 
3. content margin-right:200px 
4. navigation 宽度200px，位于content左侧
5. extra 宽度100%，位于content底部 
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2ee89ea4a1.png)

### 32. Two columns liquid, fixed side and large one (n.32)
  
#### 要求

1. 在30基础上，把百分比宽度30%换成固定200px
2. wrapper margin-left:-200px为navigation留出空间 
3. content margin-left:200px 
4. navigation 宽度200px，位于content右侧
5. extra 宽度100%，位于content底部 

#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2ee92bda19.png)

### 33. Two colums fixed (n.33) 

#### 要求

1. 23的扩展，增加container宽度700px，实现方式可简化，因为宽度固定  
1. container 居中且宽度700px
2. wrapper 宽度500px
3. navigation 宽度200px，位于content右侧 float:right
4. extra 宽度200px，位于content右侧 float:right; clear: right
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2ee8e86837.png)	
	
### 34. Two colums fixed (n.34) 
 
#### 要求

1. 24的扩展，增加container宽度700px，实现方式可简化，因为宽度固定 
1. container 居中且宽度700px
2. wrapper 宽度500px
3. navigation 宽度200px，位于content左侧 float:left
4. extra 宽度200px，位于content左侧 float:left; clear: left
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2ee8e9cc3f.png)	
	
### 35. Two colums fixed (n.35)

#### 要求

2. container 居中且宽度700px
3. wrapper 宽度500px
4. navigation 宽度200px，位于content右侧 float:right
5. extra 宽度100%，位于content底部（思考clear取值）
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2ee8ee19ae.png)	
	
### 36. Two colums fixed (n.36) 

#### 要求

2. container 居中且宽度700px
3. wrapper 宽度500px
4. navigation 宽度200px，位于content左侧 float:left
5. extra 宽度500px，位于content底部

#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2ee8faa157.png)

### 37. Two colums fixed (n.37) 

#### 要求
	
1. container 居中且宽度700px
2. wrapper 宽度500px
3. navigation 宽度200px，位于content右侧 float:right
4. extra 宽度100%，位于content底部
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2ee9e951d7.png)	
	
### 38. Two colums fixed (n.38) 

#### 要求

1. 37基础上调换wrapper和navigation顺序
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2eea1dc5ba.png)	
	
### 39. One column fixed and two halves (n.39)  

#### 要求
	
1. container 居中且宽度700px
2. wrapper 宽100%
3. navigation 宽度50%，位于content底部偏左 
4. extra 宽度50%，位于content底部偏右
	
#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2eea066350.png)	
	
### 40. One column fixed and two halves (n.40) 

#### 要求

1. 39基础上调换navigation和extra顺序

#### 图示

![image](https://ooo.0o0.ooo/2015/08/18/55d2eea062b91.png)
