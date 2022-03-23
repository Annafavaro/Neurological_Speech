# Neurological_Speech

The Neurological_Speech Repository is a public open-source implementation that supports the extraction of cognitive, linguistic and acoustic features from the speech signal.
 
## Feature Extraction 

1) ## Cognitive Features
⋅⋅⋅For the extraction of part of the the cognitive features we are using a pre-trained conformer CTC model for the librispeech dataset built on top of icefall (https://huggingface.co/csukuangfj/icefall-asr-librispeech-conformer-ctc-jit-bpe-500-2021-11-09). 
2) ## Acoustic Features
* For the extraction of the acoustic features related to pause and speech time we use DigiPsych Prosody Repository (<https://github.com/NeuroLexDiagnostics/DigiPsych_Prosody>).
* For the extraction of the acoustic features concerning F0 and energy contour we use Disvoice Repository (<https://github.com/jcvasquezc/DisVoice/tree/master/prosody>).
2) ## Linguistic Features
* For the extraction of the linguistic features related to Part-of-Speech and Syntactic Complexity we use we used Spacy
Python Library(<https://spacy.io/models>).
* For the extraction of the linguistic features related to Vocabulary Richness we use 
<https://pypi.org/project/lexicalrichness/>. 
