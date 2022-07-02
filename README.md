# graphic-ghibli-style

# 软件
- blender/MAYA/Solid works: 3D建模造型以及材质构建的一个3D软件

- 模型(model)数据
- 材质(material)数据

- 饶健平猜想: 死的模型, 死的材质
- 真实的情况是: 

- 渲染: 模型 + 材质 + 光的方向 + 啷个渲染(shader或者叫着色器)

- 色彩表示
  - RGB(3, 2, 100), 每个位值的范围都是0~255/0~1
  - 十六进制(hex): #ffffff 00 ff
  - HSB: 色相hue(0-360), 饱和度saturate(0-100), 明度bright(0-100)

- unity3D: 游戏引擎, 和unreal是竞争关系
- unreal engine(UE4, UE5): 游戏引擎
# 找资料
- 途径: b站, youtube, 知乎, 谷歌, 百度, CSDN, StackOverflow
- ghibli concept
  - 日本动画公司, 1985年中旬, 原附属德间书店
  - 日本东京都近郊的小金井市
  - 宫崎骏, 高畑勋, 铃木敏， 一起统筹
  - 代表作《龙猫》
  - 东西方元素结合

- 编译(c代码) => 二进制代码， CPU（二进制代码）=> 执行

# 美术
- 3d感觉: 光影, 透视, 近实远虚

# 其他
[吉卜力风格的云blender教程](https://www.bilibili.com/video/BV1i54y1y7NL?spm_id_from=333.337.search-card.all.click&vd_source=db0789cdda7abd0b68900f788d19ece9)

- shader
- 体积云
- 原理BSDF
- 纹理
- noise噪音, 随机算法
- 程序化生成
- 混合模式,  alpha混合

- UE4
  - DFAO， 距离场阴影的定向光
  - 网格距离场

# 风格分析
[吉卜力风格分析](https://zhuanlan.zhihu.com/p/389789800)
- 以绘画而非卡通的方式简化纹理
- 精心挑选能激发情绪的颜色
- 植被层涂有模糊和稀缺的细节
- 天空和背景对于创造虚构世界的人物和氛围至关重要
- 可变环境; 物理世界对我们的行为有反应并被我们的行为改变
- 色彩的使用是一致的, 白天和黑夜框架通常想用相同的调色板, 颜色范围会根据他们想要煽动的情绪变化
- 石材: 使用了许多用独特的笔触松散地绘制的表面纹理, 需要非常小心地处理大石头的可见细节, 不要分散人们对石头整体轮廓的注意力. 纹理不主导形体, 只是一些细节的补充
- 树: 背景中的树干通常在树皮上轻轻涂上一两种颜色和轻微的细节。前景中大树的树干细节错综复杂，层次分明，但在它们上使用的笔触仍然与众不同，并且形状也有一些简化。
- 灯光: DFAO的动态天光和有距离场阴影的定向光
  - ![灯光](https://pic1.zhimg.com/80/v2-45f44fe574166914217c0e545f1822b4_720w.jpg)
  - 网格距离场
  - ![网格距离场](https://pic1.zhimg.com/v2-52dfc5b583e4407dc75818f7516b1ac8_r.jpg)
  - DFAO: 我们可以实现更好的环境阴影和更高的对比度
  - ![DFAO](https://pic4.zhimg.com/80/v2-0a968882800a60254c2d4ae3200bd10f_720w.jpg)
  - 关闭DFAO
  - ![关闭DFAO](https://pic3.zhimg.com/80/v2-40adaa96fb3ce489a3065e8967d55c52_720w.jpg)
  - 打开DFAO
  - ![打开DFAO](https://pic1.zhimg.com/80/v2-1390c5bdf7731eabf529172736d48c70_720w.jpg)
- 植被
  - Photoshop中手工创建纹理
  - ![手工创建纹理](https://pic4.zhimg.com/80/v2-3fb64cb738a5545e719fe22c148f1c77_720w.jpg)
  - 设计纹理后, 在blender中制作一些简单的面片来拼接
  - ![面片拼接](https://pic2.zhimg.com/80/v2-91aec343c7f83409924041de9801a851_720w.jpg)
  - 修改面片法线

# 颜色与情绪2

魔法与未知

![魔法与未知](https://pic4.zhimg.com/v2-e5a2852dd4e5a7e8fea5663311aace07_r.jpg)

想象力与自由

![想象力与自由](https://pic1.zhimg.com/80/v2-72f22993259e9c27e41bc49309ca18a0_720w.png)

冒险

![冒险](https://pic3.zhimg.com/80/v2-c1f180e6566b9baf2a49016820ecdd9a_720w.png)

危险

![危险](https://pic3.zhimg.com/80/v2-48093d2b2d01e07a2e6771eaa5d74ac6_720w.png)

生机与活力

![生机与活力](https://pic4.zhimg.com/80/v2-38292d1252b75355ec041f26ca7383f7_720w.jpg)





