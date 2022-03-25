# AS_AI_2022

#### Files di esempio utilizzati nel corso 2022 (03/02 e 24/03)


- *BERT_Classification-SentTwit* rete di tipo Bert addestrata su tweet per sentiment analisys presi da qui: http://help.sentiment140.com/for-students è il file contenente l'addestramento in esecuzione al termine della lezione
- *TweetSentAnalisys* rete ripresa dal precedente *text_classifiers_comp* (vedi sotto) con lo stesso dataset di *BERT_Classification-SentTwit* ma con un numero maggiore di esempi
- *text_classifiers_comp* (realizzato nella lezione del 3 febbraio) Comparazione di diverse tipologie di reti per la classificazione in 7 categorie di testi scaricati da wikipedia
- *CharactersEmbedding* esempio di addestramento ed utilizzo di embedding di caratteri per la generazione automatica di testi
- *BERT_Classification* Rete di tipo BERT addestrata sul dataset https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz, è il file da cui siamo partiti per realizzare *BERT_Classification-SentTwit* 
- *BERTinSentimentClassification-not_trainable* come sopra ma con parte BERT impostata con trainable=False
- *BERT_sentAn* Variazione del file precedente in cui si è provato ad aumentare gli strati aggiunti a BERT ed a tenere la parte BERT non addestrabile, il risultato è però peggiore di precedenti. Una prova ulteriore che si potrebbe fare è fare questa aggiunta tenendo non addestrabile la parte BERT, ma utilizzando come base il modello precedentemente addestrato in *BERT_Classification*
- *fine_tune_bert* Esempio di utilizzo di rete di tipo BERT preso dal sito di Tensorflow: https://www.tensorflow.org/text/tutorials/fine_tune_bert
- *data_collect_preprocessing* e *data_collect_preprocessing1* (lezione del 3 febbraio) raccolta testi da Wikipedia e preprocessing
- *text_classifiers_tuner* (lezione del 3 febbraio) Tuning automatico dei metaparametri, partendo dagli stessi dati e da una struttura di base simile a quelle utilizzate in *text_classifiers_comp*
- *embedding*, *embedding2* e *embeddings_material* (lezione del 3 febbraio) esplorazione e misure del word embedding 
- *word_embeddings* Illustrazione del word embeddings preso da https://www.tensorflow.org/text/guide/word_embeddings



---
Link Utili:

https://arxiv.org/pdf/1508.02096.pdf

https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html

https://colab.research.google.com/github/tensorflow/text/blob/master/docs/tutorials/fine_tune_bert.ipynb#scrollTo=yic2y7_o-BCC

https://realpython.com/python-speech-recognition/


dataset utilizzato oggi:
http://help.sentiment140.com/for-students



---
email:
leandro.paolo.de.persiis@gmail.com
