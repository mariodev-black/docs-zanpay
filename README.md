# Zanpay Docs

Documentação pública das integrações Zanpay. O site usa Mintlify e documenta a API em `https://api.zanpaybr.com`.

## Desenvolvimento

```bash
npx mint@latest dev --port 3333
```

A prévia fica em `http://localhost:3333`.

## Validação

```bash
npx mint@latest validate
npx mint@latest broken-links
```

A navegação e a aparência ficam em `docs.json`. Atualize `openapi.json` e a página da operação em `referencia/` quando um contrato público mudar. Os guias de integração ficam em `guias/` e `webhooks/`.

O código-fonte está na branch `main`. Em projetos conectados ao Mintlify, essa branch pode ser usada para publicação automática.
