# OutdoorGymAnalytics

This repository aims to analyze the Helsinki Outdoor Gym data collected by sensors.
The challenges solved are centered around correlating the weather and impact of it on the usage of the data.

- To understand the challenges in detail go though the docs in /src/docs
- Input datasets are organized in src/dataset
- Solutions are placed in /src/notebooks
- Tests can be added under /src/tests
  
Tip:
Its easier to work on this repo in a notebook based IDE.

#Requirements:
See requirements.txt

# Development environment:
1. Install Anaconda
2. Create vitual environment
```
conda create --name dev_env --file requirements.txt
activate dev_env
cd src/dataset
jupyter notebook
```
3. You can execute the notebook in browser