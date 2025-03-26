# CPU-Based-Fine-Tuning-of-Small-Language-Models-SLMs-with-Azure-Machine-Learning-Phi-4

This hands-on will guide you through fine-tuning an open source LLM on Azure and making the fine-tuned model available on Azure. We are using the Microsoft Phi-4-mini-8k-instruct model, but you are free to use it as long as it is a public LLM registered with Hugging Face.

We will learn how to use QLoRA to fine-tune phi-4-mini-8k-instruct:QLoRA is an efficient fine-tuning technique that quantizes a pre-trained language model to 4 bits and attaches a small fine-tuned “low-rank adapter” to it. In this example, the choice was made to use a cpu for model training, which, despite the longer training time, offers a more flexible and scalable solution with better cost-effectiveness, broader availability, and ease of use for smaller training tasks and debugging, and in some cases may not require the large computational power of a GPU.
