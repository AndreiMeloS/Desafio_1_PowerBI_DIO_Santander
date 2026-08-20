# Desafio_1_PowerBI_DIO_Santander

replicar duas páginas já criadas durante o curso com a sample disponibilizada. Acesse o link do Gihub para ter acesso aos dados: 

https://github.com/julianazanelatto/power_bi_analyst 

A terceira página, a qual vocês irão criar sozinhos, deve conter alguns visuais. Esse desafio visa treinar a habilidade de criação de visuais. Assim, você poderá criar familiaridade com esses recursos. Em módulos mais avançados iremos tratar do layout mais elaborado dos nossos relatórios.  

Muito bem, a terceira página é composta por: 

Visual mapa 1: Soma de sales e unidades vendidas por país 

Visual mapa 2: Soma de lucro (profit) por país 

Visual de pizza: Lucro por segmento 

 

Além disso: 

Verifique a disposição dos visuais no relatório 

Modifique os nomes dos visuais para algo mais claro e direto (de acordo com o contexto) 

Preste atenção aos campos que são utilizados como dicas de ferramentas  

Publique o relatório 

Compartilhe como suplemento no Power Point 

Caso não tenha Power Point, salve o projeto de Power B.

________________________________________________

Nesse desafio eu fiz duas análises a primeira sobre Diabetes e a segunda sobre Finanças.


#### ANÁLISE 1 -  TRABALHANDO COM DATASETS SOBRE DIABETES

Extraído da plataforma de datsets gratuitos chamda Kaggle 

Diante de um desafio com esse a primeira coisa a se fazer é CARACTERIZAR O DATASET para ibter uma breve explicaçãosobre sample.
- Do que se trata o Dataset
  Foi um estudo que foi verificado inforamçoes relacioando a mulheres apartir de 21 anos possuem ascendência indígena Pima.
- Entender como ele está  estruturado?
  É um dataset (.csv) com diversas variáveis. Algumas delas são variáveis independentes (diversas variáveis preditoras médicas) e apenas uma é a variável dependente ou variável-alvo (Outcome).
- o QUE SEGINFICAdo CADA VARIAvel
- fAZER uma relação entreelas utilizando gráficos

Breve explicação sobre a Sample 
Colunas do Cinjunto de dados:
Gravidezes (Pregnancies): Número de vezes que a paciente esteve grávida.
Glicose (Glucose): Concentração de glicose plasmática após um teste oral de tolerância à glicose de 2 horas.
Pressão arterial (BloodPressure): Pressão arterial diastólica (mm Hg).
Espessura da pele(SkinThickness): Espessura da prega cutânea do tríceps (mm).
Insulina (Insulin): insulina sérica de 2 horas (mu U/ml).
IMC (BMI): Índice de massa corporal (peso em kg/(altura em m)^2).
DiabetesPedigreeFunction: Uma função que representa o histórico familiar de diabetes do paciente (ou seja, a probabilidade de diabetes com base no histórico familiar).
Idade (Age): Idade do paciente (em anos).
Resultado (outcome): Resultado binário (0 ou 1), onde 1 indica a presença de diabetes e 0 indica a ausência.

1. TRATANDO OS DADOS

Percebeu-e um erron nos dados do data set, onde as colunas deveriam ser separdas por "virgula" existia uma que estva seprada por "Ponto", foi necessários fazer a Localizaçã oe Substituição na seguinte ordem:

Onde tinha virgula >> Substiruir por ponto-virgula
Onde tinha ponto >> Substituirp por virgula

Agora retorna esses dados para PowerWuery e PROBLEMA RESOLVIDO!!

2. CRIANDO VISUAIS

2.1 Gráfico de Barras com Variação da glicose 

Quero verificar como a Glicose e a insulina variam de acordo com a idade das mulheres que foramestudadas nesse estudo.

<img width="171" height="213" alt="image" src="https://github.com/user-attachments/assets/72156bdf-e52d-4b1a-8388-f3bfe6f39dc2" />

Título do Gráfico foi Média de Glicose Insulina por idade

DICA:
eXISTE UMA coisa chamda dica de ferramenta, que serve para quando eu quero colocar algum outro campo quando eu coloco cursor em cima. >> Nesse caso eu adicionei a Contagem 



#### ANÁLISE 2 - TRABALAHNDO COM DATASET DE FINANCIALS 


OBTENDO DATASETS COM POWERBI SAMPLES

Dentro do proprio PowerBI >> Inicio >> Experimentare conjunto de base de daodos >> Ele retorna algum datasr nesse caso foi uma Sample denomina de "Faniancials". 























-

