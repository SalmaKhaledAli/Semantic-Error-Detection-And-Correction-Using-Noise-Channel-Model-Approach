# Semantic-Error-Detection-And-Correction-Using-Noise-Channel-Model-Approach

This model is able to detect and correct arabic words depends on the context using Noisy channel model. the dataset used in this project is QALB. 

based on the Noisy channel model we generate for every sentence a group of sentence candidates. these candidates are generated by applying on the orignal sentence up to 2 edit minimum distance. then we calculated the channel model for each candidate using bigram function. then we started to calculate the word correction for every word in the candidate sentence this function return the probability of how correct this word is. then we calculated the noisy channel model equation p(x|w)p(w) and return the maximum probability from the generated candidates. this model can detect the semantic and syntax errors in the sentences but there is a limitation for the big number sequence of words.
