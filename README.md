# NeuralNet-Seq2Seq-LSTM-Attention
(Schoolwork about Seq2Seq + LSTM + Attention)

Análise de fuga de corrente devido a deposição de sal em insuladores em alto mar. Insuladores são componentes elétricos com objetivo de isolar a passagem de corrente elétrica, no entanto em alto mar esses componentes tendem a acumular sal e possibilitar a passagem de corrente elétrica, a seguinte pesquisa tem como objetivo prever esse efeito via algoritmos de aprendizado de máquina utilizando um dataset fornecido. Segue o link do dataset dos insuladores utilizados no treinamento: https://github.com/SFStefenon/LeakageCurrent.git

O presente trabalho utiliza a combinação de arquiteturas Seq2Seq e LSTM, com a adição de estrutura "atention" para auxiliar a rede a focar em elementos relevantes na hora do treinamento. O uso de rede Seq2Seq + LSTM se deve ao fato dos dados serem séries temporais e dados que pussuem correlação temporal nescessitam que a análise leve em consideração a variação entre "o que ocorreu antes e depois" no dados. No caso a rede Seq2Seq trabalha com um input "rolante" de uma sequência e um output da sequência de dados que serão a previsão da corrente nos insuladores. 


No gráfico abaixo visualizar-se em tracejado a previsão e em linha contínua o dado real obtidos com a arquitetura do algoritmo.


![alt text](https://github.com/LeleoJs/NeuralNet-Seq2Seq-LSTM-Attention-/blob/main/trainXtest.png?raw=true)
----


Na figura abaixo visualiza-se os treinamentos e a taxa de aprendizado da rede.


![alt text](https://github.com/LeleoJs/NeuralNet-Seq2Seq-LSTM-Attention-/blob/main/learn_rate.png?raw=true)
