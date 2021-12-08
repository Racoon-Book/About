# 浣熊财记 更新日志

> 浣熊财记更新日志
> 
> 注：英文部分为开发者备注

- [浣熊财记 更新日志](#浣熊财记-更新日志)
  - [v.1.1. (111)](#v11-111)
  - [v1.0.5 (109)](#v105-109)
  - [v1.0.3 (106)](#v103-106)
  - [v1.0.2 (103)](#v102-103)
  - [v1.0.1 (102)](#v101-102)
  - [v1.0.0 (100)](#v100-100)

## v.1.1. (111)

* 优化日期的处理
  * 添加和修改财记时可以选择日期
    * added `DatePicker` in `ExpenseSheet`
  * 重构了日期的处理
    * removed `DateInRegion` and use `Date` instead
  * 更好的支持了语音添加之前（昨天/上周/上个月）的账目
    * fixed bugs in `OriginalText2SpentAt()`
* 优化界面UI
  * 添加了语音输入时主页的模糊效果
    * added blur in `BookTab`
  * 美化了统计界面上方的选择窗口
    * added padding above `SegmentPicker` in `ReportTab`
  * 优化了统计界面的计数
    * fixed logic bug in `StoryReportView` and added one more item
  * 增大了语音输入的确认按钮
    * made buttons in `VoiceInputView` larger

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