# Portfólio Pessoal - Gabriel Adami Tobaldini
Este projeto é um portfólio pessoal responsivo desenvolvido para demonstrar habilidades em desenvolvimento web. O site apresenta informações profissionais, habilidades técnicas, projetos exemplificados e formas de contato.

## Descrição do Site
O portfólio é um site de página única, com design moderno e responsivo. O layout é centrado no usuário, com navegação intuitiva e seções claramente definidas. O design prioriza a experiência do usuário com animações, transições e uma estrutura de informação hierárquica.

## Funcionalidades de Cada Seção

### 1. Navegação
- Menu de navegação fixo no topo;
- Links para todas as seções do site;
- Efeito de transparência ao rolar a página.

### 2. Início
- Apresentação pessoal com foto de perfil;
- Tags destacando principais áreas de atuação;
- Botões de chamada para ver os projetos e contato.

### 3. Sobre Mim
- Cards informativos sobre experiência profissional e acadêmica;
- Seção de habilidades técnicas com barras de progresso animadas;
- Animação das barras de progresso ao entrar na viewport.

### 4. Projetos
- Lista de projetos de exemplo desenvolvidos com descrições;
- Links para repositórios no GitHub;
- Efeito de hover com deslocamento e sombra;
- Numeração visual para melhor organização.

### 5. Experiência
- Timeline vertical mostrando trajetória profissional e acadêmica;
- Organização cronológica reversa (mais recente primeiro);
- Formatação clara de datas e descrições.

### 6. Contato
- Informações de contato (email, telefone, localização);
- Links para redes sociais com ícones de seta;
- Formulário de contato funcional com validação de campos;
- Feedback visual após envio da mensagem.

### 7. Rodapé (Footer)
- Informações de copyright;
- Design minimalista em fundo escuro.

## Tecnologias Utilizadas

- **HTML**: Estruturação semântica do conteúdo;
- **CSS**: Variáveis CSS para consistência visual, flexbox grid para layouts responsivos, animações e transições para interatividade;
- **JavaScript**: Manipulação do DOM para interatividade, Intersection Observer API para animações baseadas em scroll, validação de formulário.

## Estrutura do Projeto
portfolio/
│
├── index.html                  # Arquivo HTML principal
│
├── src/
│   ├── assets/
│   │   ├── fonts/              # Fontes personalizadas (se houver)
│   │   └── images/             # Imagens do site
│   │       ├── profile.jpg     # Foto de perfil
│   │
│   ├── styles/
│   │   ├── reset.css           # Reset CSS para normalização
│   │   ├── root.css            # Variáveis CSS globais
│   │   ├── fonts.css           # Configurações de tipografia
│   │   ├── main.css            # Estilos principais
│   │   └── responsive.css      # Media queries para responsividade
│   │
│   └── scripts/
│       └── main.js             # JavaScript principal
│
└── README.md                   # Documentação do projeto

## Como Executar o Projeto

### Instalação Local
1. Clone o repositório: git clone https://github.com/seu-usuario/portfolio.git;
2. Navegue até a pasta do projeto: cd portfolio;
3. Abra o arquivo `index.html` em seu navegador: use um servidor local como Live Server do VS Code

Desenvolvido por Gabriel Adami Tobaldini, trabalho acadêmico de Desenvolvimento Web.