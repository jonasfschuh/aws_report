# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 15 de setembro de 2024

Empresa: Lecter Industries 

Contexto: Lecter Industries possui uma matriz e duas filiais. Esse projeto demonstra a utilização dos serviços iniciais da Amazon Web Services utilizar para interligar a rede e rodas os aplicativos de toda empresa.
Responsável: Jonas Fernando Schuh

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Lecter Industries, realizado por Jonas Fernando Schuh. 
O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: Configuração de Rede com AWS Virtual Private Cloud (VPC)
- Nome da ferramenta: AWS Virtual Private Cloud (VPC)
- Foco da ferramenta: Criação de uma rede privada segura e escalável.
- Descrição de caso de uso: Configurar uma VPC que interligue a matriz e as duas filiais, criando sub-redes específicas para cada unidade. Utilizar VPN ou AWS Direct Connect para conectar a rede local de cada filial à VPC na nuvem, garantindo comunicação segura entre todas as unidades.

Etapa 2: Gerenciamento de Identidade e Acesso com AWS Identity and Access Management (IAM)
- Nome da ferramenta: AWS Identity and Access Management (IAM)
- Foco da ferramenta: Controle de acesso e gerenciamento de identidade.
- Descrição de caso de uso: Implementar políticas de segurança e controle de acesso para usuários e aplicativos, assegurando que apenas pessoas autorizadas tenham acesso aos recursos específicos de acordo com suas funções. Definir papéis e permissões para acesso a aplicativos e dados críticos, centralizando a gestão de identidade para todas as unidades da empresa.

Etapa 3: Hospedagem de Aplicativos com AWS Elastic Beanstalk
- Nome da ferramenta: AWS Elastic Beanstalk
- Foco da ferramenta: Desdobramento e gerenciamento simplificado de aplicativos.
- Descrição de caso de uso: Utilizar o Elastic Beanstalk para hospedar e gerenciar os aplicativos da Lecter Industries, garantindo alta disponibilidade e escalabilidade automática.
- Integrar com outras ferramentas da AWS, como RDS para banco de dados e S3 para armazenamento, garantindo um ambiente robusto para o funcionamento dos sistemas da empresa.

## Conclusão
A implementação de ferramentas na empresa Lecter Industries tem como esperado benefícios dessa ferramentas, o que aumentará a eficiência e a produtividade da empresa. 
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

### Benefícios Resumidos das Ferramentas:
- AWS VPC: Garante uma rede segura e personalizada, interligando matriz e filiais de forma eficiente e escalável.
- AWS IAM: Oferece controle granular de acesso, garantindo que apenas usuários autorizados acessem recursos específicos, melhorando a segurança.
- AWS Elastic Beanstalk: Simplifica o gerenciamento de aplicativos, reduzindo a necessidade de operações manuais e permitindo rápida adaptação a mudanças de demanda.

### Comparativo de Redução nos Custos Financeiros:
- Redução de Infraestrutura Local: A utilização da AWS elimina a necessidade de servidores físicos e infraestrutura de rede local complexa, reduzindo significativamente os custos de manutenção, eletricidade e espaço físico.
- Escalabilidade Sob Demanda: As ferramentas da AWS permitem escalar recursos automaticamente conforme a necessidade, evitando gastos com capacidade ociosa.
- Menor Custo Operacional: Automação e gerenciamento centralizado diminuem a necessidade de grandes equipes de TI para monitoramento e manutenção, reduzindo custos com pessoal.

### Comparativo financeiro entre um servidor on-premise e os serviços da AWS. 
Se considerou os principais custos envolvidos em ambas as opções. Essa análise incluirá custos iniciais e recorrentes, como hardware, manutenção, eletricidade, suporte, além de custos associados aos serviços da AWS, como uso de instâncias, armazenamento, e tráfego de dados.

1. Custo de Servidor On-Premise
Custos Iniciais:
- Hardware: Compra de servidores físicos, switches, roteadores, firewalls, etc.
  Estimativa: Entre $5.000 a $20.000 USD por servidor, dependendo da capacidade e especificações.
- Infraestrutura: Instalação de racks, cabeamento, sistemas de ar-condicionado e backup de energia (UPS).
  Estimativa: Aproximadamente $5.000 a $15.000 USD.
- Licenciamento de Software: Licenças de sistema operacional, banco de dados, e outros softwares de gestão.
  Estimativa: $1.000 a $5.000 USD por servidor, dependendo dos softwares usados.

Custos Operacionais Anuais:
- Manutenção de Hardware: Substituição de componentes, reparos e upgrades de hardware.
  Estimativa: Cerca de 10-15% do custo inicial de hardware por ano ($500 a $3.000 USD).
- Eletricidade: Consumo de energia elétrica dos servidores e sistemas de resfriamento.
  Estimativa: Entre $1.000 a $2.500 USD por servidor por ano.
- Custos de Pessoal: Equipe de TI para manutenção, monitoramento e gerenciamento.
  Estimativa: $30.000 a $60.000 USD por ano (para uma equipe mínima).
- Suporte e Garantia: Planos de suporte e garantia adicionais para o hardware.
  Estimativa: Cerca de $1.000 a $3.000 USD por ano.

Total Estimado para Servidor On-Premise (5 anos):
  Custo Total (5 anos): Aproximadamente $70.000 a $150.000 USD (considerando todos os fatores mencionados).

2. Custo dos Serviços AWS
Custos Iniciais:
- Infraestrutura: Não há custos iniciais significativos, pois a infraestrutura é gerenciada pela AWS.
- Custos Operacionais Anuais:
  Instâncias EC2 (Elastic Compute Cloud): Para rodar servidores equivalentes a um servidor on-premise.
  Estimativa: Instância do tipo t3.medium (para workloads leves): Aproximadamente $500 a $1.000 USD/ano. Instância m5.large (para workloads mais intensivas): Cerca de $1.800 a $3.600 USD/ano.
- Armazenamento (S3 e EBS): Armazenamento de dados e backups.
  Estimativa: Aproximadamente $200 a $1.000 USD/ano, dependendo do volume de dados.
- Tráfego de Dados (Data Transfer): Custos associados à transferência de dados entre a AWS e a internet.
  Estimativa: $100 a $500 USD/ano, dependendo da quantidade de dados trafegados.
- Serviços Adicionais (VPC, IAM, Elastic Beanstalk): Custos variáveis baseados em uso.
  Estimativa: Geralmente incluído no custo das instâncias e do armazenamento ou valores baixos ($100-200 USD/ano).

Total Estimado para AWS (5 anos):
  Custo Total (5 anos): Aproximadamente $15.000 a $30.000 USD (para pequenas e médias empresas com uso moderado).
  
3. Comparativo de Redução de Custos:
Servidor On-Premise (5 anos): $70.000 a $150.000 USD
AWS (5 anos): $15.000 a $30.000 USD

Conclusão do Comparativo Financeiro:
- A opção da AWS oferece uma redução potencial de 60% a 80% nos custos totais ao longo de 5 anos, principalmente devido à eliminação dos altos custos iniciais de hardware e infraestrutura, além da flexibilidade e escalabilidade oferecidas pelo modelo de pagamento conforme o uso.
- Essa economia pode ser ainda maior se considerarmos a agilidade na implementação, a facilidade de manutenção e o ganho em produtividade da equipe de TI, que não precisará se preocupar com a gestão física dos servidores.

Esse plano deve proporcionar uma infraestrutura eficiente, segura e com custos mais baixos para a Lecter Industries.

Assinatura do Responsável pelo Projeto:
Jonas Fernando Schuh
