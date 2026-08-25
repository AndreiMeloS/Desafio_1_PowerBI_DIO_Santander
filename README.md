# 📊 Power BI Analyst — DIO & Santander

Projeto desenvolvido durante o **Módulo 1 do curso Power BI Analyst**, realizado pela **DIO em parceria com o Santander**.

O desafio teve como objetivo trabalhar com diferentes datasets no Power BI, passando pelas etapas de **caracterização dos dados, tratamento, exploração e construção de análises visuais**.

Foram desenvolvidas duas análises:

- 🩺 **Análise 1 — Diabetes**
- 💰 **Análise 2 — Financials**

> Este projeto também foi utilizado como oportunidade para documentar o processo de construção dos dashboards e registrar as principais decisões tomadas durante as análises.

---

# 🩺 Análise 1 — Diabetes

## 📌 Sobre o Dataset

O dataset utilizado foi obtido gratuitamente através da plataforma **Kaggle**.

O conjunto de dados apresenta informações relacionadas a mulheres com **21 anos ou mais e ascendência indígena Pima**, permitindo analisar diferentes variáveis médicas e sua relação com a ocorrência de diabetes.

### Estrutura do Dataset

O arquivo está estruturado em formato `.csv` e possui diversas variáveis independentes — utilizadas como preditoras — e uma variável dependente, denominada **Outcome**, que representa o resultado relacionado à presença ou ausência de diabetes.

### 📋 Principais variáveis

| Variável | Descrição |
|---|---|
| **Pregnancies** | Número de vezes que a paciente esteve grávida |
| **Glucose** | Concentração de glicose plasmática após teste oral de tolerância à glicose de 2 horas |
| **BloodPressure** | Pressão arterial diastólica (mm Hg) |
| **SkinThickness** | Espessura da prega cutânea do tríceps (mm) |
| **Insulin** | Insulina sérica de 2 horas (mu U/ml) |
| **BMI** | Índice de Massa Corporal |
| **DiabetesPedigreeFunction** | Indicador relacionado ao histórico familiar de diabetes |
| **Age** | Idade da paciente |
| **Outcome** | Resultado binário: `0` = ausência de diabetes e `1` = presença de diabetes |

---

## 🛠️ 1. Tratamento dos Dados

Durante o carregamento do dataset foi identificado um problema na separação das colunas.

Os dados deveriam estar separados por **vírgulas**, porém parte do arquivo apresentava uma inconsistência envolvendo o uso de ponto e vírgula.

Para solucionar o problema, foi realizada uma operação de **Localização e Substituição**, seguindo esta sequência:

```text
Vírgula (,) → Ponto e vírgula (;)

Ponto e vírgula (;) → Vírgula (,)
```

Após o ajuste, os dados foram novamente carregados no **Power Query**, solucionando o problema de estruturação do dataset.

---

# 📊 2. Construção dos Visuais

# 📊 2. Construção dos Visuais

Na construção do relatório foram utilizados recursos como:

- Formas;
- Caixas de texto;
- Segmentação de dados (*Slicer*);
- Gráficos de colunas;
- Gráficos combinados;
- Gráfico de área;
- Gráfico de barras;
- Treemap.



---

## 📄 Página 1 — Análise Descritiva dos Dados de Diabetes

### 📊 2.1 — Distribuição das Variáveis por Resultado de Diabetes

**Visual:** Gráfico de Colunas Clusterizado

Utilizado para comparar os valores das variáveis analisadas de acordo com o resultado apresentado no campo **Outcome**.

![Distribuição das Variáveis por Resultado de Diabetes](https://github.com/user-attachments/assets/b319326e-0ccb-49f4-bb2f-958d1bb6516d)

---

### 📈 2.2 — Comparativo entre Indicadores de Diabetes

**Visual:** Gráfico Combinado de Colunas e Linhas

O gráfico combinado permite observar simultaneamente diferentes medidas, facilitando a comparação entre os indicadores apresentados no relatório.

![Comparativo entre Indicadores de Diabetes](https://github.com/user-attachments/assets/8acda280-9d08-4d3e-8575-a7cf5d626b5f)

---

### 📉 2.3 — Evolução dos Indicadores Analisados

**Visual:** Gráfico de Área

Utilizado para representar visualmente a distribuição dos indicadores ao longo da dimensão analisada.

![Evolução dos Indicadores Analisados](https://github.com/user-attachments/assets/707791d9-7c33-4315-9cc0-0badbb760876)

---

# 📄 Página 2 — Principais Fatores Relacionados ao Diabetes

A segunda página foi estruturada para aprofundar a análise dos **fatores associados ao resultado de diabetes**, utilizando diferentes formas de visualização.



### 📊 2.4 — Comparação dos Principais Indicadores

**Visual:** Gráfico de Barras Clusterizado

Permite comparar os indicadores selecionados de maneira direta, facilitando a identificação de diferenças entre os grupos analisados.

![Comparação dos Principais Indicadores](https://github.com/user-attachments/assets/6d17ab82-999d-43a8-b1ae-6084bd83a48b)

---

### 🟦 2.5 — Distribuição dos Fatores Associados ao Diabetes

**Visual:** Treemap

Utilizado para representar a participação relativa dos fatores analisados por meio de uma visualização hierárquica.

![Distribuição dos Fatores Associados ao Diabetes](https://github.com/user-attachments/assets/fb13b1aa-d8f2-451e-b2df-851568a91002)

---

# 💰 Análise 2 — Financials

## 📌 Sobre o Dataset

Para a segunda análise foi utilizado o dataset **Financials**, disponibilizado diretamente nos exemplos do Power BI.

O dataset pode ser acessado no próprio Power BI através do caminho:

```text
Power BI
→ Início
→ Experimentar um conjunto de dados
→ Financials
```

O objetivo desta análise foi explorar informações relacionadas a **vendas, produtos, segmentos, países e lucro**, utilizando diferentes recursos de visualização disponíveis no Power BI.

### 🗂️ Estrutura dos Dados

O dataset contém informações que permitem realizar análises sob diferentes perspectivas, incluindo:

- Produtos;
- Segmentos;
- Países;
- Vendas (*Sales*);
- Lucro (*Profit*);
- Unidades vendidas.

### 🛠️ Tratamento dos Dados

Não foi necessário realizar tratamentos iniciais nos dados antes da construção do relatório.

---

# 📊 Construção do Relatório Financials

## 📄 Página 1 — Análise de Vendas por Produto e Segmento

A primeira página foi construída com foco na análise das **vendas considerando produtos e segmentos**.

### 🎛️ 1.1 — Filtros de Análise

**Visual:** Segmentação de Dados (*Slicer*)

A segmentação de dados permite ao usuário **filtrar o relatório de forma interativa**, selecionando os valores de interesse e alterando dinamicamente os demais visuais.

![Filtros de Análise](https://github.com/user-attachments/assets/18d706bb-5e6a-4bf5-a8cb-c70b2190c175)

---

### 🥧 1.2 — Participação das Vendas por Categoria

**Visual:** Gráfico de Pizza

Utilizado para visualizar a participação relativa das categorias analisadas no total apresentado.

![Participação das Vendas por Categoria](https://github.com/user-attachments/assets/de32e793-89d2-495e-aaa7-7e2e1f7913f0)

---

### 📈 1.3 — Evolução das Vendas

**Visual:** Gráfico de Área

Utilizado para representar a evolução da métrica analisada ao longo da dimensão temporal disponível.

![Evolução das Vendas](https://github.com/user-attachments/assets/fd792aea-4343-4030-8e72-370e376f0429)

---

### 📊 1.4 — Comparativo de Vendas por Produto

**Visual:** Gráfico de Colunas Clusterizado

Permite comparar o desempenho de vendas entre os produtos apresentados no dataset.

![Comparativo de Vendas por Produto](https://github.com/user-attachments/assets/9f465721-2898-4515-a6e8-9806466c9f39)

---

# 📄 Página 2 — Análise de Vendas, Países e Lucro

A segunda página concentra a análise de **vendas e rentabilidade**, permitindo observar os resultados sob diferentes perspectivas.



### 💳 2.1 — Indicadores Gerais de Desempenho

**Visual:** Cartões

Os cartões apresentam os principais indicadores de forma resumida, permitindo uma leitura rápida dos resultados.

![Indicadores Gerais de Desempenho](https://github.com/user-attachments/assets/cacea7fe-1aab-48bf-9688-77361a85e5aa)

---

### 🥧 2.2 — Distribuição das Vendas

**Visual:** Gráfico de Pizza

Utilizado para visualizar a participação das categorias selecionadas no total de vendas.

![Distribuição das Vendas](https://github.com/user-attachments/assets/ce0856cc-aebe-48cd-8045-d9b62de12b16)

---

### 📊 2.3 — Vendas por Categoria e Segmento

**Visual:** Gráfico de Colunas Empilhadas

Permite comparar o volume de vendas e visualizar simultaneamente a composição dos resultados entre diferentes categorias.

![Vendas por Categoria e Segmento](https://github.com/user-attachments/assets/97cf777a-c929-488d-a4d2-b47baca5cb74)

---

### 📊 2.4 — Comparativo de Desempenho por País

**Visual:** Gráfico de Colunas Clusterizado

Utilizado para comparar os resultados entre os países presentes na análise.

![Comparativo de Desempenho por País](https://github.com/user-attachments/assets/03153c14-bc1b-49fa-9669-6726de7f97a5)

---

# 🌎 Página 3 — Análise Geográfica de Vendas e Rentabilidade

Para a terceira página, recomendo o título:

> **🌎 Análise Geográfica de Vendas e Rentabilidade**

Esse nome é mais profissional e representa bem a combinação dos mapas de **Sales**, **Units Sold**, **Profit** e a análise de lucro por segmento.

---

### 🗺️ 3.1 — Vendas e Unidades Vendidas por País

**Visual:** Mapa

Apresenta a distribuição geográfica das **vendas e unidades vendidas**, permitindo identificar diferenças de desempenho entre os países.

![Vendas e Unidades Vendidas por País](https://github.com/user-attachments/assets/e1d0e81f-aa5e-4f1b-b4cb-05f4cd416a9f)

---

### 🗺️ 3.2 — Distribuição do Lucro por País

**Visual:** Mapa

Permite analisar a distribuição geográfica do **lucro (Profit)** e identificar os países com maior participação no resultado.

![Distribuição do Lucro por País](https://github.com/user-attachments/assets/1a4e7836-42e3-40d3-8a42-99246235f112)

---

### 🥧 3.3 — Participação do Lucro por Segmento

**Visual:** Gráfico de Pizza

Apresenta a participação de cada segmento no lucro total, permitindo identificar quais segmentos possuem maior contribuição para a rentabilidade.

![Participação do Lucro por Segmento](https://github.com/user-attachments/assets/fc4ff940-f784-46be-a967-2dba45dabcd8)


---

# 🧠 Principais Recursos Praticados

Durante o desenvolvimento das duas análises, foram praticados recursos importantes do Power BI, incluindo:

- 📥 Importação de datasets;
- 🧹 Tratamento e organização de dados;
- 🔄 Power Query;
- 🎛️ Segmentação de dados;
- 📊 Gráficos de colunas;
- 📈 Gráficos combinados;
- 📉 Gráficos de área;
- 🥧 Gráficos de pizza;
- 🗺️ Mapas;
- 🟦 Treemap;
- 💳 Cartões;
- 🎨 Formatação e organização visual de relatórios;
- 🔎 Exploração de dados através de diferentes perspectivas.

---

# 📚 Aprendizados

O projeto permitiu praticar não apenas a criação de gráficos, mas principalmente o processo de transformação de um dataset em uma **análise visual estruturada**.

Entre os principais aprendizados estão:

1. **Caracterizar o dataset antes de iniciar a análise;**
2. **Compreender o significado das variáveis;**
3. **Identificar e solucionar problemas de carregamento dos dados;**
4. **Utilizar o Power Query para ajustes na estrutura dos dados;**
5. **Escolher diferentes tipos de visuais de acordo com o objetivo da análise;**
6. **Utilizar filtros interativos para facilitar a exploração dos dados;**
7. **Organizar diferentes páginas de relatório de acordo com perspectivas analíticas;**
8. **Transformar dados em informações visualmente acessíveis.**

---

# 🛠️ Ferramentas

| Ferramenta | Utilização |
|---|---|
| **Power BI** | Construção dos relatórios e dashboards |
| **Power Query** | Tratamento e preparação dos dados |
| **Kaggle** | Fonte do dataset de Diabetes |
| **Power BI Samples** | Fonte do dataset Financials |

---

# 📌 Projetos Desenvolvidos

### 🩺 Diabetes
**Foco:** análise descritiva e identificação de fatores relacionados ao resultado de diabetes.

### 💰 Financials
**Foco:** análise de vendas, produtos, segmentos, países e rentabilidade.

---

## 👨‍💻 Sobre o Projeto

Projeto desenvolvido como parte do **Módulo 1 do curso Power BI Analyst — DIO + Santander**, com foco na prática de análise de dados e construção de relatórios interativos no Power BI.

> **Objetivo:** desenvolver a capacidade de transformar dados brutos em análises visuais que facilitem a interpretação e a tomada de decisão.






__________________________________________________________________________________________________________________________________

