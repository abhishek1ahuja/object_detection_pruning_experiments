# Progress Update 
Last Update: Oct 18, 2023

**Aim:** to perform pruning experiments for the task of Image Classification
**Dataset:** Incidents Dataset
**Base models:** MobileNet / ResNet-50
**Pruning Technique:** Lottery Ticket Hypothesis

**Goal:** to to replicate Lottery Ticket Hypothesis (LTH) and produce pruning graphs like below as demonstrated in the project https://github.com/arjun-majumdar/Lottery_Ticket_Hypothesis-TensorFlow_2 notebook https://github.com/arjun-majumdar/Lottery_Ticket_Hypothesis-TensorFlow_2/blob/master/Conv_2_LTH_CIFAR10.ipynb

![LTH - Percentage pruned vs Accuracy](assets/charts/lth_arjun_pc_pruned_vs_accuracy.png)

![LTH - Percentage pruned vs Loss](assets/charts/lth_arjun_pc_pruned_vs_loss.png)

![LTH - Percentage pruned vs Num of Epochs (Early Stopping)](assets/charts/lth_arjun_pc_pruned_vs_num_epochs_until_convergence.png)

![LTH - Percentage pruned vs Starting Accuracy](assets/charts/lth_arjun_pc_pruned_vs_starting_accuracy.png)

![LTH - Percentage pruned vs Starting Loss](assets/charts/lth_arjun_pc_pruned_vs_starting_loss.png)

![LTH - Percentage pruned vs Best Accuracy](assets/charts/lth_arjun_pc_pruned_vs_best_acc.png)

![LTH - Percentage pruned vs Best Loss](assets/charts/lth_arjun_pc_pruned_vs_best_loss.png)



Current progress: atttempt to replicate LTH tensorflow experiment with different base model and dataset
![Incidents Mobilenet Transfer Learning Baseline](assets/charts/learning_curve_incidents_mobilenet_baseline.png)

