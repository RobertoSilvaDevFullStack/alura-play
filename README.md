# AluraPlay 🎬

Uma réplica da interface do YouTube criada como projeto educacional, focada em conteúdo de tecnologia da Alura.

![AluraPlay Preview](https://img.shields.io/badge/Status-Concluído-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-blue)

## 📋 Sobre o Projeto

O **AluraPlay** é uma interface que simula a página inicial do YouTube, desenvolvida com foco em aprendizado de HTML e CSS. O projeto apresenta vídeos educacionais da Alura sobre programação, data science, mobile e outras tecnologias.

## 🚀 Funcionalidades

- ✅ Interface responsiva (Mobile, Tablet, Desktop)
- ✅ Layout idêntico ao YouTube
- ✅ Vídeos funcionais incorporados do YouTube
- ✅ Sistema de navegação completo
- ✅ Efeitos de hover e transições
- ✅ Grid flexível de vídeos

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização e animações
- **Flexbox**: Layout flexível
- **CSS Grid**: Organização de conteúdo
- **Google Fonts**: Tipografia (Roboto)

## 📱 Responsividade

O projeto adapta-se a diferentes tamanhos de tela:

- **📱 Mobile**: Menu inferior, layout simplificado
- **📱 Tablet (834px+)**: Menu lateral, barra de pesquisa
- **💻 Desktop (1440px+)**: Menu expandido, layout completo

## 🎨 Design

### Paleta de Cores

```css
--azul-escuro: #154580   /* Menu lateral */
--azul-medio: #3970BE    /* Hovers e bordas */
--azul-claro: #E5F1FF    /* Fundo principal */
--cinza-texto: #444444   /* Textos */
--cinza-claro: #ECECEC   /* Elementos */
```

## 📁 Estrutura do Projeto

```
alura-play/
├── index.html          # Página principal
├── README.md           # Documentação
├── css/
│   ├── reset.css       # Reset CSS
│   ├── estilos.css     # Estilos principais
│   └── flexbox.css     # Layout responsivo
└── img/                # Recursos visuais
    ├── favicon.ico
    ├── cabecalho/      # Ícones do header
    ├── menu/           # Ícones do menu
    └── videos/         # Thumbnails
```

## 🚀 Como Executar

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/RobertoSilvaDevFullStack/alura-play.git
   ```

2. **Navegue até o diretório:**

   ```bash
   cd alura-play
   ```

3. **Abra o arquivo `index.html` no navegador**

   Ou use um servidor local:

   ```bash
   # Com Python
   python -m http.server 8000

   # Com Node.js (http-server)
   npx http-server

   # Com Live Server (VS Code)
   # Clique direito no index.html > Open with Live Server
   ```

## 📚 Conteúdo dos Vídeos

O projeto inclui 16 vídeos educacionais sobre:

- **Programação**: JavaScript, Go, Hardware
- **Data Science**: Ferramentas, Bootcamps, Práticas
- **Mobile**: React Native, Flutter, Frameworks
- **Carreira**: Mercado de trabalho, Transições
- **Tecnologia**: Linux, Jetpack Compose

## 🎯 Objetivos de Aprendizagem

Este projeto é ideal para praticar:

- ✅ HTML semântico e estruturado
- ✅ CSS Flexbox e Grid
- ✅ Design responsivo
- ✅ Metodologia mobile-first
- ✅ Organização de código CSS
- ✅ Integração com APIs externas (YouTube)

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie sua feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Desenvolvedor

**Roberto Silva**

- GitHub: [@RobertoSilvaDevFullStack](https://github.com/RobertoSilvaDevFullStack)

---

**Feito com ❤️ durante o curso da Alura**
