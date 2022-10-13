# Modeling

## Selecionar técnica de modelagem

Etapa na qual se determina quais técnicas de modelagem serão utilizadas, por exemplo: regressão, classificação/recomendação. É preciso identificar
também qual algoritmo será aplicado, por exemplo: regressão utilizando redes neurais com back propagation. É preciso documentar a técnica que
será utilizada. Se for utilizar mais de uma técnica, documente cada uma delas. É interessante utilizar mais de uma técnica pois assim poderá
comparar e selecionar o melhor modelo. Muitas técnicas de modelagem assumem premissas sobre os dados, como por exemplo, todos os atributos apresentam uma distribuição
uniforme, ou nenhum valor nulo é aceito, etc. É preciso deixar claro quais são as premissas assumidas para cada técnica a ser utilizada. Estas perguntas NÃO devem ser respondidas de fato, elas servem como guia
para a produção do relatório.
- [ ] Quais são os tipos de variáveis que se está trabalhando?
- [ ] De acordo com o objetivo do projeto e com os dados disponíveis qual técnica faz mais sentido? Por quê?
- [ ] Quais premissas foram assumidas para cada técnica e por quê?
- [ ] Pensando no negócio, quais os critérios para selecionar a técnica?

## Criar design de teste
Antes de construir um modelo é preciso gerar um procedimento ou mecanismo para testar a qualidade e a validade do modelo gerado. Assim,
para conseguir gerar o modelo, testá-lo e validá-lo é preciso separar os dados em 3 conjuntos: treino, teste e validação. Basicamente é preciso utilizar
uma parte dos dados para treinar o modelo, outro conjunto para testá-lo e por fim um conjunto para validar.
Por exemplo: em modelos supervisionados como classificação é comum utilizar frequência de erros como medida de qualidade. Para isso costuma-se separar o dataset em treino e teste. O modelo é construído
utilizado o dataset de treino e a qualidade é estimada utilizando o dataset de teste. Como o modelo não teve contato com o dataset de teste, a assertividade que ele terá com o teste será uma medida válida da qualidade
do modelo. Estas perguntas NÃO devem ser respondidas de fato, elas servem como guia para a produção do relatório.
- [ ] Como o modelo será treinado, testado e avaliado?
- [ ] O dataset será dividido em quantos conjuntos? Por quê?
- [ ] Como o dataset será divido?

## Modelo de construção
Rode a ferramenta de modelagem no dataset preparado para construir o modelo. Por mais glamoroso que pareça, isso pode ser apenas a execução de
algumas linhas de código como “reg = LinearRegression (). Fit (X, y)”. Quando se constrói modelos, as ferramentas fornecem opções de configuração dos
parâmetros que podem ser ajustados. Esses ajustes terão impacto direto na estrutura do modelo. Liste os parâmetros utilizados bem como os valores
definidos para cada um deles, deixando claro o raciocínio utilizado nessas escolhas. Com o modelo construído, descreva-o deixando claro o tipo do
modelo (ex: regressão linear ou redes neurais) e as variáveis utilizadas. Explique como o modelo é interpretado. Documente todas as dificuldades
encontradas no processo de modelagem. Por fim insira o modelo gerado. Estas perguntas NÃO devem ser respondidas de fato, elas servem como guia
para a produção do relatório.
- [ ] Quais parâmetros foram selecionados? Por quê?
- [ ] Quais valores foram assumidos para cada parâmetro? Por quê?
- [ ] Como interpretar o modelo? Qual é a complexidade nessa interpretação?

## Avaliação do modelo
Nesta etapa se avalia os modelos gerados tanto de um ponto de vista técnico (ex: acurácia) quanto do ponto de vista do negócio (levando em consideração
os objetivos de negócio e seus critérios de sucesso). Geralmente, vários modelos competem entre sí e o cientista de dados precisa interpretar os
resultados do modelo com base no conhecimento do domínio, nos critérios de sucesso pré-definidos e no design do teste. Faça um resumo dos resultados, listando a qualidade dos
modelos gerados e ranqueie a qualidade de cada modelo com relação aos outros. Nessa etapa, provavelmente será necessário revisar os parâmetros adotados na construção do modelo, fazer novos ajustes e rodar novamente a
construção dos modelos. Embora o guia CRISP-DM sugira "iterar a construção e avaliação do modelo até que você acredite fortemente que encontrou o(s) melhor(es)
modelo(s)", na prática, as equipes devem continuar iterando até encontrar um modelo "bom o suficiente", prossiga com o CRISP - Ciclo de vida do DM e,
em seguida, melhore ainda mais o modelo em iterações futuras. Estas perguntas NÃO devem ser respondidas de fato, elas servem como guia para a produção do relatório.
- [ ] Algum modelo atende aos critérios de qualidade técnico e do negócio?
- [ ] Foi preciso reajustar os parâmetros?
- [ ] Baseado em que foram definidos novos valores para os parâmetros?
