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

<img src="images/Demo_1/Proposed/R/test_withOUT_C.jpg",height=300 , width=300>


* Target Speech
<audio controls>
  <source src="audios/Demo_1/Source/p225_003_001.wav" />
Your browser does not support the audio element.
</audio>


![Target_1](https://github.com/thuhcsi/icassp2021-multi-factor-vc/blob/main/images/Demo_1/Baseline/P%2BR%2BT/test_withOUT_C.jpg)


* Baseline approach
<audio controls>
  <source src="audios/Demo_1/Source/p225_003_001.wav" />
Your browser does not support the audio element.
</audio>
<div>

![image](https://github.com/thuhcsi/icassp2021-multi-factor-vc/blob/main/images/Demo_1/Baseline/P%2BR%2BT/test_withOUT_C.jpg)


* Proposed approach
<audio controls>
  <source src="audios/Demo_1/Source/p225_003_001.wav" />
Your browser does not support the audio element.
</audio>
<div>

![image](https://github.com/thuhcsi/icassp2021-multi-factor-vc/blob/main/images/Demo_1/Baseline/P%2BR%2BT/test_withOUT_C.jpg)


#### Explanation

...tbc


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
