# Auth Vanguard UI

[![Tailwind Version](https://img.shields.io/badge/Tailwind-v4.2.1-38bdf8)](https://tailwindcss.com)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## 🖥️ Preview
Acesse o projeto online: [devablsouza.github.io/auth-vanguard-tailwind-ui/](https://devablsouza.github.io/auth-vanguard-tailwind-ui/)

## 🏗 Architecture Overview
Esta solução utiliza uma abordagem **Utility-First** com a engine Tailwind CSS v4. O layout é construído sobre um sistema de **Flexbox adaptativo**, alternando entre fluxos verticais (mobile) e horizontais (desktop) para otimizar a experiência do usuário em diferentes viewports.

## 🛠 Tech Stack
| Tecnologia | Versão | Justificativa |
| :--- | :--- | :--- |
| HTML5 | Semântico | Base estrutural para SEO e acessibilidade. |
| Tailwind CSS | 4.2.1 | Engine de última geração com suporte nativo a variáveis CSS e OKLCH. |
| Node.js | ^20.x | Runtime necessário para execução do CLI de build. |

## 🚀 Core Features
- **Responsive Auth Layout:** Transição fluida entre resoluções usando breakpoints `md:` e `lg:`.
- **Modern UI Assets:** Interface enriquecida com elementos visuais de alta fidelidade.
- **CLI-Driven Workflow:** Pipeline de build otimizado para desenvolvimento rápido.

## 🗺 Technical Roadmap
### Phase 1: Foundation (Security & A11y)
- [ ] Alterar input de senha para `type="password"`.
- [ ] Implementar tags `<form>` e botões de `type="submit"`.
- [ ] Adicionar `aria-label` para melhorar a acessibilidade.

### Phase 2: Scaling
- [ ] Componentização de elementos repetitivos (Inputs/Buttons).
- [ ] Implementação de validação de formulário (ex: Regex para E-mail).
- [ ] Suporte nativo ao Dark Mode via variantes do Tailwind.

### Phase 3: Optimization
- [ ] Configuração de PurgeCSS avançado para redução do bundle de produção.
- [ ] Integração com CI/CD para deploys automatizados.

## ⚙️ Installation & Usage
Para iniciar o ambiente de desenvolvimento:
```bash
# Instalar dependências
npm install

# Rodar o compilador Tailwind em modo watch
npm run dev