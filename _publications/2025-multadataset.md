---
title: "MuLTa-Telegram"
collection: publications
category: papers
permalink: /publication/2025-11-30-multa-telegram-dataset
excerpt: 'MuLTa-Telegram: A Fine-Grained Italian and Polish Dataset for Hate Speech and Target Detection.'
date: 2025-11-30
venue: 'Proceedings of the Eleventh Italian Conference on Computational Linguistics (CLiC-it 2025) (pp. 582-594)'
paperurl: 'https://aclanthology.org/2025.clicit-1.56.pdf'
citation: ''
---

> Leonardelli, E., Casula, C., Salto, S. V., Bak, J. E., Muratore, E., Kołos, A., Louf, T. & Tonelli, S. (2025, September). MuLTa-Telegram: A Fine-Grained Italian and Polish Dataset for Hate Speech and Target Detection. In Proceedings of the Eleventh Italian Conference on Computational Linguistics (CLiC-it 2025) (pp. 582-594).

This paper introduces the MuLTa-Telegram dataset, a Multi- Lingual and multi-Target dataset specifically developed to detect hate speech on Telegram, an understudied yet influential platform in which extremist and fringe content can be found. The dataset contains about 4,000 Telegram messages in Italian and Polish, annotated for the presence of hate speech and its targets, including also target identity group mentions even when no hate is expressed. Unlike most existing hate speech datasets, which focus on a single target group, our dataset is explicitly designed to capture a diverse range of targets, ensuring a broad and representative sample of hateful (and non-hateful) content. Our work addresses the growing need for updated hate speech datasets, as many existing resources are based on platforms that no longer provide research-friendly data access, such as Twitter (X). Crucially, we show that training on existing out-of-domain data leads to poor results on Telegram data, underscoring the necessity of in-domain datasets for effective hate speech detection. We evaluate hate speech classification setups in an extensive series of experiments in both languages, including multilingual, multi-task, and LLM-based approaches. We find that incorporating target information leads to the best performances, enabling multilingual generalization. On the contrary, classification of specific targets shows much room for improvement across setups.