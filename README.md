
# ML Knowledge Distillation for fine-tuning pre-trained models.
This project/experiment was conducted at The University of Scranton with the purpose of learning and exploring the knowledge distillation technique 
in the context of fine-tuning pre-trained models. Specifically, the technique is applied to the compact series of BERT models 
(bert-medium, bert-small, bert-mini, and bert-tiny) with bert-base-uncased as the teacher model, all imported from the HuggingFace hub.

## Models

### BERT base model used as teacher
bert-base-uncased: https://huggingface.co/google-bert/bert-base-uncased

### Compact BERT models used as students
bert-medium: https://huggingface.co/prajjwal1/bert-medium

bert-small: https://huggingface.co/prajjwal1/bert-small

bert-mini: https://huggingface.co/prajjwal1/bert-mini

bert-tiny: https://huggingface.co/prajjwal1/bert-tiny

## Dataset
SetFit/imdb on HuggingFace hub: https://huggingface.co/datasets/SetFit/imdb

## Related Papers
Knowledge distillation: https://arxiv.org/abs/1503.02531

BERT: https://arxiv.org/abs/1810.04805

BERT family: https://arxiv.org/abs/1908.08962
