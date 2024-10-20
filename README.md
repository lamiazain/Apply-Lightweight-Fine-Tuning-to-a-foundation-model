# Project Introduction

Lightweight fine-tuning is one of the most important techniques for adapting foundation models, because it allows you to modify foundation models for your needs without needing substantial computational resources.

In this project, we will apply __parameter-efficient fine-tuning__ using the Hugging Face ```peft``` library.

# Project Summary:
In this project, we will bring together all of the essential components of a PyTorch + Hugging Face training and inference process. Specifically, we will:

- Load a pre-trained model and evaluate its performance
- Perform parameter-efficient fine tuning using the pre-trained model
- Perform inference using the fine-tuned model and compare its performance to the original model.
  
# Important documentation links

- [Hugging Face PEFT configuration](https://huggingface.co/docs/peft/package_reference/config)
- [Hugging Face LoRA adapter](https://huggingface.co/docs/peft/package_reference/lora)
- [Hugging Face Models save_pretrained](https://huggingface.co/docs/transformers/main/en/main_classes/model#transformers.PreTrainedModel.save_pretrained)
- [Hugging Face Text Generation](https://huggingface.co/docs/transformers/main_classes/text_generation)
  
### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/lamiazain/Apply-Lightweight-Fine-Tuning-to-a-foundation-model.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Apply-Lightweight-Fine-Tuning-to-a-foundation-model
   ```
3. Install the requirements.txt file:
   ```
   !pip install requirements.txt
   ```
## License
This is a Udacity Guided Project in the [Generative AI](https://www.udacity.com/enrollment/nd608) NanoDegree.
