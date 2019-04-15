# pygui_template
pyqt5 template. (Pyside2 may be supported in the future.)

## start

```
pip install pygui_cli
```

or

```
git clone https://github.com/625781186/pygui_cli
cd pygui_cli
python setup.py install 
```



## use

```
tpl add .
```

## styles

quick change theme color : 

```
1.please setup node.exe  // 安装node.exe
2.npm install -g stylus  // 安装stylus模块
3.cd source/styles       // 切换到项目目录
4.rename style.css to style_backend.css  //备份原样式
5.stylus style.styl     // 生成新的样式
```

## Feature

| Function              | Arguments | Type | Default | 翻译               |
| --------------------- | --------- | ---- | ------- | ------------------ |
| SingleApp             |           | Bool | True    | 只允许开启一个程序 |
| CustomFrameLessWindow |           | Int  | 3       | 样式类型           |
| SplashScreen          |           | Bool |         | 启动动画           |
| ErrorLogging          | -         | -    | -       | 异常日志器         |
|                       |           | -    | -       |                    |

|               |      |                              |
| ------------- | ---- | ---------------------------- |
| Settings      |      | 配置文件                     |
| FuncMixin     |      | 常用QT函数给MainWindow继承用 |
| UI_Components |      | 常用UI组件库                 |



## Document/Contribution

()[]



