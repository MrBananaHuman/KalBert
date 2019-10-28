# KalBert
Korean ALBERT (A Lite BERT for Self-supervised Learning of Language Representations) language model

Training based on albert_zh (https://github.com/brightmart/albert_zh)

512 sequences, Large KalBert:
https://drive.google.com/drive/folders/1a_yZIidugit3TxF__f8LSRPc8gfO2CV-?usp=sharing

* Training data: ~6GB
  - Korean Wiki
  - Kaist Book corpus
  - Saejong corpus
  
* Morph tokenizing without tag + BPE
  - (e.g. 이순신은 조선 중기의 무신이다. -> 이순신 은 조선 중기 의 무신 이 다 .)
  
* Training steps: 191,000

* KorQuAD v 1.0 Dev set
  - f1: 90.01, em: 81.26

