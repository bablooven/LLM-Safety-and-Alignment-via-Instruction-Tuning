## Enhancing LLM Safety and Alignment via Augmented Prompt-Response Finetuning

**Project Description**:
We are presently immersed in a research initiative examining the ramifications of integrating "honest/unsafe" instances, which consist of prompts with harmful or inappropriate content intent alongside abstention or appropriate responses, into an instruction-tuning dataset for a Large Language Model (LLM) during its Supervised Fine-tuning (SFT) process. Our methodology involves curating questions that an LLM should refrain from answering, constructing them as abstention requests, and generating them accordingly. Leveraging v GPT-4, we have produced these "unsafe" prompts.

Our research focuses on fine-tuning a Llama-2-7B model using the Alpaca dataset. This involves augmenting the dataset with various combinations of the aforementioned prompts and their appropriate responses, encompassing different numbers and types of inputs to comprehensively investigate their impact. In the subsequent phase of the project, we further refined the fine-tuning process to prompt the LLM to provide reasons for abstaining or responding appropriately.

**Conservativeness Inference Score (%) by Model**:

![Website Image](https://github.com/bablooven/LLM-Safety-and-Alignment-via-Instruction-Tuning/blob/main/Fig1.png)

**Safety Inference Score (%) by Model for LLM-attacks dataset**:

![Website Image](https://github.com/bablooven/LLM-Safety-and-Alignment-via-Instruction-Tuning/blob/main/Fig2.png)

**Safety Inference Score (%) by Model for Do-not Answer dataset**:

![Website Image](https://github.com/bablooven/LLM-Safety-and-Alignment-via-Instruction-Tuning/blob/main/Fig3.png)

**Safety Inference Score (%) by Model for Beaver dataset**:

![Website Image](https://github.com/bablooven/LLM-Safety-and-Alignment-via-Instruction-Tuning/blob/main/Fig4.png)





