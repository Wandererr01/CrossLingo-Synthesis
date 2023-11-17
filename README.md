# CrossLingo-Synthesis
Seamlessly translating text across diverse scripts

## Introduction 
The problem statement given was a cross-coding translation task.
## What is cross-coding translation / text generation ?
### Cross coding translation that contain more than one script / language example...
Statement: I had about a 30 minute demo just using this new headset<br>
Output required: मझे सिर्फ ३० **minute** का **demo** मिला था इस नये **headset** का इस्तेमाल करने के<br>
लिए
### Complete cross-coding
There is another kind of cross coding -
Statement: I had about a 30 minute demo just using this new headset<br>
Output: Mujhe sirf 30 minut ka demo mila tha us naye headset ka istemal karne ke liye<be>
(The script is written in eenglish alphabets while keeping the pronunciation same)

## Explorer
`requirements.txt` python dependencies<br>
`english_to_hinglish_tokenizer` directory to the trained tokenizer<br>
`my-t5-hinglish-translator` directory to the translator<br>
`train_full_crosscoded.ipynb` script to train fully cross-coded english to hinglish translator<br>
`full_cross_coding_translation.ipynb` script to translate english to fully cross coded hinglish<br>
`train-cross-coding.ipynb` kaggle sheet <br>


## Usage
```shell
git clone https://github.com/Wandererr01/CrossLingo-Synthesis.git
cd CrossCodedText
pip install -r requirements.txt
```

###  To train locally -
Use `train_full_crosscoded.ipynb` to train the algorithm for fully cross-coding translation model (tokenizer and translator)

## Kaggle Sheet 
Kaggle [Kaggle](https://www.kaggle.com/code/wandererr01/train-cross-coding)
