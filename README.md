## Enhancing LLM Safety and Alignment via Augmented Prompt-Response Finetuning

Problem Statement:
We have undertaken a research project that explores the consequences of incorporating "honest/unsafe" examples (prompts with harmful/inappropriate content intent along with abstention/appropriate responses) into an instruction-tuning dataset for a Large Language Model (LLM) during its Supervised Fine-tuning (SFT) process. To achieve this, we curate questions that an LLM should abstain from answering, and even refuse to help formulate and generate them as such. We have generated these "unsafe" prompts, by leveraging v GPT-4. Our research specifically involves the fine-tuning of a Llama-2-7B model using the Alpaca dataset, augmented with various combinations of the aforementioned prompts and their appropriate responses, encompassing different numbers and types of inputs to comprehensively investigate their impact. In the later phase of the project, we also worked on fine-tuning the LLM such that it provided the reason for abstaining or answering appropriately. Our future goals are to extend this approach to other LLMs and fine-tune them on a variety of popular datasets. 

**Conservativeness Inference Score (%) by Model**
![Website Image](https://github.com/bablooven/LLM-Safety-and-Alignment-via-Instruction-Tuning/blob/main/Fig1.png)

