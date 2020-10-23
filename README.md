# icassp2021-multi-factor-vc
Please visit https://thuhcsi.github.io/icassp2021-multi-factor-vc/
# SPEECH REPRESENTATION LEARNING FOR ROBUST MULTI-FACTOR VOICE CONVERSION


## MAP:Demo

### Sample 1

#### Text
Text: Xu Wen please share your answer with us.

#### Synthesized in Rhythm conversion task

* Source Speech
<audio controls>
  <source src="audios/Demo_1/Source/p225_003_001.wav" />
Your browser does not support the audio element.
</audio>
region img { 
<img src="images/Demo_1/Source/p225_p225_331_source_1.jpg",height=500 , width=300>
} region

* Target Speech
<audio controls>
  <source src="audios/Demo_1/Source/p225_003_001.wav" />
Your browser does not support the audio element.
</audio>
region img { 
<img src="images/Demo_1/Source/p225_p225_331_source_1.jpg",height=500 , width=300>
} region


* Baseline approach
<audio controls>
  <source src="audios/Demo_1/Source/p225_003_001.wav" />
Your browser does not support the audio element.
</audio>
region img { 
<img src="images/Demo_1/Source/p225_p225_331_source_1.jpg",height=500 , width=300>
} region


* Proposed approach
<audio controls>
  <source src="audios/Demo_1/Source/p225_003_001.wav" />
Your browser does not support the audio element.
</audio>
region img { 
<img src="images/Demo_1/Source/p225_p225_331_source_1.jpg",height=500 , width=300>
} region



#### Explanation

The baseline approach has word tokenization error around the 3-rd character,
resulting in pause deletion between the 2-nd and the 3-rd characters and improper pause insertion between the 3-rd and 4-th characters,
changing the meaning to `Xu Wen Gen we share your answer`.

The baseline approach also has syllable pronunciation error at the 8-th character,
incorrectly predicting the pronunciation of the character from `yi2` to `yi4`.

The proposed system has synthesized the speech with expected pronunciations and pauses.

### Sample 2

#### Text

Chinese: 用科技推动教育进步是我们的理念。

English Translation: Using technology to push the evolution of education is our concept.

#### Synthesized speech

* Baseline approach
<audio controls>
  <source src="https://github.com/thuhcsi/interspeech2019-tts-samples/raw/master/sample2-baseline.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

* Proposed approach
<audio controls>
  <source src="https://github.com/thuhcsi/interspeech2019-tts-samples/raw/master/sample2-proposed.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

#### Explanation

The baseline system synthesized the speech with expected pronunciations.
However the baseline approach has pause deletion between the 7-nd and the 8-rd characters and improper pause insertion between the 9-rd and 10-th characters,
changing the meaning to `Using technology to push the education. Evolution is our concept`.

The proposed system has synthesized the speech with expected pronunciations and pauses.
