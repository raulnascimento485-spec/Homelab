# Homelab — Laboratório de Infraestrutura

Projeto pessoal de laboratório de infraestrutura, desenvolvido para estudar e praticar administração de servidores Linux, virtualização, redes, containers, monitoramento e automação.

## Objetivos

- Aprender administração de servidores Linux.
- Praticar Docker e Docker Compose.
- Gerenciar bancos de dados.
- Implementar monitoramento e diagnóstico.
- Estudar segurança e boas práticas de infraestrutura.
- Desenvolver conhecimentos em DevOps e Cloud Computing.

## Infraestrutura atual

Servidor baseado em Ubuntu Server, utilizando Docker para executar serviços independentes.

### Serviços

| Serviço | Função |
|---|---|
| Nginx | Hospedagem de páginas web |
| PostgreSQL | Banco de dados relacional |
| Adminer | Gerenciamento do banco de dados |
| Netdata | Monitoramento de recursos |
| Uptime Kuma | Monitoramento de disponibilidade e alertas |
| Dozzle | Visualização de logs dos containers |
| Gitea | Hospedagem e gerenciamento de repositórios Git |

## Tecnologias

- Ubuntu Server
- Linux
- Docker
- Docker Compose
- PostgreSQL
- Nginx
- Git
- GitHub
- SQLite
- Gitea
- SSH
- UFW

## Estrutura do repositório

```text
homelab/
├── docker/
│   ├── projeto-web.yaml
│   ├── uptime-kuma.yaml
│   ├── dozzle.yaml
│   ├── gitea.yaml
│   └── .env.example
├── docs/
├── scripts/
├── .gitignore
└── README.md
```

## Segurança
Credenciais, tokens, chaves privadas, arquivos de ambiente reais e backups não fazem parte deste repositório.
As configurações disponibilizadas são exemplos e podem exigir adaptações para cada ambiente.
## Status do projeto
Em desenvolvimento. Novos serviços, melhorias e documentações serão adicionados progressivamente.
