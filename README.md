# Coffee Shop — Landing Page

Uma landing page responsiva com seções de **Hero**, **Receitas**, **Reserva** e **Footer**.

## 🧭 Navegação
- O menu superior faz scroll para as seções correspondentes (rolagem suave).
- Links são pretos por padrão e mudam para azul ao passar o mouse (hover).

## 🛠️ Tecnologias
- HTML5 semântico
- CSS3 (BEM, Grid/Flex)
- Google Fonts (Inter 400/500/700 e Noto Serif 400 *italic*)

## 📂 Estrutura
```
project-root/
├── index.html
├── pages/
│   └── index.css
├── images/
└── README.md
```

## 🚀 Como executar
Abra `index.html` no navegador. Não há dependências de build.

## ✅ Conformidade com o Briefing
- Importações de fontes consolidadas em **uma** única tag.
- Links pretos com **hover azul**.
- Seção de **Receitas** com grid responsivo e vídeos com `aspect-ratio`.
- `scroll-behavior: smooth` com fallback para `prefers-reduced-motion`.

## 🔎 A melhorar (opcional)
- Adicionar testes de acessibilidade (ex. Lighthouse).
- Otimizar imagens (formato moderno e `loading="lazy"`).
