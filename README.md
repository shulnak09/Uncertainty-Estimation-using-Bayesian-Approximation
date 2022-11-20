# Uncertainty-Estimation-using-Bayesian-Approximation

In this work, we estimate the posterior predictive distribution using Monte Carlo dropout during trajectory
forecasting for pedestrians. Our probabilistic model using MC dropout outperforms previous deterministic 
methods in terms of perfromance metrics like ADE and FDE.


##### Sample Trajectoy prediction with uncertainty. As per literature, we observe 8 (3.2 secs) historical steps to predict 12 steps (4.8 secs) into future.
  
  ![1D_CNN_ETH_traj_do_0.2_and_FP_4.8_secs_ID_58_traj_legend.pdf](https://github.com/shulnak09/Uncertainty-Estimation-using-Bayesian-Approximation/files/10050701/1D_CNN_ETH_traj_do_0.2_and_FP_4.8_secs_ID_58_traj_legend.pdf)


**cite** 
Contains the tensorflow implementation of our  [paper] (https://ieeexplore.ieee.org/document/9882968) on oogle colab. If you find this code 
helpful in your research, please consider citing our paper:

  @ARTICLE{9882968,
  author={Nayak, Anshul and Eskandarian, Azim and Doerzaph, Zachary},
  journal={IEEE Open Journal of Intelligent Transportation Systems}, 
  title={Uncertainty Estimation of Pedestrian Future Trajectory Using Bayesian Approximation}, 
  year={2022},
  volume={3},
  number={},
  pages={617-630},
  doi={10.1109/OJITS.2022.3205504}}
