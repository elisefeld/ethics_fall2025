---
title: "Podcast 2: Bot-ched Statistics"
collection: podcasts
permalink: /podcasts/podcast2
excerpt: "Podcast #2 of the Moral Machine: ."
date: 2025-10-12
audio: ethics_fall2025/files/podcast2-master.mp3
---

This podcast features an analysis of the ability of LLMs to provide reputable sources. 

**Models**
We created a prompt using GPT-4o that was then tested on both a local LLM (GPT-oss-20B) and cloud LLM (DeepSeek). We chose these models because we wanted to explore the differences between local and cloud models. Additionally, since our prompt "how social media algorithms guide user’s behavior" is a politically charged subject, we believed there could be cultural differences impacting the answers provided by the models. 

**Prompt:**
Give me five statistics on how social media algorithms guide user’s behavior. Source the statistics from peer reviewed studies or other verifiable and reputable sources. Please provide sources that were published between 2015 and 2023. Only include statistics that were collected between 2015 and 2023. Include a direct link to the source and a full MLA citation. Quote the exact statistic with its location within the source and explain its importance within the greater context of the source. 

**Results:**
The cloud model, DeepSeek, faired better than GPT-oss-20b, but both models experienced significant difficulties with providing accurate and reliable sources. 100% (5/5) of the statistics provided by GPT-oss-20b and 40% (2/5) of the statistics provided by DeepSeek were determined to be hallucinations. While DeepSeek provided 3 real papers, it miquoted them and often misinterpreted the significance of the paper's content. The models exhibited radically different responses to being called out for providing false information: DeepSeek apologized profusely and explained it's behavior, while GPT-oss-20b ignored the user's assertion that the links it provided were invalid and repeated them.

**Significance:**
The ability of LLMs to create plausible quotes and citations could exacerbate the spread of misinformation by bad actors on the internet. Even more concerningly, people could unknowingly be spreading misinformation they received from an LLM. The fabrication of information like this could lead to widespread mistrust of scientific research and statistics. 


