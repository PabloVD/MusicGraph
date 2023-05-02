# XarxaMusical

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Alt text](https://img.shields.io/pypi/pyversions/python-binance.svg)

---

## Description

Given a list of bands belonging to a musical movement, create a graph of memberships and collaborations using [Networkx](https://networkx.org/).

Data is stored in folder `data` and are text files with several rows, wach of them with the following format: `band;members;collaborations`. `members` and `collaborations` are lists of musicians or bands separated by commas `,`. z`collaborations` includes collaborations between bands and musicians from other projects, and also between bands in songs or split albums.

---

## Examples

Here are some examples of musical movements, showing the relations between bands.

- [Neofolk bands](https://en.wikipedia.org/wiki/Neofolk)

![Neofolk bands](examples/neofolk_graph.png "Neofolk")

- [Valencian](https://en.wikipedia.org/wiki/Valencian_Community) musical scene

![Valencian musical scene](examples/valencian_graph.png "Valencian")

- [Basque Radical Rock](https://en.wikipedia.org/wiki/Basque_Radical_Rock)

![Basque Radical Rock](examples/rock_radical_vasco_graph.png "Basque Radical Rock")

---

## To do

- Improve graph visualization
- Add legend
- Add more musical movements
