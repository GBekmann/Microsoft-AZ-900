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

## Tipos de Seviços de computação em Nuvem

Dentro da nuvem, temos três modelos de serviços disponibilizados com base na computação em nuvem, estes são:

# **IaaS (Infrastructure as a Service)**
# **IaaS (Infrastructure as a Service)**
# **IaaS (Infrastructure as a Service)**

Quando nos referimos a Infraestrutura como serviço, estamos nos referindo a infra-estrutura de hardware. Ou seja, Estamos utilizando recursos referentes a processamento e armazenamento.

Podemos citar exemplos como criação de VMs na Azure ou armazenamento utilizando o OneDrive

***

**SaaS (Software as a Service)**

Quando nos referimos a SaaS

**PaaS (Platform as a Service)**


> Esses Data Centers disponibilizam não só uma equipe especializada na manutenção física dos servidores, como também dispõem de uma infraestrutura totalmente preparada para garantir o melhor funcionamento dos sistemas, assegurando sempre sua plena operação.

***

## Modelos de nuvem
Atualmente, temos três modelos de nuvem comumente utilizados pelas empresas:

>### Nuvem Privada (On-Premise)
>
>Este modelo refere-se a servidores físicos instalados dentro da própria empresa. Suas principais características são:
>
>*   As organizações criam um ambiente de nuvem em seu próprio datacenter.
>*   As organizações são responsáveis por operar os serviços que fornecem.
>*   Não fornece acesso a usuários fora da organização.
>*   Maior custo inicial, porém, após implementada, basta realizar manutenções quando necessário.

>### Nuvem Pública
>
>A **nuvem pública** consiste em uma plataforma gerenciada online, na qual é possível não apenas armazenar grandes quantidades de dados, mas também hospedar serviços e implementar políticas de segurança nos dispositivos.
>
>*   Pertence a provedores de serviços de nuvem ou hosting.
>*   Fornece recursos e serviços a várias organizações e usuários.
>*   É acessada via conexão de rede segura (geralmente pela internet).
>*   Possui uma vasta quantidade de ferramentas próprias concedidas pelo provedor (firewalls, MDMs, sistemas de análise de dados, acesso a aplicações do ecossistema etc.).
>*   Custo sob demanda.

 Toda a parte de manutenção fica a cargo do provedor do serviço de nuvem.

>### Nuvem Híbrida
>
>A **nuvem híbrida** consiste na adoção dos dois tipos de nuvem citados acima: privada e pública. Resumidamente, junta o melhor dos dois mundos.
>
>*   Maior escalabilidade sob demanda.
>*   Melhor gestão de recursos.
>*   Interoperabilidade.
>*   Custo variável.

>### Multi-Cloud
>
>O conceito de **multi-cloud** tem sido cada vez mais adotado por empresas de grande porte, que utilizam mais de um tipo de nuvem pública para hospedar seus dados. Apesar da complexidade na implementação, oferece maior redundância.
>
>*   Maior complexidade.
>*   Menor downtime (se um serviço falhar, outro assume).
>*   Maior custo.

***

## Custos Operacionais (CapEx & OpEx)

Dentro das possibilidades de implementação de nuvem, é importante entender os tipos de despesas:

>### CapEx (Capital Expenditure)
>
>O termo **CapEx** significa **Despesas de Capital** e refere-se aos gastos de uma empresa para aquisição, melhoria ou manutenção de um ativo fixo por longo prazo.
>
>Principais características:
>
>*   Custos iniciais elevados.
>*   Exige tempo para implementação e para o investimento tornar-se operacional.
>*   São investimentos estratégicos e visam o longo prazo.
>*   Custos operacionais tendem a diminuir com o tempo.
>*   Ideal para aquisição, melhorias ou expansões.
>
>No contexto de computação em nuvem, o **CapEx** representa o investimento necessário para construir a infraestrutura física de um servidor privado. É um custo elevado no início, mas tende a reduzir os gastos operacionais ao longo do tempo.

>### OpEx (Operational Expenditure)
>
>O termo **OpEx** refere-se às **despesas operacionais**, como assinaturas de licenças e outros custos recorrentes (salários, seguros, contas etc.).
>
>Principais características:
>
>*   Não é um ativo, mas sim uma despesa.
>*   Custos recorrentes e, em alguns casos, variáveis.
>*   Geralmente exige menos tempo para tornar-se operacional.
>
>No contexto de computação em nuvem, representa os custos da utilização das plataformas, que costumam cobrar mensalmente conforme os recursos utilizados.
>
***

# Benefícios da Nuvem

Quando falamos sobre nuvem, especialmente nuvens públicas, é inegável que elas oferecem um conjunto robusto de funcionalidades e ferramentas, tornando sua implementação uma vantagem significativa para empresas e profissionais de TI.

## 1. Alta Disponibilidade

Os serviços em nuvem possuem estrutura voltada para manter os sistemas sempre operacionais, seguindo práticas para mitigar impactos em casos de indisponibilidade.

Por padrão, as provedoras de nuvem tendem a ter contratos e uma série de padrões:

>###  SLA (Service Level Agreement) e Créditos
>
>*   Os contratos incluem um **SLA**, que define a disponibilidade garantida (ex.: 99,9%).
>*   Se o provedor não cumprir, a provedora oferece créditos financeiros ou descontos (apenas em serviços voltados a nuvem).
>*   Exemplo: Em caso do servidor ficar indisponível por um tempo que passe do estimado no contrato de SLA, a provedora concede uma bonificação generosa de crédito como compensação.

>### Comunicação e Transparência
>
>*   O provedor envia alertas e relatórios sobre incidentes.
>*   Publica atualizações em **status pages** (ex.: status.aws.amazon.com).
>*   Em casos críticos, pode haver contato direto com clientes corporativos.

>### Recuperação e Continuidade
>
>*   Ativação de planos de contingência para restaurar serviços rapidamente.
>*   Uso de redundância geográfica para minimizar impacto.
>*   Em alguns casos, migração temporária para outra região.

>### Suporte Técnico Prioritário
>
>*   Clientes com planos premium recebem suporte dedicado durante incidentes.
>*   Pode incluir engenheiros especializados para ajudar na mitigação.

>### Relatório Pós-Incidente
>
>*   Após normalização, o provedor envia um relatório explicando:
>       -  Causa raiz do problema
>       -  Medidas corretivas para evitar recorrência
***

## 2. Escalabilidade

Capacidade de aumentar ou reduzir recursos conforme a demanda, garantindo desempenho e eficiência.

## 3. Elasticidade
A elasticidade refere-se a quando há um salto repentino acentuado na demanda, os recursos implantados podem ser expandidos(automaticamente ou manualmente).

Da mesma forma que os recursos podem ser expandidos, eles também podem ser reduzidos(automaticamente ou manualmente).

## 4. Confiabilidade

Devido ao design da nuvem ser descentralizado, isto é, ser disponibilizada em diversos locais. Acaba que sua infraestrutura oferece bastante confiabilidade e resiliência.

Pelo fato de seu design ser descentralizado, a nuvem nos permite a implantação de recursos em várias regiões do mundo.

## 5. Previsibilidade

A nuvem oferece muita previsibilidade, devido a não só o acompanhamento real de custo operacional da plataforma, como também o desempenho que possuí escalabilidade.
Mas sua previsibilidade também é bastante influenciada pelo **Microsoft Azure-Well-Architected Framework.**

## 6. Segurança
A nuvem oferece diversas ferramentas relacionadas a segurança, estas vão desde sistemas para autorizar/autenticar o acesso de usuários a até complexos sistemas de proteção em tempo real nos dispositivos…

Podemos citar alguns exemplos como:

>### Entra ID (Antigo Active Directory)
>
>Sistema de autenticação/autorização de usuários do qual ajuda a proteger o acesso a aplicativos e recursos da Azure.
>
>A implementação não fica a cargo da Microsoft, cabendo a nós gestores/administradores, realizar a implementação.

>### Microsoft Defender
>
>O Defender implementado na Azure oferece diversas ferramentas relacionadas à detecção de ameaças, integração com DevOps e gerenciamento de posturas de segurança.

>### Microsoft Intune
>
>O Intune é a ferramenta responsável pelo gerenciamento de ponto de extremidade baseado em nuvem.
>
>Basicamente, é por ele que podemos implementar políticas de segurança nas máquinas. Privando os usuários de realizar ajustes inesperados ou até de instalar softwares/arquivos suspeitos.
>
>Podemos também realizar diagnósticos no dispositivo e até gerenciar em massa a implementação de atualizações, ajustes e diagnósticos…

Temos também a possibilidade de realizar a implementação de Firewalls no ambiente de nuvem e também realizar a implementação de uma VPN.
***
## 7. Governança

A auditoria baseada em nuvem nos ajuda a determinar responsáveis para a administração do ambiente em nuvem. 

Disponibilizando conjuntamente, ferramentas para diagnosticar se o ambiente como um todo está seguindo os padrões definidos pela auditoria e também, nos disponibilizando ferramentas e estratégias para mitigação de recursos fora de conformidade.

A plataforma também, dispõe de inúmeras automações que possam nos auxiliar na padronização de gestão da nuvem.
***
## 8. Gerenciabilidade

Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem. 

Estes são:

>### Gerenciamento da nuvem
>
>O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Na nuvem, você pode:
>
>- Escalar automaticamente a implantação de recursos com base na necessidade.
>- Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
>- Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
>- Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real.

>### Gerenciamento na nuvem
>
>Diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Podemos gerencia-los por meio de:
>
>- Por meio de um portal da Web
>- Usando interface de linha de comando
>- Usando APIs
>- Usando PoweShell

