# 蓝天云自动续费

使用Github Action自动续费蓝天云，免费易用<br>

作者：**[XJHya](https://github.com/xjh2009)**<br>
B站，抖音，名字不一，转载请注明作者<br>

## 使用方式

### Fork本项目
Fork本项目<br>
#### 启动Action
进入您自己的项目，点击Action，启用Github Action功能<br>

### 添加续费任务
renewid.json文件，添加你的产品ID
<br>
```json
[
  "114514",
  "1919810"
]
```
文件提交后，自动进入Github Action构建

### 定时执行
修改/.github/workflows/renew.yaml文件 <br>
每日北京时间6点自动续费<br>
