# Steps that I followed for setting up Adaptive Sampling on my MacBook Pro
1. Downloading MinKNOW offline version (This version is for performing nanopore sequecing of field expeditions)
2. Installation of [BOSS-RUNS](https://github.com/goldman-gp-ebi/BOSS-RUNS) using mamba (I used homebrew)
```
brew install --cask miniforge
# Important for initialization of conda/mamba
conda init "$(basename "${SHELL}")"
eval "$(mamba shell hook --shell zsh)"
```
3. Installation of [ReadFish](https://github.com/LooseLab/readfish/tree/main?tab=readme-ov-file#testing) using the yaml file and conda.
```
conda env create -f readfish_env.yml
conda activate readfish
```
4. Installation of [dorado basecall server](https://nanoporetech.com/software/other/dorado-basecall-server) version == 7.9.8

