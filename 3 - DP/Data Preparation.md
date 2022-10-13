# Data Preparation

## Selecionar Dados
Etapa que visa determinar quais conjuntos de dados serão usados e documentar os motivos para inclusão / exclusão de dados
no dataset bruto. Você explicará os motivos para incluir ou excluir cada parte dos dados que possui com base na relevância para seus
objetivos, qualidade de dados e problemas técnicos - como limites para o número de campos ou linhas que suas ferramentas podem
manipular, ou a adequação dos formatos de dados às suas necessidades.
Estas perguntas NÃO devem ser respondidas de fato, elas servem como guia para a produção do relatório.
- [ ] Quais dados do dataset bruto são relevantes para seu  projeto?
- [ ] Será que alguma linha ou coluna não poderia ser  excluída? Se sim, quais os critérios que embasam isso?
- [ ] Pensando no negócio, quais os critérios para selecionar os dados?
- [ ] Se a dificuldade para conseguir o dado é muito grande, faz sentido continuar com sua análise?

## Limpando os dados
Frequentemente, essa é a tarefa mais demorada. Uma prática comum durante essa tarefa é corrigir, imputar ou remover valores errôneos.
A descrição dos dados é a fase da etapa de Data Understanding que visa aplicar análises estatísticas simples para que alguns parâmetros estatísticos sejam conhecidos. Este é o momento em
que o time inicia de fato as análises em cima da massa coletada e, utilizando a perspectiva de ciência de dados, consegue mensurar o tamanho do dataset, o formato e o comportamento matemático dos
dados através de médias, medianas, quartis, por exemplo. Estas perguntas NÃO devem ser respondidas de fato, elas servem como guia para a produção do relatório.
- [ ] Dados do tipo data então fazendo sentido do ponto de vista temporal?
- [ ] Se a feature é composta por número e string, será que não vale a pena transformar essa variável apenas em número para manipulação?
- [ ] Dados nulos não podem ser retirados ou preenchidos pela média, moda ou mediana dos dados?

## Construindo os dados
A intenção dessa etapa é encontrar informações novas a partir dos dados que já se possui, isso pode ser feito a partir de manipulações da features existentes como criar campos (por
exemplo, usar a data de entrega e a data em que um cliente fez um pedido para calcular quanto tempo o cliente espera para receber um pedido), agregar dados ou qualquer outro tipo de relação que seja
possível de ser feita e concorde com o objetivo do projeto. O ouput dessa etapa é a descrição dos registros criados a partir dos dados brutos. Utilize o próximo slide para relatar quais features
foram geradas. Estas perguntas NÃO devem ser respondidas de fato, elas servem como guia para a produção do relatório.
- [ ] Existem dados que, quando somados ou subtraídos resultam em informações relevantes?
- [ ] Os dados estão no melhor formato para as análises?
- [ ] Transformar algum dado do tipo string em numérico poderia ajudar em alguma análise?

## Integrando os dados
A integração de dados é o processo de reunir dados de vários locais e combiná-los em uma visualização. É o processo de consolidação de dados com a intenção de fornecer acesso
consistente e entrega de informações. A integração de dados pode incluir os outros processos de limpeza, mapeamento e transformação de dados, visto que pode ser incorporada no processo
de preparação de dados. Existem muitas técnicas que os analistas de dados usam para integrar dados de várias fontes. Estas são algumas das técnicas mais
importantes usadas na integração de dados:
- [ ] Existem datasets diferentes que podem ser integrados?
- [ ] Existem dados de mesma origem que podem ser somados?
- [ ] Será que é possível somar dados financeiros para gerar informações úteis?

## Formatando os dados
Formate os dados conforme necessário tendo sempre em ente que esse tipo de manipulação deve facilitar o entendimento o dado sem mudar seu significado. Por exemplo, você pode
converter valores de string que armazenam números em valores numéricos para poder realizar operações matemáticas. Os dados frequentemente podem vir em diferentes formatos e
isso pode ser um complicador para a etapa de modelagem que virá logo em seguida. Um fator que deve ser levado em consideração é o tipo de ferramenta que será usada na análise dos dados, ela pode
limitar a construção do modelo. O resultado para essa tarefa são seus dados reformatados mediante sua necessidade, preencha o próximo slide com quais
dados foram formatados e o motivo para essa mudança. Estas perguntas NÃO devem ser respondidas de fato, elas servem como guia para a produção do relatório.
- [ ] Será que precisamos mudar o formato de algum dado?
- [ ] Será que a ferramenta que será usada na análise suporte o formato dos dados atuais?
- [ ] Será que poderíamos desmembrar alguma informação em duas ou mais colunas que facilitem a formatação dos dados?

