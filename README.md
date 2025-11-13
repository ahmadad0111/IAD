# Adaptive Human–AI Coordination via Hierarchical Action Disentanglement


## Results

Below are visualizations showing **partner-skill evolution** during evaluation in two layouts: **Cramped Room** and **Forced Coordination**.

- **Cramped Room Evaluation**

This figure shows how the AI agent selects skills when partnering with different partners with diverse play styles. Each **row corresponds to a specific partner**, and the **color indicates which skill** the AI agent is using at each timestep throughout the episode. This visualization highlights how the AI agent adapts its skill selection to match the partner’s behavior.
  
  ![Cramped Room](plots/cramped_room_skill_evolution.png)

**Gameplay GIFs for all partners (0–15)**

In the following GIFs, the **blue agent** acts as the partner from the self-play population, while the **green-hat player** represents the AI agent being evaluated. Each GIF illustrates how the AI agent adapts its behavior and skill selection to coordinate with a specific partner.
| Partner 0 | Partner 1 | Partner 2 | Partner 3 |
|-----------|-----------|-----------|-----------|
| ![P0](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent0.gif) | ![P1](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent1.gif) | ![P2](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent2.gif) | ![P3](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent3.gif) |

| Partner 4 | Partner 5 | Partner 6 | Partner 7 |
|-----------|-----------|-----------|-----------|
| ![P4](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent4.gif) | ![P5](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent5.gif) | ![P6](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent6.gif) | ![P7](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent7.gif) |

| Partner 8 | Partner 9 | Partner 10 | Partner 11 |
|-----------|-----------|------------|------------|
| ![P8](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent8.gif) | ![P9](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent9.gif) | ![P10](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent10.gif) | ![P11](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent11.gif) |

| Partner 12 | Partner 13 | Partner 14 | Partner 15 |
|------------|------------|------------|------------|
| ![P12](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent12.gif) | ![P13](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent13.gif) | ![P14](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent14.gif) | ![P15](Results/10M/IAD/cramped_room/visualizations/cramped_room_blue_riayn_green_spagent15.gif) |

---

- **Forced Coordination Evaluation**
  
This figure shows how the AI agent selects skills when partnering with different partners with diverse play styles. Each **row corresponds to a specific partner**, and the **color indicates which skill** the AI agent is using at each timestep throughout the episode. This visualization highlights how the AI agent adapts its skill selection to match the partner’s behavior.
  ![Forced Coordination](plots/forced_coordination_skill_evolution.png)


**Gameplay GIFs for all partners (0–15)**

In the following GIFs, the **blue agent** acts as the partner from the self-play population, while the **green-hat player** represents the AI agent being evaluated. Each GIF illustrates how the AI agent adapts its behavior and skill selection to coordinate with a specific partner.
| Partner 0 | Partner 1 | Partner 2 | Partner 3 |
|-----------|-----------|-----------|-----------|
| ![P0](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent0.gif) | ![P1](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent1.gif) | ![P2](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent2.gif) | ![P3](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent3.gif) |

| Partner 4 | Partner 5 | Partner 6 | Partner 7 |
|-----------|-----------|-----------|-----------|
| ![P4](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent4.gif) | ![P5](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent5.gif) | ![P6](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent6.gif) | ![P7](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent7.gif) |

| Partner 8 | Partner 9 | Partner 10 | Partner 11 |
|-----------|-----------|------------|------------|
| ![P8](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent8.gif) | ![P9](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent9.gif) | ![P10](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent10.gif) | ![P11](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent11.gif) |

| Partner 12 | Partner 13 | Partner 14 | Partner 15 |
|------------|------------|------------|------------|
| ![P12](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent12.gif) | ![P13](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent13.gif) | ![P14](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent14.gif) | ![P15](Results/10M/IAD/forced_coordination/visualizations/forced_coordination_blue_riayn_green_spagent15.gif) |


These visualizations illustrate how different partners evolve **distinct skill patterns** over time while maintaining dominant skills, highlighting **human-AI coordination dynamics**.

  


### Installation
* Create a new environment.
```
conda create -n hipt python=3.10
conda activate hipt
```
* Setup Overcooked AI environement. This repo uses an older commit of the [Overcooked AI](https://github.com/HumanCompatibleAI/overcooked_ai) repo. Make sure you are pulling from the correct version. 

```
git clone https://github.com/HumanCompatibleAI/overcooked_ai.git
cd overcooked_ai
git checkout 16f9428d99d9002be6611f3bab48f1bfe5c74c32
```

* Install dependencies.
```
./install.sh
```

### Training

* Note: This project uses Weights and Biases for logging. To enable logging, create a free account at [Weights and Biases](https://wandb.ai/). Then run ```wandb login``` and enter your API key. If you would like to disable tracking, set ```track=False``` .

To train a population of Self-Play Agents run the following command:
```
python main.py model=population layout={layout_name}
```

To train a IAD/HiPT/FCP agent with an existing SP Population run the following command:
```
python main.py model={hipt/fcp} layout={layout_name} layout.partner_pop_path={path_to_sp_population}
```
where ```layout_name``` is the name of the layout to train on and ```path_to_sp_population``` is the path to the SP population to use.

### Evaluation

To enable evaluation after training an agent/agent population simply set ```eval=True``` at the end of the training command. For example:
```
python main.py model=population eval=True #Plots the crossplay heatmap matrix

python main.py model={hipt/fcp} layout={layout_name} layout.partner_pop_path={path_to_sp_population} eval=True #Evaulates the HiPT/FCP agent on a SP Population and generates gifs of the gameplay.
```
