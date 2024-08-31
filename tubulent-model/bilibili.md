# P7 
1. [湍流模型的意义](https://www.bilibili.com/video/BV1MT411c77H?t=875.4&p=7)
2. 陶文权:所谓湍流模型就是把湍流的脉动值附加项与时均值联系起来的一些特定关系式
3. ![image](https://github.com/user-attachments/assets/c9874dfa-aec3-4b06-b867-bdfd9d57f5a5)
4. 即对于N-S方程，只有4个方程，4个未知量 $\bar{u},\bar{v},\bar{w},\bar{p}$ 但是经过RANS后，多了一项**雷诺应力项**未知量，这样**4个**方程**5个未知量**，无法求解，所谓模型就是将**雷诺应力项**与其他时均值 $\bar{u},\bar{v},\bar{w},\bar{p}$ 联系起来(即用这些量表示)，**从而再将5未知变为4未知量的关系式**
5. ![image](https://github.com/user-attachments/assets/15dc2985-6e4e-447a-9bbc-69ee8f134d3c)
## [涡粘模型(EVM)](https://www.bilibili.com/video/BV1MT411c77H?t=1459.4&p=7)
1. 涡粘模型不直接处理雷诺应力项 $-\rho\bar{u_{i}^{'}}\bar{u_{j}^{'}}$
   
