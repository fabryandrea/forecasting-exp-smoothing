# An Introduction to Exponential Smoothing in Python

This meetup will give a general overview of forecasting methodologies, then delve into implementing exponential smoothing in Python.

To use this notebook:
- if you have Anaconda installed:
  install pylab
  
  conda install pylab
  
- if you have Docker installed:
  pull the image from the Docker repository
  
  docker pull jupyter/datascience-notebook
  
  edit the Dockerfile to add pylab and then build it
  
  docker build --rm -t jupyter/datascience-notebook .
  
  then you can make a directory on your local drive and start a container with the notebook on port 8888:
  docker run -p 8888:8888 -v ~/notebooks:/home/jovyan jupyter/datascience-notebook
  

