# Project: Emerging Technologies 2021
Student name: Alex Burns <br />
Student ID: G00375766

## What is this repository?

This repository is my submission for the assessment in the Emerging Technologies module for 4th Year Software Development 2021/2022 at GMIT.
In this repository you will find the following:

  * **datasets** - This directory holds the `winequality-red.csv` dataset that is used in `scikit-learn.ipynb`.
  * **Dockerfile|docker-compose.yaml|.dockerignore** - These Docker files allow you to create a Docker container and image that will run this repositories Jupyter notebooks.
  * **scikit-learn.ipynb** - This Jupyter notbook contains an overview of the scikit-learn Python library, and demonstrations of scikit-learn's *Decision Tree Classification*, *Random Forest Classification*, and *Support Vector Machine Classification*.

## Quick Links

Static version of scikit-learn notebook:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/Jharopa/emerging-tech-project/blob/main/scikit-learn.ipynb)

Dynamic version of scikit-learn notebook:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jharopa/emerging-tech-project/HEAD?filepath=scikit-learn.ipynb) 

## Running on local machine

### Prerequisites

  * Install Git - [here](https://git-scm.com/downloads)
  * Instal Docker - [here](https://docs.docker.com/get-docker/)

### Instructions

  * In a terminal, clone this repository to your local machine using `git clone https://github.com/Jharopa/emerging-tech-project.git` or `git clone git@github.com:Jharopa/emerging-tech-project.git`.
  * Navigate into the cloned repositoriy's directory and run the command `docker-compose up`.
  * After this has finished running you can copy the URL produced by this command `http://127.0.0.1:8888/lab?token=<Some Token>`, and paste it into your web browser to access Jupyter lab and this repositories notebooks.
