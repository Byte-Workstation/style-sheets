# Vuepress Default Theme Fix SCSS

......

> vuepress是一个很优秀的静态网站生成器

> vuepress的默认主题还不够理想

> vuepress的第三方主题让人看得眼花缭乱

> 自己开发一个vuepress主题又显得太过繁琐

于是就有了这张针对**阅读体验**优化的scss样式表

## 修改内容

- 调亮了暗色模式下的前景色
- 调整顶栏的样式（去除下边框，加模糊效果）
- 把Mobile模式下的侧边栏按钮及其运行机制加到了桌面模式   (*1)
- 调整内容的显示宽度（740px -> 800px）

> *1: 原本桌面模式的侧边栏是固定的，这就导致正文在偏右侧而不是屏幕的中心，作者表示非常不爽

## 使用方法
- 下载
- 把index.scss丢到项目中的.vuepress/styles文件夹中
- dev一下看看喜不喜欢
