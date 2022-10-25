# Pretraining a RoBERTa Model from Scratch

RoBERTa is another interesting and popular variant of BERT. Researchers observed that BERT is severely undertrained and proposed several approaches to pre-train the BERT model. RoBERTa is essentially BERT with the following changes in pre-training:
- Use dynamic masking instead of static masking in the MLM task.
- Remove the NSP task and train using only the MLM task.
- Train with a large batch size.
- Use byte-level BPE (BBPE) as a tokenizer.
