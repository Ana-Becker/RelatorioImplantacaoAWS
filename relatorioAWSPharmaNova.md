# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 18/09/2023
Empresa: PharmaNova Labs 
Responsável: Ana Clara R R M Becker

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa PharmaNova Labs, realizado por Ana Clara Becker. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: 
- <u>Amazon S3</u>
- O S3 (Simple Storage Service) é um serviço da AWS para o armazenamento de objetos que oferece um repositório altamente escalável, durável e seguro para armazenar e recuperar dados, chamados de "objetos". O foco principal do Amazon S3 é fornecer armazenamento de objetos de alto desempenho, durabilidade e acessibilidade com a facilidade de uso.
- Ao realizar ensaios clínicos para o desenvolvimento de novos medicamentos é necessário um sistema seguro, durável e escalável (não há preocupação com o tamanho de armazenamento, em adquirir mais espaço) para conseguir armazenar, gerenciar e acessar grandes volumes de dados que incluem informações de pacientes, resultados de testes, imagens médicas e documentação regulatória.
- Vantagens do Amazon S3:
* Existem políticas de controle de acesso e autenticação usando o AWS Identity and Access Management (IAM) para garantir que apenas pessoal autorizado tenha acesso aos dados.
* O Amazon S3 permite a criação de versões de objetos, o que é útil para rastrear mudanças nos dados.
* Os dados são criptografados em repouso por padrão no Amazon S3.
* Existem opções de armazenamento com preços variados, permitindo a otimização de custos com base na frequência de acesso aos dados.

### Etapa 2: 
- <u>Amazon RDS</u>
- O Amazon Relational Database Service (RDS) é uma plataforma de gerenciamento de banco de dados da AWS que oferece uma maneira conveniente e escalável de configurar, operar e dimensionar bancos de dados relacionais. 
- A plataforma contribuirá em muitos aspectos, entre eles o gerenciamento e armazenamento de dados críticos de pesquisa e ensaios clínicos de maneira segura, escalável e altamente disponível, nos permitindo avançar na pesquisa e desenvolvimento de medicamentos com eficiência e conformidade regulatória.
- Recursos vantajosos do RDS:
* Todos os dados clínicos como informações de pacientes, resultados de testes, dados de ensaios clínicos e registros de medicamentos em teste, serão armazenados no banco de dados do Amazon RDS.
* A empresa poderá utilizar ferramentas de monitoramento da AWS, como o Amazon CloudWatch, para acompanhar o desempenho do banco de dados, detectar anomalias e otimizar consultas SQL para melhorar a eficiência.
* À medida que os projetos de pesquisa avançam e a quantidade de dados aumenta, a empresa poderá facilmente dimensionar verticalmente ou horizontalmente o banco de dados usando as capacidades de dimensionamento do Amazon RDS, garantindo desempenho consistente.
* O Amazon RDS pode ser configurado de acordo com as regulamentações específicas do setor farmacêutico, garantindo conformidade com padrões rigorosos de segurança e privacidade de dados, como o HIPAA (Health Insurance Portability and Accountability Act).
* Os cientistas, pesquisadores e equipe de desenvolvimento têm acesso rápido e seguro aos dados em tempo real para análise, relatórios e tomada de decisões críticas.

### Etapa 3: 
- <u>Amazon Comprehend Medical</u>
- É um serviço de processamento de linguagem que usa machine learning para entender e extrair automaticamente dados de saúde de textos médicos como prescrições, procedimentos ou diagnósticos.
- Com este serviço conseguimos identificar de maneira rápida e eficiente os efeitos adversos de testes de produtos farmacêuticos para assim acelerar a análise de ensaios clínicos, melhorar a segurança dos medicamentos e atender aos requisitos regulatórios.



## Conclusão
A implementação de ferramentas na empresa PharmaNova Labs tem como esperado *a inovação, a eficiência e a segurança nas operações da empresa, acelerando seu progresso na pesquisa, desenvolvimento e entrega de tratamentos médicos inovadores*. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


## Anexos

[[PPT]()] 

[https://aws.amazon.com/pt/s3/?nc2=type_a]
[https://aws.amazon.com/pt/health/?nc2=h_ql_sol_ind_hcl]
[https://aws.amazon.com/pt/blogs/aws/amazon-comprehend-medical-natural-language-processing-for-healthcare-customers/]
[https://aws.amazon.com/pt/quicksight/]
[https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html]



Assinatura do Responsável pelo Projeto:

Ana Clara R R M Becker