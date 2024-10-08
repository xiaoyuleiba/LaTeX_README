# 一个 LaTeX 用法的中文备忘录

Word写作业多了之后, 若是一个大文本长期在同一个设备编辑, 就感觉会突然卡顿, 重启也没用, 但是换个设备就恢复了. 而且排版控制经常自动崩溃, 包括但不限于:
* 题注序号突然开始只能生成 1
* 字体自行变化
* 自行重新排版

若是对格式要求不高还行, 若是有一定需求就总会想着:
> ### **我亲爱的作业, 你已经长大了, 该学会自动排版了.**

于是乎, LaTeX 的登场便是顺理成章了. LaTeX开源免费, 功能强大, 但是过于强大, 入门速度较Word等更慢. 各类LaTeX编辑器对系统资源的消耗更小, 也就对电池 (星巴克氛围组) 友好.

本备忘录是留给自己的一个用法总结: 插图, 交叉引用, 快捷键, 化学式, 公式, 日语编排, 等等. 它的目的是满足一个 (物理) 化学系学生的作业需要, 论文需要, 以及毕业需要.

有缘人若是看到了, 也希望能帮到你. 但是你都能找到这里了, 我觉得也帮不到你多少了.

这个备忘录更新较少, 但我平常在用的功能是确确实实在一点点增加.

之后的更新计划, 那也要等到我闲下来, <mark>可能是2024年10月及以后吧, 也就是做完实验之后, 或者是本科毕业之后</mark>.

## 已有的代码示例:
* `pdf` 文件加密
* SI单位
* 公式
* 抄写 (用于引入代码等)
* 化学 (方程) 式
* 数学符号
* 附录生成
* 颜色的引入
    * 背景颜色调整
    * 文字颜色调整
        * 主要是因为编辑器的背景色不一定是白色, 左边代码右边内容色差大了眼睛难受
* 行距调整
* 文本框
* 初步的表格生成
    * Excel内容的初步导入
    * Excel背景色等的再现
* 交叉引用
* 超链接
* 插入图片
    * 普通图片
    * 子图
* 列表
    * 有序列表
    * 无序列表
* `ctex` 文档类基本使用方法
* `jscls` 文档类基本使用方法
    * 可能会被删除, 因为在大部分场合可以被 `bxjscls` 和 `jlreq`替代: MiKTeX 对 (u)pLaTeX 兼容性很差.

* ~~多种LaTeX引擎名输出 (这玩意没什么必要)~~
* ~~脚注样式加强 (这玩意也没什么必要)~~

## 预计加入的内容
* 对已加入内容的整理, 优化与补充
    * 公式和SI单位的很多东西会被推倒重来, 现在回去看感觉当时写的时候很多东西还不成熟.
* 文字围绕图片
* Font Awesome
* 三线表
* `.svg`图片导入
* `bxjscls`文档类基本使用方法
* `jlreq`文档类基本使用方法
* 定义颜色名
* 指定文档类的使用
* 双栏对照
* `pandoc` + `Zettlr` + `LaTeX` 套件的使用方法: 快速写作业时的首选
* etc.
### 预计很久以后加入的内容
* `tikz`的超基本用法
* `beamer`的超基本用法
    * 模板的选择与修改
    * 遮罩控制
    * 视频等动态元素的导入
    * pdf放映软件测评

##
这些东西其实都有很多更好的 (中文) 教程, 我也只不过是边学边写拾人牙慧罢了.
