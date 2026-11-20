# Diretrizes de Contribuição

Este repositório segue um fluxo simples e rastreável para alterações de código, interface e documentação.

## Fluxo via Issue e Pull Request
1. Crie uma **Issue** descrevendo o ajuste, correção ou melhoria usando os modelos em `.github/ISSUE_TEMPLATE/`.
2. Trabalhe em uma branch dedicada (`fix/`, `feat/` ou `refactor/`), evitando commits diretos na `main`.
3. Abra um **Pull Request** preenchendo `.github/PULL_REQUEST_TEMPLATE.md` e vinculando a Issue (`Resolve #N`).

## Qualidade, Privacidade e Interface
* Preserve a arquitetura 100% client-side (nenhum dado clínico ou nome de paciente deve trafegar para servidores externos, em conformidade com a LGPD).
* Mantenha funcionamento sem etapa de build (HTML5, CSS3, JavaScript e `PDF.js` local em `lib/`).
* Mantenha português do Brasil claro e sem travessões nos textos da interface e da documentação.
* Antes do merge, valide a abertura local do `index.html`, a importação de PDFs, os dois modos de tema e a exportação/restauração de backup em JSON.
