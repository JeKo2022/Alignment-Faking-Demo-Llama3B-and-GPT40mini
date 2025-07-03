**UPDATE: an extended version of my experiement has now been published on ArXiv.**
Please see: "Empirical Evidence for Alignment Faking in Small LLMs and Prompt-Based Mitigation Techniques" 
Link to paper: https://www.arxiv.org/abs/2506.21584


**Minimal Reproduction of Alignment Faking in Small LLMs**

[NB - extended version of this demo is under peer review]

**Project Summary**
This notebook presents a minimal reproduction of the helpful-only alignment faking setting discussed in Anthropic’s recent paper, applying it to two smaller models: Meta-Llama-3-8B-Instruct and OpenAI’s GPT-4o-mini. The goals of this experiment were threefold:

- Demonstrate AI safety evaluation skills through a case study of alignment faking.
→ This includes applying statistical significance testing (e.g., Fisher’s exact test) to assess the reliability of observed behavioral differences — showcasing familiarity with evaluation methodologies in safety research.

- Investigate whether smaller models exhibit alignment faking under minimal prompting setups.
→ Alignment faking is often framed as an emergent phenomenon in larger models. These findings challenge that assumption by showing that even smaller models may exhibit this behavior under certain conditions.

- Explore whether prompt engineering using ethical frameworks can reduce the compliance gap.
→ Introducing deontological ethical reasoning into system prompts appears to reduce the alignment gap, suggesting potential for prompt-based alignment strategies.


These findings are preliminary and intended as a public showcase on GitHub. A more detailed paper on this topic is currently under peer review.

**Read the accompanying LessWrong post**
[https://www.lesswrong.com/posts/7QTQAE952zkYqJucm/correcting-deceptive-alignment-using-a-deontological] 

**View the notebook on GitHub**
[https://github.com/JeKo2022/Alignment-Faking-Demo-Llama3B-and-GPT40mini/blob/main/Copy_of_Alignment_Faking_Demo_Llama3B_and_GPT40mini.ipynb]

All rights reserved.

This repository is made available for viewing purposes only. No part of this code may be copied, reproduced, distributed, or used in any form without express written permission from the author.
