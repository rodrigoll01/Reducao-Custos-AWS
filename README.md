# Reducao-Custos-AWS
Projeto AWS - Redução de Custos - ACME

Relatório de Implementação de Ferramentas AWS para Redução de Custos na empresa ACME.

Data: [27/072023]
Empresa: ACME 
Responsável: [Rodrigo Lima Cavalcante]

1. Introdução

Este relatório detalha o processo de implementação de três serviços da Amazon Web Services (AWS), realizado por [Rodrigo Lima Cavalcante] para alcançar a redução de custos imediatos na empresa [ACME]. Os serviços selecionados foram cuidadosamente escolhidos com base em sua relevância técnica e potencial para otimizar os gastos relacionados à infraestrutura de TI, garantindo eficiência operacional e resultados econômicos positivos.

2. Análise da Infraestrutura Atual

Antes de prosseguir com a seleção dos serviços AWS, realizamos uma análise detalhada da infraestrutura de TI existente na empresa. Identificamos os recursos e serviços em uso, bem como os custos associados a cada um deles. A análise revelou ineficiências, subutilização de recursos e gastos desnecessários em várias áreas.

3. Seleção dos Serviços AWS

Com base na análise da infraestrutura existente, selecionamos os três serviços da AWS a seguir, considerando sua capacidade de impactar positivamente os custos imediatamente:

a) Amazon EC2 (Elastic Compute Cloud)

Descrição Técnica: O Amazon EC2 oferece recursos de computação escaláveis na nuvem. Ele permite que os usuários lancem instâncias de servidores virtualizados, permitindo a seleção de tipo de instância, sistema operacional, armazenamento e outros recursos personalizáveis.

Motivo da Escolha: Identificamos que a empresa mantém servidores locais subutilizados e, muitas vezes, ociosos durante certos períodos do dia. A implementação do Amazon EC2 permitirá migrar cargas de trabalho para a nuvem, onde poderemos ajustar dinamicamente a capacidade de acordo com a demanda, reduzindo, assim, os custos operacionais e evitando gastos de capital associados à aquisição de novos servidores. Além disso, a possibilidade de escolher instâncias sob demanda ou instâncias reservadas nos permitirá otimizar ainda mais os gastos.

b) AWS Lambda

Descrição Técnica: O AWS Lambda é um serviço de computação serverless que permite executar código sem a necessidade de gerenciar servidores. Ele responde a eventos definidos pelo usuário e dimensiona automaticamente a capacidade computacional conforme a demanda.

Motivo da Escolha: Observamos que a empresa mantém vários aplicativos e processos em execução contínua, mesmo durante períodos de baixa demanda. Ao adotar o AWS Lambda, poderemos executar esses processos de forma eficiente, pagando apenas pelos recursos computacionais efetivamente utilizados. Isso resultará em economia significativa, especialmente quando comparado à manutenção de servidores tradicionais que operam continuamente.

c) Amazon RDS (Relational Database Service)

Descrição Técnica: O Amazon RDS é um serviço gerenciado de banco de dados relacional que oferece suporte a várias engines de banco de dados, como MySQL, PostgreSQL, SQL Server e outros. Ele gerencia tarefas de rotina, como provisionamento, aplicação de patches, backup e recuperação.

Motivo da Escolha: Observamos que a empresa possui um servidor de banco de dados local que requer manutenção regular e atualizações de segurança. Ao migrar para o Amazon RDS, eliminaremos a necessidade de gerenciar fisicamente o servidor, reduzindo a carga operacional da equipe de TI e evitando gastos com hardware e licenciamento de software. Além disso, o Amazon RDS oferece opções de dimensionamento flexíveis, permitindo que a empresa pague apenas pelo armazenamento e recursos de processamento utilizados, o que resultará em economia significativa a longo prazo.

4. Plano de Implementação

O plano de implementação dos serviços AWS selecionados consiste nas seguintes etapas:

a) Avaliação da Migração: Realizar uma avaliação detalhada dos sistemas existentes para determinar a viabilidade técnica da migração para os serviços da AWS selecionados. Identificar possíveis problemas e garantir a compatibilidade com a arquitetura atual.

b) Configuração dos Serviços: Configurar os serviços da AWS conforme as necessidades específicas da empresa. Criar instâncias EC2, funções Lambda e instâncias do Amazon RDS, garantindo uma implementação segura e eficiente.

c) Migração dos Dados: Para os serviços que envolvem migração de dados, elaborar um plano detalhado para transferir os dados existentes do ambiente local para a nuvem, garantindo a integridade e segurança dos dados.

d) Testes e Otimização: Realizar testes abrangentes para garantir o funcionamento correto e eficiente dos serviços implementados. Ajustar e otimizar a configuração, conforme necessário, para alcançar os melhores resultados em termos de redução de custos.

e) Treinamento da Equipe: Proporcionar treinamento adequado à equipe de TI para operar e gerenciar os novos serviços AWS implementados, garantindo a adoção correta e a utilização eficiente das ferramentas.

5. Benefícios Esperados

A implementação dos serviços AWS mencionados neste relatório resultará nos seguintes benefícios para a empresa:

Redução de Custos Imediatos: A migração para a nuvem permitirá reduzir os custos operacionais e de capital associados à manutenção de servidores locais e infraestrutura de TI.

Uso Eficiente de Recursos: Os serviços AWS permitem que a empresa pague apenas pelos recursos computacionais efetivamente utilizados, evitando o desperdício de recursos e otimizando os gastos.

Flexibilidade e Escalabilidade: Com a AWS, a empresa terá a flexibilidade de dimensionar os recursos conforme a demanda, resultando em maior eficiência operacional e custos mais otimizados.

6. Conclusão

A implementação dos serviços AWS selecionados neste projeto é uma estratégia eficiente para a redução de custos imediatos na empresa [Nome da Empresa]. O uso do Amazon EC2, AWS Lambda e Amazon RDS permitirá uma gestão mais inteligente dos recursos de TI, possibilitando a redução de gastos e a otimização do desempenho dos sistemas. A migração para a nuvem e a adoção de soluções serverless representam passos importantes em direção à modernização da infraestrutura de TI, alinhando a empresa com as melhores práticas de mercado.

7. Recomendações

Além dos serviços AWS selecionados, recomendamos que a empresa continue a monitorar regularmente os custos e a utilização dos recursos na plataforma da AWS. O uso de ferramentas como o AWS Cost Explorer e o AWS Trusted Advisor auxiliará na identificação contínua de oportunidades de otimização e economia de custos.

Referências

[https://aws.amazon.com/pt/ec2/]

[https://aws.amazon.com/pt/lambda/]

[https://aws.amazon.com/pt/rds/]

[Rodrigo Lima Cavalcante - Cloud Engineer]
