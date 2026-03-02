## Hi there 👋

<!--
**qqh0618/qqh0618** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!-- 头部横幅：可以使用自定义图片或简单的文字排版 -->
<div align="center">
  <h1>Hi there, I'm WenJie Yao 👋</h1>
  <h3>Researcher in Federated Learning & Cross-Domain Privacy</h3>
  
  <!-- 添加一些徽章来展示技术栈 -->
  <p>
    <img src="https://img.shields.io/badge/Research-Federated%20Learning-blue?style=for-the-badge" alt="FL">
    <img src="https://img.shields.io/badge/Focus-Cross--Domain%20Adaptation-green?style=for-the-badge" alt="CrossDomain">
    <img src="https://img.shields.io/badge/Framework-PyTorch-red?style=for-the-badge&logo=pytorch" alt="PyTorch">
    <img src="https://img.shields.io/badge/Papers-4%20Published-orange?style=for-the-badge" alt="Papers">
  </p>
</div>

---

### 🎓 About Me

I am currently a Ph.D at Harbin University of Science and Technology.

My research primarily focuses on **Federated Learning (FL)**, with a specific emphasis on solving the **Federated Cross-Domain** challenges. I aim to design robust frameworks that enable efficient knowledge transfer across heterogeneous data distributions while preserving privacy.

- 🔭 **Current Work**: Designing a novel **Federated Cross-Domain Framework** to address domain shift in decentralized settings.
- 📄 **Publications**: Author of **4 papers** in top-tier conferences/journals (e.g., TII, TMC, EAAI, and so on).
- 🌱 **Open Source**: Committed to releasing reproducible code for my research.

---

### 📝 Selected Publications

Here are my latest works on Federated Learning:

#### 1. FedRDA: Representation Deviation Alignment in Heterogeneous Federated Learning

**Journal:** IEEE Transactions on Industrial Informatics.

**Abstarct:**
Federatedlearning has garnered significant attention in the Internet of Things and healthcare applications due to its ability to train a shared global model across distributed clients. However, imbalanced data distribution leads to model discrepancies among clients. Most existing methods adopt implicit alignment strategies while overlooking explicit modeling of geometric and directional discrepancies in feature representations, which undermines local model optimization. To address this issue, we propose a method of representation deviation alignment in federated learning, which projects features onto the principal feature space to measure deviations between local and global feature representations explicitly. Specifically, Federated learning with Representation Deviation Alignment (FedRDA) employs a feature encoder to extract compact features and construct unbiased principal feature spaces for global and local models. Then, the residual projection in the feature space serves as a quantitative measure of the representation deviation, effectively capturing the latent direction differences between models. Besides, we introduce a representation consistency alignment strategy, which ensures that the distribution of local client features becomes more uniform within the global feature space. Extensive experiments on SVHN, CIFAR-10, CIFAR-100, Tiny-ImageNet, and GC10 demonstrate that FedRDA effectively reduces the classifier bias caused by representational differences.

#### 2. A Class-Aware Calibration and Balanced Consistency Weighting Framework for Federated Semi-Supervised Learning
> **Journal**: Engineering Applications of Artificial Intelligence
> **Abstarct:**
Federated Semi-Supervised Learning (FSSL) is suitable for situations where a global model is learned with limited labeled participants and a majority of clients providing only unlabeled data. Existing methods, such as two-stage sampling, address the difficulties arising from non-independent and identically distributed (Non-IID) data by resampling unlabeled instances with low confidence scores, guided by predicted shifts in data distribution. However, such methods often fail to consider the adverse effects caused by class imbalance within individual clients during training. To address this issue, we introduce CCWFed, a novel federated semi-supervised approach that integrates class-aware calibration and balanced consistency weighting. For labeled clients, we introduce a class frequency-aware prediction calibration mechanism during local training, which adjusts the model outputs to mitigate the influence of majority class bias on the decision boundaries of minority class. For unlabeled clients, we design a pseudo-label-aware balanced consistency weighting strategy aimed at mitigating the propagation of pseudo-label bias under unknown unlabeled data distributions. Furthermore, to fully leverage the potential contributions of unlabeled clients during advanced training stages while ensuring stable aggregation at the beginning, we design a stage-adaptive dynamic model aggregation method. The evaluation results indicate that CCWFed achieves superior performance compared to other methods on three distinct Non-IID datasets, validating its effectiveness under complex data distribution conditions.


---

### 🚀 Current Project: Federated Cross-Domain Framework

We are actively developing a comprehensive framework to streamline research in **Federated Cross-Domain Adaptation**.

**Key Features:**
- 🔄 **Domain Adaptation Modules**: Built-in algorithms for feature alignment and distribution matching.
- 🛡️ **Domain Generalization Modules**: Supports differential privacy and secure aggregation protocols.
- 🧪 **Benchmark Suite**: Includes standard datasets with simulated cross-domain for FL.
- ⚡ **Efficiency**: Optimized for communication efficiency in bandwidth-constrained environments.

👉 **Check out the repository**: [🔗 GitHub Repo Link](你的框架仓库链接)

---

### 📫 Connect with Me

I'm always open to discussing new research ideas, collaborations, or feedback on my framework.

- 📧 **Email**: shanliang0618@163.com

<!--
- 🌐 **Personal Website**: [你的个人主页链接]
- 🎓 **Google Scholar**: [你的 Scholar 链接]
- 💬 **Twitter/X**: [你的 Twitter 链接 (可选)]
-->

<div align="center">
  <sup>If you find my work useful, please consider citing my papers or starring my repositories! ⭐</sup>
</div>
