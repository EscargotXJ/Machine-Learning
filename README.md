# Machine-Learning
机器学习相关概念及算法——来源：林轩田，机器学习基石+机器学习技法
## 机器学习基石
### When Can Machine Learn?
1. **The Learning Problem**
  >主要介绍了什么是机器学习，什么样的场合下可以使用机器学习解决问题，然后用流程图的形式展示了机器学习的整个过程，最后把机器学习和数据挖掘、人工智能、统计这三个领域做个比较。
2. **Learning to Answer Yes/No**
  >介绍了**线性感知机模型**，以及解决这类感知机分类问题的简单算法：**PLA**。我们详细证明了对于线性可分问题，PLA可以停下来并实现能够在平面中选择一条**直线**将样本数据完全正确分类。对于不是线性可分的问题，可以使用PLA的修正算法Pocket Algorithm来解决。
3. [Types of Learning](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture3%E2%80%94%E2%80%94Types-of-Learning)
  >**机器学习的类型**，包括Out Space、Data Label、Protocol、Input Space四种类型。
4. [Feasibility of Learning](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture4%E2%80%94%E2%80%94Feasibility-of-Learning)
  >介绍了**机器学习的可行性**。首先引入NFL定理，说明机器学习无法找到一个g能够完全和目标函数f一样。接着介绍了可以采用一些统计上的假设，例如Hoeffding不等式，建立Ein和Eout的联系，证明对于某个h，当N足够大的时候，Ein和Eout是PAC的。最后，对于h个数很多的情况，只要有h个数M是有限的，且N足够大，就能保证Ein~Eout，证明机器学习是可行的。
### Why Can Machine Learn?
5. [Training versus Testing](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture5%E2%80%94%E2%80%94Training-versus-Testing)
6. [Theory of Generalization](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture6%E2%80%94%E2%80%94Theory-of-Generalization)
7. [The VC Dimension](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture7%E2%80%94%E2%80%94The-VC-Dimension)
8. [Noise and Error](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture8%E2%80%94%E2%80%94Noise-and-Error)
### How Can Machine Learn?
9. [Linear Regression](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture9%E2%80%94%E2%80%94-Linear-Regression)
10. [Logistic Regression](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture10%E2%80%94%E2%80%94Logistic-Regression)
11. [Linear Models for Classification](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture11%E2%80%94%E2%80%94Linear-Models-for-Classification)
12. [Nonlinear Transformation](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture12%E2%80%94%E2%80%94Nonlinear-Transformation%EF%BC%88%E9%9D%9E%E7%BA%BF%E6%80%A7%E5%8F%98%E6%8D%A2%EF%BC%89)
### How Can Machine Learn Better?
13. [Hazard of Overfitting](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture13%E2%80%94%E2%80%94Hazard-of-Overfitting)
14. [Regularization](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture14%E2%80%94%E2%80%94Regularization)
15. [Validation](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture15%E2%80%94%E2%80%94Validation)
16. [Three Learning Principles](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture16%E2%80%94%E2%80%94Three-Learning-Principles)
## 机器学习技法
### Course Design
![image.png](https://upload-images.jianshu.io/upload_images/10860788-82be7f8fb9614e79.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 哲学的讨论，理论推导，演算法分析，实物应用解说
* 基本工具->复杂、实用模型
* **特征转换**的三种主要技法：
  > 1. **Embedding Numerous Features**: how to **exploit** and **regularize** numerous features?
     <br>—inspires **Support Vector Machine** (SVM) model
   <br>(很多特征：运用，控制复杂度)
  > 1. **Combining Predictive Features**: how to **construct** and **blend**(混合) predictive features?
<br>—inspires **Adaptive Boosting (AdaBoost)** model
  > <br>(预测性质的特征：找出，混合，逐步增强法)
  > 1. Distilling **Implicit Features**: how to **identify** and **learn** implicit features?
  > —inspires **Deep Learning** model
  > <br>(隐藏特征：学习)
### Embedding Numerous Features: Kernel Models
1. [Linear Support Vector Machine](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-1:-Linear-Support-Vector-Machine)
2. [Dual Support Vector Machine](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-2:-Dual-Support-Vector-Machine)
3. [Kernel Support Vector Machine](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture3:-Kernel-Support-Vector-Machine)
4. [Soft-Margin Support Vector Machine](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-4:-Soft-Margin-Support-Vector-Machine)
5. [Kernel Logistic Regression](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-5:-Kernel-Logistic-Regression)
6. [Support Vector Regression](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-6:-Support-Vector-Regression)
### Combining Predictive Features: Aggregation Models
7. [Blending and Bagging](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-7:-Blending-and-Bagging)
8. [Adaptive Boosting](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-8:-Adaptive-Boosting)
9. [Decision Tree](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-9:-Decision-Tree)
10. [Random Forest](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-10:-Random-Forest)
11. [Gradient Boosted Decision Tree](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-11:-Gradient-Boosted-Decision-Tree)
### Distilling Implicit Features: Extraction Models
12. [Neural Network](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-12:-Neural-Network)
13. [Deep Learning](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-13:-Deep-Learning)
14. [Radial Basis Function Network](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-14:-Radial-Basis-Function-Network)
15. [Matrix Factorization](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-15:-Matrix-Factorization)
16. [Finale](https://github.com/LXxxxxxj/Machine-Learning/wiki/Lecture-16:-Finale)
