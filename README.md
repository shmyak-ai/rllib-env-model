# A deterministic (reproducible) example of a custom subclass Keras model with a simple custom Gymnasium environment for RLlib 2.3.0
Issues:
1. Config with 'tf2' mode and eager tracing enabled reports
   `input_dict["is_training"]) KeyError: 'is_training'`
2. 'tf' mode cannot restore policy from a checkpoint
