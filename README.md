网页缩放检测
=========

> 简介：基于jQuery的返回顶部控件，使用方法简单，只需要Back2top.init()即可


----------

##使用方法


	在sass文件中引用样式
	@import "components/back2top/back2top.css";

	var WebpageZoomDetect = require('back2top');

##api方法

###Back2tip.init(timeInterval)

####一、接口功能

	通过init方法即可初始化并使用该返回顶部的组件。如果用户需要自定义样式，可以直接更改back2top.css文件。

####二、参数说明

	/**
	 * 初始化，可控制动画时间
	 * @param {Integer}     timeInterval  动画时间，可选，默认300ms
	 */

####三、示例
1、初始化组件

	// 初始化
	Back2top.init();

2、指定动画时间

	// 初始化并指定动画时间为500ms（默认：300ms）
	Back2top.init(500);





