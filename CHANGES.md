---
noteId: "54778722aaa511ef8f85cdcd7fa2a98d"
tags: []

---

# Changes in the third edition

Below are the changes in the book between the second (2019) and the third edition (2022). For the changes between the first (2017) and the second edition (2019), please check out [this other page](https://homl.info/changes2).

* All the code was updated to the latest library versions. In particular, this third edition introduces many new additions to Scikit-Learn (e.g., feature name tracking, histogram-based gradient boosting, label propagation, and more). It also introduces the _Keras Tuner_ library for hyperparameter tuning, Hugging Face's _Transformers_ library for natural language processing, and Keras's new preprocessing and data augmentation layers.
* Several vision models were added (ResNeXt, DenseNet, MobileNet, CSPNet, and EfficientNet), as well as guidelines for choosing the right one.
* Chapter 15 on sequence processing using RNNs and CNNs now analyzes the Chicago bus and rail ridership data instead of generated time series, and it introduces the ARMA model and its variants.
* Chapter 16 on natural language processing now builds an English-to-Spanish translation model, first using an encoder–decoder RNN, then using a transformer model. The chapter also covers language models such as Switch Transformers, DistilBERT, T5, and PaLM (with chain-of-thought prompting). In addition, it introduces vision transformers (ViTs) and gives an overview of a few transformer-based visual models, such as data-efficient image transformers (DeiTs), Perceiver, and DINO, as well as a brief overview of some large multimodal models, including CLIP, DALL·E, Flamingo, and GATO.
* Chapter 17 on generative learning now introduces diffusion models, and shows how to implement a denoising diffusion probabilistic model (DDPM) from scratch.
* Chapter 19 migrated from Google Cloud AI Platform to Google Vertex AI, and uses distributed Keras Tuner for large-scale hyperparameter search. The chapter now includes TensorFlow.js code that you can experiment with online. It also introduces additional distributed training techniques, including PipeDream and Pathways.
* To allow for all the new content, some sections have been moved online, including [installation instructions](INSTALL.md), and appendix A (the exercise solutions, now available at the end of each notebook). Other sections have been removed and will be added to this repository within the next few weeks, including kernel principal component analysis (kPCA), mathematical details of Bayesian Gaussian mixtures, TF Agents, and former appendices C (support vector machine math), and E (extra neural net architectures).
