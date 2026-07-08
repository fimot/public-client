# Fimot — public-client

Repositório **público** de distribuição do cliente do Fimot.

- `launcher_config.json` — lido pelo launcher; aponta a versão atual e onde baixar.
- **Releases** — cada release traz o `tibia-client.zip` (cliente compilado + assets criptografados).

O build é automático: um push na `main` do repositório de código gera um novo
release aqui e atualiza o `current_version` deste arquivo. O launcher instalado
nos jogadores detecta e atualiza sozinho.

> Este repositório contém apenas binários distribuíveis. O código-fonte é privado.
