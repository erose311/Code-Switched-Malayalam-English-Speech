# Code-Switched-Malayalam-English-Speech Corpus

The MLENSPEECH dataset was created as part of my Master's dissertation project "ASR system for Malayalam-English Code-Switched Speech" in July 2022. 
Please refer to [MLENSPEECH_chapter](https://drive.google.com/file/d/1Y2Y5Bz1bFhXdM4uCvVSsUphk83jF_IUB/view?usp=sharing) for detailed explanation of the data collection, processing, transcription and annotation scheme, and statistics of the dataset.

MLENSPEECH contains audio recordings that were scrapped from publicly available YouTube videos and then manually split into utterances. The dataset is designed for training and evaluating ASR models for code-switching, which is the practice of alternating between languages or dialects within a single utterance.

## Data Format

The dataset comprises of mono audio files in WAV format, at a sample rate of 16kHz. The file transcriptions.txt contains the transcription (Malayalam words in Malayalam script and English words in Latin script) corresponding to each utterance is of the following format: _&lt;utterance\_id&gt; &lt;transcription&gt;_ where, *&lt;utterance\_id&gt;* is of the format _&lt;spk\_id&gt;\_AudioSample&lt;index&gt;_ where, _<spk\_id>_ is the speaker ID, _&lt;index&gt;_ is the n<sup>th</sup> utterance for a specific speaker and _<transcription>_ is the associated transcription. 
 Eg: 5\_AudioSample017 is utterance ID of the 17<sup>th</sup> utterance of Speaker 5.
 
All audio files are named by utterance ID.

## Data Statistics
- Number of speakers: 5
- Total number of utterances: 2883
- Duration of audio: 3 hours 20 minutes (200 minutes)
- Number of code-switched utterances: 2883 (100% of total)
- Average Speaking Rate: 154.28
  
| Speaker | Gender | Domain | # Utterances | Speaking Rate | Duration (minutes) |
| :-------- | :-------- | :-------- | :-------- | :-------- | :-------- |
| Spk1 | Male | Finance | 566 | 113.48 | 45.7 |
| Spk2 | Female | General | 746 | 151.14 | 45.04 | 
| Spk3 | Male | Finance | 544 | 130.14 | 45.14 |
| Spk4 | Male | General | 572 | 162.85 | 31.00 |
| Spk5 | Female | Finance | 455 | 140.72 | 0.43 | 32.83 |

For more detailed statistics, please refer Section 3.4 in [MLENSPEECH_chapter](https://drive.google.com/file/d/1Y2Y5Bz1bFhXdM4uCvVSsUphk83jF_IUB/view?usp=sharing)

## License
This dataset is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.
