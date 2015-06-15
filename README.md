# quadmaps.erl

erlang 实现的静态四叉树场景管理.

因为不是按照物体大小动态分割的，而是直接平均分割地图，
所以叫静态四叉数场景管理。


测试结果:

把一个 1000 * 1000 的地图分割5次，随机放入1000个单位
然后对(x, y, x+60, y+60) 的区域进行一次搜索，获取其中的单位列表
评价耗时 100微妙， (0.0001秒)

