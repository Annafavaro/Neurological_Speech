# Neurological_Speech

The Neurological_Speech Repository is a public open-source implementation that supports the extraction of cognitive, linguistic and acoustic features from speech recordings. This project has the aim of designing, extracting and analyzing speech and language production of subjects with different neurological disorders. 
In this repository we report the code that support the **feature extraction** and that for the **statistical analysis** that we perform to evaluate the significance of the features between experimental groups.
 
## Feature Extraction 

1) ## Cognitive Features
⋅⋅⋅For the extraction of part of the the cognitive features we use a pre-trained conformer CTC model for the librispeech dataset built on top of icefall (https://huggingface.co/csukuangfj/icefall-asr-librispeech-conformer-ctc-jit-bpe-500-2021-11-09). 

2) ## Acoustic Features
* For the extraction of the acoustic features related to pause and speech time we use DigiPsych Prosody Repository (<https://github.com/NeuroLexDiagnostics/DigiPsych_Prosody>).
* For the extraction of the acoustic features related F0 and energy contour we use Disvoice Repository (<https://github.com/jcvasquezc/DisVoice/tree/master/prosody>).


3) ## Linguistic Features
* For the extraction of the linguistic features related to Part-of-Speech and Syntactic Complexity we use Spacy Python Library(<https://spacy.io/models>).
* For the extraction of the linguistic features related to Vocabulary Richness we use <https://pypi.org/project/lexicalrichness/>. 

## Feature Analysis 

We report the pipeline for the statistical analysis that is meant to asses the significance of the features between experimental groups. 
