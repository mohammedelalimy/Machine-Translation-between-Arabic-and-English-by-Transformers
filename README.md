# Machine-Translation-Arabic-to-English-by-Transformers
# Ways to apply fine tuning :

- full fine tuning : train all internal model parameters (called full parameter tuning). While this option is simple (conceptually), it is the most computationally expensive. Additionally, a known issue with full parameter tuning is the phenomenon of catastrophic forgetting.

- Transfer learning :The big idea with transfer learning (TL) is to preserve the useful representations/features the model has learned from past training when applying the model to a new task. This generally consists of dropping “the head” of a neural network (NN) and replacing it with a new one (e.g. adding new layers with randomized weights).

- Parameter Efficient Fine tuning : PEFT involves augmenting a base model with a relatively small number of trainable parameters. The key result of this is a fine-tuning methodology that demonstrates comparable performance to full parameter tuning at a tiny fraction of the computational and storage cost.

- LORA : PEFT encapsulates a family of techniques, one of which is the popular LoRA (Low-Rank Adaptation) method.



