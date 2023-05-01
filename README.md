# 项目名称
开发适用于触屏电脑交互操作的 Linux 图形界面
# 项目描述
经过多年的发展，以 KDE、GNOME 为代表的 Linux 桌面操作系统已逐步成熟。在手机方面，近年来也衍生出了诸如 KDE Plasma Mobile、PureOS、Tizen、Kai OS 等多种开源的图形用户界面。但是针对大屏设备触摸操作优化的开源图形界面仍待提高，本项目的目标就是实现一个针对大屏触控交互进行优化的图形界面。
# 所属赛道
2021全国大学生操作系统比赛的“OS功能设计”赛道
# 参赛要求
以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求
### 项目导师
* 张晓飞
  * github: FelixZhang
  * Email: zhangxf@dingdaoos.com
* 金燕江
  * github: jinyanjiang
  * Email: jinyj@dingdaoos.com
### 难度
中等
# 特征
* 参照当前主流的平板电脑图形界面设计
* 基于Kwin窗口管理器实现
# 文档
# License
GPLv2
# 预期目标
以下内容为建议目标，不要求全部完成。参与项目的同学也可向导师提出新想法，达成一致后可加入预期目标
* 默认全屏打开应用

  ![打开与退出应用](/images/打开与退出应用.gif)
* 主屏幕显示全部App图标
* 底部程序坞
  * 自动隐藏
  * 自动展示收藏程序和常用程序图标
* 随位置上下文变化样式的动态光标

  ![动态光标](/images/动态光标.gif)
* 下拉式控制中心，参照iPadOS

  ![控制中心](/images/控制中心.gif)
* 通知中心，参照iPadOS

  ![通知中心](/images/通知中心.gif)
* 针对触控操作，优化全局 UI 元素
  * 调整控件尺寸
  * 长按特定控件（如输入框、图标），弹出上下文菜单
* 实现以下触控手势：
  * 从下边缘轻扫至屏幕中心停顿，打开 App 切换器

    ![多任务](/images/多任务.gif)
  * 从下边缘向上轻扫，回到主屏幕
  * 三指捏合，回到主屏幕

    ![多任务-关闭应用](/images/多任务-关闭应用.gif)
  * 从右上角向下轻扫，打开下拉式控制中心

    ![控制中心](/images/控制中心.gif)
  * 从顶部除右上角外的位置向下轻扫，打开通知中心

    ![通知中心](/images/通知中心.gif)
  * 沿下边缘左右横扫，切换 App
  * 当应用打开时，从下边缘向上轻扫一指宽停顿，打开程序坞
  * 沿左边缘侧拉，划出 Widget，并重新布局主界面

    ![插件](/images/插件.gif)
  * 提供在桌面电脑与平板电脑交互模式之间切换的能力
# 附录

