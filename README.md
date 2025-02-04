# Projeto FullStack

# garagem_hamburgueria
Homepage da Garagem Hamburgueria

# Geração da página com a ajuda do CHATGPT:
Aqui está a estrutura completa da **Garagem Hamburgueria** com HTML, CSS e JavaScript.  

---

### **1. `index.html`** (Página Principal)
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
            <img src="images/logo.png" alt="Garagem Hamburgueria">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#menu">Cardápio</a></li>
                <li><a href="#about">Sobre</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="banner">
        <h1>O Melhor Hambúrguer da Cidade!</h1>
        <p>Sabor artesanal feito com paixão.</p>
        <a href="#menu" class="btn">Ver Cardápio</a>
    </section>

    <section id="menu">
        <h2>Nosso Cardápio</h2>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="images/burger1.jpg" alt="Burger Clássico">
                <h3>Clássico da Garagem</h3>
                <p>Pão artesanal, carne angus, queijo cheddar e molho especial.</p>
                <span class="price">R$ 25,00</span>
            </div>
            <div class="menu-item">
                <img src="images/burger2.jpg" alt="Burger BBQ">
                <h3>BBQ Bacon</h3>
                <p>Pão brioche, carne angus, queijo prato, bacon crocante e molho BBQ.</p>
                <span class="price">R$ 28,00</span>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>Sobre Nós</h2>
        <p>A Garagem Hamburgueria nasceu da paixão por hambúrgueres artesanais e ingredientes de qualidade.</p>
    </section>

    <section id="contact">
        <h2>Contato</h2>
        <p>📍 Rua dos Sabores, 123 - São Paulo</p>
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

### **2. `styles.css`** (Estilo da Página)
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #222;
    color: #fff;
    text-align: center;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #111;
    padding: 15px;
}

.logo img {
    height: 50px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

.banner {
    background: url('images/banner.jpg') no-repeat center center/cover;
    padding: 100px 20px;
}

.banner h1 {
    font-size: 40px;
    margin-bottom: 10px;
}

.banner p {
    font-size: 18px;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    background: #ff6600;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 15px;
}

.menu-grid {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
}

.menu-item {
    background: #333;
    padding: 15px;
    border-radius: 10px;
    text-align: center;
    width: 250px;
}

.menu-item img {
    width: 100%;
    border-radius: 10px;
}

.menu-item h3 {
    margin-top: 10px;
    font-size: 22px;
}

.price {
    font-size: 18px;
    color: #ff6600;
    font-weight: bold;
    display: block;
    margin-top: 5px;
}

footer {
    background: #111;
    padding: 20px;
    margin-top: 20px;
}
```

---

### **3. `script.js`** (Interatividade)
```js
document.addEventListener("DOMContentLoaded", function () {
    console.log("Garagem Hamburgueria - Site carregado!");
    
    // Exemplo de interatividade: alerta ao clicar no botão do cardápio
    document.querySelector(".btn").addEventListener("click", function () {
        alert("Veja nosso cardápio delicioso!");
    });
});
```

---

## **Hospedagem**
Para hospedar remotamente, você pode usar:
1. **GitHub Pages** (grátis)
   - Crie um repositório e envie os arquivos.
   - Vá em *Settings > Pages* e selecione a branch para hospedar.

2. **Netlify** (rápido e fácil)
   - Acesse [Netlify](https://www.netlify.com/), faça login e faça o upload da pasta.

3. **Vercel** (ideal para projetos modernos)
   - Acesse [Vercel](https://vercel.com/), conecte seu repositório e implante o site.

---

### **📌 O que podemos melhorar?**
- Adicionar mais itens ao cardápio 🍔
- Criar uma página para pedidos online 🛒
- Melhorar o design do site 🎨

O que acha? Quer adicionar mais funcionalidades? 🚀

---

