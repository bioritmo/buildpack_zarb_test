# SSH Key Buildpack

Um Cloud Native Buildpack (CNB) para configurar chaves SSH durante o processo de build, permitindo acesso a repositórios Git privados.

## Estrutura de Arquivos

```
buildpack-ssh-key/
├── buildpack.toml      # Configuração do buildpack
├── bin/
│   ├── detect         # Script de detecção
│   └── build          # Script de build
└── README.md          # Documentação
```