# update log
* 1.2.7 新增摇一摇开启日志（仅钉钉）
* 1.2.6 功能只留下 关闭、情况、刷新
* 1.2.5 点击单条log现在可以直接格式化显示，且自动复制到剪贴板，方便拷贝

# 简介
* 手机web调试工具

## 具有如下功能：

* 刷新页面
	当前页面的`window.location.reload();`

* 打印代码中的log信息
	调用`dinglog.log(String or JSON);`

* 可执行代码

	````
		dinglog.run("弹出alert",function(){
			alert(1);
		});
	````

# 安装

````
	tnpm install @ali/dinglog --save

````


# 使用

````
	var Dinglog = require("@ali/dinglog");

	Dinglog.log("first log");

````




## 效果图1 关闭状态
<img src="https://static.dingtalk.com/media/lADOB4to6M0EcM0CgA_640_1136.jpg_620x10000q90.jpg" width="400"/>;

## 效果图2 开启状态
<img src="https://static.dingtalk.com/media/lADOB4to580EcM0CgA_640_1136.jpg_620x10000q90.jpg" width="400"/>

