# Docker Study Repository

Este repositório serve para fins de estudo de boas práticas com Docker, incluindo:

- **Dockerfile** otimizado com multi-stage builds e usuário não-root
- **Skills de agente** para Claude Code com boas práticas documentadas
- **Estrutura de exemplo** com Node.js/Express

## Estrutura

```
docker/
├── app/               # Aplicação de exemplo (Node.js + Express)
├── .github/
│   └── skills/        # Skills de agente para boas práticas Docker
│       └── docker-best-practices/
├── Dockerfile         # Exemplo de Dockerfile otimizado
└── README.md
```

## Boas Práticas Demonstradas

- Multi-stage builds para imagens menores
- Usuário não-root por segurança
- Layer caching otimizado
- Healthcheck configurado
- .dockerignore configurado
