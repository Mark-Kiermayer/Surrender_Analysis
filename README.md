# Surrender_Analysis
Surrender in Life Insurance

We provide both data and calibrated models for 4 different assumptions (profiles) and surrender behavior of policyholders. For detailed information see e.g. the respective paper "Modeling surrender risk in life insurance: theoretical and experimental insight"

Brief description of the files:
  - dict_range_scale_{profile}.pkl: dictionary containing information on min-max values (of training data for the resp. profile) which min-max-scaling applies to input features
  - profile_{profile}.7z: directory with training and test data for the resp. profile; also, models with calibrated parameters are provided in the sub-directory models
