# Machine-Translation-between-Arabic-and-English-by-Transformers
# Ways to apply fine tuning :

- full fine tuning : train all internal model parameters (called full parameter tuning). While this option is simple (conceptually), it is the most computationally expensive. Additionally, a known issue with full parameter tuning is the phenomenon of catastrophic forgetting.

- Transfer learning :The big idea with transfer learning (TL) is to preserve the useful representations/features the model has learned from past training when applying the model to a new task. This generally consists of dropping “the head” of a neural network (NN) and replacing it with a new one (e.g. adding new layers with randomized weights).

- Parameter Efficient Fine tuning : PEFT involves augmenting a base model with a relatively small number of trainable parameters. The key result of this is a fine-tuning methodology that demonstrates comparable performance to full parameter tuning at a tiny fraction of the computational and storage cost.

- LORA : PEFT encapsulates a family of techniques, one of which is the popular LoRA (Low-Rank Adaptation) method.

- Model on Huggigface for ar_en translation:
  https://huggingface.co/Elalimy/my_awesome_peft_finetuned_helsinki_model
- Model on Huggigface for ar_en translation:
  https://huggingface.co/Elalimy/finetuned_helsinki_peft_model__en_to_ar
- Dataset used is custom dataset for computer science terminology in addition to puplic words it also on Huggingface:
   https://huggingface.co/datasets/Elalimy/Arabic_Eng_MT
  also used opus100 dataset it is be availabe on huggingface 




