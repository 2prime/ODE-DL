# Deep Learning And ODE

A very early paper using differential equation to design residual like network

**Chen Y, Yu W, Pock T. On learning optimized reaction diffusion processes for effective image restoration CVPR2015**

The First papers introducing the idea linking ODEs and Deep ResNets

**Weinan E. A proposal on machine learning via dynamical systems[J]. Communications in Mathematics and Statistics, 2017, 5(1): 1-11.**

**Sonoda S, Murata N. Transport analysis of infinitely deep neural network[J]. The Journal of Machine Learning Research, 2019, 20(1): 31-82. (It's on arxiv 2017)**

**Haber E, Ruthotto L. Stable architectures for deep neural networks[J]. Inverse Problems, 2017, 34(1): 014004.**

**Lu Y, Zhong A, Li Q, et al. Beyond finite layer neural networks: Bridging deep architectures and numerical differential equations[J]. arXiv preprint arXiv:1710.10121, 2017.(ICLR workshop 2018/ICML2018)**

#### Architecture Design

Chang B, Meng L, Haber E, et al. Reversible architectures for arbitrarily deep residual neural networks[C]//Thirty-Second AAAI Conference on Artificial Intelligence. 2018.

Haber E, Ruthotto L. Stable architectures for deep neural networks[J]. Inverse Problems, 2017.

Lu Y. et al., Beyond Finite Layer Neural Network: Bridging Deep Architects and Numerical Differential Equations, ICML 2018.

Chang B, Chen M, Haber E, et al. Antisymmetricrnn: A dynamical system view on recurrent neural networks[J]. arXiv preprint arXiv:1902.09689, 2019.(ICLR2019)

Latent ODEs for Irregularly-Sampled Time Series
Yulia Rubanova, Ricky T. Q. Chen, David Duvenaud
Advances in Neural Information Processing Systems (NeurIPS).

Chen R T Q, Duvenaud D. Neural Networks with Cheap Differential Operators[C]//2019 ICML Workshop on Invertible Neural Nets and Normalizing Flows (INNF). 2019.

Dupont E, Doucet A, Teh Y W. Augmented neural odes[J]. arXiv preprint arXiv:1904.01681, 2019.

Zhong Y D, Dey B, Chakraborty A. Symplectic ODE-Net: Learning Hamiltonian Dynamics with Control[J]. arXiv preprint arXiv:1909.12077, 2019.

Che Z, Purushotham S, Cho K, et al. Recurrent neural networks for multivariate time series with missing values[J]. Scientific reports, 2018, 8(1): 6085.

###### Modeling other networks

Tao Y, Sun Q, Du Q, et al. Nonlocal Neural Networks, Nonlocal Diffusion and Nonlocal Modeling. NeurIPS 2018. *(Modeling nonlocal neural networks)*

Lu Y, Li Z, He D, et al. Understanding and Improving Transformer From a Multi-Particle Dynamic System Point of View. arXiv preprint arXiv:1906.02762, 2019.*(Modeling Transformer like seq2seq learning networks)*

Variational Integrator Networks for Physically Meaningful Embeddings <a href="https://arxiv.org/pdf/1910.09349.pdf">link</a>


###### Changing schemes

Zhang L, Schaeffer H. Forward Stability of ResNet and Its Variants. arXiv preprint arXiv:1811.09885, 2018.

Zhu M, Chang B, Fu C. Convolutional Neural Networks combined with Runge-Kutta Methods. arXiv:1802.08831, 2018.

Xie X, Bao F, Maier T, Webster C. Analytic Continuation of Noisy Data Using Adams Bashforth ResNet. arXiv:1905.10430, 2019.

Dynamical System Inspired Adaptive Time Stepping Controller for Residual Network Families  AAAI2020

#### Training Algorithm

###### Adjoint Method

Li Q, Chen L, Tai C, et al. Maximum principle based algorithms for deep learning[J]. The Journal of Machine Learning Research, 2017, 18(1): 5998-6026.

Li Q, Hao S. An optimal control approach to deep learning and applications to discrete-weight neural networks[J]. arXiv preprint arXiv:1803.01299, 2018.

Chen T Q, Rubanova Y, Bettencourt J, et al. Neural ordinary differential equations[C]//Advances in neural information processing systems. 2018: 6571-6583.

Zhang D, Zhang T, Lu Y, et al. You only propagate once: Painless adversarial training using maximal principle[J]. arXiv preprint arXiv:1905.00877, 2019.(Neurips2019)

###### Multi-grid like algorithm

Chang B, Meng L, Haber E, et al. Multi-level residual networks from dynamical systems view[J]. arXiv preprint arXiv:1710.10348, 2017.

Parpas P, Muir C. Predict Globally, Correct Locally: Parallel-in-Time Optimal Control of Neural Networks. arXiv:1902.02542.

#### Linking SDE

Lu Y. et al., Beyond Finite Layer Neural Network: Bridging Deep Architects and Numerical Differential Equations, ICML 2018.

Sun Q, Tao Y, Du Q. Stochastic training of residual networks: a differential equation viewpoint[J]. arXiv preprint arXiv:1812.00174, 2018.

Tzen B, Raginsky M. Neural Stochastic Differential Equations: Deep Latent Gaussian Models in the Diffusion Limit[J]. arXiv preprint arXiv:1905.09883, 2019.

Twomey N, Kozłowski M, Santos-Rodríguez R. Neural ODEs with stochastic vector field mixtures[J]. arXiv preprint arXiv:1905.09905, 2019.

neural jump stochastic differential equation arXiv:1905.10403

neural stochastic differential equation arXiv:1905.11065

Wang B, Yuan B, Shi Z, et al. Enresnet: Resnet ensemble via the feynman-kac formalism. arXiv preprint arXiv:1811.10745, 2018.



#### Theoritical Papers

Weinan E, Han J, Li Q. A mean-field optimal control formulation of deep learning[J]. Research in the Mathematical Sciences, 2019, 6(1): 10.

Thorpe M, van Gennip Y. Deep limits of residual neural networks[J]. arXiv preprint arXiv:1810.11741, 2018.

Avelin B, Nyström K. Neural ODEs as the Deep Limit of ResNets with constant weights[J]. arXiv preprint arXiv:1906.12183, 2019.

Zhang H, Gao X, Unterman J, et al. Approximation Capabilities of Neural Ordinary Differential Equations[J]. arXiv preprint arXiv:1907.12998, 2019.

Hu K, Kazeykina A, Ren Z. Mean-field Langevin System, Optimal Control and Deep Neural Networks[J]. arXiv preprint arXiv:1909.07278, 2019.

Tzen B, Raginsky M. Theoretical guarantees for sampling and inference in generative models with latent diffusions[J]. arXiv preprint arXiv:1903.01608, 2019.(COLR2019)

#### Robustness

Zhang J, Han B, Wynter L, Low KH, Kankanhalli M. Towards robust resnet: A small step but a giant leap. IJCAI 2019.

Yan H, Du J, Tan V Y F, et al. On Robustness of Neural Ordinary Differential Equations[J]. arXiv preprint arXiv:1910.05513, 2019.

Liu X, Si S, Cao Q, et al. Neural SDE: Stabilizing Neural ODE Networks with Stochastic Noise[J]. arXiv preprint arXiv:1906.02355, 2019.

Reshniak V, Webster C. Robust learning with implicit residual networks[J]. arXiv preprint arXiv:1905.10479, 2019.

Wang B, Yuan B, Shi Z, et al. Enresnet: Resnet ensemble via the feynman-kac formalism[J]. arXiv preprint arXiv:1811.10745, 2018.(Neurips2019)



#### Generative Models

Neural Ordinary Differential Equations (BEST PAPER AWARD)
Ricky T. Q. Chen, Yulia Rubanova, Jesse Bettencourt, David Duvenaud
Advances in Neural Information Processing Systems (NeurIPS).

FFJORD: Free-form Continuous Dynamics for Scalable Reversible Generative Models (ORAL)
Will Grathwohl, Ricky T. Q. Chen, Jesse Bettencourt, Ilya Sutskever, David Duvenaud
International Conference on Learning Representations (ICLR).

Invertible Residual Networks (LONG ORAL)
Jens Behrmann, Will Grathwohl, Ricky T. Q. Chen, David Duvenaud, Jörn-Henrik Jacobsen

Residual Flows for Invertible Generative Modeling (SPOTLIGHT)
Ricky T. Q. Chen, Jens Behrmann, David Duvenaud, Jörn-Henrik Jacobsen
Advances in Neural Information Processing Systems (NeurIPS).

Quaglino A, Gallieri M, Masci J, et al. Accelerating Neural ODEs with Spectral Elements[J]. arXiv preprint arXiv:1906.07038, 2019.

Yıldız Ç, Heinonen M, Lähdesmäki H. ODE $^ 2$ VAE: Deep generative second order ODEs with Bayesian neural networks[J]. arXiv preprint arXiv:1905.10994, 2019.(Neurips2019)

ANODEV2: A Coupled Neural ODE Framework arXiv:1906.04596

Port-Hamiltonian Approach to Neural Network Training CDC19

#### Image Processing


Liu R, Lin Z, Zhang W, et al. Learning PDEs for image restoration via optimal control[C]//European Conference on Computer Vision. Springer, Berlin, Heidelberg, 2010: 115-128.

Chen Y, Yu W, Pock T. On learning optimized reaction diffusion processes for effective image restoration CVPR2015

Xiaoshuai Zhang*, Yiping Lu*, Jiaying Liu, Bin Dong. "Dynamically Unfolding Recurrent Restorer: A Moving Endpoint Control Method for Image Restoration" Seventh International Conference on Learning Representations(ICLR) 2019(*equal contribution)

Xixi Jia, Sanyang Liu, Xiagnchu Feng, Lei Zhang, "FOCNet: A Fractional Optimal Control Network for Image Denoising," in CVPR 2019.


###### very early work for learning ode/pdes
Zhu S C, Mumford D B. Prior learning and Gibbs reaction-diffusion[C]. Institute of Electrical and Electronics Engineers, 1997.

Gilboa G, Sochen N, Zeevi Y Y. Estimation of optimal PDE-based denoising in the SNR sense[J]. IEEE Transactions on Image Processing, 2006, 15(8): 2269-2280.

Bongard J, Lipson H. Automated reverse engineering of nonlinear dynamical systems[J]. Proceedings of the National Academy of Sciences, 2007, 104(24): 9943-9948.

Liu R, Lin Z, Zhang W, et al. Learning PDEs for image restoration via optimal control[C]//European Conference on Computer Vision. Springer, Berlin, Heidelberg, 2010: 115-128.


#### Review Paper

Liu G H, Theodorou E A. Deep learning theory review: An optimal control and dynamical systems perspective[J]. arXiv preprint arXiv:1908.10920, 2019.


