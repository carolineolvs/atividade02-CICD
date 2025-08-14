# Projeto de Exemplo - CI/CD com GitHub Actions

Este projeto demonstra como configurar um pipeline de integração e entrega contínua (CI/CD) para uma aplicação Node.js com GitHub Actions e Jest.

## Scripts

- `npm test`: roda os testes automatizados com Jest

## Estrutura

- `src/`: código-fonte
- `tests/`: testes automatizados
- `.github/workflows/ci.yml`: workflow do GitHub Actions

## CI/CD

- **CI:** Ao fazer push para `main`, os testes são executados automaticamente.
- **CD:** (Opcional) O deploy é feito automaticamente com o Vercel.

