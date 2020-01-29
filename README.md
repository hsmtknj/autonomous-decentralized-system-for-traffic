# Autonomous Decentralized System for Traffic

## Introduction

This project shows a simulation of "an autonomous decentralized system for trafiic".

In a designated area, multi-agent moves freely while avoiding a collition.

Each agent optimizes their behavior and upload their status and next actions and so on to a cloud which is like a data center.

That cloud collects agent's information and distributes it to all agents, which enable all agents to share information.

Conditions of this simulation are shown below.

TODO: implement demo animation


## Simulation Conditions

### Environment
- There is a grid map where each section is sepalated by road.
    - The size of map is 50 x 50.
    - The size of one section is 10 x 10.
    - The map has 4 x 4 intersectio.
- There are multi-agent.
    - Each agent can move to next in one step.
    - Each agent can go forward, turn left or turn right radomly in intersections.
- There is a cloud.
    - The cloud collects and distribe the following information of all agent in every step.
        - current position
        - traveling derection

TODO: update following rules
### Rules (Behavior)
- 
- 
