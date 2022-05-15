# duifene_check-in_tool

早上起不来？上课不想去？老师上课会签到？没关系，只要一个群体中有一个人去上课，在工具中输入老师给的对分易签到码，就可以帮助所有人成功签到！（能坚持上课当然要去了，这个只是备用方案啦。）

## 部署说明

```python
https://github.com/rainb0w-q/duifene_check-in_tool.git
cd duifene_check-in_tool
pip3 install -r requirements.txt
python3 main.py
```

接着访问1012端口即可：

```
http://localhost:1012/
```

## 特别说明

在添加成员时，studentid的值可以通过如下方式得到：

登陆对分易并随意点击进入一门课中的考勤模块：

![1](D:\duifene_Group_check-in_tool\images\1.jpg)

接着在控制台中输入如下语句即可得到studentid的值：

![2](D:\duifene_Group_check-in_tool\images\2.jpg)

## 运行截图（部分）

![image-20220515140433409](D:\duifene_Group_check-in_tool\images\3.png)

![image-20220515140517374](D:\duifene_Group_check-in_tool\images\4.png)

![image-20220515140544380](D:\duifene_Group_check-in_tool\images\5.png)

![image-20220515140611001](D:\duifene_Group_check-in_tool\images\6.png)