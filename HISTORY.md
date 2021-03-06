# History

---

## 1.2.0
* refactor: 精度性能优化，图表的性能是原来的 4+ 倍；
* feat: 支持简单的加法运算符，简化了区间数据图表的绘制；
* feat: 增加 map 坐标系，用于地图投影的绘制；
* feat: 新增两套主题，并修改默认主题。

## 1.2.1
* refactor: guide/Arc 算法优化；
* fix: tooltip corsshair遮盖点的问题；
* fix: treemap 字段写死的问题。

## 1.2.2
* fix: 修复Safari浏览器下，时间戳含‘Z’出错问题；
* fix: 修复仪表盘白边；
* fix: 修复饼图文本重叠的问题；
* fix: 饼图选中动画bug；
* refactor: 优化 tooltip 出现的效果。

## 1.2.3
* refactor: 图例自动换行
  * 废弃 lineHeight 概念，使用 bbox.height 代替。对于大小连续图例，会使其不重叠，同时文本竖直分布不均；
  * fix: theme 中 spacingX 及 spacingY，概念为每个图例之间的左右间距及上下间距。在默认theme中根据视觉进行了优化。
* feat: chart.guide() 新添加 min 和 max 关键字，用于快速定位坐标轴起点和终点；
* fix: 修复 treemap 部分分层边框无法绘制的问题；
* fix: 修复 tooltip 辅助线首次出现的位置问题。
* fix: 修复 axis label 旋转text-anchor失效问题。
