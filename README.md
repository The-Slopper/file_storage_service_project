# go-fileservice

Serviço HTTP em Go para buscar metadados de arquivos remotos e calcular
estatísticas de uso. Sem dependências externas.

## Rodando

```bash
go run .
```

## Endpoints

- `GET /fetch?url=` — busca o conteúdo de um recurso e retorna o tamanho
- `GET /stats` — retorna a média de bytes dos últimos downloads
- `GET /report?discount=` — aplica desconto ao total acumulado
