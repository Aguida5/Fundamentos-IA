# Fundamentos-IA

Dado ao momento em que o mundo está passando com a pandemia COVID19, resolvi escolher o seguinte código contendo o Data Set com imagens de RAIO X que serão avaliadas pela rede para identificar se os pacientes tem ou não PNEUMONIA, o que é uma característica da virose.

O Data Set de imagens e o código estão no endereço: 
https://www.kaggle.com/paultimothymooney/detecting-pneumonia-in-x-ray-images/data

As imagens foram salvas em .

Para processar o modelo foi necessário:
•	Salvar as imagens em um diretório local
•	Importar diversas bibliotecas, como por exemplo o sklearn e keras
•	Data Set com + de 3.000 imagens – > sendo que o conjunto de treinamento utilizou 2.682  imagens e o 
restante delas foram utilizadas para efetuar a validação do modelo
•	Para cada conjunto de treinamento foram usadas duas (2) classes
•	6 épocas, sendo que a cada finalização de uma época, foi rodado call-back para salvar métricas a cada época finalizada;
•	Pesos das classes antigas e novos pesos das classes

Foram plotadas múltiplas imagens rotuladas como “Sem Pneumonia” e “Com Pneumonia”.

Para a predição foram consideradas o numero de classes e uma função de ativação denominada de “softmax”.

A acurácia inicial foi de 82% e após o recalculo a acurácia foi de 79,9%.
