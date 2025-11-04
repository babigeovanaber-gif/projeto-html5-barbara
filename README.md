# Organização Exemplo


---

## 🏁 Entrega Final — Versão v3.0.0

### Controle de Versão (Git/GitHub)
- Branching adotado: **GitFlow** (main, develop, feature/*).
- Commits semânticos (ex.: `feat:, fix:, docs:, refactor:`).
- Releases com versionamento semântico (ex.: `v1.0.0`, `v2.0.0`, `v3.0.0`).

### Acessibilidade (WCAG 2.1 AA)
- Navegação por teclado em componentes interativos (menu, toggles, formulários).
- Skip link para pular direto ao conteúdo.
- Modos: **claro**, **escuro**, e **alto contraste** (persistidos em localStorage).
- Foco visível para usuários que navegam com teclado.
- Suporte básico a leitores de tela (atributos ARIA adicionados nos controles).

### Otimização para Produção
- Arquivos minificados disponíveis em `css/styles.min.css` e `js/app.min.js`.
- Recomenda-se compressão adicional de imagens antes do deploy (ex.: TinyPNG).

### Como publicar (deploy)
- Fazer merge de `develop` em `main` e criar tag `v3.0.0`.
- Configurar GitHub Pages (ou qualquer serviço de hospedagem) apontando para a branch `main`.
- Confirmar que o repositório está público para correção pela disciplina.

---
