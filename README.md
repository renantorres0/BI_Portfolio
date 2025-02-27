# BI Portfolio 📊
 
Bem-vindo ao meu portfólio de Business Intelligence (BI). Este repositório contém uma coleção de projetos e análises que demonstram minhas habilidades e experiências na área de BI.

## Descrição 📄

Este portfólio inclui projetos que abrangem diversas áreas do BI, como análise de dados, visualização de dados, relatórios e painéis interativos. Cada projeto é acompanhado de uma descrição detalhada, conjunto de dados utilizado, e as ferramentas e técnicas aplicadas.

## Índice 🗂️

- [Projetos](#projetos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Contribuição](#contribuição)
- [Contato](#contato)

## Projetos 📁

Aqui estão alguns dos projetos incluídos neste portfólio:

1. [**Análise de Métricas RFV**](https://github.com/renantorres0/BI_Portfolio/tree/main/An%C3%A1lise%20de%20M%C3%A9tricas%20RFV)
   - Descrição: Agrupar clientes em clusters baseados no comportamento de compra para personalizar campanhas de marketing.
   - Ferramentas: SQL, Python, SciKit Learn, Google Colab
   - Dados: Arquivo em excel que contém inicialmente as seguintes colunas
     
    | Coluna | Descrição | Tipo |
    |--------|-----------|------|
    | InvoiceNo | Identificação da transação | Int |
    | StockCode | Código de estoque do produto | String |
    | Description | Descrição do produto | String |
    | Quantity | Quantidade de produtos por transação | Int |
    | InvoiceDate | Data da transação | Datetime |
    | UnitPrice | Preço unitário do produto | Float |
    | CustomerID | Identificação do cliente | Int |
    | Country | País de origem da transação | String |

   - Etapas:
       - Etapa 01: Análise exploratória dos dados
       - Etapa 02: Pré-processamento dos dados
       - Etapa 03: Seleção de um algoritmo de clusterização
       - Etapa 04: Análise dos clusters obtidos
       - Etapa 05: Interpretação dos dados obtidos
         ![image](https://github.com/user-attachments/assets/3ecad0b0-6283-4950-ba81-87f1b3b56f02)
       - Conclusão

3. [**Dashboard de Vendas**](https://github.com/renantorres0/BI_Portfolio/tree/main/Dashboard%20de%20Vendas)
   - Descrição: Painel gerencial para um e-commerce visualizando métricas de vendas, com filtros para analistas estudarem resultados e estratégias.
   - Ferramentas: Power BI, Excel
   - Dados: Os arquivos em excel contém inicialmente as seguintes colunas
     
    | Coluna | Descrição | Base |
    |--------|-----------|------|
    | idcompra | numero de identificação da compra | base compra |
    | idcanalvenda | Canal de venda | base compra |
    | bandeira | Qual foi a bandeira que a compra foi realizada | base compra |
    | Data | Data da compra | base compra |
    | Preço | Preço da compra | base compra |
    | Preço_com_frete | Preço da compra + frete | base compra |
    | Nome_Departamento | Departamento do produto | base compra |
    | estado | Estado da compra | base compra |
    | cliente_Log | Identificação do cliente | base compra |
    | cliente_Log | Identificação do cliente | base cliente |
    | Idade | Idade do cliente | base cliente |
    | uf_nascimento | Cidade de nascimento | base cliente |
    | Renda | renda do cliente | base cliente |
   
   - Previews:
     ![Visão compras](https://github.com/user-attachments/assets/e91a375f-ddfa-4a57-bb36-7501aba81045)
     ![Visão clientes](https://github.com/user-attachments/assets/c28a3e9a-4729-4190-a4fe-50602da41aa7)


4. [**Dashboard de eCommerce**](https://github.com/renantorres0/BI_Portfolio/tree/main/Dashboard%20eCommerce)
   - Descrição: Dashboard no Power BI para acompanhar o desempenho das campanhas e ajudar a equipe de marketing a alcançar as metas trimestrais com dados detalhados e insights estratégicos.
   - Ferramentas: Power BI, Excel
   - Dados: Os arquivos em excel contém inicialmente as seguintes colunas
     
    | Coluna | Descrição |
    |--------|-----------|
    | Data do período analisado | Data do período |
    | Receita total | Receita total da data |
    | Soma da Receita média por compra | Soma da Receita média na data |
    | Total de compradores | quantidade de compradores na data |
    | Visualizações | Quantidade de visualizações na data |
    | Compradores por dia | Quantidade de compradores no dia |
    | Compradores por origem | Quantidade de compradores por origem |
    | Usuários totais por plataforma | Quantidade de usuarios na plataforma |
    | Usuários totais por cidade | Quantidade de usuarios na plataforma por cidade |
    | Usuários ativos por gênero | Quantidade de compradores por genero |
   
   - Previews:
     ![eCommerceX](https://github.com/user-attachments/assets/194486a1-dc08-47ab-8136-dda356261fc8)
     ![Compradores e Visualizações](https://github.com/user-attachments/assets/478b7f9f-8528-446c-82e1-7e590da6140a)

6. [**Prevenção Streaming**](https://github.com/renantorres0/BI_Portfolio/tree/main/Preven%C3%A7%C3%A3o%20Streaming)
   - Descrição: Modelo de classificação para prever a probabilidade de cancelamento de assinaturas na plataforma de streaming e ajudar a reduzir o churn.
   - Ferramentas: SQL, Python, Python Graph Galery, SciKit Learn, Google Colab
   - Dados: Os arquivos em excel contém inicialmente as seguintes colunas
     
    | Coluna | Descrição | Tipo |
    |--------|-----------|------|
    | client_id | Código de identificação do cliente | Int |
    | age | Idade do cliente | Int |
    | gender | Gênero do cliente | String |
    | region | Região de origem do cliente | String |
    | subscription_days | Dias de assinatura ativa do cliente | Int |
    | subscription_type | Tipo de conta | String |
    | num_contents | Quantidade de conteúdos assistidos | Int |
    | avg_rating | Avaliação média dos conteúdos da plataforma | Int |
    | num_active_profiles | Número de perfis ativos na plataforma | Int |
    | num_streaming_services | Quantidade de serviços de streaming que o cliente possui | Int |
    | devices_connected | Quantidade de dispositivos conectados à conta | Int |
    | churned | Se o cliente cancelou a conta ou não | Int |

   - Etapas:
       - Etapa 01: Análise exploratória dos dados (Data Undestanding)
          ![image](https://github.com/user-attachments/assets/0a7800e7-b911-436d-bb22-939510f5bbc8)
          ![image](https://github.com/user-attachments/assets/8a25f7f0-6510-4014-a7e9-279d967a2fcb)
       - Etapa 02: Tratamento dos dados (Data Preaparation)
       - Etapa 03: Modelagem dos Dados - Regressão Logística
          ![image](https://github.com/user-attachments/assets/b32766e9-d573-486a-b6fc-5cb70b59963d)
       - Etapa 04: Modelagem dos Dados - Tunning
          ![image](https://github.com/user-attachments/assets/21428ec5-eaf4-4784-81b3-9b0a1869ab31)
       - Etapa 05: Modelagem dos Dados - Random Forest
          ![image](https://github.com/user-attachments/assets/01dc7263-9d8b-4b6f-be8c-bebe70bdd8e9)

8. [**Regressão para Marketing**](https://github.com/renantorres0/BI_Portfolio/tree/main/RFM%20eCommerce)
   - Descrição: Relação entre investimentos em publicidade e geração de leads, com identificação de fatores impactantes e criação de um modelo preditivo para estimar retornos de vendas com base nos investimentos.
   - Ferramentas: SQL, Python, Python Graph Galery, SciKit Learn, Google Colab  
   - Dados: A tabela contém informações dos investimentos feitos pelo youtube, facebook, newspaper e também a quantidade de cada.
     
    | Coluna | Descrição |
    |--------|-----------|
    | youtube | Investimento youtube |
    | facebook | Investimento facebook |
    | newspaper | Investimento newspaper |
    | sales | Valor das vendas |

    - Etapas:
       - Etapa 01: Análise descritiva
       - Etapa 02: Análise exploratória
         
         ![image](https://github.com/user-attachments/assets/6862b395-9087-4e55-880c-c41e7dfe1bf1)
       - Etapa 03: Modelagem
       - Etapa 04: Calculando a predição
    
9. [**RFM eCommerce**](https://github.com/renantorres0/BI_Portfolio/tree/main/Regress%C3%A3o%20para%20Marketing)
   - Descrição: Cálculo de métricas RFM (Recência, Frequência e Ticket Médio) dos clientes de um e-commerce a partir de uma base de dados CSV e geração de um output CSV com essas informações.
   - Ferramentas: SQL, Python, Python Graph Galery, SciKit Learn, Google Colab, Excel
   - Dados: A tabela contém informações de compras de um e-commerce em 37 países. Contém a identificação do cliente e os dados da compra.
     
    | Coluna | Descrição |
    |--------|-----------|
    | CustomerID | Código de identificação do cliente |
    | Description | Descrição do produto |
    | InvoiceNo | Código da fatura |
    | StockCode | Código de estoque do produto |
    | Quantity | Quantidade do produto |
    | InvoiceDate | Data do faturamento (compra) |
    | UnitPrice | Preço unitário do produto |
    | Country | País da compra |

   - Etapas:
       - Etapa 01: Leitura e Inspeção dos dados
       - Etapa 02: Tratamento de Valores faltantes na Identificação de Cliente
       - Etapa 03: Tratamento de Preços e Quantidades Inválidos
       - Etapa 04: Remoção de Linhas Duplicadas
       - Etapa 05: Correção dos Tipos de Dados
       - Etapa 06: Tratamento de Outliers
       - Etapa 07: Criação da Coluna Preço Total
       - Etapa 08: Cálculo da Última Coluna
       - Etapa 09: Plotagem de Gráficos
         ![image](https://github.com/user-attachments/assets/a49e05e1-dec0-4ed8-8498-3ec9e9d46975)
         ![image](https://github.com/user-attachments/assets/da0d01f9-d7d8-4784-9d18-6ebab596739c)
         ![image](https://github.com/user-attachments/assets/b2144c9a-dca7-4e4a-a936-3e5e3d40034f)
         ![image](https://github.com/user-attachments/assets/95aed3d7-60a6-4c40-927f-3951f32fc8fd)
       - Etapa 10: Cálculo do RFM

## Instalação 🛠️

Para visualizar e interagir com os projetos localmente, siga os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/renantorres0/BI_Portfolio.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd BI_Portfolio
   ```

## Uso 👨🏻‍💻

Cada projeto possui um diretório próprio com as instruções específicas de uso e visualização. Siga as instruções dentro de cada diretório de projeto para abrir e interagir com os relatórios e dashboards.

## Tecnologias Utilizadas 💻

- **Power BI**: Para criação de dashboards interativos e relatórios.
- **SQL**: Para manipulação e consulta de dados.
- **Excel**: Para análise de dados e criação de gráficos.
- **Google Colab**: Para escrever e executar código Python diretamente no navegador, com recursos poderosos como GPUs gratuitas e integração com o Google Drive.
- **Python Graph Galery**: Para gerar elementos visuais diretamente através da linguagem Python.
- **SciKit Learn**: Para documentação com os principais modelos utilizados para clusterização.

## Contribuição 🫱🏼‍🫲🏼

Contribuições são bem-vindas! Se você quiser contribuir com este portfólio, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas mudanças:
   ```bash
   git commit -m 'Adiciona minha feature'
   ```
4. Push para a branch:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

## Contato ✉️

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- **Email**: nantorres0@example.com
- **LinkedIn**: [Renan Torres](https://www.linkedin.com/in/renan-torres-121a06106/)

Espero que você aproveite os projetos e que eles possam demonstrar minhas habilidades e experiências em Business Intelligence. Obrigado por visitar meu portfólio! 😍
