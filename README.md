# Predict BTC rate base on Time series challenge from Data Worshop


# Purpose
Use the knowledge from 5 DW challenge in order to predict BTC exchange value.

# Content
Created container has already installed fbprophet needed for challenge 5.

The downgrade of pystan has been applied

```conda install -c plotly plotly==3.10.0 -y```

# Prereqisits
You need to install docker in order to use this repository

https://www.docker.com/products/docker-desktop

# Data
Data are downloaded from coinbase with usage of script from https://gitlab.com/klemenko/bitcoin
For:
- 5 minutes
- 15 minutes
- 1h
- 6h
- 1 day

# How to run
After downloading:
1. Go to the repository
2. Execute command: `docker-compose up`
3. Check the output:
```conda_1  | [C 06:49:20.946 NotebookApp]
conda_1  |
conda_1  |     To access the notebook, open this file in a browser:
conda_1  |         file:///root/.local/share/jupyter/runtime/nbserver-6-open.html
conda_1  |     Or copy and paste one of these URLs:
conda_1  |         http://0229b6271693:1111/?token=e3c9a12b757da01127e1c11018f543924a484b3a6ee519e1
conda_1  |      or http://127.0.0.1:1111/?token=e3c9a12b757da01127e1c11018f543924a484b3a6ee519e1
```
and navigate with your browser to the endpoint form the output example:

`http://127.0.0.1:1111/?token=e3c9a12b757da01127e1c11018f543924a484b3a6ee519e1`

All your notebooks will be under the `notebooks` subdirectory.
# Resources
https://dataworkshop.eu/challenge

https://www.docker.com/products/docker-desktop

https://facebook.github.io/prophet/docs/quick_start.html

https://gitlab.com/klemenko/bitcoin