
给bitmap转成纹理，然后显示出来，

研究一下，怎么给图片等比缩放到合适屏幕的大小，包括横屏竖屏，怎么设置矩阵，还有旋转，水平竖直镜像

这里有几个问题：
1，为什么onDrawFrame会调两次
2，为什么输出了4张图片，第一张是裁过的，第二张是拉伸的，第三张是两张覆盖的，第四张是拉伸的
3，怎么样可以让输出图片适应到竖屏，怎么样适应到横屏