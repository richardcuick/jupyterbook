# 计算公式

容积（单位为英尺ft或立方米） 

长为 L 、宽为 W 、高为 H 、底部直径为 D 、边长为S (?)

|形状|公式|
|-|-|
|立方体|L x W x H|
|圆柱体|0.785 x D x D x H ( D = L = W )|
|六边体|2.6 x S x S x H ( S = L = W )|
|八边体|1.73 x S x S x H ( S = L = W )|
|球体|0.523 x D x D x D ( D = L = W = H )|

容积换算 (从立方英尺换算为桶BBL) BBL = V / 5.614

计算泥浆罐、泥浆泵和不同类型钻柱的面积

|形状|公式|
|-|-|
|梯形面积|( B1 + B2 ) x H / 2|
|圆形面积|3.1416 x R x R|
|三角形面积|H x B / 2|
|长方形面积|L x W|
|正方形面积|L x L|

公制和英制之间的转换
|名称|换算公式|
|-|-|
|长度|1 米 = 3.281 英尺<br/>1 英寸 = 2.54 厘米|
|重量|1 磅 = 4535924 克|
|容量|1 加仑 = 3.785412 升|

英制单位
|名称|换算公式|
|-|-|
|长度|1 英尺 = 12 英寸<br/>1 码 = 3 英尺<br/>1 英里 = 1760 码<br/>1 英寸 = 16 个小段|
|重量|1 磅 = 16 盎司|
|容量|1 桶 = 5.614 立方英尺<br/>1 立方英尺 = 7.48 加仑<br/>1 桶 = 42 加仑|

---

D 为孔直径、d 为钻杆外径

环空容量 = ( D² / 1029.4 ) - ( D² / 1029.4 ) = - bbls/ft

在钻机数学中，计算在操作过程中需要多少桶来填充井口，以监测井口的流入和流出。

根据环空容量种类，定义从井口泵入或排出多少桶，以增加或减少每英尺的压力。

---

一般井筒计算：Capacity ( BBL / FT ) = ( ID ) 2 / 1029.4（ID为钻井管内径）

体积:指泥浆坑、井筒或环空、管道或任何其他容器内的实际泥浆量

Volume ( BBL ) = ( ( ID ) 2 / 1029.4 ) * MD（MD为钻头深度）

排量:当钻柱或套管下入井中时，从井中排出的泥浆体积。

Disp. ( BBL ) = ( ( OD ) 2 - ( ID ) 2 / 1029.4 ) * MD

环空体积:井壁与钻柱之间的泥浆体积

Annular volume ( BBL ) = ( ( ID hole ) 2 - ( OD drill pipe ) 2 /1029.4 x MD（OD为钻杆外径）

---

Lag time = volume / flow rate

泥浆在两个指定深度点之间进入井内所需的时间 = 体积/流量

pump out put ( POP ) ( BBL / STK ) = ( ID2 ine x L stroke x eff. ) / 4116

泵产量 ( 桶 / 冲程 ) = ( 泥浆泵内衬的内径 ( 单位为英寸 ) x 泥浆泵柱塞冲程长度 x eff ) / 4116

Flow rate ( GPM ) = POP x SPM x 42

流量 = pop x 每分钟冲次 x 42

Total circ time ( min ) = V active / ( POP x SPM )

总循环时间 = 活性泥浆体积 /（ POP x SPM )

Bottoms up time ( min ) = Vannulus / ( POP x SPM )

底部上升时间 ( 表示从底部上升到顶部的时间 ) = 环空流量 /（ POP x SPM ）

bottom up strokes ( stk ) = Vannulus / POP

底部循环次数 = 环空流量 / POP

Hydrostatic press. ( Psi ) = 0.052 x M.wt ( ppg ) x TVD ( ft )

静水压力 = 0.052 * 泥浆密度 x 真实垂直深度

Annular velocity  AV ( ft / min )  =  V Pump Output ( gal / min ) x 24.5 / IDwell2 ( in. ) - ODPipe2 ( in. )

环空流速 = 泵输出体积 ( 流量 ) x 24.5 / ( 井眼的静止水力深度平方 - 套管内径平方 )