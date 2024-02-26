by: Samuel Chu, Jonathan Dong, Yiming Hao, Brianda Plascencia

Finalized report will go [here]("adsadda") when it is done. Finalized code will go [here]("sdqdqwqdq") when it is done.

# Introduction

Researchers in the health world are always looking at new ways to develop new drugs to help combat evolving diseases, as an article by Jim O'Neill in 2016 stated that "By 2050, drug-resistant pathogens are expected to be the leading cause of death in the world". A great example that would reinforce this statement would be the emergence of COVID-19 and its variants which have caused the deaths of millions of people around the globe. When taken in consideration with other notable diseases such as swine flu, ebola, HIV, etc, it would ever so emphasize the need to quickly devlop drugs that would help to limit them and their mutations/evolutions.

One avenue that researchers have been looking into has been anitmicrobial peptides (AMPs), chains of amino acids that have displayed proprties useful in fighting pathogens. By being able to identify AMPs presences within these chains, researchers would be able to use them to produce better drugs or antibiotics. However, due to how AMPs are structured, detecting new AMPs are both difficult and costly. 

With the advent of deep learning models, researchers have been looking toward using these as they are capable or identifying AMPs quickly, efficiently, and accurately. In a paper published by Ma et al. titled "Identification of antimicrobial peptides from the human gut microbiome using deep learning", the authors utilized a combination of numerous deep learning models such as a long short-term memory model (LSTM), an attention model, and a bidirectional encoder representations from transformers model (BERT) in order to test their accuracy at identifying AMPs on an existing dataset of AMPs and non-AMPs. Through all the combinations, an ensemble of the LSTM, attention and BERT models performed the best at identifying AMPs and non-AMPs. For our project, we would like to replicate these models and train them on **new** data and see if we can accurately detect new AMP presences. In particular, we would like to test the ensemble model on a dataset called FINRISK in order to see whether we can identify AMP presences within the data collected and correlate it to any possible conditon or disease.

While studies have been done on AMP identification as well as on the FINRISK dataset, none of them have been conducted in the way that we are doing it. The goal of this project is that by providing a fast and efficient solution in identifying AMPs, we can use these results to either treat or prevent these diseases within patients and help quicken their recovery process 

# Data

Our dataset that we would use for this project is called FINRISK. It is a study done by the Finnish government in which the dataset consists of the DNA samples from Finnish participants and their health outcomes.

Our models take in amino acid data as input, which means that we had to first convert the DNA data within the dataset to the appropriate value. A script was written such that it would take in the DNA inputs and return its 6 frame translation.

[Will include images of the data and possibly other things to talk about]

# Methods

Our model consists of an ensemble of deep learning models. They consist of the LSTM model, the attention model and the BERT model. 

After we obtained the outputs from the model, we performed statistical tests in order to see if there was a correlation between detecting AMP presence and a person actually having a certain health condition or disease. This is done to ensure that the model produced relevant information regarding a person's health.

[Will include more details]

# Results

Results will be put here when we have them and get a better look at them.

# Discussion

[Interpreting these results will go here]

Through this project we hope that our methods and results were able to acheive the intended results. By doing so, we would have an efficient solution in regards to being able to identify AMPs.

[Possible explanation of things to work on in the future or to improve on]
