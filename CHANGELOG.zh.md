<p align="right">
  <a href="./CHANGELOG.md">English</a>
</p>
<!--rehype:style=float: right; bottom: -36px; position: relative;-->

更新日志
===

<a target="_blank" href="https://jaywcjlove.github.io/maslink/?id=6745227444" title="Musicer for macOS">
<img alt="Musicer AppStore" src="https://jaywcjlove.github.io/sb/download/macos.svg" height="51">
</a>

## [v3.5.0](https://github.com/jaywcjlove/musicer/releases/tag/v3.5.0)

1. feat: 新增比特率和采样率显示。
2. fix: 修复新窗口无法正确置顶的问题。
3. fix: 修复因采样率不匹配导致 FLAC 文件无法播放的问题。
4. fix: 修复迷你窗口的布局样式问题。
5. chore: 优化多语言本地化显示。
6. chore: 修复多个构建警告。

## [v3.4.0](https://github.com/jaywcjlove/musicer/releases/tag/v3.4.0)

1. feat: 优化文件及文件夹重命名相关问题的处理逻辑
2. feat: 新增德语翻译支持

## [v3.3.0](https://github.com/jaywcjlove/musicer/releases/tag/v3.3.0)

1. feat: 新增音频输出设备选择功能
2. feat: 列表新增音乐文件无法读取状态标识
3. perf: 优化列表渲染偶发卡顿问题

## [v3.2.1](https://github.com/jaywcjlove/musicer/releases/tag/v3.2.1)

1. pref: 优化长时间循环播放导致的偶发性卡顿
2. fix: 修复 macOS 27 菜单项图标不显示问题

## [v3.2.0](https://github.com/jaywcjlove/musicer/releases/tag/v3.2.0)

1. feat: 隐藏标准和大封面模式下的关闭按钮，鼠标悬停时才显示。
2. feat: 增加均衡器功能，支持调节音效。
3. feat: 播放列表新增搜索功能。
4. feat: 优化歌词翻译与逐字滚动（卡拉OK）的显示效果。
5. fix: 列表加载后自动选中第一首歌曲。
6. fix: 修复设置中“隐藏文件夹”切换状态无法保存的问题。
7. fix: 修复播放列表上方区域无法拖动窗口的问题。

## [v3.1.0](https://github.com/jaywcjlove/musicer/releases/tag/v3.1.0)

1. feat: 新增曲目信息编辑窗口，支持修改曲目标签
2. feat: 新增经典、柱状、胶囊、分段式四种进度条样式
3. feat: 新增曲目无缝衔接播放功能
4. feat: 新增六种应用系统语言本地化适配
5. feat: 新增可移动桌面歌词功能
6. feat: 新增卡拉OK歌词同步及可锁定桌面悬浮层功能
7. fix: 修复状态栏专辑封面不显示的问题，恢复正常展示
8. fix: 关闭播放器窗口外围蓝色聚焦高亮边框

## [v3.0.0](https://github.com/jaywcjlove/musicer/releases/tag/v3.0.0)

1. 性能：优化音乐列表性能
2. 性能：提升播放响应速度与切歌流畅度
3. 样式：优化波形图视觉样式
4. 样式：优化拖拽交互样式
5. 修复：恢复空格键播放/暂停快捷键，加快列表滚动速度
6. 修复：修正列表选中播放、悬浮状态及播放指示标识
7. 修复：在系统正在播放组件中展示专辑封面
8. 修复：消除编译警告兼容 macOS 27

## [v2.2.0](https://github.com/jaywcjlove/musicer/releases/tag/v2.2.0)

1. perf: 优化性能，降低音乐播放动画导致的 CPU 占用

## [v2.1.0](https://github.com/jaywcjlove/musicer/releases/tag/v2.1.0)

1. ui: 修复界面样式问题。

## [v2.0.0](https://github.com/jaywcjlove/musicer/releases/tag/v2.0.0)

1. feat: 添加播放/暂停命令菜单
2. feat: 添加对 macOS 26 的支持
3. ui: 优化界面布局

## [v1.9.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.9.0)

1. feat: 支持通过右键菜单在应用中打开文件
2. fix: 修复元数据缺失标题时不显示的问题
3. fix: 修复刷新时偶发文件权限丢失的问题

## [v1.8.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.8.0)

1. perf：优化音乐列表加载
2. perf：提升列表加载效率
3. ui：更新主菜单界面

## [v1.7.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.7.0)

1. 新增: 新增大封面播放器。
2. 新增: 新增进度条样式选择功能。
3. 修复: 修复工具栏自动隐藏的问题。
4. 修复: 修复国际化问题。

## [v1.6.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.6.0)

1. feat: 新增窗口宽度设置功能。
2. fix: 修复拖动窗口时的抖动问题。

## [v1.5.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.5.0)

1. ui: 修复迷你界面在参数缺失时的显示问题。
2. feat: 新增文件扫描深度设置选项。

## [v1.4.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.4.0)

1. 新增：支持丢失权限后的重新授权功能。
2. 新增：支持将单个音乐文件拖入播放器。
3. 新增：支持通过 Dock 图标添加文件夹和音乐。
4. 修复：修复显示文件夹名称时中文乱码的问题。

## [v1.3.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.3.0)

1. feat: 新增隐藏状态栏图标的选项
2. feat: 播放器区域支持双击操作
3. feat: 新增键盘快捷键支持

## [v1.2.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.2.0)

1. feat: 支持使用 Mac 默认媒体键（F7/F8/F9）控制音乐播放
2. feat: 添加右键菜单选项以刷新列表数据
3. feat: 增加状态栏图标显示专辑封面的设置选项
4. feat: 支持马赛克风格专辑封面显示

## [v1.1.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.1.0)

1. feat: 支持启用或禁用音乐文件夹。
2. feat: 支持自定义强调色设置。
3. feat: 新增播放条颜色设置。
4. feat: 在右键菜单中添加上一首/下一首歌曲控制。
5. feat: 在右键菜单中添加循环选项。
6. feat: 新增迷你播放器界面。
7. feat: 在音乐文件夹列表中添加右键菜单操作。
8. fix: 修复清空播放列表后播放仍继续的问题。

## [v1.0.0](https://github.com/jaywcjlove/musicer/releases/tag/v1.0.0)


<!--idoc:config:
title: 更新日志
-->
