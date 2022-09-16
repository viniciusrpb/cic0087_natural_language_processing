# CIC0269 - Processamento de Linguagem Natural (Natural Language Processing)

Códigos-fontes (Notebooks Python) e recursos de apoio para a disciplina **CIC0269 - Processamento de Linguagem Natural (Natural Language Processing)**, do Departamento de Ciência da Computação da Universidade de Brasília. 

## Autores

Prof. Dr. Vinícius Ruela Pereira Borges

[Matheus Stauffer Viana de Oliveira](https://github.com/mstauffer)

## Sumário

1. Introdução ao Processamento de Linguagem Natural

2. Princípios de Linguística

3. [Expressões Regulares](lectures/cap03_regex.ipynb)

   3.1. Teste sua RegEx (ao vivo) aqui: [RegExPal](https://www.regexpal.com/)

4. Pré-processamento de Textos

   4.1. [Pré-processamento de Textos](lectures/cap04_text_preprocessing.ipynb)
   
   4.2. [LIWC em Língua Portuguesa](resources/LIWC2007_Portugues_win.dic)
   
   4.3. [Aplicação: Part-of-Speech (PoS) Tagging utilizando Dicionários](lectures/pos_tagging.ipynb)

5. Extração de Características de Textos

   5.1. [Bag-of-Words & TF-IDF](lectures/cap05_1_extracao_caracteristicas.ipynb)

6. Similaridade entre Textos

   6.1. Edit Distance <!--[Edit Distance](lectures/cap06_1_edit_distance.ipynb)-->

   6.2. [Similaridade Cosseno](lectures/cap06_2_cosine_similarity.ipynb)
   
   6.3. [Aplicação: Recuperação de Textos Baseada em Conteúdo (Text Retrieval)](lectures/information_retrieval_reuters.ipynb)

7. Modelos de Linguagem Probabilísticos

   7.1. [Modelos de Linguagem Unigrama and Bigrama](lectures/cap07_1_probabilistic_language_models.ipynb)
   
8. Classificação de Textos

   8.1. Regressão Logística <!-- [](lectures/cap08_1_regressao_logistica.ipynb) -->
   
   8.2. [Métricas de Avaliação de Desempenho de Classificação](lectures/cap08_2_metricas_avaliacao_desempenho.ipynb)

   8.3. [Estratégias de Amostragem](lectures/cap08_3_estrategias_amostragem.ipynb)
   

9. Redes Neurais Artificiais

   9.1. [Perceptron Simples](lectures/cap09_1_perceptron_simples.ipynb)
   
   9.2. [Multilayer Perceptron com Backpropagation (XOR)](lectures/cap09_2_multilayer_perceptron_backpropagation.ipynb)
   
   9.3. [Multilayer Perceptron via Keras (XOR)](lectures/cap09_3_multilayer_perceptron_keras.ipynb)
   
   9.4. [Aplicação: Classificação de Polaridade em Tweets com Multilayer Perceptron (Keras)](lectures/cap09_4_sentiment_analysis_dnn.ipynb)


10. Construção e Anotação de Corpos de Texto
 
    10.1. [Planejando um Processo de Anotação na Ferramenta TagTog](lectures/cap10_1_processo_anotacao.ipynb)
    
    10.2. [Avaliação de Qualidade: Métricas de Concordância](lectures/cap10_2_metricas_concordancia.ipynb)


11. Redes Neurais Convolucionais
 
    11.1. [Princípios Básicos de Convolução](lectures/cap11_1_basics_convolution.ipynb)
 
    11.2. [Implementando uma AlexNet para Classificação de Imagens de Documentos](lectures/cap11_2_cnn_alexnet.ipynb)
    
    11.3. [Transferência de Aprendizado em uma ResNet para Classificação de Imagens de Documentos](lectures/cap11_3_transfer_learning.ipynb)
    
    11.4. [Redes Neurais Convolucionais em Textos](lectures/cap11_4_cnn_text.ipynb)



12. Redes Neurais Recorrentes
 
    12.1. [Princípios de Redes Neurais Recorrentes](lectures/cap12_1_rnn.ipynb)

    12.2. [Modelos de Linguagem Baseados em RNNs](lectures/cap12_2_lang_models_rnn.ipynb)
    
    12.3. [Aplicação 1: Inferência de Linguagem Natural](lectures/natural_language_inference.ipynb)
    
    12.4. [Aplicação 2: Reconhecimento de Entidades Nomeadas](lectures/named_entity_recognition.ipynb)
    
    12.5. (Extra) Universal Language Modeling Fine-Tuning (ULMFiT)
    

13. Word Embeddings

    13.1. [Princípios de Word Embeddings utilizando word2vec](lectures/cap13_1_embeddings_principles.ipynb)

    13.2. [Aprendizado por Transferência via word2vec](lectures/cap13_2_embeddings_word2vec.ipynb)
          
    ** [word2vec Pre-trained Embeddings on Google News](https://drive.google.com/file/d/1gwXGu6xVPe4-aosMU3udK-fn_COfAKkp/view?usp=sharing) (arquivo grande! Para não estourar a RAM, utilize limite o tamanho do vocabulário)
          
    13.3. [Aprendizado por Transferência via GloVe](lectures/cap13_3_embeddings_glove.ipynb)
          
    ** [GloVe Pre-trained Embeddings](https://nlp.stanford.edu/projects/glove/) (para não estourar a RAM, utilize o embedding *Wikipedia 2014 + Gigaword 5*)

<!--- 
    12.1. [Princípios de Redes Neurais Recorrentes](lectures/cap12_1_rnn.ipynb)
    
    11.2. [Long Short Term Memory (LSTM)](lectures/cap05_2_lstm32.ipynb)
   
    11.3. [Aplicação 1:](lectures/cap05_2_lstm32.ipynb) Modelo de Linguagem
   
    11.4. [Aplicação 2:](lectures/cap05_2_lstm32.ipynb) Classificação de Textos
   
    11.5. [Aplicação 3:](lectures/cap05_2_lstm32.ipynb) Reconhecimento de Entidades Nomeadas


3. [Representação e Caracterização de Textos (Parte I)](cap02_representacoes_texto.ipynb)

4. Redes Neurais Artificiais

   4.1. [Perceptron Simples](cap03_1_perceptron_simples.ipynb)
   
   4.2. [Multilayer Perceptron](cap03_2_multilayer_perceptron.ipynb)


   

### Estudos de Caso para o Projeto

6. [Classificação de polaridade em tweets utilizando MLP](cap3_3_sentiment_analysis_dnn.ipynb)

7. [Reconhecimento de entidades nomeadas em atos de pessoal do Diário Oficial do Distrito Federal](ner_aula.ipynb)
-->

## Referências

https://web.stanford.edu/~jurafsky/slp3/

https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf


