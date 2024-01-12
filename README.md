网络安全模型模拟与可视化
这个仓库包含了基于论文 "Indefinite Mean-Field Stochastic Cooperative Linear-Quadratic Dynamic Difference Game With Its Application to the Network Security Model" 的 Python 代码，用于模拟和可视化网络安全模型。
安装
要运行模拟和可视化代码，您需要 Python 9.0 和以下库：
- NumPy
- Matplotlib
您可以使用 pip 安装这些库：
```
pip install numpy matplotlib
```
使用
代码组织在一个脚本中，执行以下任务：
1. 绘制网络安全模型的初始图表。
2. 初始化网络安全模型的参数。
3. 使用更新后的参数模拟网络安全模型的动态。
4. 绘制网络安全模型的动态变化。
要运行模拟，只需执行 Python 脚本：
```
python network_security_simulation.py
```
脚本将在 `results` 目录下保存生成的图表，并使用 Matplotlib 显示它们。
结果
脚本将产生两组图表：
- 第一组显示网络安全模型的初始图表，性能指标 `J1` 和 `J2` 相互绘制。
- 第二组显示网络安全模型随时间的动态变化，绘制了各种变量如 `x1`, `y1`, `x2`, `x3`, `x4` 和 `x5` 与时间步 `k` 的关系。
这些图表有助于可视化网络安全模型在不同参数下的行为，并可用于分析用户实施的安全措施的有效性。
参考文献
有关模拟的理论背景和方法的更多信息，请参考原始论文：
Zhang, W., & Peng, C. (2022). Indefinite Mean-Field Stochastic Cooperative Linear-Quadratic Dynamic Difference Game With Its Application to the Network Security Model. IEEE Transactions on Cybernetics, 52(11), 11815-11818.
许可
本项目根据 MIT 许可协议授权。
