# hexagonal-mesh
六边形网格聚合地理位置信息，基于百度地图的数据可视化

demo:https://nickham-su.github.io/hexagonal-mesh/

demo中随机生成了50000个坐标点，利用四叉树结构建立空间索引。当移动或缩放地图时，查询屏幕范围内的坐标点，聚合六边形区域内的坐标点数量，进行可视化。
