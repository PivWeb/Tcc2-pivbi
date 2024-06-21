GILVAN LAURENTINO DA SILVA

ANÁLISE DE VENDAS E COMPARAÇÃO DE PREÇOS UTILIZANDO POWER BI E MYSQL EM SUPERMERCADOS: Gestão a Vista para Supermercados

Indaiatuba

06 / 2024

Resumo
Este trabalho de conclusão de curso desenvolve um sistema de análise de vendas e comparação de preços para supermercados, utilizando Power BI como ferramenta de visualização e MySQL como sistema de gerenciamento de banco de dados. O problema identificado é a falta de uma ferramenta integrada que permita uma análise eficiente dos dados de vendas e a comparação de preços de produtos em tempo real, auxiliando na tomada de decisões estratégicas. O objetivo geral é criar um sistema que ofereça insights valiosos por meio de um dashboard interativo, facilitando a gestão de preços e o entendimento dos padrões de consumo. A metodologia aplicada inclui o levantamento de requisitos, modelagem de dados, desenvolvimento de casos de uso, criação do banco de dados e construção do dashboard no Power BI. Os resultados obtidos demonstram que a integração entre Power BI e MySQL permite um acesso eficiente e detalhado aos dados de vendas, possibilitando comparações precisas de preços, identificação de tendências de mercado e ajuste dinâmico de estratégias de precificação. A análise de dados revela melhorias na segmentação de clientes e na personalização de ofertas, além de facilitar a detecção de problemas como rupturas de estoque e desempenho insatisfatório de produtos. Em conclusão, a sinergia entre Power BI e MySQL otimiza a gestão de supermercados, aumentando a eficiência operacional, a competitividade no mercado e fornecendo insights valiosos para o desenvolvimento de campanhas promocionais e otimização do mix de produtos.
Palavras-chave: análise de vendas; comparação de preços; supermercados.

1.	INTRODUÇÃO

Na área de Engenharia de Software, o desenvolvimento de sistemas de análise de dados e visualização tem se tornado cada vez mais relevante, especialmente em setores que lidam com grandes volumes de informações, como o varejo. A temática deste trabalho concentra-se na criação de uma solução para análise de vendas e comparação de preços em supermercados, utilizando tecnologias de visualização de dados e gerenciamento de banco de dados. A necessidade de uma gestão eficiente e a tomada de decisões estratégicas fundamentadas em dados precisos são imperativas para manter a competitividade no mercado.

O problema a ser solucionado é a inexistência de uma ferramenta integrada que permita uma análise abrangente e eficiente dos dados de vendas e a comparação de preços em tempo real. Essa falta de integração dificulta a identificação de tendências de mercado, a detecção de problemas operacionais e a personalização de estratégias de marketing e precificação. A hipótese central é que a combinação de Power BI e MySQL pode superar essas dificuldades, proporcionando uma plataforma robusta e interativa para a análise de dados.

Objetivo Geral

O objetivo geral deste trabalho é desenvolver um sistema de software que integre Power BI e MySQL para fornecer uma análise detalhada e interativa das vendas e comparação de preços em supermercados, facilitando a tomada de decisões estratégicas e melhorando a eficiência operacional.

Objetivos Específicos

Levantamento de Requisitos: Identificar e documentar as necessidades específicas dos usuários e as funcionalidades necessárias para o sistema.
Modelagem de Dados: Estruturar o banco de dados MySQL de forma a suportar a análise eficiente de grandes volumes de dados de vendas.
Desenvolvimento de Casos de Uso: Elaborar cenários detalhados que descrevam como os usuários interagirão com o sistema.
Criação do Banco de Dados: Implementar o banco de dados MySQL com base na modelagem definida.
Construção do Dashboard: Desenvolver o dashboard interativo no Power BI, integrando-o com o banco de dados MySQL para a visualização e análise dos dados.
Testes e Validação: Realizar testes abrangentes para garantir que o sistema atende aos requisitos e é capaz de fornecer insights precisos e valiosos.

Justificativa

O desenvolvimento deste produto de software justifica-se pela crescente demanda por soluções que permitam uma gestão mais eficaz e informada no setor de supermercados. A utilização de ferramentas como Power BI e MySQL não só melhora a eficiência operacional como também aumenta a competitividade no mercado, ao oferecer uma análise detalhada e precisa dos dados de vendas. Este sistema proporcionará aos gestores uma visão clara e detalhada dos padrões de consumo e preços, permitindo ajustes rápidos e informados nas estratégias de marketing e precificação.

2. ESPECIFICAÇÕES INICIAIS DO SOFTWARE

2.1 Escopo do Produto

O escopo deste projeto de software abrange o desenvolvimento de um sistema de análise de vendas e comparação de preços para supermercados, utilizando Power BI como ferramenta de visualização e MySQL como sistema de gerenciamento de banco de dados. O propósito é fornecer uma solução integrada que permita aos gestores de supermercados realizar análises detalhadas e interativas dos dados de vendas, comparar preços de produtos e tomar decisões estratégicas informadas. O desenvolvimento inclui o levantamento de requisitos, modelagem de dados, criação do banco de dados, desenvolvimento de casos de uso, construção de dashboards no Power BI, e testes e validação do sistema. O produto final permitirá a visualização de dados de vendas em tempo real, identificação de padrões de consumo, análise de tendências de mercado, segmentação de clientes e personalização de ofertas, além de fornecer alertas sobre rupturas de estoque e desempenho de produtos.


2.2 Funcionalidade do Produto:

As principais funcionalidades do software incluem:
Telas em PHP : Para controle de Usuários e Clientes
Dashboard Interativo: Visualização gráfica dos dados de vendas, permitindo filtros e análises personalizadas.
Comparação de Preços: Ferramenta para comparar preços de produtos entre diferentes fornecedores e concorrentes.
Análise de Tendências: Identificação de tendências de mercado e padrões de consumo ao longo do tempo.
Segmentação de Clientes: Agrupamento de clientes com base em comportamentos de compra e preferências.
Alertas de Estoque: Notificações sobre rupturas de estoque e desempenho insatisfatório de produtos.
Relatórios Personalizados: Geração de relatórios detalhados com insights sobre vendas, preços e comportamento do consumidor.
Integração com MySQL: Conexão direta ao banco de dados para atualização em tempo real dos dados visualizados no Power BI.

2.3 Ambiente Operacional e Tecnologias:

O ambiente operacional e as tecnologias utilizadas no desenvolvimento do software incluem:

Plataforma: O sistema será acessível via web, permitindo que os usuários utilizem navegadores compatíveis (Google Chrome, Mozilla Firefox, Microsoft Edge).
Sistema Operacional (SO): O software será compatível com os principais sistemas operacionais, incluindo Windows, macOS e Linux.
Hardware: O software não exige especificações de hardware avançadas, mas recomenda-se o uso de computadores com processador mínimo de Intel Core i5, 8GB de RAM e 256GB de armazenamento.

Tecnologias Utilizadas:
PHP 8+ : Para Gestao e Controle de Usuários e Clientes
Power BI: Ferramenta de visualização de dados da Microsoft, utilizada para criar dashboards interativos.
MySQL: Sistema de gerenciamento de banco de dados relacional, utilizado para armazenar e gerenciar grandes volumes de dados de vendas.
Linguagens de Programação: SQL para manipulação de dados no MySQL, e DAX (Data Analysis Expressions) para cálculos e agregações no Power BI.
Outras Aplicações: O sistema poderá integrar-se a outras ferramentas de software de supermercados, como sistemas de ponto de venda (POS) e software de gestão de relacionamento com o cliente (CRM).
O desenvolvimento e a operação do sistema garantirão que os dados sejam processados de forma eficiente, com segurança e acessibilidade adequadas para os usuários finais.

3. Metodologia:

Para o desenvolvimento do produto de software, será adotada a metodologia ágil Scrum. Esta metodologia permite uma abordagem iterativa e incremental, facilitando a adaptação a mudanças nos requisitos e garantindo a entrega contínua de valor ao cliente. O projeto será dividido em sprints, com duração de duas semanas, durante as quais serão realizadas reuniões diárias de acompanhamento do progresso, sprint planning para definir as atividades a serem realizadas e sprint review para revisar o trabalho concluído. A equipe será auto-organizável e multifuncional, composta por desenvolvedores, analistas de dados e especialistas em visualização de dados.







4. Desenvolvimento:

Apresentação de Diagrama de Caso de Uso:
O diagrama de caso de uso abaixo ilustra as principais interações entre os atores externos e o sistema de análise de vendas e comparação de preços:

A modelagem de casos de uso é uma etapa crucial no desenvolvimento de sistemas, pois define as interações entre os usuários e o sistema. A seguir, apresento os principais casos de uso do sistema de análise de vendas e comparação de preços para supermercados.

Atores:
Administrador: Responsável por gerenciar o sistema, incluindo a inserção e atualização de dados.
Analista de Vendas: Usuário que utiliza o sistema para visualizar relatórios e análises de vendas.
Gerente de Produto: Usuário que analisa comparações de preços e tendências para tomar decisões estratégicas.

Casos de Uso:

CU01: Importar Dados de Vendas
Ator Principal: Administrador , Analista de Vendas, Gerente de Produto
Objetivo: Importar dados de vendas de um arquivo CSV para o banco de dados MySQL.
Pré-condições: O arquivo CSV está no formato correto e acessível.
Pós-condições: Os dados de vendas são armazenados na tabela Vendas do banco de dados.
Fluxo Principal:
Administrador seleciona a opção "Importar Dados de Vendas".
Sistema solicita o upload do arquivo CSV.
Administrador seleciona o arquivo CSV e confirma a importação.
Sistema valida o formato e os dados do arquivo.
Sistema insere os dados na tabela Vendas do banco de dados MySQL.
Sistema notifica o Administrador sobre o sucesso da operação.

CU02: Importar Dados de Preços
Ator Principal: Administrador , Analista de Vendas, Gerente de Produto
Objetivo: Importar dados de preços de um arquivo CSV para o banco de dados MySQL.
Pré-condições: O arquivo CSV está no formato correto e acessível.
Pós-condições: Os dados de preços são armazenados na tabela Preços do banco de dados.
Fluxo Principal:
Administrador seleciona a opção "Importar Dados de Preços".
Sistema solicita o upload do arquivo CSV.
Administrador seleciona o arquivo CSV e confirma a importação.
Sistema valida o formato e os dados do arquivo.
Sistema insere os dados na tabela Preços do banco de dados MySQL.
Sistema notifica o Administrador sobre o sucesso da operação.

CU03: Visualizar Análises de Vendas
Ator Principal: Analista de Vendas , Gerente de Produto , Administrador
Objetivo: Visualizar relatórios e dashboards de análise de vendas no Power BI.
Pré-condições: Dados de vendas foram importados e estão atualizados.
Pós-condições: Analista de Vendas obtém insights através dos relatórios e dashboards.
Fluxo Principal:
Analista de Vendas acessa o dashboard no Power BI.
Sistema exibe o painel de controle com gráficos e métricas de vendas.
Analista de Vendas utiliza filtros para personalizar a visualização dos dados.
Sistema atualiza os gráficos e métricas conforme os filtros aplicados.
Analista de Vendas analisa os dados e gera relatórios conforme necessário.

CU04: Comparar Preços por Período
Ator Principal: Gerente de Produto , , Analista de Vendas, Administrador
Objetivo: Comparar preços de produtos entre diferentes períodos utilizando o Power BI.
Pré-condições: Dados de preços foram importados e estão atualizados.
Pós-condições: Gerente de Produto obtém insights sobre a variação de preços ao longo do tempo.
Fluxo Principal:
Gerente de Produto acessa o dashboard no Power BI.
Sistema exibe o painel de controle com gráficos de comparação de preços.
Gerente de Produto seleciona os períodos para comparação.
Sistema atualiza os gráficos com as variações de preços entre os períodos selecionados.
Gerente de Produto analisa os dados e toma decisões estratégicas baseadas nas informações apresentadas.
 
. 


Arquitetura do Software e Tecnologias Utilizadas:

O software será desenvolvido seguindo uma arquitetura cliente-servidor, onde o Power BI atuará como cliente para visualização de dados, e o MySQL como servidor para armazenamento e gerenciamento dos dados de vendas. A comunicação entre o Power BI e o MySQL será realizada por meio de consultas SQL , Para Controle de Acesso e Clientes / usuários será utilizada uma tela em PHP 8+ com gestão e controle de algumas funcionalidades. As principais tecnologias utilizadas incluem:

PHP 8+: Controle de Acesso aos  Usuários / Clientes e com Gestão Financeira das Contas  ADMIN e Cliente.
Power BI: Ferramenta de visualização de dados da Microsoft.
MySQL: Sistema de gerenciamento de banco de dados relacional.
Linguagens de Programação: SQL para consultas ao banco de dados e DAX para expressões de análise de dados no Power BI, PHP para Gestao de Segurança e Gestão Financeira de Clientes.
Telas e Códigos-fonte
A seguir são apresentadas algumas telas do sistema  relevantes :
 
Tela de Acesso ao ADMIN do Sistema.
 
Tela Para Acesso do Cliente / Usuário ou para se Cadastrar
 
Tela Inicial para o Cliente acessar o Power BI

 
Arquivo de Importação / Leitura por  Power BI ou PHP

 
Tela Principal de Utilização dos Usuários Finais.

 
Trechos do Código em PHP.

Repositório de Código-fonte, O código-fonte do projeto está disponível no seguinte repositório: link_para_o_repositório.



5. CONSIDERAÇÕES FINAIS
Ao concluir este projeto de pesquisa e Criação de Software, é possível observar os benefícios tangíveis que um sistema de análise de vendas e comparação de preços pode proporcionar aos supermercados. Através da integração entre Power BI e MySQL, foi possível desenvolver uma ferramenta poderosa que oferece insights valiosos para a tomada de decisões estratégicas, melhorando a eficiência operacional e a competitividade no mercado. Os resultados obtidos demonstram a eficácia dessa abordagem, permitindo aos gestores uma visão detalhada do desempenho de vendas, identificação de tendências de mercado e ajuste dinâmico de estratégias de precificação.

No entanto, sempre há espaço para melhorias e expansões futuras deste trabalho. Uma possível melhoria seria a incorporação de técnicas avançadas de análise de dados, como machine learning, para previsão de vendas e otimização de preços. Além disso, a inclusão de mais fontes de dados externas, como dados climáticos e sazonais, poderia enriquecer ainda mais as análises realizadas. Por fim, a realização de testes mais abrangentes em ambientes reais de supermercados poderia validar ainda mais a eficácia e relevância deste sistema.

Em suma, este trabalho abre portas para uma série de possibilidades de melhoria e continuação, visando sempre aprimorar a gestão e o desempenho dos supermercados no mercado competitivo atual.










REFERÊNCIAS BIBLIOGRÁFICAS
A parte Power BI foi desenvolvida com base no curso feito na DIO ; Disponível em:
<https://web.dio.me/course/coleta-e-extracao-de-dados-com-power-bi/learning/0ed1f1c5-601d-402b-9230-eccb791a184d?back=/track/formacao-power-bi-analyst&tab=undefined&moduleId=undefined> Acesso em: 21 jun. 2024.

Modelo que serviu de Base para a Parte PHP:
SILVA, R. RamonSilva20/mapos. Disponível em: <https://github.com/RamonSilva20/mapos>. Acesso em: 21 jun. 2024.




