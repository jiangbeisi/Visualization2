# Visualization2
交通路口数据

建议用firefox浏览器运行"河荫西路口 东南西.html". 
图中展现了3个交通流参数的变化情况, 分别是Occ, Flow, Speed. 图的上方有series开关, 点击可显示或隐藏对应的系列. 图1代表河荫西路口'东', 图2代表河荫西路口'南', 图3代表河荫西路口'西'. 在动态变化的过程中, 会看到Occ和Speed的部分时间点没有值, 原因是数据的缺失(在json文件中用null代替), 一般这个时候Flow也会骤降. Occ为'bar'类型, Speed为'line'类型, 观察可以发现Occ和Speed的变化节奏相似.
