# RoboCup2D-data

The aim of this repository is to provide soccer datasets (including tracking data and event data) generated by the RoboCup Soccer Simulator.

An overview of this project can be found in [the slide](./SoccerGameplayDataGeneration.pdf).


## Provided Data

- [Round Robin games by 13 teams from RoboCup2021](http://alab.ise.ous.ac.jp/robocupdata/rc2021-roundrobin/)
  - [RoboCup2021 Information Board](https://docs.google.com/document/d/18FbbsghP-4K5P_G2hUpANdibdUzqepqLAmdL2jZ_FMM/edit?usp=sharing)
- [Round Robin games by 10 teams from RoboCup2024](http://alab.ise.ous.ac.jp/robocupdata/rc2024-roundrobin/)
  - [RoboCup2024 Information Board](https://docs.google.com/document/d/1LZI8iDtDIxBufzyQpeKdrYMLOe_qbWMZ3VlWmxIGV-Y/edit?usp=sharing)
- ...

## Data Generation Tools

- [rcssserver](https://github.com/rcsoccersim/rcssserver) : The RoboCup Soccer Simulator
- [rcgamestats](https://github.com/hidehisaakiyama/rcgamestats) : Distributed execution system
- [rcg2data](https://github.com/hidehisaakiyama/rcg2data) : Convert RoboCup logs into CSV and extract event data.

## Reference

If you use our data, please refer the following paper:

- Hidehisa Akiyama, Tomoharu Nakashima, Soccer Gameplay Data Generation: Toward Integrating Computer Simulations and Human Sports Analysis, [RoboCup International Symposium 2024]((https://2024.robocup.org/research/symposium/)) (2024) [Preprint](./RoboCupSymposium2024_paper.pdf)
