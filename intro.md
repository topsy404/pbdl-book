欢迎 ... 
============================

```{figure} resources/logo-xl.jpg
---
name: pbdl-logo-large
---
```

欢迎来到《基于物理的深度学习》(v0.1) 👋


**没时间的话;先看这个总结**: 

本书是对深度学习在物理仿真领域相关的所有内容的一个实用且全面的介绍。
为了让大家尽快上手，所有的主题以Jupyter notebooks的形式提供动手实践的代码示例。
除了从数据中进行标准的 _监督_ 学习，我们还将研究 _物理损失_ 约束，紧密关联（机器/深度）学习算法和 _可微分的模拟_ ，以及强化学习和不确定性建模。
我们正处在激动人心的时代：这些方法具备从根本上改变计算模拟所能实现的目标的巨大潜力。

---


## 接下来

_先睹为快_ ，接下的章节将介绍：
- 怎样训练（神经）网络来推断一个流体在像机翼形状的物体周边的流动情况，同时估计预测的不确定性。这将用到代替传统数值模拟的 _代理模型_ 。
- 怎样使用模型方程作为残差来训练表示解的网络，怎样通过使用 _可微分的模拟_ 来提高这些残差约束。
- 怎样与一个完整的模拟器更加紧密的交互以解决 _逆问题_ 。例如，我们将演示如何在训练流程中利用模拟器来规避标准强化学习中的收敛问题。

通过这些内容，我们将介绍不同的将物理模型引入深度学习的方法，例如：_基于物理的深度学习_ 的方法。
这些算法的变体将按照集成紧密度递增的顺序依次介绍，同时我们还将讨论不同算法间的优缺点。
了解每一种不同的技术在哪些场景下适应是非常重要的。


```{admonition} 运行代码，在这里，就是现在
:class: tip

我们使用Jupyter notebooks的一个关键好处是，所以的代码示例都可以在你的浏览器中当场运行。
你可以随时调整代码还观察变化，--快来试一下吧--
<br><br>
Jupyter notebooks另一个厉害之处在于它还是一种[文学式编程](https://zh.wikipedia.org/wiki/%E6%96%87%E5%AD%A6%E7%BC%96%E7%A8%8B).
```

## 意见与建议

本 _书_ 中的"书"指的是一些数字文本和代码示例的合集，由[TUM的基于物理模拟的研究小组](https://ge.in.tum.de)维护。
如果您有任何的意见和建议，请随时与我们联系，例如通过[邮件](mailto:i15ge@cs.tum.edu)。
如果您发现了错误，请让我们知道！我们知道本书还很不完美，我们也非常渴望进一步改进它。 先谢为敬😀! 除此之外，我们还维护了一个最近研究论文的[合集](https://github.com/thunil/Physics-Based-Deep-Learning)。

```{figure} resources/divider-mult.jpg
---
height: 220px
name: divider-mult
---
Some visual examples of numerically simulated time sequences. In this book, we explain how to realize algorithms that use neural networks alongside numerical solvers.
```

## 致谢！

本项目离不开全体贡献者的帮助。感谢每一个贡献者🙏，下面是名单（按照字母顺序排排列）： 

- [Philipp Holl](https://ge.in.tum.de/about/philipp-holl/)
- [Maximilian Mueller](https://ge.in.tum.de/)
- [Patrick Schnell](https://ge.in.tum.de/about/patrick-schnell/)
- [Felix Trost](https://ge.in.tum.de/)
- [Nils Thuerey](https://ge.in.tum.de/about/n-thuerey/)
- [Kiwon Um](https://ge.in.tum.de/about/kiwon/)

同时感谢Georg Kohl提供的分割线图片 (cf. {cite}`kohl2020lsim`)，Li-Wei Chen提供的机翼数据图片和Chloe Paillard对本书的校对。

% future:
% - [Georg Kohl](https://ge.in.tum.de/about/georg-kohl/)

## 引用

如果您觉得本书有用，请通过如下方式引用:
```
@book{thuerey2021pbdl,
  title={Physics-based Deep Learning},
  author={Nils Thuerey and Philipp Holl and Maximilian Mueller and Patrick Schnell and Felix Trost and Kiwon Um},
  url={https://physicsbaseddeeplearning.org},
  year={2021},
  publisher={WWW}
}
```
