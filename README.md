# Fisio-Digital
![Logo da empresa](imagens/logo.png)

Aplicação web de fisioterapia para auxiliar na marcação de consultas e atualização de fichas de avaliação, criada com o objetivo de facilitar as avaliações no Centro de Práticas da Uniceplac, este site promete agilizar os atendimentos, dar um fim em fichas fisicas preenchidas manualmente e facilitar cada vez mais o trabalho dos fisioterapeutas. 

# Justificativa e Necessidade de Negócio

Uma análise criteriosa do fluxo de atendimentos de fisioterapia no Centro de Práticas da Uniceplac identificou dificuldades significativos no processo atual. O sistema que eles possuem atualmente, baseado integralmente em registros manuais em papel, resulta em ineficiências operacionais, como atrasos na recuperação de informações, retrabalho para preenchimento e consolidação de dados, e risco de perda de informações críticas. Essa metodologia compromete a agilidade e a qualidade dos atendimentos, além de limitar o conforto e a produtividade dos fisioterapeutas envolvidos. A digitalização e automação são essenciais para modernizar o serviço, garantir a integridade dos dados e otimizar a experiência de alunos, professores e pacientes.
## 3. Descrição do Escopo do Produto

### 3.1. Objetivo Geral

Desenvolver e implantar uma plataforma web centralizada para a gestão completa dos atendimentos de fisioterapia, desde o agendamento de consultas até o acompanhamento contínuo da evolução do paciente, garantindo segurança, acessibilidade e eficiência.

### 3.2. Objetivos Específicos

- **Otimizar o Agendamento:** Implementar um sistema de agendamento online intuitivo para pacientes e fisioterapeutas.  
- **Centralizar a Documentação do Paciente:** Criar um prontuário eletrônico seguro para upload, armazenamento e atualização de laudos e fichas de acompanhamento.  
- **Melhorar a Comunicação e Adesão:** Integrar um sistema de notificações para lembrar pacientes e fisioterapeutas sobre os compromissos, visando reduzir a taxa de faltas.  
- **Aprimorar a Experiência do Usuário (UX):** Desenvolver uma interface clara, intuitiva e responsiva, com perfis de acesso distintos para fisioterapeutas e pacientes.  

### 3.3. Principais Entregáveis

- **Plataforma Web Funcional:** Incluindo os seguintes módulos:  
  - **Módulo de Agendamento:** Calendário interativo para marcação, consulta e cancelamento de horários.  
  - **Módulo de Gestão de Pacientes:** Sistema para cadastro de pacientes e gestão de prontuários eletrônicos (laudos, fichas de avaliação e evolução).  
  - **Módulo de Notificações:** Sistema de envio de e-mails e/ou notificações push.  

- **Interfaces de Usuário (UI):**  
  - **Painel do Fisioterapeuta:** Com visualização da agenda, acesso aos prontuários dos pacientes, ferramentas para edição de fichas e dashboard de acompanhamento.  
  - **Portal do Paciente:** Com funcionalidades para agendar consultas, visualizar horários marcados e acessar seu histórico.  

- **Documentação do Projeto:** Manual de usuário para ambos os perfis e documentação técnica do sistema.

### 3.4. Funcionalidades Detalhadas

- **Autenticação e Segurança:** Sistema de login e senha para todos os usuários, com controle de acesso baseado em perfis (fisioterapeuta, paciente).  
- **Agendamento:** Tela de agendamento com seleção de data, horário e profissional disponível.  
- **Gestão de Documentos:** Upload de arquivos (PDF, JPG, PNG) associados diretamente ao prontuário do paciente.  
- **Prontuário Eletrônico:** Edição contínua das fichas de acompanhamento pelo fisioterapeuta, com histórico de alterações.  
- **Comunicação:** Notificações automáticas via e-mail e/ou push para confirmação e lembrete de consultas.  
- **Dashboard:** Painel visual para fisioterapeutas com resumo de consultas (passadas e futuras) e acesso rápido ao histórico clínico dos pacientes.  
- **Design Responsivo:** Interface adaptável para uso em desktops, tablets e smartphones.

### 3.5. Especificações Técnicas

- **Backend:** PHP  
- **Frontend:** HTML5, CSS3, JavaScript  
- **Banco de Dados:** MySQL  
- **Segurança:** Implementação de criptografia para dados sensíveis e total conformidade com a Lei Geral de Proteção de Dados (LGPD).  
- **Arquitetura:** Níveis de acesso baseados em perfil de usuário.
