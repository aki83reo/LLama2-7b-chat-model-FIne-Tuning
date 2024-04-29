LLama2 Chat Model Fine-Tuning for Regex Questions
This project aims to fine-tune the LLama2 7B chat model to answer questions related to regular expressions (Regex). Due to the limited dataset available, the results should be interpreted with caution.

Dataset
We used the Python.org Regex PDF as our training dataset. This dataset provides a comprehensive overview of regular expressions, making it suitable for training our model.

Fine-Tuning Techniques
To improve the efficiency and effectiveness of the fine-tuning process, we employed the following techniques:

PEFT (Parameter Efficient Fine-Tuning): This technique significantly reduces the number of trainable parameters of a model while maintaining the same performance as full training. It helps in reducing memory consumption and training time.
LoRA (Low-Rank Adaptation of Model): LoRA works by inserting a smaller number of new weights into the model and training only these weights. This makes training faster, memory-efficient, and produces smaller model weights, which are easier to store and share.
Qlora (Quantized LoRA): Qlora quantizes the pretrained base weights in 4-bit precision, further reducing the model size and memory footprint.
Results
The fine-tuned LLama2 model shows promising results in answering Regex-related questions. However, further evaluation and testing are required to assess its performance accurately.

