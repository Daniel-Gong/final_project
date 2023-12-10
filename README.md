# Bayesian Telephone: Memory Consolidation and Recall as Generative Processes

Code availability for Bayesian Telephone: Memory Consolidation and Recall as Generative Processes, a paper written for the **Algorithms of the Mind** course at Yale. 

## Key Files

Julia_Notebook.ipynb contains the code used to implement a Hopfield network and variational autoencoder to model consolidation and recall of memory. Julia_Notebook.ipynb also implements an inverse graphics engine using the Gen.jl package. This inverse graphics engine was used to create reconstructed images from true obsrvations (from a datset constructed of Cornell boxes using Mitsuba 3). 

## Deprecated Files

Generative_Model.ipynb contains drafted code to implement a Bayesian system that infers latent parameters associated with images from a Mitsuba 3 constructed dataset and implements generation of reconstructed images built by rendering Mitsuba 3 images with similar latent parameters. This file also contains some code experimenting with building a probabilistic model of "forgetting" which was abandoned. Ideas from this sandbox file were used to implement parts of Julia_Notebook.ipynb. 
