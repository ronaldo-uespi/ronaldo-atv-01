# Ronaldo - Portfólio MVP

Portfólio profissional minimalista desenvolvido como **Atividade 01** da disciplina de desenvolvimento web. Um MVP (Minimum Viable Product) focado em clareza visual, responsividade e boas práticas de código.

## 🎯 Sobre o Projeto

Este é meu portfólio de apresentação profissional, criado com tecnologias fundamentais de front-end: **HTML5, CSS3 e JavaScript vanilla**. O projeto demonstra habilidades em:

- ✨ **Layout responsivo** que funciona em dispositivos de qualquer tamanho
- 🎨 **Design limpo e minimalista** com paleta de cores harmoniosa
- 🌓 **Modo claro/escuro** com persistência em localStorage
- ♿ **Acessibilidade** com semântica HTML adequada e ARIA labels
- 📱 **Mobile-first** com suporte para telas pequenas até desktops

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|------------|--------|-----|
| **HTML5** | Latest | Estrutura semântica |
| **CSS3** | Latest | Estilização responsiva com Grid e Flexbox |
| **JavaScript** | ES6+ | Interatividade e gerenciamento de tema |
| **Git** | Latest | Controle de versão |

## 📁 Estrutura do Projeto

```
ronaldo-atv-01/
├── index.html         # Arquivo principal HTML
├── styles.css         # Estilos CSS (6KB)
├── script.js          # Lógica JavaScript (2KB)
├── profile.jpg        # Foto de perfil
├── README.md          # Este arquivo
├── LICENSE            # Licença do projeto
├── .gitignore         # Arquivos ignorados pelo Git
└── .gitattributes     # Configurações de atributos Git
```

## ✨ Principais Características

### 📌 Navegação Clara
- Menu no topo com links para seções (Sobre, Projetos, Contato)
- Links internos com âncoras para navegação suave
- Botão de alternância de tema (claro/escuro)

### 👤 Seção "Sobre Mim"
- Apresentação profissional
- Foto de perfil em alta qualidade
- Descrição de habilidades e objetivo
- Layout responsivo com imagem e texto lado a lado (desktop)

### 💼 Galeria de Projetos
- Grid dinâmico renderizado com JavaScript
- Cartões com título, descrição, tags e links
- Muda de 1 coluna (mobile) → 2 colunas (tablet) → 3 colunas (desktop)
- Projetos incluem links para repositórios

### 📧 Formulário de Contato
- Campos para nome, email e mensagem
- Validação HTML5 (obrigatório)
- Design responsivo em duas colunas (desktop)
- Botão de envio estilizado

### 🎨 Design System
- **Modo Claro**: Paleta neutra com acentos azuis e alaranjados
- **Modo Escuro**: Tema escuro com alto contraste
- **Cores Principais**:
  - Fundo: `#f7f4ef` (claro) / `#0e0f12` (escuro)
  - Texto: `#1e1c18` (claro) / `#f5f6f7` (escuro)
  - Destaque: `#1d3557` (azul) / `#e07a5f` (laranja)

### 🌓 Alternância de Tema
- Botão toggle no header
- Detecta preferência do sistema com `prefers-color-scheme`
- Salva escolha do usuário em `localStorage`
- Transições suaves entre temas

## 🚀 Como Usar

### Visualizar no Navegador
1. Clone o repositório:
   ```bash
   git clone https://github.com/ronaldo-uespi/ronaldo-atv-01.git
   cd ronaldo-atv-01
   ```

2. Abra o arquivo `index.html` diretamente no navegador:
   - Clique duplo em `index.html`
   - Ou arraste o arquivo para o navegador
   - Ou use um servidor local (veja abaixo)

### Com Servidor Local (Recomendado)
**Opção 1 - Python 3:**
```bash
python -m http.server 8000
```
Acesse: `http://localhost:8000`

**Opção 2 - Node.js com http-server:**
```bash
npx http-server
```

**Opção 3 - VSCode com Live Server:**
- Instale a extensão "Live Server"
- Clique direito em `index.html` → "Open with Live Server"

## 📊 Responsividade

O projeto utiliza **mobile-first** e é otimizado para:

| Dispositivo | Breakpoint | Layout |
|------------|-----------|--------|
| 📱 Celular | < 420px | Stack único, ajustes compactos |
| 📱 Celular | 420px - 719px | Coluna única, padding menor |
| 📋 Tablet | 720px - 1023px | 2 colunas (projetos), flex (nav) |
| 💻 Desktop | ≥ 1024px | 3 colunas (projetos), layout completo |

## 🎓 Conceitos Demonstrados

- ✅ **Semântica HTML5**: `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`
- ✅ **CSS Grid & Flexbox**: Layouts responsivos sem frameworks
- ✅ **CSS Custom Properties**: Variáveis de tema (`--bg`, `--text`, etc.)
- ✅ **Media Queries**: Adaptação para diferentes telas
- ✅ **JavaScript DOM**: Manipulação dinâmica de elementos
- ✅ **localStorage**: Persistência de preferências do usuário
- ✅ **Acessibilidade**: Labels, ARIA attributes, contrast ratio
- ✅ **Git**: Versionamento e controle de código

## 📝 Projeto Seguinte

Após esta atividade, o portfólio foi **migrado para React** na Atividade 02:
- 🔗 [ronaldo-atv-02-react](https://github.com/ronaldo-uespi/ronaldo-atv-02-react)
- Componentização com React
- Renderização dinâmica
- Build com Vite

## 📄 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autor

**Ronaldo Inácio**
- 📧 Email: ronaldo.202093@yahoo.com
- 🐙 GitHub: [@ronaldo-uespi](https://github.com/ronaldo-uespi)
- 🎓 Atividade 01 - Desenvolvimento Web

---

**Última atualização:** 13 de abril de 2026

**Status:** ✅ Concluído e funcional
