## Material fork

主要有一下修改

## mathjax支持

```
\begin{align}
\theta\_0 & := \theta\_0 - \alpha\frac{\partial}{\partial\theta\_0}J(\theta\_0,\theta\_1) \\\\
& = \theta\_0 - \alpha\frac{\partial}{\partial\theta\_0} \frac{1}{2m} \sum\_{i=1}^{m}(h\_\theta(x^{(i)}) - y^{(i)})^2 \\\\
& = \theta\_0 - (\alpha \frac{1}{2m} \* 2 \* \sum\_{i=1}^{m}(h\_\theta(x^{(i)}) - y^{(i)})) \* \frac{\partial}{\partial\theta\_0}(h\_\theta(x^{(i)}) - y^{(i)}) \\\\
& = \theta\_0 - \frac{\alpha}{m}  * \sum\_{i=1}^{m}(h\_\theta(x^{(i)}) - y^{(i)})
\end{align}
```

## 改用搜狐畅言
