# heatmap-d3
通过d3.js实现的heatmap，展示年-月-温度

#### 概览

```
project
|	readme.md
|----d3	// 引用的d3库
|	|----d3.min.js
|	index.css
|	challenge1.html	// 第一个demo
|	challenge2.html	// 第二个demo
|	temperature.json	// json数据文件
|	temperature.xlsx	// 未转换成json之前的数据文件
|	xlsxToJson.py	// 转换数据的python脚本
|----img
	|----challenge1.png	// 第一个demo图片
	|----challenge2.png	// 第二个demo图片
```

#### Tip

1. 用python脚本对数据的处理，没有使用d3自带的d3.json、d3.csv等；建议可以试一下。
2. 由于浏览器存在跨域问题，读取本地json采用了上传文件的方式，打开网页以后选择json数据文件。
3. 格子颜色代表当月每天最高温度或者最低温度的平均数，即json中的average，title里的平均温度。

#### Challenge1

![image](https://github.com/awefeng/heatmap-d3/blob/master/img/challenge1.png)

#### Challenge2

![image](https://github.com/awefeng/heatmap-d3/blob/master/img/challenge2.png)
