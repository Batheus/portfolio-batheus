# 🌐 Portfólio Profissional — Matheus Henrique

Este repositório contém o código-fonte do meu website de portfólio pessoal. O projeto foi desenvolvido para apresentar minha jornada profissional como Desenvolvedor de Software e DevOps, exibindo minhas competências em Python, Go, Azure e Engenharia de Machine Learning.

Acesse o site em [batheus.dev](https://batheus.dev).

## ✨ Visão geral
O projeto adota uma estética **Dark / Cyberpunk minimalista**, priorizando **performance**, animações suaves e responsividade. Foi construído com tecnologias web nativas (HTML/CSS/JS) para manter leveza e alta performance, sem dependência de frameworks pesados.

## 🚀 Funcionalidades
- **Design responsivo** — layout adaptável para Desktop, Tablet e Mobile (menu hambúrguer animado).
- **Interatividade**
  - Efeito de digitação (Typewriter) na seção *Hero*.
  - Cursor com efeito de brilho (Glow) dinâmico.
  - Efeito *Glitch* no nome principal.
- **Animações de scroll** — elementos aparecem suavemente com a API `IntersectionObserver` (fade-in / slide-up).
- **Glassmorphism** — cabeçalho e cartões com fundo translúcido e desfoque.
- **Seções**: Sobre, Experiência (linha do tempo), Competências Técnicas e Projetos.

## 🧰 Tecnologias utilizadas
- **HTML5** — estrutura semântica e acessível.
- **CSS3**
  - Variáveis CSS (`:root`) para fácil manutenção de temas.
  - Flexbox e CSS Grid para layout.
  - `@keyframes` para animações complexas.
- **JavaScript (ES6+)**
  - Manipulação do DOM.
  - Lógica de menus, animações e efeitos.
- **Bibliotecas externas (via CDN)**
  - Font Awesome — ícones.  
  - Google Fonts — fontes *Outfit* e *Space Grotesk*.

## 📂 Estrutura do projeto
```
├── assets/             # Imagens e ícones (ex: og-image.png)
├── css/
│   └── style.css       # Estilos globais e responsividade
├── js/
│   └── script.js       # Lógica de animações e interatividade
├── index.html          # Arquivo principal
└── README.md           # Documentação
```

## 💻 Como executar localmente
1. Clone o repositório:
```bash
git clone https://github.com/Batheus/portfolio.git
```

2. Acesse a pasta do projeto:
```bash
cd portfolio
```

3. Abra `index.html`:
- Você pode abrir diretamente no navegador.
- Recomendado: usar a extensão **Live Server** no VS Code para simular um servidor local e visualizar alterações em tempo real.

## 🎨 Personalização
As cores principais estão definidas em variáveis no início do arquivo `css/style.css`. Para alterar o tema, modifique os valores hexadecimais:

```css
:root {
    --bg-color: #0a0a0a;          /* Cor de fundo principal */
    --accent-cyan: #00f3ff;       /* Cor de destaque primária */
    --accent-purple: #bd00ff;     /* Cor de destaque secundária */
    /* ... */
}
```

## 📬 Contato
- **LinkedIn:** [batheusdev](https://linkedin.com/in/batheusdev)  
- **GitHub:** [Batheus](https://github.com/batheus)  
- **E-mail:** batheus.dev@gmail.com
- **Site:** [batheus.dev](https://batheus.dev)
- **Telefone para Contato:** [WhatsApp](https://wa.me/5511970462720)

---

<p align="center">Feito com 💜 por Matheus Henrique</p>
