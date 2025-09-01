由于Windows11混乱的任务栏更新，截至本readme更新前，TrafficMonitor作者暂时无适配计划。

本仓库计划在Windhawk中，魔改Taskbar Clock Customization，实现TrafficMonitor的功能

<img width="500" height="96" alt="image" src="https://github.com/user-attachments/assets/65733aab-7781-46f7-a997-565c63011924" />

已实现功能：
1. 迁移Taskbar Clock Customization的基础功能，包括获取天气、获取web文本、获取网速
2. 实现了一个数据延迟较高的耗电情况显示
3. 使用等宽字体暂时实现多个部件的对齐

计划实现功能
1. 数据延迟较低的耗电情况显示（参考TrafficMonitor的PowerMon组件）
2. 优化对齐逻辑，允许使用非等宽字体
3. 允许接入天气api
4. 允许查看组件详情
