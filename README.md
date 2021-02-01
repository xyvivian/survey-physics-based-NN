# survey-physics-based-NN
This repository is about papers that utilize the physics and neural networks.


|  Name   | Description | Data | Sources |
|  ----  | ----  | ---- | ---- |
| Physics Informed Deep Learning | Enforce underlying physics laws as a regularization, the loss of neural networks is the MSE of prediction and actual data + MSE of PDEs/ODEs. | Synthetic PDEs |[Github](https://maziarraissi.github.io/PINNs/)  |
| Deep Learning for Physical Processes: Incorporating Prior Scientific Knowledge |  Use geometric transformations to wrap and estimate the motion vector. Use convolutional-deconvolutional (CDNN) to predict the next image(time step). | Synthetic SST data of the [Atlantic ocean](https://resources.marine.copernicus.eu/?option=com_csw&product_id=GLOBAL_ANALYSIS_FORECAST_PHY_001_024&view=details) | [arXiv](https://arxiv.org/abs/1711.07970) |
| Towards physics-informed deep learning for turbulent flow prediction| Based on RANS-LES method, the Navior-stokes equation's velocity w(decoupled into v(t) and u(t) along x,y directions) can be decomposed into components with neural network filters, then a shared decoder is used to learn the interactions. | Two dimensional turbulent flow simulated with Lattice Boltzmann Method | [arXiv](https://arxiv.org/abs/1911.08655) |
|Physics Guided RNNs for Modeling Dynamical Systems: A Case Study in Simulating Lake Temperature Profiles |   |     | [arXiv](https://arxiv.org/abs/1810.13075) |

