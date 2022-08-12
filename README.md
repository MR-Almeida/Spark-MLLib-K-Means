# Spark MLLib K-Means

O intuito deste codigo é mostrar como se aplicar o algoritmo K-Means através do PySpark, mostrar as bibliotecas, fazer análise exploratória, alguns jeitos de programar para poder fazer a limpeza e o pré-processamento dos dados.

Vou estar utilizando o dataset ddos carros mais conhecido com o objetivo de aplicar o aprendizado não superviosionado, para a partir dos dados que temos conseguir agrupa-los de acordos as caracteristicas de suas variavés a fim de formar grupos mais homogenios possivel.

### K-Means

### Descrição

- Algoritmo Não Supervisionado.
- Agrupamento de Dados por Similaridade.
- Particiona os dados em um número "k" de clusters, sendo que cada observação pertende a apenas um cluster.
- A clusterização é feita medindo a distância entre os pontos de dados e agrupando-os.
- Múltiplas medidas de distância podem ser usadas, como distância Euclidiana e distância Manhattan.

Vantagens
- Veloz
- Eficiente quando se tem muitas variáveis

Desvantagens
- O valor de K precisa ser conhecido
- O valor inicial de k tem influência nos clusters criados

Aplicação
- Agrupamento preliminar antes de se aplicar técnicas de classificação
- Clusterização geográfica
