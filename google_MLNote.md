## 问题构建（Framing）：  

### 什么是（监督式）机器学习：  

* 通过学习*如何组合输入信息*来对从未见过的数据做出有用的**预测**。  

  * Labels（标签）：指我们要预测的真实事物：**y**

    * 基本线性回归中的y变量。	  

  * Features（特征）：表示数据的方式，指用于描述数据的输入变量：**$x_i$**。

    * 基本线性回归中的${x_1, x_2,x_3,...,x_n}$。 

  * Sample(样本)：指数据的特定实例（为一个矢量）：**x**.

    * 有标签：具有{特征，标签}：（**x**，**y**）：用于训练模型。
    * 无标签：具有{特征，？}：（**x**，？）：用于对新数据做出预测。

  * Model（模型）：将样本映射到预测标签：**y'**

    * **执行预测的工具**。通过从数据债学习规律这一过程来尝试创建模型。
    * 由模型的内部参数定义，这些内部参数值是通过学习得到的。

    
