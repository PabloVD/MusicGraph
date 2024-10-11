# XarxaMusical

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Description

Given a list of bands belonging to a musical movement, create a graph of memberships and collaborations using [Networkx](https://networkx.org/) and [ipysigma](https://github.com/medialab/ipysigma).

Data is stored in folder `data` and are text files with several rows, wach of them with the following format: `band;members;collaborations`. `members` and `collaborations` are lists of musicians or bands separated by commas `,`. `collaborations` includes collaborations between bands and musicians from other projects, and also between bands in songs or split albums.

Updated to create interactive graphs with [ipysigma](https://github.com/medialab/ipysigma).

---

## Examples

Here are some examples of musical movements, showing the relations between bands. Most of info has been extracted from [Wikipedia](https://en.wikipedia.org), [Discogs](https://www.discogs.com/), [Rate Your Music](https://rateyourmusic.com/) and other sources. In the images below, purple nodes correspond to bands/artits while orange nodes to musicians, orange lines indicate member of band and purple lines indicate collaborations.

- [Jazz](https://en.wikipedia.org/wiki/Jazz) scene

![Jazz](examples/jazz.png "Jazz")

- [Neofolk](https://en.wikipedia.org/wiki/Neofolk) bands

![Neofolk bands](examples/neofolk.png "Neofolk")

- [Valencian](https://en.wikipedia.org/wiki/Valencian_Community) musical scene

![Valencian musical scene](examples/valencian.png "Valencian")

- [Basque Radical Rock](https://en.wikipedia.org/wiki/Basque_Radical_Rock)

![Basque Radical Rock](examples/rock_radical_vasco.png "Basque Radical Rock")

- [Norwegian Black Metal](https://en.wikipedia.org/wiki/Early_Norwegian_black_metal_scene)

![Norwegian Black Metal](examples/norwegian_black_metal.png "Norwegian Black Metal")

- Collaboration network of [Extremoduro](https://en.wikipedia.org/wiki/Extremoduro) and related bands

![Extremoduro](examples/extremoduro.png "Extremoduro")

---

## To do

- [x] Improve graph visualization, using `ipysigma`
- [ ] Reorganize as a class
- [ ] Create web application or IPyWidget
- [ ] Write web scrapping tool to parse data from Rate Your Music and/or Wikipedia.

## Contact

If you want to include new data or have comments or suggestions, Feel free to create a pull request or contact me at <pablo.villanueva.domingo@gmail.com>.