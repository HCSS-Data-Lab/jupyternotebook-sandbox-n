# About Jupyternotebook Sandbox-m   
[![Publish hcss jupyter docker image](https://github.com/HCSS-Data-Lab/jupyternotebook-sandbox-m/actions/workflows/action.yml/badge.svg?branch=master)](https://github.com/HCSS-Data-Lab/jupyternotebook-sandbox-m/actions/workflows/action.yml)  

HCSS Jupyternotebook Definition for N. 

## Frameworks used
- Jupyter  
- scipy  

# Docker image details 
## Jupyter notebook
Base image: jupyter/scipy-notebook:33add21fab64         # special version for jupyterhub (https://github.com/jupyter/docker-stacks)  
Exposed ports: 8888  
Additional installed resources:  
- Troubleshooting: vim, net-tools, dos2unix  
- Data science: sklearn, pandas, seaborn
