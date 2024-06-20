## Sistema de Gerenciamento de Tarefas 

## Objetivo

Desenvolver um sistema de gerenciamento de tarefas utilizando FastAPI, aplicando os conceitos de controllers, services e
repositories.

## Descrição do Projeto

O projeto consiste em criar uma API para gerenciamento de tarefas que permite a criação, leitura, atualização e exclusão
de tarefas. Cada tarefa deve ter um título, descrição, status e data de criação.

## Estrutura do Projeto

![image](https://github.com/arianeccdias/FastApi_Ari/assets/91470759/b20f5c29-5495-49f0-bd6b-90a1a7829b14)

fastapi-task-management/
├── app/
│   ├── controllers/
│   │   └── task_controller.py
│   ├── services/
│   │   └── task_service.py
│   ├── repositories/
│   │   └── task_repository.py
│   ├── models/
│   │   └── task_model.py
│   ├── main.py
│   └── database.py
└── tests/
    ├── test_controllers.py
    ├── test_services.py
    └── test_repositories.py

## Descrição dos Componentes

- **Controllers**: Responsáveis por definir os endpoints da API.
- **Services**: Contêm a lógica de negócios e validações.
- **Repositories**: Gerenciam a interação com o banco de dados.

![image](https://github.com/arianeccdias/FastApi_Ari/assets/91470759/b5cfb1a3-4eff-4d05-8b8f-b963a9654641)





