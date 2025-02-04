# Projeto FullStack

# garagem_hamburgueria
Homepage da Garagem Hamburgueria

# Geração da página com a ajuda do CHATGPT:
Aqui está a estrutura completa da **Garagem Hamburgueria** com HTML, CSS e JavaScript.  

---

Aqui está a **estrutura completa da Garagem Hamburgueria**, com todos os arquivos organizados e seus conteúdos.  

---

## **📂 Estrutura de Arquivos**
```
/garagem-hamburgueria
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
    <title>Garagem Hamburgueria</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <div class="logo">
            <a href="index.html">
                <img src="images/logo.png" alt="Garagem Hamburgueria">
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
        <p>&copy; 2024 Garagem Hamburgueria. Todos os direitos reservados.</p>
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
    <title>Cardápio - Garagem Hamburgueria</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <a href="index.html">
                <img src="images/logo.png" alt="Garagem Hamburgueria">
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
        <p>&copy; 2024 Garagem Hamburgueria. Todos os direitos reservados.</p>
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
    <title>Sobre Nós - Garagem Hamburgueria</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <a href="index.html">
                <img src="images/logo.png" alt="Garagem Hamburgueria">
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
        <p>A Garagem Hamburgueria nasceu da paixão por hambúrgueres artesanais e ingredientes de qualidade.</p>
    </section>

    <footer>
        <p>&copy; 2024 Garagem Hamburgueria. Todos os direitos reservados.</p>
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
    <title>Contato - Garagem Hamburgueria</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <div class="logo">
            <a href="index.html">
                <img src="images/logo.png" alt="Garagem Hamburgueria">
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
        <p>📧 contato@garagemhamburgueria.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Garagem Hamburgueria. Todos os direitos reservados.</p>
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

