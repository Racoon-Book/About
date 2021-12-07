# 浣熊财记 更新日志

- [浣熊财记 更新日志](#浣熊财记-更新日志)
  - [v1.0.5 (109)](#v105-109)
  - [v1.0.3 (106)](#v103-106)
  - [v1.0.2 (103)](#v102-103)
  - [v1.0.1 (102)](#v101-102)
  - [v1.0.0 (100)](#v100-100)

## v1.0.5 (109)

* 添加了主页的月份选择框
  * added `DatePicker` in `BookTab`
* 重构了侧边栏的选项
  * changed `SideMenu` to `MeTab`
* 关闭了黑夜模式的自动适配
  * disabled dark mode

## v1.0.3 (106)

* 修改了 App Store 的显示语言为简体中文
  * changed `Development Language` from `English` to `Chinese`
* 纠正了关于页面错误的信息
  * fixed inaccurate name in `AboutSideMenu`

## v1.0.2 (103)

* 优化了未添加财记时财记页面的显示
  * bettered background of `StoryTab` if no story exists

## v1.0.1 (102)

* 关于页面添加当前版本信息
  * added version and build information in `AboutSideMenu`
* 修复了原始输入转换为事件时的处理
  * `func OriginalText2Event(from originalText: String) -> String?` return nil if `originalText` not successfully converted

## v1.0.0 (100)

* 浣熊财记正式上架 `App Store`
  * 记账快捷简单：截图一键导入，语音智能识别
  * 沉淀生活轨迹：花销折射生活，财记凸显回忆
  * 定制标签关注：标签多维管理，关注核心呈现
  * 注重情感体验：浣熊相伴成长，成就激励前行