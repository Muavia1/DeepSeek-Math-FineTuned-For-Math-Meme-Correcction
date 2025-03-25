# DeepSeek-Math-FineTuned-For-Math-Meme-Correcction

This project fine-tunes the DeepSeek-Math-7B model using LoRA (Low-Rank Adaptation) to correct mathematical memes and equations efficiently. By leveraging 4-bit quantization and PEFT (Parameter-Efficient Fine-Tuning), the model improves mathematical reasoning while maintaining a lightweight footprint.

Key Features:

🚀 LoRA Fine-Tuning on attention layers for efficient adaptation

💾 4-bit Quantization using bitsandbytes for reduced memory usage

📊 Custom Training Dataset for math meme correction

🎯 Hugging Face Trainer for structured optimization

Example Correction:
✅ Input: (10/5) + 3 = 8?
❌ Incorrect! Solve brackets first: (10/5) = 2, then add 3 → Correct answer: 5
