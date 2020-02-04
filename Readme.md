# 用UE4复刻Chrome离线游戏 Dino
> U4.26.2
#### 素材地址
[点击转到](https://github.com/wayou/t-rex-runner.git)
## 游戏场景分析
* 恐龙
* 仙人掌
* 地面
* 星星
* 云朵

## 动画分析
* 恐龙
  * 发呆(静止,游戏还没开始的时候)
  * 眨眼睛(奔跑偶尔,或者发呆的时候偶尔)
  * 奔跑(游戏开始的时候)
  * 死亡(受到伤害的时候)
* 翼龙(🕊)
  * 飞翔

## 事件
* 等待游戏开始
* 游戏开始(加速跑动画)
* 游戏进行
* 游戏结束(死亡?)


大致以上.


>这里本来想用C++来写的,但是出现了一些让我没有办法理解的BUG
>创建C++文件的时候如果在二级别目录下那么就会报错,.cpp找不到头文件.

