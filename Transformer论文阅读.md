**Swin Transformer Assisted Prior Attention Network for Medical Image Segmentation**

**用于医学图像分割的Swin Transformer辅助的先验注意网络**

**摘要：**

Transformer completement convolutional neural network (CNN) has achieved better performance than improved CNNbased methods. Especially, Transformer is utilized to be combined with U-shaped structure, skip-connections, encoder and 
even all of them. However, the intermediate supervision network based on coarse-to-fine strategy has not been combined with Transformer to improve the generalization of CNN-based methods. In this paper, we propose Swin-PANet, which is 
applying window-based self-attention mechanism by Swin Transformer in intermediate supervision network, called prior attention network. A new enhanced attention block based on CCA is also proposed to aggregate the features from skipconnections and prior attention network and further refine boundaries details. Swin-PANet addresses the dilemma that 
Transformer attention learning is capable of using prior boundary information and its poor interpretability. Hence, the intermediate supervision network assisted by Swin Transformer provides better attention learning and interpretability in 
network for accurate and automatic medical image segmentation. The experimental results evaluate the effectiveness, consistently outperforming state-of-the-art methods in two famous medical segmentation tasks.

与基于CNN的改进方法相比，Transformer completement卷积神经网络（CNN）取得了更好的性能。特别是，Transformer被用来与U型结构、跳过连接、编码器甚至全部结合起来。
甚至是所有这些。然而，基于从粗到细策略的中间监督网络还没有与Transformer结合起来以提高基于CNN的方法的泛化能力。在本文中，我们提出了Swin-PANet，它是 在中间监督网络中应用Swin Transformer的基于窗口的自我注意机制，称为先注意网络。我们还提出了一个新的基于CCA的增强型注意力块，以聚合来自跳过连接和先前注意力网络的特征，并进一步细化边界细节。Swin-PANet解决了以下两难问题：Transformer注意力学习能够使用先前的边界信息，而其可解释性差。

因此，由Swin Transformer辅助的中间监督网络提供了更好的注意力学习和可解释性。
该网络用于准确和自动的医学图像分割。实验结果评估了其有效性，在两个著名的医学分割任务中一直优于最先进的方法。