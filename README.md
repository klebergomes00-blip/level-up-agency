# LEVELUP — Presença Digital & Websites de Alta Conversão

> Projeto oficial da **LEVELUP**, agência especializada em **Google Business Profile**, **Landing Pages** e **Websites de Alto Padrão**.

---

## 📁 Estrutura do Projeto

A base de código segue uma arquitetura modular, limpa e otimizada para deploy estático:

```
/
├── index.html                      # Página principal (Landing Page de Alta Conversão)
├── favicon.png                     # Ícone do site para navegadores
├── robots.txt                      # Diretivas de indexação para motores de busca
├── sitemap.xml                     # Mapa do site para indexação no Google/Bing
├── vercel.json                     # Configuração de deploy na Vercel (Cache + Security Headers)
├── netlify.toml                    # Configuração de deploy na Netlify
├── .gitignore                      # Arquivos ignorados pelo Git
│
├── assets/                         # Diretório central de recursos
│   ├── css/                        # Estilos e fontes
│   │   ├── fonts.css               # Declaração de fontes locais
│   │   ├── fonts-extended.css      # Variações de peso tipográfico
│   │   └── tokens.css              # Tokens de design e variáveis globais
│   ├── js/                         # Scripts e bibliotecas de animação
│   │   ├── gsap.min.js             # GSAP 3.12.5
│   │   ├── ScrollTrigger.min.js    # ScrollTrigger para animações de rolagem
│   │   ├── lucide.min.js           # Ícones Lucide
│   │   ├── iconify-icon.min.js     # Componente Web Iconify
│   │   └── tailwind.min.js         # Fallback local do Tailwind CSS
│   ├── images/                     # Imagens e marcas (kebab-case)
│   │   ├── logo-3d.png             # Logo principal 3D
│   │   ├── logo-3d-transparent.png # Logo 3D com fundo transparente
│   │   ├── bg-earth.png            # Planeta de fundo da Seção 1 (Hero)
│   │   ├── bg-dobra5.png           # Background da Seção 5
│   │   ├── bg-dobra8.jpg           # Background da Seção 8 (Google Profile)
│   │   ├── bg-dobra9.png           # Background da Seção 9 (Jornada)
│   │   ├── preview-fernando-corretor.jpg # Preview de projeto do portfólio
│   │   └── preview-google-maps.jpg       # Preview de presença local
│   └── videos/                     # Vídeos de alta definição
│       ├── bg-dobra2.mp4           # Vídeo de fundo Seção 2
│       ├── bg-dobra3.mp4           # Vídeo de fundo Seção 3
│       ├── showcase-projeto1.mp4   # Demonstração de projeto 1
│       ├── showcase-projeto2.mp4   # Demonstração de projeto 2
│       └── hero-ambient.mp4        # Vídeo ambiente de fundo
│
└── templates/                      # Hub e Catálogo de Design Systems
    ├── index.html                  # Portal / Navegador de Design Systems
    ├── design-system.html          # Design System v1.0 (Oficial / Completo)
    ├── design-system-v2.html       # Design System v2.0 (Dark Glass & Telemetria)
    └── design-system-v3.html       # Design System v3.0 (Editorial & Motion)
```

---

## 🚀 Como Testar Localmente

Por ser um projeto puramente estático (HTML, Vanilla CSS, JS moderno com Tailwind e GSAP via CDN + Fallbacks locais), você pode executá-lo de qualquer uma das seguintes formas:

### Opção 1: Extensão Live Server (VS Code / Antigravity IDE)
Clique com o botão direito em `index.html` e selecione **"Open with Live Server"**.

### Opção 2: Node.js (`npx serve`)
```bash
npx serve .
```

### Opção 3: Python
```bash
# Python 3
python -m http.server 3000
```

Abra no navegador em `http://localhost:3000`.

---

## 🌐 Como Fazer Deploy

### 1. Vercel (Recomendado)
1. Conecte seu repositório no [Vercel](https://vercel.com).
2. O arquivo `vercel.json` já está pré-configurado com **caching imutável de 1 ano** para `assets/**` e cabeçalhos de segurança (`X-Frame-Options`, `X-Content-Type-Options`).
3. Clique em **Deploy** — nenhuma configuração de build é necessária.

### 2. Netlify
1. Conecte o repositório no [Netlify](https://netlify.com).
2. O arquivo `netlify.toml` cuidará automaticamente da publicação da raiz e das regras de cache.

### 3. GitHub Pages
1. No repositório GitHub, acesse **Settings > Pages**.
2. Em **Branch**, selecione `main` e pasta `/ (root)`.
3. Salve e o site estará online em minutos.

### 4. Servidor VPS / CPanel / Hospedagem Tradicional
Basta fazer o upload de todos os arquivos e pastas para o diretório `public_html` (ou raiz do servidor web Nginx/Apache).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico**: Estruturação moderna com tags semânticas e acessibilidade.
- **Tailwind CSS 3.4**: Estilização utilitária de alta fidelidade com fallback local.
- **GSAP & ScrollTrigger 3.12.5**: Coreografia de movimento, pinning de seções e animações de scroll.
- **Iconify & Solar Icons**: Sistema de ícones vetoriais com renderização Web Component.
- **Google Fonts**: Tipografias *Playfair Display* (Editorial Serif), *Inter* (UI Sans) e *JetBrains Mono* (Telemetria).
- **SEO & Schema.org**: Metadados Open Graph, Twitter Cards e JSON-LD para autoridade em motores de busca.

---

## 📞 Contato & Suporte

- **WhatsApp**: [+55 (61) 99622-9988](https://wa.me/5561996229988)
- **Website**: [LEVELUP Agency](https://levelup.agency)
