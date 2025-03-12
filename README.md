# NeuralNet-Seq2Seq-LSTM-Attention
(Schoolwork about Seq2Seq + LSTM + Attention)

Análise de fuga de corrente devido a deposição de sal em insuladores em alto mar.

O presente trabalho utiliza a combinação de arquiteturas Seq2Seq e LSTM, com a adição de estrutura "atention" para auxiliar a rede a focar em elementos relevantes na hora do treinamento. O uso de rede Seq2Seq + LSTM se deve ao fato dos dados serem séries temporais e dados que pussuem correlação temporal nescessitam que a análise leve em consideração a variação entre "o que ocorreu antes e depois" no dados. No caso a rede Seq2Seq trabalha com um input "rolante" de uma sequência e um output da sequência de dados que serão a previsão da corrente nos insuladores. 
No gráfico abaixo pode visualizar-se em tracejado a previsão e em linha contínua o dado real.


![alt text](https://github.com/LeleoJs/NeuralNet-Seq2Seq-LSTM-Attention-/blob/main/trainXtest.png?raw=true)
----

Na figura abaixo visualiza-se os treinamentos e a taxa de aprendizado da rede.
![alt text](https://github.com/LeleoJs/NeuralNet-Seq2Seq-LSTM-Attention-/blob/main/learn_rate.png?raw=true)
