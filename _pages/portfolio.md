---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

### [ImprovNet: Generating Controllable Musical Improvisations with Iterative Corruption Refinement](https://github.com/keshavbhandari/improvnet)
*London, 2025*
Deep learning has enabled remarkable advances in style transfer across various domains, offering new possibilities for creative content generation. However, in the realm of symbolic music, generating controllable and expressive performance-level style transfers for complete musical works remains challenging due to limited datasets, especially for genres such as jazz, and the lack of unified models that can handle multiple music generation tasks. This paper presents ImprovNet, a transformer-based architecture that generates expressive and controllable musical improvisations through a self-supervised corruption-refinement training strategy. ImprovNet unifies multiple capabilities within a single model: it can perform cross-genre and intra-genre improvisations, harmonize melodies with genre-specific styles, and execute short prompt continuation and infilling tasks. The model's iterative generation framework allows users to control the degree of style transfer and structural similarity to the original composition. Objective and subjective evaluations demonstrate ImprovNet's effectiveness in generating musically coherent improvisations while maintaining structural relationships with the original pieces. The model outperforms Anticipatory Music Transformer in short continuation and infilling tasks and successfully achieves recognizable genre conversion, with 79% of participants correctly identifying jazz-style improvisations. Our code and demo page can be found at https://github.com/keshavbhandari/improvnet.

### [Yin-Yang: Developing Motifs With Long-Term Structure And Controllability](https://github.com/keshavbhandari/yinyang)
*London, 2025*
Transformer models have made great strides in generating symbolically represented music with local coherence. However, controlling the development of motifs in a structured way with global form remains an open research area. One of the reasons for this challenge is due to the note-by-note autoregressive generation of such models, which lack the ability to correct themselves after deviations from the motif. In addition, their structural performance on datasets with shorter durations has not been studied in the literature. In this study, we propose Yin-Yang, a framework consisting of a phrase generator, phrase refiner, and phrase selector models for the development of motifs into melodies with long-term structure and controllability. The phrase refiner is trained on a novel corruption-refinement strategy which allows it to produce melodic and rhythmic variations of an original motif at generation time, thereby rectifying deviations of the phrase generator. We also introduce a new objective evaluation metric for quantifying how smoothly the motif manifests itself within the piece. Evaluation results show that our model achieves better performance compared to state-of-the-art transformer models while having the advantage of being controllable and making the generated musical structure semi-interpretable, paving the way for musical analysis. Our code and demo page can be found at https://github.com/keshavbhandari/yinyang.

### [Text2midi: Generating Symbolic Music from Captions](https://github.com/AMAAI-Lab/text2midi)
*London, 2025*
This paper introduces text2midi, an end-to-end model to generate MIDI files from textual descriptions. Leveraging the growing popularity of multimodal generative approaches, text2midi capitalizes on the extensive availability of textual data and the success of large language models (LLMs). Our end-to-end system harnesses the power of LLMs to generate symbolic music in the form of MIDI files. Specifically, we utilize a pretrained LLM encoder to process captions, which then condition an autoregressive transformer decoder to produce MIDI sequences that accurately reflect the provided descriptions. This intuitive and user-friendly method significantly streamlines the music creation process by allowing users to generate music pieces using text prompts. We conduct comprehensive empirical evaluations, incorporating both automated and human studies, that show our model generates MIDI files of high quality that are indeed controllable by text captions that may include music theory terms such as chords, keys, and tempo. We release the code and music samples on our demo page for users to interact with text2midi.

### [ChirpNet - A Neural Bird Sound Synthesis Model](https://keshavbhandari.github.io/portfolio/bird-sound-synthesis.html)
*Evanston, 2022* <br/>
Automated species recognition through Artificial Intelligence (AI) can provide
ecologists and wildlife conservationists the means to detect and monitor
vocalizing avian species of interest. However, AI systems rely on a multitude
of data to learn the inductive biases and to generalize to the vocalizations of
bird species. This is problematic when classifying rare bird species which
have limited presence in naturally occurring audio data. In this project, we
try to address this problem by generating synthetic avian audio samples as
a type of augmentation that can be used in future works to improve the bird
sound classification accuracy.

Click <ins>*[**here**](https://keshavbhandari.github.io/portfolio/bird-sound-synthesis.html)*</ins> to read more about this work and listen to the generated samples.

### [Bird Sound Denoiser](https://keshavbhandari.github.io/portfolio/bird-sound-denoiser/)
*Evanston, 2022* <br/>
In this project, I applied Facebook's Demucs - state-of-the-art audio denoiser to remove
noisy environmental background sounds from a bird sound dataset. These sounds consist of insects
such as crickets, rain, wind, machines, vehicles, etc. which were synthetically added in to a clean
set through a source separation task.

Click <ins>*[**here**](https://keshavbhandari.github.io/portfolio/bird-sound-denoiser/)*</ins> to read more about this work and listen to the generated samples.

### [Audioneme - Detecting Speech Disorder in Children](https://keshavbhandari.github.io/portfolio/child-speech-disorder-detection/)
*Evanston, 2022* <br/>
There has been an increased interest in developing automated methods that quantify speech patterns for 
diagnosing speech disorders in children. In this project, I fine-tuned Facebook's Wav2Vec2 on child speech 
data in conjunction with the utterance transcriptions to automate screening and assessment of speech disorders 
and speech intelligibility in children. The dataset for this project consisted of weakly labeled 
utterances comprising ~15,000 recordings of children with and without speech disorder.

Click <ins>*[**here**](https://keshavbhandari.github.io/portfolio/child-speech-disorder-detection/)*</ins> to read more about this work.


### [Efficient Scaling and Pre-Training of Language Models with Electra and Reformers](https://keshavbhandari.github.io/portfolio/electra-reformer/)
*Evanston, 2021* <br/>
In this paper, we repurpose a highly efficient Reformer encoder architecture to serve as the foundational blocks 
for the Electra pre-training methodology, thereby allowing the network to scale to 8 times the size of its transformer 
counterpart while maintaining the same memory requirements. The subsequent downstream performance of this scaled up architecture 
is at par with the transformer based Electra benchmark, while being pre-trained using only a third of the data.

Click <ins>*[**here**](https://keshavbhandari.github.io/portfolio/electra-reformer/)*</ins> to read more about this work.

### [Augmentations to improve rare bird call classification for a highly imbalanced multi-label soundscape environment](https://keshavbhandari.github.io/portfolio/bird-sound-classification-augmentations/)
*Evanston, 2021* <br/>
In this study, we present a deep learning solution to classify multiple bird vocalizations in a multi-label multi-species soundscape 
environment without a clear distinction between foreground and background species. Specifically, we focus on testing the effectiveness 
of various data augmentation methods to improve the classification of rare bird calls against some of the key challenges typical to a 
soundscape dataset - multiple overlapping bird calls, high environmental noise and high class imbalance.

Click <ins>*[**here**](https://keshavbhandari.github.io/portfolio/bird-sound-classification-augmentations/)*</ins> to read more about this work.

