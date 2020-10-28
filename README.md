## Desafio-Deep-Learning-CNN

# Contexto 

As imagens neste conjunto de dados foram retiradas do dataset do Kaggle chamado **flying-planes** no link <https://www.kaggle.com/eabdul/flying-vehicles>. 

# Conteúdo 

Este conjunto de dados contém diferentes tipos de veículos voadores, ou seja: Drone, Helicóptero, Avião de Passageiros, Jato de Combate, etc. Pode-se usar este conjunto de dados para realizar a classificação de imagem multiclasse.  

# Divisão do Dataset

O dataset está formado por 6 classes como: aviao, drone, foguete, helicoptero, jato, missel no qual são 100 para treinamento para cada classe existente e 20 para teste a cerca de cada diretório descrito no data/test.

# Reconhecimentos

O conjunto de dados foi criado após aula do Sr. Doglas &lt;https://github.com/DoglasProg>, nosso novo professor da pós-graduação em Ciência de Dados na Unifacisa Campina Grande - PB.

# Requisito 

- Anaconda
- Visual Studio Code
- Python Interpreter (version Python 3.7.9)
- Comandos para realizar o treinamento:
<br>
-python main.py --device False epochs 10
<br>
-python main.py --device False --epochs 10 --pesos True
