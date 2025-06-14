# Fisio-Digital
![Logo da empresa](imagens/logo.png)

Aplicação web de fisioterapia para auxiliar na marcação de consultas e atualização de fichas de avaliação, criada com o objetivo de facilitar as avaliações no Centro de Práticas da Uniceplac, este site promete agilizar os atendimentos, dar um fim em fichas fisicas preenchidas manualmente e facilitar cada vez mais o trabalho dos fisioterapeutas. 

## Justificativa e Necessidade de Negócio

Uma análise criteriosa do fluxo de atendimentos de fisioterapia no Centro de Práticas da Uniceplac identificou dificuldades significativos no processo atual. O sistema que eles possuem atualmente, baseado integralmente em registros manuais em papel, resulta em ineficiências operacionais, como atrasos na recuperação de informações, retrabalho para preenchimento e consolidação de dados, e risco de perda de informações críticas. Essa metodologia compromete a agilidade e a qualidade dos atendimentos, além de limitar o conforto e a produtividade dos fisioterapeutas envolvidos. A digitalização e automação são essenciais para modernizar o serviço, garantir a integridade dos dados e otimizar a experiência de alunos, professores e pacientes.

# Descrição do Escopo do Produto

Desenvolver e implantar uma plataforma web centralizada para a gestão completa dos atendimentos de fisioterapia, desde o agendamento de consultas até o acompanhamento contínuo da evolução do paciente, garantindo segurança, acessibilidade e eficiência.

### Objetivos Específicos

- **Otimizar o Agendamento:** Implementar um sistema de agendamento online intuitivo para pacientes e fisioterapeutas.  
- **Centralizar a Documentação do Paciente:** Criar um prontuário eletrônico seguro para upload, armazenamento e atualização de laudos e fichas de acompanhamento.  
- **Melhorar a Comunicação e Adesão:** Integrar um sistema de notificações para lembrar pacientes e fisioterapeutas sobre os compromissos, visando reduzir a taxa de faltas.  
- **Aprimorar a Experiência do Usuário (UX):** Desenvolver uma interface clara, intuitiva e responsiva, com perfis de acesso distintos para fisioterapeutas e pacientes.  

### Principais Entregáveis 

- **Plataforma Web Funcional:** Incluindo os seguintes módulos:  
  - **Módulo de Agendamento:** Calendário interativo para marcação, consulta e cancelamento de horários.  
  - **Módulo de Gestão de Pacientes:** Sistema para cadastro de pacientes e gestão de prontuários eletrônicos (laudos, fichas de avaliação e evolução).  
  - **Módulo de Notificações:** Sistema de envio de e-mails e/ou notificações push.  

- **Interfaces de Usuário (UI):**  
  - **Painel do Fisioterapeuta:** Com visualização da agenda, acesso aos prontuários dos pacientes, ferramentas para edição de fichas e dashboard de acompanhamento.  
  - **Portal do Paciente:** Com funcionalidades para agendar consultas, visualizar horários marcados e acessar seu histórico.  

- **Documentação do Projeto:** Manual de usuário para ambos os perfis e documentação técnica do sistema.

### Especificações Técnicas

- **Backend:** PHP  
- **Frontend:** HTML5, CSS3, JavaScript  
- **Banco de Dados:** MySQL  
- **Segurança:** Implementação de criptografia para dados sensíveis e total conformidade com a Lei Geral de Proteção de Dados (LGPD).  
- **Arquitetura:** Níveis de acesso baseados em perfil de usuário.

## Distribuição da Plataforma e Assistência ao Usuário

### Distribuição da Plataforma

A plataforma web será hospedada em um ambiente de nuvem confiável, garantindo alta disponibilidade, escalabilidade e segurança. O sistema estará acessível por meio de navegadores modernos, sem a necessidade de instalação local, permitindo o uso em desktops, tablets e smartphones.

#### Principais características da distribuição:

- **Hospedagem em Nuvem:** Utilização de serviços como AWS, Azure ou DigitalOcean para garantir estabilidade e redundância.
- **Disponibilidade Contínua:** A plataforma será operante 24 horas por dia, 7 dias por semana.
- **Atualizações Automatizadas:** Melhorias e correções serão aplicadas diretamente no ambiente de produção, minimizando a necessidade de intervenção do usuário.
- **Backup Regular:** Rotinas de backup diárias garantirão a segurança e recuperação dos dados em caso de falhas.

### Assistência ao Usuário

Para garantir uma experiência de uso eficiente e sem interrupções, será oferecido suporte técnico aos usuários da plataforma, com diferentes canais de atendimento e materiais de apoio.

#### Formas de Suporte:

- **Central de Ajuda Online:** Base de conhecimento com artigos, tutoriais e perguntas frequentes.
- **Atendimento via E-mail:** Canal dedicado para dúvidas técnicas, sugestões e relatos de problemas.
- **Documentação do Usuário:** Manual completo em formato digital, segmentado por perfis de acesso (paciente e fisioterapeuta), com instruções claras de uso.

# Entrega e Distribuição da Plataforma

## Itens Entregues

A entrega da plataforma será composta por diversos itens que garantem sua execução funcional e uso eficaz:

- **Programas Executáveis:**  
  Versão final do sistema desenvolvida em PHP (backend), com HTML5, CSS3 e JavaScript (frontend), e banco de dados MySQL.

- **Scripts de Instalação:**  
  Scripts para deploy automatizado em ambiente de produção (Linux + Apache/Nginx), configuração de banco de dados e permissões de acesso.

- **Documentação do Usuário:**  
  - Manual do Paciente  
  - Manual do Fisioterapeuta  
  - Manual Técnico do Administrador

## Empacotamento do Software

O produto final será empacotado com os seguintes componentes:

- **Repositório de Código-Fonte:**  
  Entregue via GitHub (privado), com estrutura organizada por módulos e tags de versão.

- **Build Final em ZIP:**  
  Pacote contendo:  
  - Código-fonte da aplicação  
  - Scripts de instalação  
  - Arquivos de configuração padrão  
  - Pastas separadas para cada tipo de documentação (PDF, Markdown)

- **Vídeos Explicativos:**  
  Dois vídeos curtos (.mp4) demonstrando o uso dos principais módulos (agendamento e prontuário).

## Distribuição do Software

A distribuição será feita por meio dos seguintes canais:

- **Entrega Local:**  
  Upload para servidor do Centro de Práticas da Uniceplac (on-premise) ou hospedagem em Nuvem (AWS/Azure).

- **Distribuição via Internet (Git):**  
  Caso a hospedagem fique sob responsabilidade do cliente, será disponibilizado o repositório com instruções detalhadas.

- **Controle de Acesso e Licenciamento:**  
  - Sistema protegido por autenticação com senhas criptografadas  
  - Controle de permissões por perfil de usuário  
  - Licenciamento interno limitado ao Centro de Práticas da Uniceplac, sem redistribuição

## Instalação do Software

### Pré-requisitos Técnicos

- Servidor Linux com PHP 8+, MySQL 5.7+, Apache/Nginx  
- Acesso SSH e FTP

### Procedimentos

- Upload dos arquivos empacotados  
- Execução do script de instalação  
- Configuração do banco de dados  
- Teste funcional de todos os módulos

**Responsabilidade:**  
O time técnico do projeto realizará a primeira instalação. Futuras instalações seguirão a documentação entregue.

## Migração

### Substituição de Sistema Antigo

- O sistema anterior (fichas preenchidas no papel) será descontinuado para os novos atendimentos.  
- Os dados antigos não serão migrados.

### 11.2 Preparação para Migração Futura

- O sistema contará com estrutura modular para integração de APIs externas.  
- Caso deseje-se, futuramente, digitalizar fichas antigas, o sistema irá permitir upload de PDFs nos prontuários.

## Auxílio e Suporte ao Usuário

### Treinamento Formal

- Sessões presenciais de capacitação 

### Documentação de Apoio

- Manuais do usuário e vídeos curtos com instruções de uso  
- FAQ e guia de primeiros passos impressos

### Suporte Técnico

- Canal de e-mail institucional para dúvidas  
- Atendimento remoto agendado para problemas técnicos

# EAP (Estrutura Analítica do Projeto)

## Planejamento

### Levantamento de Requisitos
- **Reuniões com stakeholders**
- **Documentação dos requisitos**

### Modelagem Inicial
- **Criação de wireframes**
- **Aprovação de protótipos**

## Desenvolvimento

### Backend
- **Cadastro e login de usuários**
- **Agendamento de atendimentos**
- **Prontuário eletrônico**

### Frontend
- **Telas responsivas**
- **Integração com backend**

## Testes
- **Teste por módulo e Avaliação com fisioterapeutas**

## Opinião Especializada
Algumas atividades do projeto requerem a participação direta de especialistas para garantir conformidade, qualidade e segurança na entrega da plataforma.

### Avaliação com Fisioterapeutas

Serão realizados testes práticos com fisioterapeutas do Centro de Práticas da Uniceplac, com o objetivo de validar a **usabilidade da interface**, identificar pontos de melhoria na navegação e assegurar que o fluxo de uso esteja alinhado às rotinas clínicas reais.

### Consultoria em LGPD e Sistemas de Saúde 

A funcionalidade da **ficha de avaliação** envolve requisitos legais e questões de segurança da informação. Será necessária a **consulta com um especialista em LGPD (Lei Geral de Proteção de Dados)** e sistemas voltados à área da saúde, a fim de garantir que:

- Os dados do paciente estejam devidamente protegidos.
- O sistema respeite as normas vigentes de sigilo médico.
- A arquitetura atenda aos padrões de conformidade exigidos para soluções digitais de saúde.
