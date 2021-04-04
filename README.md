# Easy-framework-for-EI-balance
This is a simple framework to realize excitatory and inhibitory balance. In this project, three kinds of models are exhibited.
The first model is in Model1 shown in Amit & Brunel, 1997:
\begin{equation}
\begin{aligned} \tau_{m} \dot{V}^{\alpha}(t) &=-V^{\alpha}(t)+V_{\text {leak }}+P^{\alpha}(t) \\ \tau_{\alpha} \dot{\mu}_{i}^{\alpha}(t) &=-I_{i}^{\alpha}(t)+\tau_{m} \sum_{\beta} \sum_{j}^{C} J_{i j}^{\alpha \beta} \sum_{k} \delta\left(t_{i j}^{k}-t\right) \end{aligned}
\end{equation}
This is achieved in Model1.
