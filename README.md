# wumpus-world-ai-portfolio


This repository contains my Python/Google Colab implementation for the COA207 Foundations of Artificial Intelligence portfolio.

## Contents

- `F529147_WumpusWorld.ipynb` — the full Wumpus World implementation and test cases.

## How to run

Open the notebook in Google Colab and select:

Runtime → Run all

The notebook requires no additional installations or dependencies.

## Description

The project implements a knowledge-based Wumpus World agent using explicit sets to represent safe cells, possible hazards and known hazards. The agent uses logical rules from percepts such as breeze, stench, vibration and glitter. It also uses Breadth-First Search to plan paths through known safe cells.

The main twist is the addition of a trap. When triggered, the trap causes the Wumpus to move one step towards the agent, forcing the agent to update its assumptions.
