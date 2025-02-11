# Principles of AI: LLMs (UPenn, Stat 9911, Spring 2025)

This course explores of Large Language Models (LLMs), from their fundamental principles to cutting-edge research directions. We aim to discuss the design and future of AI systems through lecture content and student-led presentations.

The course is structured around topics such as transformer architectures, empirical behaviors, training paradigms, and safety considerations. Students will also explore emerging challenges and the broader implications of AI technologies.

## Course Topics and Goals
- Introduce fundamental concepts in AI and LLMs.
- Discuss architecture and principles of LLMs, including transformers.
- Explore topics in LLMs and modern AI systems such as training paradigms (pre-training, post-training, alignment), inference/test-time computations, embeddings/representations, evaluations, capabilities, safety/security (jailbreaking, oversight, hallucinations, uncertainty), interpretability (circuits).
- Student presentations on key research papers and recent breakthroughs.

## Reference Materials
- [Course Syllabus](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/syllabus.pdf). 
- [Lecture  Notes](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/Stat_9911_Principles_of_AI.pdf); Work in progress.

## Lecture Content

### Introduction (Lec [01](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/Stat_9911_Lec_01.pdf), [02](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/Stat_9911_Lec_02.pdf))
- What is AI? Definitions and Goals
- Historical Overview of Artificial Intelligence
- The Challenge of AGI and Feasibility of AI in Daily Tasks

### LLM Architectures (Lec [03](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/Stat_9911_Lec_03.pdf), [04](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/Stat_9911_Lec_04.pdf), [05](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/Stat_9911_Lec_05.pdf), [06](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/Stat_9911_Lec_06.pdf))
- Input/Output Processing in AI Systems
- Transformer Mechanisms and Attention
- Key Architecture Details: Positional Encoding, Faster Attention
- Variations Across Model Architectures (e.g., GPT, Llama)
- Empirical Behavior: Scaling Laws, Emergence
- Extensions: Vision and Multimodal Language Models

### Pre-Training and Post-Training (Lec [07](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/Stat_9911_Lec_07.pdf))
- Pre-Training Paradigms
- Post-Training: Fine-Tuning and Instruction Tuning
- Alignment: Reward Learning and Reinforcement Learning from Human Feedback (RLHF)

### Inference, Decoding, and Test-Time Computation (Lec [08](https://github.com/dobriban/Principles-of-AI-LLMs/blob/main/Stat_9911_Lec_08.pdf))
- Simple and Advanced Sampling Methods
- Prompting, Chain-of-Thought, and Tree-of-Thought
- Reasoning

### Safety and Robustness
- Jailbreaking and Oversight Mechanisms
- Addressing Hallucinations in AI Systems
- Ensuring Robustness and Security

### Mechanistic Interpretability
- Embeddings and Representations
- Transformer Circuits

## Student Presentations
After initial lectures, students will lead presentations on topics of their choice in recent advances or research questions in AI. 

## Additional Resources
### Links to other courses
- [Foundations of Large Language Models](https://www.dropbox.com/scl/fo/v3jbijgpew64vv77cpwen/h?rlkey=hx1ux02uvhzdpq6tmbvo0bsuk&e=1&dl=0), U of Michigan, 2024
- [Language Modeling from Scratch](https://stanford-cs336.github.io/spring2024/), Stanford, Spring 2024
- [Recent Advances on Foundation Models](https://cs.uwaterloo.ca/~wenhuche/teaching/cs886/), U of Waterloo, Winter 2024
- [Large Models](https://www.cs.toronto.edu/~cmaddis/courses/csc2541_w25/), U of Toronto, Winter 2025


### Videos 
- Andrej Karpathy's [Neural Networks: Zero to Hero](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) video lectures. 100% coding-based, hands-on tutorial on implementing basic autodiff, neural nets, language models, and GPT-2 mini (124M params). 

### Key papers
- [The Llama 3 Herd of Models](https://arxiv.org/abs/2407.21783) describes the Llama "open-weights LLM" developed by Meta. Possibly the highest information content anywhere about LLMs.
- [DeepSeek-V3 Technical Report](https://arxiv.org/abs/2412.19437v1) and [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning
](https://arxiv.org/abs/2501.12948) describe the open-weights DeepSeek V3 and R1 models, which bring together several innovations in training LLMs to make them achieve comparable performance to some top closed models.

### Tutorials, books and book chapters 
- The corresponding sections in the [Understanding Deep Learning](https://udlbook.github.io/udlbook/) book. See also the associated tutorial posts: [LLMs](https://www.borealisai.com/research-blogs/a-high-level-overview-of-large-language-models/); Transformers [1](https://www.borealisai.com/research-blogs/tutorial-14-transformers-i-introduction/), [2](https://www.borealisai.com/research-blogs/tutorial-16-transformers-ii-extensions/), [3](https://www.borealisai.com/research-blogs/tutorial-17-transformers-iii-training/); [Training and fine-tuning](https://www.borealisai.com/research-blogs/training-and-fine-tuning-large-language-models/);  [Inference](https://www.borealisai.com/research-blogs/speeding-up-inference-in-transformers/)
- [Foundations of Large Language Models](https://arxiv.org/abs/2501.09223) book

### Workshops, conferences
[NeurIPS](https://nips.cc/), [ICML](https://icml.cc/), [ICLR](https://iclr.cc/)


