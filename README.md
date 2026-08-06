# Rota Principal — mattpocock/skills

Documentação de referência, estação por estação, do pacote de skills [mattpocock/skills](https://github.com/mattpocock/skills) para o Claude Code — do primeiro `/grill-with-docs` até o `/code-review` final, com os comandos opcionais e os desvios de manutenção organizados como uma rota de metrô.

Página única em HTML/CSS/JS, sem build, sem dependências além de fontes do Google Fonts. Abra o arquivo direto no navegador.

## Como usar

Baixe o repositório e abra `rota-principal-mattpocock-skills.html` em qualquer navegador — não precisa de servidor.

```bash
git clone https://github.com/LuanRodrigues15/<nome-do-repo>.git
cd <nome-do-repo>
start rota-principal-mattpocock-skills.html   # Windows
open rota-principal-mattpocock-skills.html    # macOS
```

Ou publique via **GitHub Pages** (Settings → Pages → branch `main`, pasta `/root`) para acessar por um link direto.

## O que tem na página

- **Rota principal**: as estações fixas (00 a 05), do setup ao code review, com bifurcações marcadas onde a decisão é sua.
- **Comandos úteis fora da rota**: skills que não têm um lugar fixo no fluxo, agrupadas por para que servem.
- **Fora da rota**: skills de manutenção — `triage`, `wayfinder`, `improve-codebase-architecture` — usadas quando algo foge do caminho principal.
- **Glossário** de siglas (ADR, PRD, TDD etc.), com atalhos clicáveis a partir de qualquer menção no texto.
- **Sidebar recolhível**, com legenda de símbolos, selos de sessão e índice de navegação rápida.
- **Tema claro/escuro**, com preferência salva no navegador.

## Estrutura

Tudo em um único arquivo (`rota-principal-mattpocock-skills.html`), propositalmente:

- CSS num único bloco `<style>`, com variáveis de tema (`:root` / `[data-theme="light"]`).
- Conteúdo estruturado como estações (`.station`) dentro de uma linha do tempo (`.route`), cada uma com um card colapsável (`<details>`).
- JS vanilla no fim do arquivo — sem framework, sem etapa de build.

## Licença

Uso pessoal / de referência. Ajuste conforme necessário para o seu caso.
