# O Que Vende um Carro?
Sou aluno da TripleTen no curso de Ciência de Dados, estou divulgando projetos que desenvolvi para meu portifólio. Este é o terceiro projeto.

Neste projeto sou analista na Lista de Eixo de Manivela. Centenas de propagandas gratuitas de veículos são publicadas no site todos os dias. Preciso estudar os dados coletados nos últimos anos e determinar quais fatores influenciaram o preço de um veículo.

**Temos os seguintes parâmetros** 
* Preço
* Idade do veículo quando a propaganda foi colocada
* Quilometragem
* Número de cilindros
* Condição

**Descrição dos Dados**
O conjunto de dados contém os seguintes campos:
* price
* model_year
* model
* condition
* cylinders
* fuel — gasolina, diesel etc.
* odometer — a quilometragem do veículo quando a propaganda foi publicada
* transmission
* paint_color
* is_4wd — Se o veículo é 4 por 4 (tipo Booleano)
* date_posted — a data que a propaganda foi publicada
* days_listed — dias desde a publicação até a retirada

**Conclusão**

Vemos uma relação clara de quanto mais novo o carro maior o preço, assim como com menos km rodado é também, mais caro. Os carros automáticos são claramente mais caros também. As cores que são mais caras são preto, cinza, vermelho e branco. Sendo branco a mais frequente(analisado anteriormente com .describe()). Então o carro mais caro seria um carro branco com pouca kilometragem, novo e automático.
