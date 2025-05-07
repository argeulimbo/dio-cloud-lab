# Bradesco Java Cloud Native - Trabalhando com Ambiente Cloud na Azure

## [ Introdução a Computação em Nuvem ]
Neste módulo inicial, introduz conceitos básicos sobre Cloud (nuvem), tais como:
* Modelos de Nuvem: Privada, Pública e Híbrida.
* Domínio de Objetivo: são conjuntos de metas e objetivos para um projeto de nuvem, estabelece sua atuação e o que se espera de resultado deste projeto, de forma resumida, é o planejamento do projeto.
* CAPEX: refere-se ao investimento feito em infraestrutura física inicial com equipamentos para a gestão da nuvem, como hacks, servidor, refrigeração do ambiente, entre outros.
* OPEX: refere-se ao custo operacional, onde em nuvem se dá de forma periódica e seu pagamento já é feito de forma imediata e previamente estabelecido os limites de sua estrutura.

## [Benefícios da Computação em Nuvem]
* Alta disponibilidade
* Escalabidade: Adaptar para recurso específico
* Elasticidade: Se houver esgotamento de recurso, de forma automática (Configurada) ou manual, pode ser possível incluir mais recurso
* Confiabilidade
* Previsibilidade
* Segurança: o modelo de segurança relaciona-se com o gerenciamento de acesso por exemplo
* Governança: auditoria de nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com os padrões do projeto
* Gerenciabilidade: gerenciar os recursos de nuvem, como escalar automaticamente a implantação de recursos com base em necessidade -> Por meio do portal / Usando interface de linha de comando / Usando APIs / Usando PowerShell

## [ Tipos de Serviço de Nuvem ]
* IaaS - Infraestrutura como Serviço
  - Servidores e armazenamento
  - Firewalls e segurança de rede
  - Planta física/edifício do datacenter 
  - Serviço de nuvem mais flexível
  - Configura e gerencia o hardware para o aplicativo

* PaaS - Plataforma como Serviço
  - Sistemas Operacionais
  - Ferramentas para desenvolvedores, análise de negócios de gerenciamento de database
  - Fornece ambiente para criação, teste e implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente
  - Focado no desenvolvimento de Aplicativos
  - O gerenciamento de plataforma é realizado pelo provedor de nuvem

* SaaS - Software como Serviço
  - Aplicativos/Apps Hospedados
  - A aplicação já existe, já sabemos o que ela entrega
  - Os usuários se conectam e usam aplicativos com base em nuvem pela internet: Microsoft Office 365, email e calendários
  - Modelo de preço de pagamento conforme o uso - licença de uso
  - Usuários pagam pelo software que utilizam em um modelo de assinatura

[ Componentes de Arquitetura do Azure ]
* Regiões 
  - São compostas de um ou mais datacenters muito próximos
  - Fornecem flexibilidade e escala para reduzir a latência do cliente
  - Preservam a residência dos dados com uma oferta abrangente de conformidade

* Zonas de disponibilidade
  - Fornece proteção contra tempo de inatividade devido falha do datacenter
  - Separe fisicamente os datacenters dentro da mesma região
  - Cada datacenter é equipado com alimentação, resfriamento e rede independentes

* Pares de Região
  - Mínimo de 300 milhas de separação entre pares de regiões 
  - Replicação automática para alguns serviços
  - Recuperação de região priorizada em caso de interrupção
  - https://aka.ms/PairedRegions-ptb

* Regiões Soberanas do Azure
  [Serviços Governamentais dos EUA]
   - Atende às necessidades de segurança e conformidade das agências federais, governos estaduais e locais dos EUA e seus provedores de soluções
   - Instância separada do Azure

  [Azure China]
   - Operada pela 21Vianet, instância fisicamente separada dos serviços de nuvem do Azure
   - Todos os dados permanecem dentro da China por conformidade
   
* Recursos do Azure
  - Componentes como: armazenamento, máquinas virtuais, redes, funções, bancos de dados sql, serviços e aplicativos
  - É um contêiner que usa para gerenciar e agregar recursos em uma única unidade

* Assinaturas Azure
  - Desenvolvimento
  - Teste
  - Produção

  [ Computação e Rede na Azure ]

* Tipos de Computação
  - Azure como máquinas virtuais (VMs) sendo emulações de software de computadores físicos
  - Inclui processador virutal, memória, armazenamento e rede
  - Oferta de IaaS que oferece personalização e controle total

* Redes Virtuais
  - Área de trabalho virtual
  - Reduz risco de que o recurso seja deixado para trás
  - Implatanções reais de várias sessões
 
* Serviços de Contêineres do Azure
  - Ambiente leve e virutalizado
  - Não exige gerenciamento do sistema operacional
  - Pode responder a alterações sob demanda

* Contêineres
  - Ambiente leve e em miniatura adequado para execução de microsserviços
  - Projetado para escalabilidade e resiliência por meio da orquestração
  - Aplicativos e serviços são empacatados em um contêiner que fica na parte superior do SO do host

* Azure Functions
  - PaaS que dá suporte a operçaões de computação sem servidor 
  - Código baseado em eventos é executado quando chamado, sem exigir uma infraestrutura de servidor durante períodos inativos (REST)

* Máquinas Virtuais (VM)
  - Suporte a ambientes Windows ou Linux
  - Útil para migrações de lift-and-shift para nuvem

[ Identidade, Acesso e Segurança ]
* Microsoft Entra ID - serviço de gerenciamento de identidades e acesso baseado em nuvem do Microsoft Azure
  - Autenticação
  - Logon único (SSO)
  - Gerenciamento de aplicativos
  - Negócios para Negócios (B2B)
  - Gerenciamento de dispositivos
    
* Autenticação
  - Identifica pessoa ou serviço buscando acesso a um recurso
  - Solicita credenciais de acesso legítimo
    
* Autorização
  - Determina nível de acesso da pessoa ou serviço
  - Define quais dados pode acessar e o que pode fazer com eles
    
* Autenticação Multifator (MFA)
  - Segurança adicional
  - Autenticação em 2 fatores ou mais
  - Relacionamento -> Algo que você sabe <> algo que você possui <> Algo que você é
    
* Acesso Condicional
  - Associação de usuário ou grupo
  - Local do IP
  - Dispositivo
  - Aplicativo
  - Detecção de risco



### Social Media
* Instagram: https://www.instagram.com/argeu.souza
* My GitHub: https://www.github.com/argeulimbo
* Linkedin: https://www.linkedin.com/in/argeu-phelipe-de-souza-40053a227/
