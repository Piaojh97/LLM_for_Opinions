# LLM-Polarization

Official implementation of this paper.

Emergence of human-like polarization among large language model agents

# Run
## Assigning LLM
Fill in:
<ol>
<li> OpenAI-API key
<li> LLM Model for simulation
</ol>
in file <strong>utils_repub_pol_5_gpt_affect_dummy_simulate_sorted_fix.py</strong>

## Defining simulation settings
Define keywords for experiment prompts:
<ol>
<li> environment: Field of Conversation
<li> topic: Topic to discuss
<li> S_m2: Extreme negative standpoint
<li> S_m1: Moderate negative standpoint
<li> S_0: Neutral standpoint
<li> S_m2: Extreme positive standpoint
<li> S_m1: Moderate positive standpoint
<li> S_m2_e: Explaination of S_m2
<li> S_m1_e: Explaination of S_m1
<li> S_0_e: Explaination of S_0
<li> S_p1_e: Explaination of S_p1
<li> S_p2_e: Explaination of S_p2
<li> side_s_0: Negative agent discription
<li> side_e_0: Neutral agent discription
<li> side_b_0: Positive agent discription
</ol>

Define experimental settings:
<ol>
<li> datasource: Path to network for initialization
<li> num_epoch: Epoch number to simulate
<li> starting_epoch: Which epoch to continue simulation (0 for new simulation)
<li> side_init: The initialize standpoint distribution of agents
<li> abb: Output path for experimental result
</ol>  
in file <strong>run.py</strong> 

