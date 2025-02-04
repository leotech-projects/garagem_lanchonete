# Projeto FullStack

# garagem_hamburgueria
Homepage da Garagem Hamburgueria JF

# Geração da página com a ajuda do CHATGPT:
Aqui está a estrutura completa da **Garagem Hamburgueria JF** com HTML, CSS e JavaScript.  

---

Aqui está a **estrutura completa da Garagem Hamburgueria JF**, com todos os arquivos organizados e seus conteúdos.  

---

## **📂 Estrutura de Arquivos**
```
/garagem-hamburgueria-jf
│── index.html        # Página principal
│── menu.html         # Página do Cardápio
│── about.html        # Página Sobre a Hamburgueria
│── contact.html      # Página de Contato
│── styles.css        # Arquivo de Estilos
│── script.js         # Arquivo de Scripts
│── /images           # Pasta para imagens (logo, hambúrgueres, banner)
│── /assets           # Outros arquivos (ícones, fontes)
```

---

## **📄 1. `index.html` (Página Principal)**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Garagem Hamburgueria JF</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <div class="logo">
            <a href="index.html">
                <img src="images/logo.png" alt="Garagem Hamburgueria JF">
            </a>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="menu.html">Cardápio</a></li>
                <li><a href="about.html">Sobre</a></li>
                <li><a href="contact.html">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h1>O Melhor Hambúrguer da Cidade!</h1>
        <p>Sabor artesanal feito com paixão.</p>
        <a href="menu.html" class="btn">Ver Cardápio</a>
    </section>

    <footer>
        <p>&copy; 2025 Garagem Hamburgueria JF. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
```

---

## **📄 2. `menu.html` (Página do Cardápio)**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cardápio - Garagem Hamburgueria JF</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <a href="index.html">
                <img src="images/logo.png" alt="Garagem Hamburgueria JF">
            </a>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="menu.html">Cardápio</a></li>
                <li><a href="about.html">Sobre</a></li>
                <li><a href="contact.html">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h1>Nosso Cardápio</h1>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="images/burger1.jpg" alt="Clássico da Garagem">
                <h3>Clássico da Garagem</h3>
                <p>Pão artesanal, carne angus, queijo cheddar e molho especial.</p>
                <span class="price">R$ 25,00</span>
            </div>
            <div class="menu-item">
                <img src="images/burger2.jpg" alt="BBQ Bacon">
                <h3>BBQ Bacon</h3>
                <p>Pão brioche, carne angus, queijo prato, bacon crocante e molho BBQ.</p>
                <span class="price">R$ 28,00</span>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Garagem Hamburgueria JF. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
```

---

## **📄 3. `about.html` (Página Sobre Nós)**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre Nós - Garagem Hamburgueria JF</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <a href="index.html">
                <img src="images/logo.png" alt="Garagem Hamburgueria JF">
            </a>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="menu.html">Cardápio</a></li>
                <li><a href="about.html">Sobre</a></li>
                <li><a href="contact.html">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="about">
        <h1>Sobre Nós</h1>
        <p>A Garagem Hamburgueria JF nasceu da paixão por hambúrgueres artesanais e ingredientes de qualidade.</p>
    </section>

    <footer>
        <p>&copy; 2025 Garagem Hamburgueria JF. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
```

---

## **📄 4. `contact.html` (Página de Contato)**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contato - Garagem Hamburgueria JF</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <div class="logo">
            <a href="index.html">
                <img src="images/logo.png" alt="Garagem Hamburgueria JF">
            </a>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="menu.html">Cardápio</a></li>
                <li><a href="about.html">Sobre</a></li>
                <li><a href="contact.html">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contato</h1>
        <p>📞 (11) 99999-9999</p>
        <p>📧 contato@garagemhamburgueriajf.com</p>
    </section>

    <footer>
        <p>&copy; 2025 Garagem Hamburgueria jf. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
```

---

## **📄 5. `styles.css` (Arquivo de Estilos)**
```css
body {
    background-color: #222;
    color: #fff;
    text-align: center;
}

header {
    background: #111;
    padding: 15px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

.banner {
    background: url('images/banner.jpg') no-repeat center center/cover;
    padding: 100px 20px;
}
```

---

## **📄 6. `script.js` (Arquivo de Scripts)**
```js
document.addEventListener("DOMContentLoaded", function () {
    console.log("Site carregado!");
});
```

---

### **🚀 Agora sua hamburgueria está completa!**
Para hospedar, basta enviar os arquivos para **GitHub Pages, Netlify ou Vercel**.

Se precisar de mais alguma funcionalidade, me avise! 😊🍔🚀

---
# Explicação dos arquivos:
## Arquivo styles.css
Aqui está a explicação detalhada, linha por linha, para um aluno **iniciante em programação fullstack**, sobre o significado de cada item deste código CSS:

---

## **1. Seletor `body { ... }`**
```css
body { 
    background-color: #222;
    color: #fff;
    text-align: center;
}
```
### O que faz?
- **`body`**: Seletor que aplica estilos ao **corpo** de toda a página HTML.

### Explicação das propriedades:
1. **`background-color: #222;`**  
   - Define a **cor de fundo** da página como **#222** (um tom de cinza escuro).
   - O código hexadecimal `#222` representa um tom próximo ao preto, mas um pouco mais claro.

2. **`color: #fff;`**  
   - Define a **cor do texto** como `#fff`, que representa a cor **branca**.
   - Isso garante que o texto fique visível sobre o fundo escuro.

3. **`text-align: center;`**  
   - Centraliza **todo o texto** dentro do `<body>` da página.
   - Isso significa que qualquer texto que não tenha um alinhamento específico herdará essa configuração.

---

## **2. Seletor `header { ... }`**
```css
header {
    background: #111;
    padding: 15px;
}
```
### O que faz?
- **`header`**: Seletor que estiliza o **cabeçalho** (`<header>`) da página, onde geralmente estão o **logo e o menu de navegação**.

### Explicação das propriedades:
1. **`background: #111;`**  
   - Define a cor de fundo do cabeçalho como **#111** (preto bem escuro).
   - Isso diferencia visualmente o cabeçalho do restante da página.

2. **`padding: 15px;`**  
   - Adiciona **espaçamento interno** de `15px` ao redor do conteúdo do `<header>`, criando um layout mais agradável.

---

## **3. Seletor `nav ul { ... }`**
```css
nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}
```
### O que faz?
- **`nav ul`**: Seletor que estiliza a **lista `<ul>` dentro da navegação (`<nav>`)**.
- O `<ul>` contém os itens de menu, como **Início, Cardápio, Sobre, Contato**.

### Explicação das propriedades:
1. **`list-style: none;`**  
   - Remove os **pontos (•)** padrão que aparecem nas listas (`<ul>`).
   - Isso torna a lista mais adequada para um menu de navegação.

2. **`display: flex;`**  
   - Transforma a `<ul>` em um **container flexível**.
   - O **Flexbox** é um método moderno para alinhar e distribuir elementos dentro de um container.

3. **`justify-content: center;`**  
   - Alinha os itens da `<ul>` (**os links do menu**) **ao centro** da página.
   - Se essa propriedade não existisse, os itens ficariam alinhados à esquerda por padrão.

---

## **4. Seletor `nav ul li { ... }`**
```css
nav ul li {
    margin: 0 15px;
}
```
### O que faz?
- **`nav ul li`**: Seletor que estiliza os **itens individuais da lista** (`<li>`) dentro da `<ul>` do menu de navegação.

### Explicação das propriedades:
1. **`margin: 0 15px;`**  
   - Adiciona **margem lateral** de `15px` entre cada `<li>` do menu.
   - Isso **afasta um item do outro**, evitando que fiquem muito próximos.

---

## **5. Seletor `.banner { ... }`**
```css
.banner {
    background: url('images/banner.jpg') no-repeat center center/cover;
    padding: 100px 20px;
}
```
### O que faz?
- **`.banner`**: Seletor que estiliza a **seção do banner** da página (provavelmente um `<section>` com classe `.banner`).

### Explicação das propriedades:
1. **`background: url('images/banner.jpg') no-repeat center center/cover;`**  
   - Define uma **imagem de fundo** (`banner.jpg`) armazenada na pasta **images**.
   - **`no-repeat`**: Evita que a imagem de fundo se repita.
   - **`center center`**: Posiciona a imagem de fundo **no centro vertical e horizontal**.
   - **`/cover`**: Faz a imagem ocupar **100% da largura e altura da seção**, mantendo a proporção correta.

2. **`padding: 100px 20px;`**  
   - Adiciona um **espaçamento interno**:
     - `100px` na parte superior e inferior → deixa o banner mais alto.
     - `20px` nas laterais → mantém um espaço para o conteúdo.

---

## **📌 Resumo**
| Seletor | Explicação |
|---------|-----------|
| **`body`** | Define o **fundo da página**, **cor do texto** e **centraliza o conteúdo**. |
| **`header`** | Aplica um **fundo escuro** e **espaçamento** ao cabeçalho. |
| **`nav ul`** | Remove os **pontos da lista**, transforma-a em **Flexbox** e **centraliza os links**. |
| **`nav ul li`** | Adiciona **espaçamento lateral** entre os links do menu. |
| **`.banner`** | Insere uma **imagem de fundo**, **centraliza** e **ajusta tamanho** corretamente. |

---

## **🚀 Conclusão**
Este código CSS melhora a aparência e o layout do site, deixando-o mais profissional e organizado.


