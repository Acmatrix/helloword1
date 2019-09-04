# 博士期间的研究目标
firtst repository
hello robotics， i like active control of noise and vibration. I' had a phd candidates for the adaptive filter based algorithm, and try to obtain the cooperation between machine learning and active noise control algorithm for further research and practical implementation.

前面围绕的非稳态时变振动信号的跟踪控制开展了博士论文的相关研究工作。而这一方面工作与现有机器学习理论的体系是如何的。实际上，非稳态系统的跟踪控制实际上是自适应滤波器理论（Simon Haykin（S. 赫金））与实际工程应用的结合。自适应滤波器理论参见大牛Simon Haykin（S. 赫金）作品。其相关算法的分析推导，从这部著作可以衍生到该大牛的另一部作品，神经网络与机器学习。两者的语言描述风格和思维方式都是一致的。从而我们可以建立起对这些算法的体系结构。
    从更深的层次上讲，自适应滤波器原理是目前主要是针对通信行业的开展研究，而机器学习主要是针对分类问题和预测问题开展研究。其中两者相同的是预测问题及其围绕相同算法开展的收敛性分析和收敛优化。所用理论架构都是一致的。所以该大牛跨界式的从自适应滤波器理论跨到了机器学习。其实，从源头上，B.Widerow等人提出的LMS是自适应滤波器与神经网络的原始基础，只是一种是应用在通信领域的快速发展，另一种是在神经网络理论方面的发展。机器学习的分类问题则是自己单独的角度出发，发展了自己的理论体系。
    
   非稳态系统的跟踪控制实际上可以具体为这么几种描述。1、比如在通信领域，存在某个信号需要跟踪预测，而这个信号如果是稳态信号，那么跟踪与预测控制就相对容易很多，比如通信中的谐波信号跟踪控制，自适应噪声抵消，这些都是确定性稳态信号的跟踪控制；在振动控制领域，主动减振主动降噪，则是一样的原理控制体系。只是主动减振或者主动降噪则是需要一个执行机构、如麦克风等
