---
title: "Language Specific Knowledge: Do Models Know Better in X than in English?"
collection: publications
category: preprints
permalink: /publication/lskextractor
excerpt: 'This paper introduces Language Specific Knowledge (LSK), exploring how language models can exhibit better reasoning in languages other than English, particularly in culturally specific contexts.'
date: 2025-05-21
venue: 'arXiv'
slidesurl: ''
paperurl: 'https://arxiv.org/pdf/2505.14990'
citation: 'Ishika Agarwal, Nimet Beyza Bozdag, Dilek Hakkani-Tür. 2025. Language Specific Knowledge: Do Models Know Better in X than in English?. arXiv:2505.14990'
---

Code-switching is a common phenomenon of alternating between different languages in the same utterance, thought, or conversation. We posit that humans code-switch because they feel more comfortable talking about certain topics and domains in one language than another. With the rise of knowledge-intensive language models, we ask ourselves the next, natural question: Could models hold more knowledge on some topics in some language X? More importantly, could we improve reasoning by changing the language that reasoning is performed in? We coin the term Language Specific Knowledge (LSK) to represent this phenomenon. As ethnic cultures tend to develop alongside different languages, we employ culture-specific datasets (that contain knowledge about cultural and social behavioral norms). We find that language models can perform better when using chain-of-thought reasoning in some languages other than English, sometimes even better in low-resource languages. Paired with previous works showing that semantic similarity does not equate to representational similarity, we hypothesize that culturally specific texts occur more abundantly in corresponding languages, enabling specific knowledge to occur only in specific "expert" languages. Motivated by our initial results, we design a simple methodology called LSKExtractor to benchmark the language-specific knowledge present in a language model and, then, exploit it during inference. We show our results on various models and datasets, showing an average relative improvement of 10% in accuracy. Our research contributes to the open-source development of language models that are inclusive and more aligned with the cultural and linguistic contexts in which they are deployed.