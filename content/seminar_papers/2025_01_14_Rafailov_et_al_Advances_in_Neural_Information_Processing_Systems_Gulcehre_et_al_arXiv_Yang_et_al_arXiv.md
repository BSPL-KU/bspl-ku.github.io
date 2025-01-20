---
title: "[Article] Direct preference optimization: Your language model is secretly a reward model"
title: "[Article] Reinforced self-training (rest) for language modeling"
title: "[Article] Rlcd: Reinforcement learning from contrast distillation for language model alignment"
date: 2025-01-14
---
summary:  
(1) This paper proposes a method to directly align language models using human preference data without reinforcement learning. It simplifies the optimization process by utilizing a binary classification loss based on human preferences, eliminating the need for explicit reward model training. This approach is simpler, more stable, and more efficient than RLHF.
(2) ReST is a reinforcement learning algorithm that improves language model policies by sampling outputs from an initial model and refining them using offline RL. It enhances data reusability, reduces computational costs, and aligns outputs with human preferences.
(3) RLCD aligns language models using contrastive distillation by generating preference data from positive and negative prompts. A reward model trained on these preferences refines the model via reinforcement learning. This approach reduces noise in preference data and achieves superior alignment compared to RLHF.

[Rafailov, Rafael, et al. "Direct preference optimization: Your language model is secretly a reward model." Advances in Neural Information Processing Systems 36 (2024).](https://proceedings.neurips.cc/paper_files/paper/2023/hash/a85b405ed65c6477a4fe8302b5e06ce7-Abstract-Conference.html)
[Gulcehre, Caglar, et al. "Reinforced self-training (rest) for language modeling." arXiv preprint arXiv:2308.08998 (2023).](https://arxiv.org/abs/2308.08998)
[Yang, Kevin, et al. "Rlcd: Reinforcement learning from contrast distillation for language model alignment." arXiv preprint arXiv:2307.12950 (2023).](https://arxiv.org/abs/2307.12950)
