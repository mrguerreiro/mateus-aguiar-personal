<div align="center">

<img src="assets/logo.jpeg" alt="Mateus Aguiar" width="150" style="border-radius:50%">

# Mateus Aguiar — Personal Trainer & Consultoria

**Página institucional (landing page) com planos, serviços e contato direto via WhatsApp.**

[![Site no ar](https://img.shields.io/badge/🌐_Ver_site-online-25D366?style=for-the-badge)](https://mrguerreiro.github.io/mateus-aguiar-personal/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-(14)_99801--7399-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5514998017399)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-deploy-222?style=flat&logo=github)
![Sem dependências](https://img.shields.io/badge/depend%C3%AAncias-0-success?style=flat)

</div>

---

## ✨ Sobre

Site de página única, **rápido e 100% estático** (HTML + CSS + JavaScript puro, sem frameworks nem dependências externas). Visual preto & branco alinhado à identidade da marca, com foco em converter visitantes em contatos no WhatsApp.

**🔗 Acesse:** <https://mrguerreiro.github.io/mateus-aguiar-personal/>

---

## 📸 Telas

<div align="center">

### 💻 Desktop

<img src="docs/screenshots/desktop-hero.png" alt="Hero" width="90%">

<table>
  <tr>
    <td width="50%"><img src="docs/screenshots/desktop-servicos.png" alt="Serviços"></td>
    <td width="50%"><img src="docs/screenshots/desktop-planos.png" alt="Planos"></td>
  </tr>
</table>

### 📱 Mobile

<img src="docs/screenshots/mobile-hero.png" alt="Mobile" width="300">

</div>

---

## 🚀 Funcionalidades

- 🟢 **CTA de WhatsApp** em vários pontos, com mensagem pré-preenchida (cada plano abre uma mensagem personalizada)
- 📋 **3 planos** (Essencial, Acompanhamento e Personal) e **6 serviços** em cards
- 📱 **Totalmente responsivo** — testado de 360px (celular) a telões
- ⚡ **Carregamento instantâneo** — arquivo único, sem bibliotecas
- 🎞️ Animações de entrada ao rolar a página
- 🔒 **Cabeçalhos de segurança** (Content-Security-Policy) bloqueando recursos externos
- ♿ Boas práticas de acessibilidade (textos alternativos, contraste, navegação por âncoras)

---

## 📁 Estrutura

```
.
├── index.html              Página completa (HTML + CSS + JS inline)
├── assets/
│   ├── logo.jpeg           Logo da marca
│   └── mateus.jpg          Foto do personal
├── docs/screenshots/       Imagens usadas neste README
├── .nojekyll               Evita processamento Jekyll no GitHub Pages
└── README.md
```

---

## ✏️ Como editar

| O que mudar        | Onde                                                                 |
|--------------------|----------------------------------------------------------------------|
| Preços / planos    | Seção `#planos` no `index.html`                                       |
| Textos / serviços  | Direto no `index.html`                                                |
| Nº do WhatsApp     | Variável `WA_NUMBER` no bloco `<script>` (formato `55` + DDD + número) |
| Mensagem padrão    | Variável `WA_MSG_DEFAULT` no `<script>`                              |
| Logo / foto        | Substitua os arquivos em `assets/` mantendo os mesmos nomes           |

### Publicar alterações

```bash
git add -A
git commit -m "descreva a mudança"
git push
```

O GitHub Pages reconstrói o site automaticamente em ~1 minuto.

---

## 💬 Contato

<div align="center">

[![Falar no WhatsApp](https://img.shields.io/badge/💬_Fale_com_o_Mateus-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5514998017399?text=Ol%C3%A1%2C%20gostaria%20de%20saber%20mais%20a%20respeito%20dos%20planos%20e%20servi%C3%A7os.)

**(14) 99801-7399**

</div>
