---
title: "Autonomous Topological Reasoning with Large Language Models"
collection: publications
category: preprints
permalink: /publication/ample
date: 2024-10-14
venue: 'Arxiv'
paperurl: 'https://pgimenes.github.io/files/autonomous-topological-reasoning.pdf'
---

<!-- [Arxiv link](https://arxiv.org/abs/2410.06722) -->

Topological reasoning with Large Language Models (LLMs) emulates human-like thought processes by efficiently exploring various reasoning paths over thought trees or graphs. However, prior works rely on static, task-specific prompting schedules to decompose problems and synthesize solutions, which are subject to a hyperparameter set requiring extensive search for high query efficiency. Additionally, the task-specific requirement restricts generalization to novel problem domains and fails to adapt to varying problem complexities. In our work, we investigate the ability of LLMs to guide thought graph exploration in a multi-agent architecture with policy agents and reasoning agents. While reasoning agents solve decomposed subproblems, policy agents maintain visibility of the reasoning trace, dynamically adaptating the problem-solving strategy. Through extensive controlled experiments, we observe that in problems with low decomposition depth, LLM-guided \az{LLM-planned? I think LLM as a planner is a thing, so shifting it slightly to that language might be helpful.} exploration can match or even outperform static schedules by up to $3.3\times$, without any search time required. At high decomposition depths, existing models lead to performance deterioration of up to $4.4\times$, highlighting the requirement for new solutions to enable more flexible and generalizable topological reasoning with LLMs.