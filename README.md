![这里写图片描述](https://raw.githubusercontent.com/xiangshuo1992/play-flexbox/master/images/icon48.png)**play-flexbox**

一秒搞定flexbox布局，可直接预览效果，拷贝CSS代码快速用于页面重构。

![这里写图片描述](https://raw.githubusercontent.com/xiangshuo1992/play-flexbox/master/images/2.gif)

你也可以通过点击以下链接（codepen示例）查看插件效果。
https://codepen.io/xiangshuo1992/pen/EovGQe


如何使用
------------
这里的使用方法是基于该扩展程序没有上线到商店，通过本地打开使用。

第一步：下载<br/>
在我的项目 https://github.com/xiangshuo1992/play-flexbox 下载源代码并解压。（顺手给个star，感谢）

![这里写图片描述](http://img.blog.csdn.net/20180105173023439?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzc3ODkwNQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

第二步：打开Chrome浏览器，打开扩展程序<br/>
也可以直接打开 chrome://extensions/

![这里写图片描述](http://img.blog.csdn.net/20180105200140854?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzc3ODkwNQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)


第三步：安装扩展程序<br/>
在解压后的文件中找到 `play-flexbox.crx` 文件，然后将该文件拖入浏览器 chrome://extensions/ 扩展程序中，浏览器会提示安装，确认添加插件就好，接下来你会在你的浏览器右上角看到这只猴子，点击进行使用。

![这里写图片描述](http://img.blog.csdn.net/20180110165310390?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzc3ODkwNQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

注：如果你想安装并调试该插件，可以先勾选开发者模式，然后导入解压的文件夹，就可以看到这个插件的图标出现在浏览器右上角了，当然你先要确保已经删掉了之前用安装包安装的插件，接下来你在编辑器中修改了代码，在这个插件下面点击重新加载就可以刷新。

![这里写图片描述](http://img.blog.csdn.net/20180105203218347?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzc3ODkwNQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

第四步：选择布局方案<br/>
通过下拉框来选择自己需要的布局方案，这里以水平垂直方向都居中，项目等分为例。

![这里写图片描述](http://img.blog.csdn.net/20180105205943992?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzc3ODkwNQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

第五步：拷贝CSS代码用于重构布局样式<br/>
父容器是“flex-wrap”，项目是“item”，这里的类名根据开发情况自行调整，样式对应起来就行。

![这里写图片描述](http://img.blog.csdn.net/20180105210656865?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzc3ODkwNQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

Vue的CSP环境
------------
只需要在 manifast.json 里面添加配置即可
```
"content_security_policy": "script-src 'self' 'unsafe-eval'; object-src 'self'"
```
