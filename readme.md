Sistema de gerenciador de tarefas
Descrição do Sistema

O Sistema do gerenciador de tarefas é uma aplicação web desenvolvida que vai ser usada para gerencias todas as tarefas que o usuário possui. O sistema vai permitir que o usuario anote tarefas importantes e visualizar o que ainda precisa ser feito. 

Características principais:

Criação simples de tarefas

Colocar em forma de lembrete digital 

Pode mover para feito, andamento e finalizado 

Pode excluir a qualquer momento

Horários Flexíveis: Possibilidade de reservas por hora, turno ou dia inteiro

Notificações: Sistema de alerta para lembrar usuários sobre suas reservas

Relatórios: Geração de relatórios de ocupação por horário, setor ou usuário

SQL SE ENCONTRA NA PASTA 'DB'

Estrutura de Pastas e Arquivos

./
├── .env.example             # Exemplo de variáveis de ambiente
├── .gitignore               # Arquivos ignorados pelo Git
├── assets/                  # Arquivos estáticos
│   └── modelo-banco.pdf     # Diagrama do banco de dados
├── config/                  # Arquivos de configuração
│   └── database.js          # Conexão com o banco de dados
├── controllers/             # Lógica de controle das requisições
│   └── HomeController.js    # Controlador da página inicial
├── docs/                    # Documentação do projeto
│   └── wad.md               # Web Application Document
├── db/                      # Banco sql
│   └── banco.sql            # Arquivo sql
├── jest.config.js           # Configuração de testes
├── models/                  # Definição dos modelos de dados
│   └── User.js              # Modelo de usuário
├── package-lock.json        # Versões exatas das dependências
├── package.json             # Dependências do projeto
├── readme.md                # Documentação do projeto (este arquivo)
├── rest.http                # Testes de API
├── routes/                  # Definição das rotas do sistema
│   └── index.js             # Rotas principais
├── scripts/                 # Scripts do frontend
├── server.js                # Arquivo principal que inicializa o servidor
├── services/                # Serviços auxiliares
│   └── parkingService.js    # Serviço para gerenciamento das tarefas
├── styles/                  # CSS do frontend
└── tests/                   # Testes automatizados
Modelo de Dados



