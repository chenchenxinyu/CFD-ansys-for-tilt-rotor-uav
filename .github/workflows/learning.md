# 前处理设置
SETUP：
- general
general is to set up the mesh

scale  make the mesh big or small, it is prepare for the mesh if fit the calculation space size, or you will set the zoom factor to fit both of them

查看图中的Domain Extents，观察计算域尺寸与要模拟的计算空间尺寸是否吻合，若不吻合的话，需要通过设置缩放因子对网格进行缩放。

check  check the mesh and view it, it include domain extents, volume statistics, face area statistics(统计), please make sure the volume statistics is positive value

report quality  it will report some qualty information about the mesh, including the minimum orthogonal quality, max ortho skew, and maximum aspect ratio
  - Minimum Orthogonal Quality：最小正交质量 (0.1), the '0' is the worst, and the one is the best, please make sure the mesh quality bigger than 0.2
  - Max Ortho Skew：最大正交歪斜率   the less the better
  - Maximum Aspect Ratio：最大长宽比

dispaly show the mesh

type 
  - pressure-bassed压力基求解器
  - density based 密度基求解器

velocity formulation
  - absolute
  - relative

time 
  - steady    稳态计算
  - transient 瞬态计算

gravity 重力加速度

unit 单位

不管使用何种单位，FLUENT在求解时始终使用国际单位制，这里设置单位只是为了前处理设置方便。

这里采用摄氏度为了表示方便

# 求解器设置


# 计算后处理

