<div align="center">

<h1>无空间世界模型</h1>

<em>为什么人工智能不需要理解空间？</em>

<br /><br />

<sub><a href="README.md">English</a> · 中文</sub>

<br /><br />

<img src="https://img.shields.io/badge/status-manifesto-8A2BE2?style=flat-square&labelColor=202020" alt="status: manifesto" />
<img src="https://img.shields.io/badge/space-optional-2F81F7?style=flat-square&labelColor=202020" alt="space: optional" />
<img src="https://img.shields.io/badge/learns_from-change-8957E5?style=flat-square&labelColor=202020" alt="learns from change" />

</div>

<br />

---

我们一直在用人类的方式教人工智能理解世界。

我们告诉它什么是距离，什么是位置，什么是前后，什么是三维空间。

但我们忽略了一个问题：

<p align="center"><strong>人工智能真的能够感受到空间吗？</strong></p>

即使给机器人装上身体，让它行走、转弯、触碰物体，它也只是一个拥有行动能力的「缸中之脑」。

它接触到的始终是传感器传递的信息，而不是人类所理解的物理世界本身。

<p align="center"><em>距离、位置、深度，这些概念究竟是世界的本质，<br />
还是人类为了理解世界建立的解释体系？</em></p>

对于模型而言，它真正接触到的是图像，是像素，是尺度变化，是连续观测之间的信息差异。

远处的汽车逐渐变大，近处的行人逐渐缩小，世界在不同尺度下呈现出不同的信息。

那么，为什么一定要把这些变化重新翻译成三维坐标？

为什么不能直接学习尺度、关系与变化？

---

### 核心思想

> 不重建三维空间，不执着于绝对距离，不强迫模型理解人类定义的位置。
>
> 直接从观测中学习世界，从尺度变化中学习规律，从行动与反馈中预测未来。

```mermaid
flowchart LR
    O["观测<br/>像素 · 连续帧"] --> S["尺度 · 关系 · 变化"] --> P["预测<br/>行动 · 反馈"]
```

<p align="center"><sub>中间没有坐标，只有观测之间真正变化的东西。</sub></p>

### 两种理解方式

| | 重建式世界模型 | 无空间世界模型 |
| :-- | :-- | :-- |
| 假设 | 三维空间就是世界 | 观测本身就是世界 |
| 学习 | 坐标、深度、位姿 | 尺度、关系、变化 |
| 单位 | 米 | 信息差异 |
| 目标 | 还原场景 | 预测下一次观测 |

---

我们不是要让人工智能以人类的方式理解世界。

我们要寻找一种更适合人工智能自身的信息理解方式。

<p align="center"><em>空间可能是人类的语言，<br />
但不一定是人工智能理解世界的语言。</em></p>

<br />

<p align="center">
<sub><a href="README.md">English</a> · 中文</sub>
</p>
