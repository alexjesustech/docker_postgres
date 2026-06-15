# docker_postgres

Configuração **Docker Compose** para subir uma base **PostgreSQL** local de desenvolvimento
(`postgres:14.3`, volume nomeado, porta `5432`).

## Status

`0.1.0` — funcional para uso local. Versionado por [SemVer](https://semver.org/lang/pt-BR/)
(`0.y.z` = ainda pode mudar).

## Uso

```bash
docker compose up -d
```

> ⚠️ As credenciais no `docker-compose.yml` são **apenas para desenvolvimento local** — defina
> valores próprios antes de qualquer uso fora da sua máquina.

## Licença

[MIT](LICENSE) © 2026 Alex Jesus.
