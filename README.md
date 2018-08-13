# vue.js-devtools
1. **第一步**
先打开谷歌的应用商店，在里面找到 vue.js devtools 这个插件,安装完成后会在右上角有 1 代表 **vue** 的图标，是灰色的，表示不可使用。
2. **第二步**
右键那个**vue**的灰色图标，点击管理扩展工具，顶上有一栏是开发者模式，打开这个模式，然后复制里面的**id**.
3. **第 3 步**
打开我的电脑，在里面搜索刚刚复制的id，在C盘里面搜索（会搜索很久），然后打开搜索到的文件![像这个样子](http://www.cnplugins.com/cdn/170517/1-1F51G03S91D.jpg)
4. **第 4 步**
将mainfest.json中代码persistent：false，修改成persistent：true。如下图所示：![](http://www.cnplugins.com/cdn/170517/1-1F51G050025F.png)

**到了这一步**你点击那个**vue**的图标，因为你是使用js引入的 vue.js(**如果是npm 安装的话一般就没问题了**) ,会显示你的vue.js的版本是生产模式的，所以要替换成开发模式。

**这里有开发模式的版本**直接复制到原来的位置:开发版本：https://vuejs.org/js/vue.js
