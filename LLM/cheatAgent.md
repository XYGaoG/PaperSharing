# [CheatAgent: Attacking LLM-Empowered Recommender Systems via LLM Agent](https://dl.acm.org/doi/pdf/10.1145/3637528.3671837)

### Introduction
Due to the powerful language understanding and in-context learning ability, LLM have provided great potential to recommendation.  But the vulnerability of LLM-empowered RS makes it under adversarial attack. For example, attackers leverage the LLM agent to insert some tokens (e.g., words) or items in the user’s prompt to manipulate the LLM-empowered recommender system to make incorrect decisions.![image]

### Challenges
In black-box attack, a mainstream method is to develop RL-based agents to obtain malicious user profiles (i.e., a series of items) and inject them into the victim RecSys for manipulating system’s decision. But existing methods suffer from several limitations:

•	vanilla RL-based agents struggle with processing the textual input (e.g., item’s title and descriptions) and context awareness, resulting in difficulty in attacking LLM-empowered RecSys.

•	most existing methods optimize the RL-based agent attackers from scratch without human-level intelligence, which subsequently leads to poor capability in planning and reasoning the attacking strategies under the black-box setting.

### Motivation
LLM has remarkable potential in approximating human-level intelligence and it can well comprehend human common sense in natural language and perform complex reasoning, so as to simulate human-like decision-making processes.
Therefore, we can leverage llms as attack agents to attack recsys.
