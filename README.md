# Gateway Service

Microservico Spring Cloud Gateway responsavel por rotear chamadas e propagar `id-account`.

## Como executar

```bash
./mvnw spring-boot:run
```

## Rotas

- `/accounts/**`
- `/auth/**`
- `/products/**`
- `/orders/**`
- `/exchanges/**`
- `/exchange/**`

## Testes

```bash
./mvnw test
```
