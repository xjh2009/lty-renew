# 蓝天云自动续费

~~使用Github Action自动续费蓝天云，免费易用~~<br>

作者：**[XJHya](https://github.com/xjh2009)**<br>
B站，抖音，名字不一，转载请注明作者<br>

## Tips
因为蓝天云封禁了这种方式我们只能归档了
所以最新解决请前往[自动签到/续费合集](https://github.com/xjh2009/all-sign-renew)<br>
![](/doc/635bbbb55f06a3b5871b0db65dfb6e44.jpg) <br>
~~因为蓝天云使用的是CloudFlareCDN会导致Github节点无法向蓝天云请求内容~~<br>
~~所以运行时可能会导致无法续费~~<br>
~~如果你拥有闲置的国内CDN/虚拟主机/服务器也可以提供给我们用于维护这个项目~~

## 使用方式

### Fork本项目
~~Fork本项目~~<br>
#### 启动Action
~~进入您自己的项目，点击Action，启用Github Action功能~~<br>

### 添加续费任务
~~renewid.json文件，添加你的产品ID~~
<br>
```json
[
  "114514",
  "1919810"
]
```
~~文件提交后，自动进入Github Action构建~~

### 定时执行
~~修改/.github/workflows/renew.yaml文件~~ <br>
~~每日北京时间6点自动续费~~<br>

## 相关项目
[自动签到/续费合集](https://github.com/xjh2009/all-sign-renew)<br>
[海绵联机自动签到](https://github.com/xjh2009/hmmc-renew)<br>
[雨云自动续费](https://github.com/xjh2009/rainyun-renew)<br>
