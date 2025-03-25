# DeepSeek-Math-FineTuned-For-Math-Meme-Correcction

This project fine-tunes the DeepSeek-Math-7B model using LoRA (Low-Rank Adaptation) to enhance its ability to correct mathematical memes and equations. By applying parameter-efficient fine-tuning (PEFT) and 4-bit quantization, the model effectively identifies and corrects incorrect mathematical expressions while maintaining computational efficiency.

🚀 Features
✅ Fine-Tuned LLM: DeepSeek-Math-7B adapted for math meme correction
✅ Efficient Training: LoRA fine-tuning on attention layers for lightweight adaptation
✅ Quantization: 4-bit bitsandbytes compression for reduced memory usage
✅ Custom Dataset: Math meme corrections in CSV format
✅ Hugging Face Trainer: Used for structured and optimized training

📉 Training Performance
LoRA applied to query, key, value, and projection layers

Significant loss reduction during training, improving equation correction accuracy

Example correction:

Input: (10/5) + 3 = 8?

Output: Incorrect! Solve brackets first: (10/5) = 2, then add 3 → Correct answer: 5
