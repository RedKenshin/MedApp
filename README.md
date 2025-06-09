
# 📱 Sistema de Agendamento de Consultas Médicas

## 👨‍🎓 Alunos do Grupo
- Nome do Aluno RENAN PEREIRA DOS SANTOS - RA: 202119070757


## 🧭 Visão Geral
Aplicativo Android desenvolvido para facilitar o agendamento de consultas médicas por parte dos pacientes, com recursos exclusivos para administradores. O sistema permite a seleção de especialidades, médicos e horários disponíveis, com autenticação de usuários.

## 👥 Papéis de Usuário

### Paciente
- Cadastro com:
  - Nome completo
  - CPF
  - E-mail
  - Telefone
  - Endereço
  - Foto de perfil (obrigatória)
- Funcionalidades:
  - Login no app
  - Agendamento de consultas:
    - Selecionar especialidade
    - Escolher data e horário
    - Escolher médico (caso haja mais de um)
  - Visualizar e editar seus próprios dados
  - Visualizar agendamentos feitos

### Administrador (ADM)
- Login com dados pré-cadastrados (não pode se registrar pelo app)
- Funcionalidades:
  - Cadastrar novos médicos
  - Editar médicos existentes
  - Gerenciar especialidades

## ✅ Requisitos Funcionais

- [x] Tela de login com autenticação
- [x] Cadastro de pacientes com validação de campos e foto
- [x] Cadastro e edição de médicos (restrito ao ADM)
- [x] Agendamento por especialidade, horário e médico
- [x] Visualização e edição de perfil
- [x] Listagem de especialidades e médicos
- [x] Persistência com Room Database

## 🧪 Requisitos de Teste (Caixa Preta)

- Impedir login de usuários não cadastrados
- Validação de campos obrigatórios vazios
- Prevenir erros de entrada como texto em campos numéricos
- Garantir tratamento de exceções (ex: divisão por zero, se aplicável)

##📱 Telas Esperadas
- Tela de Login

- Tela de Cadastro de Paciente (com upload de foto)

- Tela de Agendamento (especialidade, calendário e seleção de médico)

- Tela de Edição de Perfil do Paciente

- Tela de Administração (cadastro e edição de médicos)
