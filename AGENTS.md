# Documentação Zanpay

- Este repositório é o site público de documentação da Zanpay no Mintlify. Use MDX para o conteúdo e `docs.json` para a navegação e aparência.
- Escreva em português do Brasil. Use **Zanpay**, **Pix**, **Pix Copia e Cola** e **API e webhooks**.
- Confira caminhos, cabeçalhos, payloads, status e erros no backend antes de alterar o OpenAPI ou os exemplos. A origem de produção é `https://api.zanpaybr.com` e as rotas para integradores usam `/api/v1`.
- Documente o painel quando ele fizer parte da configuração da integração. Mantenha rotas administrativas, cookies internos e callbacks de adquirentes fora da referência pública.
- Use credenciais marcadas como exemplo e dados fictícios. Os exemplos usam centavos inteiros.
- Consulte `npx mint@latest instructions` para identificar o tópico de ajuda aplicável. Valide alterações com `npx mint@latest validate` e `npx mint@latest broken-links`.
