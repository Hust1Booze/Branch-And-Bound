# Machine Learning for variables selection in Branch and Bound(B&B) 

1. **Improving Learning to Branch via Reinforcement Learning.** ICLR 2021 Reject

2. **Learning to Branch with Offline Reinforcement Learning.** ICLR 2022 Reject
   
   *Learning a score net G(a|s) of Strong Branch, In RL, if action not in top(G(a|s)), give a negative reward  
   RL with modify A2C, Reward: improvement of dual bound*   
  
3. **Exact Combinatorial Optimization with Graph Convolutional Neural Networks.** NeurIPS 2019 [Code](https://github.com/ds4dm/learn2branch)
   
   *a bipartite graph representation of nodes in B&B, IL and GCNN*   

4. **Reinforcement Learning for Variable Selection in a Branch and Bound Algorithm.** CPAIOR 2020
   
   *prove minimise subtree equal to minimise the whole tree with DFS*  

5. **Parameterizing Branch-and-Bound Search Trees to Learn Branching Policies.** AAAI 2021 [Code](https://github.com/ds4dm/branch-search-trees)
   
    *try to generalizes across heterogeneous MILPs, add tree feature to net,not only force node feature, IL*

6. **Solving Mixed Integer Programs Using Neural Networks.** arXiv 2021 Deepmind,Google

7. **An Improved Reinforcement Learning Algorithm for Learning to Branch.** arXiv 2022 Beihang,Huawei
    
   *Offline RL then online RL, use offline data to accelerate training, modeify Double DQN and GCNN, reward: dual integral*  

8. **Branch Ranking for Efficient Mixed-Integer Programming via Offline Ranking-based Policy Learning.** ECML PKDD 2022 Shangjiao,Huawei   
    
    *only highest scores SB action and action belong to top k trajectories from current s to end, Offline RL, GCNN*  

9. **Learning to branch with Tree-aware Branching Transformers.** KBS 2022 Tsinghua [Code](https://github.com/linjc16/TBranT)  

   *Follow [Parameterizing Branch-and-Bound Search Trees to Learn Branching Policies], use attention to capture info between candidate variables
   Integrates branching history which is conducive to branching, IL*  

10. **A GNN-Guided Predict-and-Search Framework for Mixed-Integer Linear Programming.** ICLR 2023 [Code](https://github.com/sribdcn/Predict-and-Search_MILP_method)  
    
    *constructs a trust region to search for highquality feasible solutions*  

11. **Learning to Branch with Tree MDPs.** NeurIPS 2022 Delft [Code](https://github.com/lascavana/rl2branch)  
    
    *Build tree MDPs for Branch and bound in RL*  

12. **Lookback for Learning to Branch.** TMLR 2022 Oxford  
    
    *a child node’s best choice was often the parent’s second-best choice, IL*  

13. **Exact Combinatorial Optimization with Temporo-Attentional Graph Neural Networks.** ECML PKDD 2023 HuaWei [Code](https://developer.huaweicloud.com/develop/aigallery/notebook/detail?id=047c6cf2-8463-40d7-b92f-7b2ca998e935)  

    *Use Graph attention Network instead of GCN, use Gated Recurrent Unit (GRU) to capture the temporal information, IL*  

14. **LIMIP: Lifelong Learning to Solve Mixed Integer Programs.** AAAI 2023 [Code](https://github.com/ideaiitd/LiMIP)  

    *Lifelong learning of MIP and modified GCNN, IL*  

15. **Reinforcement Learning for Branch-and-Bound Optimisation Using Retrospective Trajectories.** AAAI 2023 UCL [Code](https://github.com/cwfparsonson/retro_branching)
    
    *By decompose a B&B tree to muti trajectories, agent can learn from shorter trajectories with more predictable next states, this method can ignore node selection policy, RL*  

16. **A Deep Instance Generative Framework for MILP Solvers Under Limited Data Availability.** NeurIPS 2023 USTC,HuaWei [Code](https://miralab-ustc.github.io/L2O-G2MILP)

    *Use masked variational autoencoder to iteratively corrupt and replace parts of the original graphs to generate new ones*

17. **Towards Imitation Learning to Branch for MIP: A Hybrid Reinforcement Learning based Sample Augmentation Approach.** ICLR 2024 Lenovo,ShangJiao

    *Use RL method to argument data to train IL, online rl agent use to select action in expert(SB) or trained il net(GCNN) output, offline rl agent ues to judge if the data is good enough by R>V(s)?
    R is the real Rturn-to-Go and V(s) is the offline rl estimate value, method idea seems borrowed from [Self-Imitation Learning]*

    
