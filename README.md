# Personalised Real Estate Agent Project
---

## Overview
This repository contains a project of building a personal real estate agent
using generative AI for partial fulfilment of the Generative AI Nanodegree
program by the [Udacity](https://www.udacity.com/).

## Requirements
* Install the required Python libraries under the [requirements.txt](./requirements.txt).

## File Description
* `HomeMatch.ipynb` contains all the routines and logics of the personal real estate agent.
* `listings.pkl` contains the Python's pickle object of the saved generated real estate listings.
* `img-search.jpg` is the image used to performs a similarity search based on image embeddings in the listing database.

## Usage
To build new personalisation, do the followings:
1. Install all the required Python libraries
2. Open the `HomeMatch.ipynb` in the Jupyter notebook
3. Import all the necessary Python libraries
4. Fill in the authentications needed for Open AI and HuggingFace APIs
5. Load the listings from the pickle file in the cell under Create Multimodal Embeddings section
6. Run all other proceeding cells and modify the user preferences under the Building User Preference section

## Contribution
* The following is the general guide on how to contribute to this project:
  1. Clone this repository to your local machine
  2. Create an upstream remote and sync your local copy before you branch
  3. Branch from `develop` branch for each piece of work
  4. Do the work
  5. Push to your origin repository
  6. Create a new merge request on the GitLab
* Please adhere to this [Git Branching Model](https://nvie.com/posts/a-successful-git-branching-model/).
* Please adhere to this [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html).

## License
The content of thic package is covered under [the MIT License](./license.txt).

