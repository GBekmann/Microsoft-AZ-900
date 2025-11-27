# Resumo do Curso AZ-900

## Contexto deste repositório

Resumo dos temas já abordados no curso **Formação Microsoft AZ-900 Certification**, cedido pela Digital Innovation One.

## A origem da computação em nuvem

Antigamente, empresas que precisavam trabalhar com grandes quantidades de documentos e dados tinham que realizar investimentos significativos para criar um servidor próprio para armazenar essa grande quantidade de informações.

Com o passar do tempo, as demandas dessas empresas cresciam constantemente, tornando necessários grandes investimentos em equipamentos, infraestrutura e instalação de novos servidores.

Como resposta às dificuldades relacionadas à escalabilidade desses servidores, surgiu a **Computação em Nuvem (Cloud Computing)**.

***

## Cloud Computing

Consiste em servidores e recursos de hardware disponibilizados de forma virtual e acessados pela internet. Esses servidores ficam localizados em grandes Data Centers especializados e distribuídos mundialmente.

> Esses Data Centers disponibilizam não só uma equipe especializada na manutenção física dos servidores, como também dispõem de uma infraestrutura totalmente preparada para garantir o melhor funcionamento dos sistemas, assegurando sempre sua plena operação.

***

### Modelos de nuvem

Atualmente, temos três modelos de nuvem comumente utilizados pelas empresas:

***

### Nuvem Privada (On-Premise)

Este modelo refere-se a servidores físicos instalados dentro da própria empresa. Suas principais características são:

*   As organizações criam um ambiente de nuvem em seu próprio datacenter.
*   As organizações são responsáveis por operar os serviços que fornecem.
*   Não fornece acesso a usuários fora da organização.
*   Maior custo inicial, porém, após implementada, basta realizar manutenções quando necessário.

***

### Nuvem Pública

A **nuvem pública** consiste em uma plataforma gerenciada online, na qual é possível não apenas armazenar grandes quantidades de dados, mas também hospedar serviços e implementar políticas de segurança nos dispositivos.

*   Pertence a provedores de serviços de nuvem ou hosting.
*   Fornece recursos e serviços a várias organizações e usuários.
*   É acessada via conexão de rede segura (geralmente pela internet).
*   Possui uma vasta quantidade de ferramentas próprias concedidas pelo provedor (firewalls, MDMs, sistemas de análise de dados, acesso a aplicações do ecossistema etc.).
*   Custo sob demanda.

> Toda a parte de manutenção fica a cargo do provedor do serviço de nuvem.

***

### Nuvem Híbrida

A **nuvem híbrida** consiste na adoção dos dois tipos de nuvem citados acima: privada e pública. Resumidamente, junta o melhor dos dois mundos.

*   Maior escalabilidade sob demanda.
*   Melhor gestão de recursos.
*   Interoperabilidade.
*   Custo variável.

***

### Multi-Cloud

O conceito de **multi-cloud** tem sido cada vez mais adotado por empresas de grande porte, que utilizam mais de um tipo de nuvem pública para hospedar seus dados. Apesar da complexidade na implementação, oferece maior redundância.

*   Maior complexidade.
*   Menor downtime (se um serviço falhar, outro assume).
*   Maior custo.

***

## Custos Operacionais (CapEx & OpEx)

Dentro das possibilidades de implementação de nuvem, é importante entender os tipos de despesas:

***

### CapEx (Capital Expenditure)

O termo **CapEx** significa **Despesas de Capital** e refere-se aos gastos de uma empresa para aquisição, melhoria ou manutenção de um ativo fixo por longo prazo.

Principais características:

*   Custos iniciais elevados.
*   Exige tempo para implementação e para o investimento tornar-se operacional.
*   São investimentos estratégicos e visam o longo prazo.
*   Custos operacionais tendem a diminuir com o tempo.
*   Ideal para aquisição, melhorias ou expansões.

No contexto de computação em nuvem, o **CapEx** representa o investimento necessário para construir a infraestrutura física de um servidor privado. É um custo elevado no início, mas tende a reduzir os gastos operacionais ao longo do tempo.

***

### OpEx (Operational Expenditure)

O termo **OpEx** refere-se às **despesas operacionais**, como assinaturas de licenças e outros custos recorrentes (salários, seguros, contas etc.).

Principais características:

*   Não é um ativo, mas sim uma despesa.
*   Custos recorrentes e, em alguns casos, variáveis.
*   Geralmente exige menos tempo para tornar-se operacional.

No contexto de computação em nuvem, representa os custos da utilização das plataformas, que costumam cobrar mensalmente conforme os recursos utilizados.

***

# Benefícios da Nuvem

Quando falamos sobre nuvem, especialmente nuvens públicas, é inegável que elas oferecem um conjunto robusto de funcionalidades e ferramentas, tornando sua implementação uma vantagem significativa para empresas e profissionais de TI.

***

### **1. Alta Disponibilidade**

Os serviços em nuvem possuem estrutura voltada para manter os sistemas sempre operacionais, seguindo práticas para mitigar impactos em casos de indisponibilidade.

Por padrão, as provedoras de nuvem tendem a ter contratos e uma série de padrões. Estes são

 SLA (Service Level Agreement) e Créditos

*   Os contratos incluem um **SLA**, que define a disponibilidade garantida (ex.: 99,9%).
*   Se o provedor não cumprir, A provedora oferece créditos financeiros ou descontos (Apenas em serviços voltados a nuvem).
*   Exemplo: Um exemplo que podemos citar é no caso do servidor ficar indisponível por um tempo que passe do estimado no contrato de SLA. A provedora concede uma bonificação generosa de crédito como compensação devido ao ocorrido.
***

 Comunicação e Transparência**

*   O provedor envia alertas e relatórios sobre incidentes.
*   Publica atualizações em **status pages** (ex.: status.aws.amazon.com).
*   Em casos críticos, pode haver contato direto com clientes corporativos.

***

 Recuperação e Continuidade**
git
*   Ativação de planos de contingência para restaurar serviços rapidamente.
*   Uso de redundância geográfica para minimizar impacto.
*   Em alguns casos, migração temporária para outra região.

***

 Suporte Técnico Prioritário**

*   Clientes com planos premium recebem suporte dedicado durante incidentes.
*   Pode incluir engenheiros especializados para ajudar na mitigação.

***

 Relatório Pós-Incidente**

*   Após normalização, o provedor envia um relatório explicando:
    *   Causa raiz do problema.
    *   Medidas corretivas para evitar recorrência.

***

### **7. Escalabilidade**

Capacidade de aumentar ou reduzir recursos conforme a demanda, garantindo desempenho e eficiência.

***

### **8. Elasticidade**

Refere-se à capacidade de ajustar recursos automaticamente ou manualmente diante de variações repentinas na demanda.

***

