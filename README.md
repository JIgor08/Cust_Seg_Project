Segmentação de Clientes com RFV
==============================

Neste projeto, abordei a tarefa de segmentação de clientes por meio da aplicação do algoritmo KMeans, uma técnica de aprendizado de máquina não supervisionado amplamente reconhecida por sua eficácia na descoberta de padrões ocultos em conjuntos de dados. Ao aplicar o KMeans às métricas RFV, buscamos identificar grupos de clientes com comportamentos semelhantes, permitindo que a empresa adapte suas estratégias de marketing e atendimento de acordo com as necessidades específicas de cada segmento.

O principal objetivo deste projeto é oferecer uma visão abrangente de como a segmentação de clientes com base na análise RFV e a aplicação do algoritmo KMeans podem ser utilizadas de forma sinérgica para criar uma abordagem mais personalizada e direcionada ao gerenciamento de clientes. Ao identificar segmentos distintos, a empresa pode otimizar seus recursos, concentrando-se nas áreas de maior potencial e adaptando suas abordagens para melhor atender às expectativas e preferências dos clientes.

O dataset utilizado nesse projeto pode ser baixado neste link: https://www.kaggle.com/datasets/hellbuoy/online-retail-customer-clustering

Após a segmentação, apliquei meus conhecimentos em Power BI para a criação de um dashboard contendo as informações rotuladas(dizendo a qual cluster eles pertencem) dos clientes.

### Pré-requisitos

A versão Python utilizada neste projeto é a 3.10.7
* Pip (Windows)
  ```sh
  py get-pip.py
  ```
* Virtual Env (Opcional)
  ```sh
  pip install virtualenv
  ```

### Instalação

1. Clone o repositório
   ```sh
   git clone https://github.com/JIgor08/Cust_Seg_Project.git
   ```
2. Crie e ative um ambiente virtual (Opcional)
3. Instale os pacotes
   ```sh
   pip install -r requirements.txt
   ```
### Tecnologias utilizadas:

* [![Python][Python]][Python-url]
* [![PBI][PowerBI]][pbi-url]
* [![VSCode][vscode]][vscode-url]

### Dataset:
O Dataset utilizado contém informações de vendas online ocorridas no Reino Unido durante um período de pouco mais de um ano e possui as seguintes colunas:

- <b> InvoiceNo</b>: Valor único para cada compra

- <b> StockCode</b>: Código do estoque

- <b> Description</b>: Descrição do produto

- <b> Quantity</b>: Quantidade de produtos comprados

- <b> InvoiceDate</b>: Data da compra

- <b> UnitPrice</b>: Preço por unidade de produto

- <b> CustomerID</b>: Identificador do cliente

- <b> Country</b>: País do comprador

### Desenvolvimento:
Foram aplicadas diversas técnicas durante o projeto:
- <b> Feature Selection </b>
- <b> Feature Engineering </b>
- <b> Métodos para a escolha do número adequado de Clusters (Elbow Method e Silhuette Method) </b>
- <b> Técnicas de remoção de Outliers</b>
- <b> Algoritmo KMeans para clusterização</b>
- <b> Técnicas de visualização para análise dos Clusters</b>
- <b> Análise dos produtos vendidos </b>
- <b> Criação de um Dashboard contendo as informações dos clientes segmentados </b>

### Dashboard:
[!Link para o Dashboard](https://github.com/JIgor08/Cust_Seg_Project/blob/main/reports/figures/dashboard_rfv.PNG)

<!-- Structure -->
## Estrutura do diretório

    ├── LICENSE
    ├── README.md          <- Readme contendo a descrição do projeto.
    ├── data
    │   ├── external       <- Dados coletados de terceiros.
    │   ├── interim        <- Dados com transformações.
    │   ├── processed      <- Dados finais, após a modelagem.
    │   └── raw            <- Dados originais, imutáveis.
    │
    ├── models             <- Modelos treinados, predições do modelo, ou sumário do modelo.
    │
    ├── notebooks          <- Jupyter notebooks.
    │
    ├── reports            <- Análises geradas em HTML, PDF, LaTeX, etc.
    │   └── figures        <- Gráficos gerados e figuras usadas no relatório.
    │
    └── requirements.txt   <- Arquivo com as bibliotecas necessárias para a reprodução do projeto.
                              Gerado com `pip freeze > requirements.txt`

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

Esse projeto foi executado sob a licença MIT, para mais informações acesse o arquivo LICENSE.tx

[Python]: https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=yellow1
[Python-url]: https://www.python.org/
[PowerBI]: https://img.shields.io/badge/Power_BI-000000?style=for-the-badge&logo=powerbi&logoColor=yellow
[pbi-url]: https://powerbi.microsoft.com/pt-br/
[vscode]: https://img.shields.io/badge/Visual_Studio_Code-000000?style=for-the-badge&logo=visualstudiocode&logoColor=blue
[vscode-url]: https://code.visualstudio.com/
[dashboard]:C:\Users\joaoi\Cust_Seg_Project\reports\figures\dashboard_rfv.PNG

