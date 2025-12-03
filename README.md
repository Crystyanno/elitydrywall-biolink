# 🏗️ Elity Drywall - Bio Link

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Demonstração](#demonstração)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação](#instalação)
- [Configuração](#configuração)
- [Personalização](#personalização)
- [Design](#design)
- [Responsividade](#responsividade)
- [Otimizações](#otimizações)
- [Navegadores Suportados](#navegadores-suportados)
- [Deploy](#deploy)
- [Roadmap](#roadmap)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## 🎯 Sobre o Projeto

Este projeto foi desenvolvido para centralizar todos os canais de contato e redes sociais da **Elity Drywall** em uma única página acessível através do Instagram. A solução oferece uma experiência moderna, clean e totalmente responsiva para dispositivos móveis e desktop.

### Objetivo

Facilitar o acesso dos clientes aos diversos canais de comunicação da empresa, incluindo:
- Site oficial
- WhatsApp para orçamentos e contatos
- Redes sociais (Instagram, Facebook)
- Localização no Google Maps
- Sistema de avaliações do Google

## 🖼️ Demonstração

### Desktop
```
┌─────────────────────────────────┐
│          [LOGO]                 │
│      ELITY DRYWALL              │
│  Especialistas em Drywall       │
│                                 │
│  [🌐 Visite nosso Site]         │
│  [📱 WhatsApp - Contato 1]      │
│  [📱 WhatsApp - Contato 2]      │
│  [📍 Nossa Localização]         │
│  [⭐ Avalie-nos no Google]      │
│                                 │
│     [📷] [f] [G]                │
│  ─────────────────────          │
│  © 2025 Elity Drywall           │
│  Desenvolvido por Crystyanno    │
└─────────────────────────────────┘
```

### Mobile
```
┌───────────────┐
│    [LOGO]     │
│ ELITY DRYWALL │
│  Especialistas│
│               │
│ [🌐 Site]     │
│ [📱 WhatsApp] │
│ [📱 WhatsApp] │
│ [📍 Mapa]     │
│ [⭐ Google]   │
│               │
│  [📷][f][G]   │
│  ───────────  │
│  © 2025       │
│  Dev: Crysty  │
└───────────────┘
```

## ✨ Funcionalidades

### 🔗 Links de Navegação
- ✅ **Site Oficial**: Link direto para o website da empresa
- ✅ **Dual WhatsApp**: Dois números de contato configuráveis
- ✅ **Localização**: Integração com Google Maps
- ✅ **Avaliações**: Link direto para página de reviews do Google

### 📱 Redes Sociais
- ✅ **Instagram**: @elitydrywall
- ✅ **Facebook**: Página oficial
- ✅ **Google Business**: Perfil da empresa

### 🎨 Design
- ✅ Interface minimalista e moderna
- ✅ Paleta de cores baseada na identidade visual da marca
- ✅ Animações suaves e discretas
- ✅ Hover effects em todos os elementos interativos
- ✅ Typography hierárquica e legível

### 📲 Responsividade
- ✅ Totalmente responsivo (mobile-first)
- ✅ Adaptável a todos os tamanhos de tela
- ✅ Otimizado para Instagram in-app browser
- ✅ Touch-friendly (áreas de toque adequadas)

## 🚀 Tecnologias Utilizadas

### Core
- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização avançada com Flexbox
- **JavaScript (ES6+)**: Interatividade e manipulação do DOM

### Bibliotecas
- **Font Awesome 6.4.0**: Ícones vetoriais
  ```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  ```

### Fontes
- **Inter / System Fonts**: Tipografia moderna e performática
  ```css
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  ```

## 📁 Estrutura do Projeto

```
elity-drywall-bio/
│
├── index.html              # Arquivo principal
├── README.md              # Documentação do projeto
├── assets/                # Pasta de recursos (opcional)
│   └── logo.png          # Logo da empresa
│
└── docs/                 # Documentação adicional
    ├── CONTRIBUTING.md   # Guia de contribuição
    └── CHANGELOG.md      # Histórico de versões
```

### Estrutura HTML

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <!-- Meta tags -->
    <!-- CSS inline -->
    <!-- Font Awesome CDN -->
  </head>
  <body>
    <div class="container">
      <!-- Logo -->
      <div class="logo-container">
        <img src="..." alt="Elity Drywall Logo" class="logo">
      </div>
      
      <!-- Título e Subtítulo -->
      <h1 class="title">ELITY DRYWALL</h1>
      <p class="subtitle">Especialistas em Drywall e Acabamentos</p>
      
      <!-- Links de Navegação -->
      <a href="#" class="link-btn">...</a>
      
      <!-- Redes Sociais -->
      <div class="social-links">...</div>
      
      <!-- Footer -->
      <div class="footer">...</div>
    </div>
    
    <!-- JavaScript -->
    <script>...</script>
  </body>
</html>
```

## 🔧 Instalação

### Pré-requisitos

Nenhum pré-requisito necessário! O projeto utiliza apenas HTML, CSS e JavaScript vanilla.

### Passo a Passo

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/elity-drywall-bio.git
   ```

2. **Acesse o diretório**
   ```bash
   cd elity-drywall-bio
   ```

3. **Abra o arquivo no navegador**
   ```bash
   # Linux/Mac
   open index.html
   
   # Windows
   start index.html
   ```

Ou simplesmente arraste o arquivo `index.html` para o navegador.

## ⚙️ Configuração

### 1. Adicionar a Logo

Substitua a URL da logo no elemento `<img>`:

```html
<img src="SUA_URL_AQUI" alt="Elity Drywall Logo" class="logo" id="logoImg">
```

**Opções de hospedagem da logo:**
- Imgur: https://imgur.com/upload
- Cloudinary: https://cloudinary.com
- GitHub: Coloque na pasta `assets/` do repositório

### 2. Configurar WhatsApp

Substitua os números de telefone (formato internacional):

```html
<!-- Contato 1 -->
<a href="https://wa.me/5511999999999" class="link-btn whatsapp-btn" target="_blank">

<!-- Contato 2 -->
<a href="https://wa.me/5511988888888" class="link-btn whatsapp-btn" target="_blank">
```

**Formato:** `55` (Brasil) + `11` (DDD) + `999999999` (número)

### 3. Configurar Site

No JavaScript, adicione a URL do site:

```javascript
document.getElementById('siteBtn').addEventListener('click', function(e) {
    e.preventDefault();
    window.open('https://www.seusite.com.br', '_blank');
});
```

### 4. Configurar Google Maps

Obtenha o link de localização:

1. Acesse [Google Maps](https://maps.google.com)
2. Encontre sua empresa
3. Clique em "Compartilhar"
4. Copie o link curto
5. Cole no HTML:

```html
<a href="LINK_DO_GOOGLE_MAPS_AQUI" class="link-btn" target="_blank">
```

### 5. Configurar Avaliações Google

Obtenha o link de reviews:

1. Acesse [Google Business](https://business.google.com)
2. Vá em "Perfil"
3. Copie o link "Pedir avaliações"
4. Cole no HTML:

```html
<a href="LINK_DE_AVALIACOES_AQUI" class="link-btn" target="_blank">
```

### 6. Configurar Facebook

Adicione o link da página do Facebook:

```html
<a href="https://facebook.com/elitydrywall" class="social-icon facebook" target="_blank">
```

## 🎨 Personalização

### Paleta de Cores

As cores seguem a identidade visual da Elity Drywall:

```css
/* Cor principal (Dourado) */
--primary-color: #c9a961;

/* Cores neutras */
--text-dark: #1a1a1a;
--text-light: #666666;
--text-muted: #999999;
--border-color: #e5e5e5;
--background: #ffffff;
--background-hover: #fafafa;

/* Cores de redes sociais */
--whatsapp: #25D366;
--instagram: #E4405F;
--facebook: #1877f2;
--google: #4285f4;
```

### Modificar Cores

Para alterar a cor dourada principal:

```css
/* Substitua #c9a961 pela cor desejada */
.link-btn:hover {
    border-color: #c9a961; /* Sua cor aqui */
}

.link-btn i {
    color: #c9a961; /* Sua cor aqui */
}

.footer .developer {
    color: #c9a961; /* Sua cor aqui */
}
```

### Adicionar Novos Links

```html
<a href="SEU_LINK" class="link-btn" target="_blank">
    <i class="fas fa-ICONE"></i>
    <span>Texto do Botão</span>
</a>
```

**Ícones disponíveis** (Font Awesome):
- `fa-globe` - Site
- `fa-whatsapp` - WhatsApp
- `fa-map-marker-alt` - Localização
- `fa-star` - Avaliações
- `fa-phone` - Telefone
- `fa-envelope` - Email
- `fa-calendar` - Agendamento

### Modificar Tipografia

```css
/* Tamanho do título */
.title {
    font-size: 24px; /* Ajuste conforme necessário */
}

/* Tamanho dos botões */
.link-btn {
    font-size: 15px; /* Ajuste conforme necessário */
}
```

## 📱 Responsividade

### Breakpoints

```css
/* Mobile */
@media (max-width: 480px) {
    /* Estilos para celular */
}

/* Tablet */
@media (min-width: 481px) and (max-width: 768px) {
    /* Adicione se necessário */
}

/* Desktop */
@media (min-width: 769px) {
    /* Layout padrão */
}
```

### Testes Responsivos

O projeto foi testado em:
- ✅ iPhone SE (375px)
- ✅ iPhone 12/13/14 (390px)
- ✅ iPhone 14 Pro Max (430px)
- ✅ Samsung Galaxy S21 (360px)
- ✅ iPad (768px)
- ✅ iPad Pro (1024px)
- ✅ Desktop (1920px)

## ⚡ Otimizações

### Performance

- **Inline CSS**: Reduz requisições HTTP
- **Fontes do sistema**: Carregamento instantâneo
- **CDN Font Awesome**: Cache global
- **Animações CSS**: Uso de GPU para transições
- **Lazy Loading**: Imagens carregam sob demanda

### SEO

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Elity Drywall - Especialistas em Drywall e Acabamentos. Entre em contato!">
<meta name="keywords" content="drywall, gesso, acabamentos, construção civil">
<meta name="author" content="Crystyanno">
<title>Elity Drywall - Links</title>

<!-- Open Graph (Facebook/Instagram) -->
<meta property="og:title" content="Elity Drywall">
<meta property="og:description" content="Especialistas em Drywall e Acabamentos">
<meta property="og:image" content="URL_DA_LOGO">
<meta property="og:url" content="URL_DA_PAGINA">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Elity Drywall">
<meta name="twitter:description" content="Especialistas em Drywall e Acabamentos">
<meta name="twitter:image" content="URL_DA_LOGO">
```

### Acessibilidade

- ✅ **Alt text** em todas as imagens
- ✅ **Aria labels** nos links
- ✅ **Contraste adequado** (WCAG 2.1)
- ✅ **Navegação por teclado**
- ✅ **Semantic HTML**

## 🌐 Navegadores Suportados

| Navegador | Versão Mínima |
|-----------|---------------|
| Chrome    | 90+           |
| Firefox   | 88+           |
| Safari    | 14+           |
| Edge      | 90+           |
| Opera     | 76+           |
| Samsung Internet | 14+    |

## 🚀 Deploy

### Opções de Hospedagem Gratuitas

#### 1. GitHub Pages

```bash
# Criar repositório no GitHub
# Fazer upload do index.html
# Ir em Settings > Pages
# Selecionar branch main
# Salvar
```

**URL final:** `https://seu-usuario.github.io/elity-drywall-bio/`

#### 2. Netlify

1. Acesse [Netlify](https://www.netlify.com)
2. Arraste a pasta do projeto
3. Pronto! URL disponível instantaneamente

#### 3. Vercel

```bash
npm i -g vercel
vercel
```

#### 4. Cloudflare Pages

1. Acesse [Cloudflare Pages](https://pages.cloudflare.com)
2. Conecte seu repositório GitHub
3. Deploy automático

### Domínio Personalizado

Após o deploy, você pode adicionar um domínio personalizado:

- **GitHub Pages**: Settings > Pages > Custom domain
- **Netlify**: Site settings > Domain management
- **Vercel**: Project > Domains

## 🗺️ Roadmap

### Versão 1.1
- [ ] Modo escuro (dark mode)
- [ ] Suporte a múltiplos idiomas
- [ ] Analytics integrado
- [ ] Formulário de contato

### Versão 1.2
- [ ] PWA (Progressive Web App)
- [ ] Notificações push
- [ ] Integração com CRM
- [ ] Agendamento online

### Versão 2.0
- [ ] Painel administrativo
- [ ] Estatísticas de cliques
- [ ] A/B testing
- [ ] Personalização via interface

## 🤝 Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### Padrões de Código

- **HTML**: Indentação de 4 espaços
- **CSS**: BEM methodology
- **JavaScript**: ESLint + Prettier
- **Commits**: Conventional Commits

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## 📞 Contato

**Elity Drywall**
- Instagram: [@elitydrywall](https://www.instagram.com/elitydrywall/)
- Facebook: [Elity Drywall](https://facebook.com/elitydrywall)
- WhatsApp: [Clique aqui](https://wa.me/5511999999999)

**Desenvolvedor**
- **Crystyanno**
- GitHub: [@crystyanno](https://github.com/crystyanno)
- LinkedIn: [Crystyanno](https://linkedin.com/in/crystyanno)

---

<div align="center">

**Desenvolvido com 💛 por Crystyanno**

⭐ Se este projeto te ajudou, deixe uma estrela!

</div>