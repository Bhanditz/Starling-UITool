Starling-UITool
===============

StarlingUI导出工具。 需要FlashPro作为编辑器。 导出SWF然后读取数据。
<<<<<<< HEAD
-----------------------------------------------------------

以前搞页游的时候 用flash的反射机制做UI很轻松。现在使用starling资源需要是位图。所以反射机制用不了了。
此工具就是为了解决这个问题。虽然还不完善但是已经实现了一些功能。不过需要使用该账号下的starlingFeathers包.

工具目前支持
image,sprite,button,textfield,batch,9宫格

因为工具不是基于jsfl的。所以需要导出的项目需要设置Class名。

需要注意的是。用于布局的元素 需要是独立的有点类似骨骼动画。这些独立的元素在导出之后会是一张张单独的图片。这些等于是素材
			
			而由素材组成界面布局 需要在帧上加一个标签。表示它为一个布局信息。
			
			sprite，button，batch需要加标签
			
			image，9宫格不需要加标签
			
			textfield 直接使用文本即可。不过需要设置文本必须是Dynamic Text.(支持文字颜色。大小，字体)
			

工具飞


=======

导出的数据使用StarlingFeathers下的lzm.starling.ui.layout.LayoutUitl解析
>>>>>>> 370ac861cb01675db7fc050d39e5065e5611c950
