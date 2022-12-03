# xbmu_amdo31
This is the official repository of the XBMU-AMDO31 dataset. 
Speech database of Tibetan Amdo dialect for speech recognition.

XBMU-AMDO31 version: 1.0.0 (12/03/2022)

## Download
1. Method 1: Please download from [openslr](http://www.openslr.org/133/)
2. Method 2: Please download from [huggingface](https://huggingface.co/datasets/syzym/xbmu_amdo31)

## Leaderboard

| **Contributor**| **Toolkit**       | **Train Recipe**     | **Modeling unit** | **Inference**     |**Dev/Test WER**    |
|:---------------|:------------------|:------------------|:------------------|:------------------|:------------------:|
||||| 
| <em>Baseline</em>    | [Kaldi](https://github.com/kaldi-asr/kaldi) | NNET3 | Syllables| <u>model</u> <u>example</u> | 17.71 / 15.29 |
| <em>Baseline</em>    | [Espnet](https://github.com/espnet/espnet) | [Conformer/Transformer-AED] | Syllables | <u>model</u> <u>example</u> | 14.80 / 13.80 |
| <em>Baseline</em>    | [Espnet](https://github.com/espnet/espnet) | [Conformer/Transformer-AED] | Alphabet  | <u>model</u> <u>example</u> | 18.00 / 16.30 |
| <em>Baseline</em>    | [Espnet](https://github.com/espnet/espnet) | [Conformer/Transformer-AED] | BPE500    | <u>model</u> <u>example</u> | 10.60 / 10.10 |
| <em>Baseline</em>    | [Espnet](https://github.com/espnet/espnet) | [HUBERT + Conformer/Transformer-AED] | BPE500    | <u>model</u> <u>example</u> | 9.80 / 9.10 |
| <em>Baseline</em>    | [Espnet](https://github.com/espnet/espnet) | [Conformer/Transformer-AED + wenetspeech pre-trained model] | BPE500    | <u>model</u> <u>example</u> | 9.30 / 8.90 |
| <em>Baseline</em>    | [Icefall](https://github.com/k2-fsa/icefall) |  [Pruned Stateless5](https://github.com/k2-fsa/icefall/pull/706) | BPE500 | [model](https://huggingface.co/syzym/icefall-asr-xbmu-amdo31-pruned-transducer-stateless5-2022-11-29) | 11.24 / 10.57 |
| <em>Baseline</em>    | [Icefall](https://github.com/k2-fsa/icefall) |  [Pruned Stateless7](https://github.com/k2-fsa/icefall/pull/706) | BPE500 | [model](https://huggingface.co/syzym/icefall-asr-xbmu-amdo31-pruned-transducer-stateless7-2022-12-02) | * / 9.70 |
