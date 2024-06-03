# Fine-Tuning Generative AI Models on Intel Accelerators

Welcome to the repository dedicated to providing notebooks for the fine-tuning of foundational generative AI models on Intel Gaudi Accelerators and Intel Max Series GPUs. This repository contains a series of Jupyter notebooks that demonstrate the training and fine-tuning of various state-of-the-art generative AI models using PyTorch and Hugging Face libraries.

## Introduction

This repository is designed to provide practical examples and guidance on fine-tuning generative AI models using Intel's cutting-edge hardware accelerators. Whether you are working with Intel Gaudi Accelerators or Intel Max Series GPUs, these notebooks will help you leverage the power of these platforms to enhance your AI models.

## Models Included

The first batch of notebooks includes training code for the following models:

- Qwen 1.5 1.8B
- Falcon 7B
- Llama-2 7B
- Phi 1.5B
- Gemma 2B

## Libraries and Tools Used

The code in this repository primarily utilizes the following libraries and tools:

- [PyTorch](https://pytorch.org/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [PEFT (Parameter-Efficient Fine-Tuning)](https://huggingface.co/docs/peft/index)
- [Hugging Face Accelerate](https://huggingface.co/docs/accelerate/index)
- [TRL (Transformers Reinforcement Learning)](https://github.com/huggingface/trl)
- [oneAPI Base Toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit.html)
- [Intel Extension for PyTorch](https://github.com/intel/intel-extension-for-pytorch)

## Disclaimer for Using Large Language Models
Please be aware that while Large Language Models like Camel-5B and OpenLLaMA 3b v2 are powerful tools for text generation, they may sometimes produce results that are unexpected, biased, or inconsistent with the given prompt. It's advisable to carefully review the generated text and consider the context and application in which you are using these models.

Usage of these models must also adhere to the licensing agreements and be in accordance with ethical guidelines and best practices for AI. If you have any concerns or encounter issues with the models, please refer to the respective model cards and documentation provided in the links above.

To the extent that any public or non-Intel datasets or models are referenced by or accessed using these materials those datasets or models are provided by the third party indicated as the content source. Intel does not create the content and does not warrant its accuracy or quality. By accessing the public content, or using materials trained on or with such content, you agree to the terms associated with that content and that your use complies with the applicable license.

Intel expressly disclaims the accuracy, adequacy, or completeness of any such public content, and is not liable for any errors, omissions, or defects in the content, or for any reliance on the content. Intel is not liable for any liability or damages relating to your use of public content.

Intel’s provision of these resources does not expand or otherwise alter Intel’s applicable published warranties or warranty disclaimers for Intel products or solutions, and no additional obligations, indemnifications, or liabilities arise from Intel providing such resources. Intel reserves the right, without notice, to make corrections, enhancements, improvements, and other changes to its materials.
