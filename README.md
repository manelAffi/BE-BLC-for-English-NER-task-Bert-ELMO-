# BE-BLC-for-English-NER-task-Bert-ELMO-
This is a BERT-ELMO based deep neural netwok model for English named entity recognition task .
# Requirements
AllenNLP library
# dataset
https://deepai.org/dataset/conll-2003-english
# Run
allennlp train "path To the Json File" -s "path Where To save the outputted model"
# Test
allennlp evaluate  "path to the outputted model (tar.gz)"  "path to the test data"
# To cite us
@article{affi2021blc,
  title={BE-BLC: BERT-ELMO-Based Deep Neural Network Architecture for English Named Entity Recognition Task},
  author={Affi, Manel and Latiri, Chiraz},
  journal={Procedia Computer Science},
  volume={192},
  pages={168--181},
  year={2021},
  publisher={Elsevier}
}
