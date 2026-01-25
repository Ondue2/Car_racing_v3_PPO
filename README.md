Car racing v3 of Gymnasium was solved via PPO.

Gauge information was extracted and used for gating the structural information from the CNN layer. It works well without overlapping multiple steps.

NN outputs alpha and beta for the Beta-distribution (both are larger than 1), so that the mean and std of action are state-dependently determined.

Huber loss is used for the critic loss.

The initial Zoom-in part was masked in training.

The Jupyter notebook file and trained parameters (~900 reward per 1,000 steps) were uploaded.

https://github.com/user-attachments/assets/fdbe97e6-f32c-4853-8d6d-eb17048218e0

