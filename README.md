# UTDNLP
Project Extension for Research Internship @ UTD

This project was an extension of my summer research internship at UT Dallas.

NLU tasks have traditionally utilized Convolutional Neural Networks (CNN) or BERT Transformers. In this project, I implemented the BART transformer to improve accuracy in summarizing text. 

BART is a denoising autoencoder for pretraining sequence-to-sequence models. It is trained by (1) corrupting text with an arbitrary noising function, and (2) learning a model to reconstruct the original text. It uses a standard Transformer-based neural machine translation architecture. While BERT was trained by using a simple token masking technique, BART empowers the BERT encoder by using more challenging kinds of masking mechanisms in its pre-training. For tasks involving natural language understanding (NLU), like question answering and text summarization, our model must read the text in its entirety and comprehend each token in relation to the ones that came before and after it. First, it is trained from a large corpus, and the further trained for text summarization.
