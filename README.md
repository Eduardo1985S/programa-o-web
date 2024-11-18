# Estrutura de Projeto HTML, CSS e JavaScript

Este projeto utiliza uma estrutura organizada para facilitar o desenvolvimento, manutenção e escalabilidade. Abaixo está a descrição de como as pastas e arquivos estão organizados.

---

## Estrutura de Pastas

```plaintext
project/
│
├── index.html                # Página principal do projeto
├── about.html                # Outras páginas (exemplo)
├── contact.html              # Outras páginas (exemplo)
│
├── assets/                   # Arquivos estáticos (imagens, fontes, etc.)
│   ├── images/               # Imagens do projeto
│   │   ├── logo.png
│   │   └── background.jpg
│   │
│   ├── fonts/                # Fontes personalizadas
│   │   └── custom-font.woff2
│   │
│   └── icons/                # Ícones (SVG ou outros formatos)
│       └── favicon.ico
│
├── css/                      # Arquivos CSS
│   ├── styles.css            # Estilos gerais
│   ├── bootstrap.min.css     # Bootstrap (se não usar CDN)
│   ├── animations.css        # Estilos para animações (como Animate.css)
│   └── custom.css            # Estilos personalizados
│
├── js/                       # Scripts JavaScript
│   ├── main.js               # Scripts principais
│   ├── bootstrap.bundle.min.js # Bootstrap JS (se não usar CDN)
│   ├── animations.js         # Scripts para animações (se necessário)
│   └── helpers.js            # Funções utilitárias
│
├── scss/                     # Arquivos SCSS (se usar pré-processador)
│   ├── _variables.scss       # Variáveis de estilo
│   ├── _mixins.scss          # Mixins reutilizáveis
│   ├── _bootstrap.scss       # Estilos sobreescritos do Bootstrap
│   └── main.scss             # Arquivo principal que compila tudo
│
├── vendor/                   # Bibliotecas externas (se não usar CDN)
│   ├── animate.css/          # Biblioteca de animações
│   │   └── animate.min.css
│   └── bootstrap/            # Arquivos Bootstrap locais
│       ├── css/
│       │   └── bootstrap.min.css
│       └── js/
│           └── bootstrap.bundle.min.js
│
└── README.md                 # Documentação do projeto
````

# Estrutura de Projeto HTML, CSS e JavaScript

Este documento explica a estrutura do projeto, incluindo os diretórios e arquivos principais, e como eles contribuem para a organização, escalabilidade e manutenção do projeto.

---

## Explicação da Estrutura

A estrutura foi criada para manter os arquivos organizados, modularizados e facilmente escaláveis. Aqui está uma explicação detalhada de cada parte:

### 1. **Arquivos HTML**
Os arquivos HTML formam o esqueleto do projeto e são responsáveis por estruturar o conteúdo das páginas.
- **`index.html`**: A página principal do projeto, geralmente a porta de entrada para o usuário.
- **Outras páginas**: Arquivos como `about.html` e `contact.html` representam outras páginas do site.

---

### 2. **Diretório `assets/`**
O diretório `assets/` contém arquivos estáticos usados pelo projeto:
- **`images/`**: Contém imagens como logotipos, banners e backgrounds.
- **`fonts/`**: Armazena fontes personalizadas utilizadas no projeto.
- **`icons/`**: Para ícones como o favicon do site, ou ícones SVG e PNG usados no design.

---

### 3. **Diretório `css/`**
Este diretório contém os arquivos CSS, responsáveis pela estilização do projeto:
- **`styles.css`**: Contém os estilos gerais aplicados às páginas.
- **`bootstrap.min.css`**: Arquivo do Bootstrap que oferece estilos e componentes prontos (opcional se não usar CDN).
- **`animations.css`**: Estilos para animações, como as oferecidas por Animate.css.
- **`custom.css`**: Contém estilos personalizados para ajustes específicos que não estão cobertos pelos outros arquivos.

---

### 4. **Diretório `js/`**
Os arquivos JavaScript adicionam interatividade e lógica ao site:
- **`main.js`**: Lógica principal do site.
- **`bootstrap.bundle.min.js`**: Versão local do JavaScript do Bootstrap (se não usar CDN).
- **`animations.js`**: Scripts relacionados a animações, caso o projeto precise de animações personalizadas.
- **`helpers.js`**: Funções utilitárias que podem ser reutilizadas em diferentes partes do projeto.

---

### 5. **Diretório `scss/` (opcional)**
Se o projeto utilizar SCSS (pré-processador CSS), este diretório ajuda a organizar o código:
- **`_variables.scss`**: Contém variáveis reutilizáveis (ex.: cores, tamanhos).
- **`_mixins.scss`**: Mixins são trechos de código reutilizáveis para estilos mais complexos.
- **`_bootstrap.scss`**: Permite sobrescrever estilos padrão do Bootstrap para personalização.
- **`main.scss`**: Arquivo principal que importa todos os outros arquivos SCSS e é compilado para gerar o CSS final.

---

### 6. **Diretório `vendor/`**
Armazena bibliotecas externas que o projeto usa, caso não sejam carregadas por um CDN:
- **`animate.css/`**: Contém a biblioteca de animações Animate.css.
- **`bootstrap/`**: Versão local dos arquivos do Bootstrap (CSS e JS).

---

### 7. **Arquivo `README.md`**
Este arquivo documenta o projeto, descrevendo a estrutura, tecnologias usadas, e como rodar o projeto.

---

## Por Que Usar Essa Estrutura?

1. **Organização**: Separa arquivos por tipo (HTML, CSS, JS, etc.), facilitando o gerenciamento.
2. **Manutenção**: Estrutura modular permite atualizar ou substituir partes do projeto sem confusão.
3. **Escalabilidade**: Suporte para crescimento com diretórios bem organizados.
4. **Colaboração**: Facilita o entendimento e trabalho em equipe.

---

## Como Usar Este Projeto?

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>

