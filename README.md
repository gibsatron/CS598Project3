# CS598Project
This project attempts to reproduce the results from "Back to the basics with inclusion of clinical domain
knowledge - A simple, scalable and effective model of
Alzheimer’s Disease classification"

This includes the preprocessing pipeline, TDA topological feature analysis, 3D CNN trained on MRI image volume and TDA as well as extensions with CNNs trained only on image volume or TDA or each TDA dimnension

The results are poor due to memory constraints on the host as well as GPU as well as the variability in the preprocessing pipeline as Clinica and fmriprep were unable to use and TDA was inable to capture many meaningful features. 
