# survey-physics-based-NN
This repository is about papers that utilize the physics and neural networks.


|  Name   | Description | Data | Sources |
|  ----  | ----  | ---- | ---- |
| Physics Informed Deep Learning | Enforce underlying physics laws as a regularization, the loss of neural networks is the MSE of prediction and actual data + MSE of PDEs/ODEs. | Synthetic PDEs |[Github](https://maziarraissi.github.io/PINNs/)  |
| Physics-Informed Neural Networks for Nonhomogeneous Material Identification in Elasticity Imaging |PINN | Elasticity Imaging| [arXiv](https://arxiv.org/abs/2009.04525) |
| On the Convergence of PINNs | Proving that PINN's formulation converges to solution to the underlying PDEs | | [arXiv](https://arxiv.org/abs/2004.01806) |
| Deep Learning for Physical Processes: Incorporating Prior Scientific Knowledge |  Use geometric transformations to wrap and estimate the motion vector. Use convolutional-deconvolutional (CDNN) to predict the next image(time step). | Synthetic SST data of the [Atlantic ocean](https://resources.marine.copernicus.eu/?option=com_csw&product_id=GLOBAL_ANALYSIS_FORECAST_PHY_001_024&view=details) | [arXiv](https://arxiv.org/abs/1711.07970) |
| Towards physics-informed deep learning for turbulent flow prediction| Based on RANS-LES method, the Navior-stokes equation's velocity w(decoupled into v(t) and u(t) along x,y directions) can be decomposed into components with neural network filters, then a shared decoder is used to learn the interactions. | Two dimensional turbulent flow simulated with Lattice Boltzmann Method | [arXiv](https://arxiv.org/abs/1911.08655) |
|Physics Guided RNNs for Modeling Dynamical Systems: A Case Study in Simulating Lake Temperature Profiles | Using PGRNN, LSTM-based model to predict the flow of the river. The training is done with synthetic data for generalization. |  Simulated for training, prediction data from Lake Mendota.  | [arXiv](https://arxiv.org/abs/1810.13075) |

