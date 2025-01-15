### **Aula: M01U01A05 - Layouts com Flexbox***Objetivo da Aula:**  
Ensinar como usar o modelo de layout Flexbox para alinhar, distribuir e organizar elementos em uma página, utilizando arquivos CSS externos para separar os estilos.

---

### **Atividades Práticas**

#### **Atividade 1: Centralizando um Elemento na Tela**
**Contexto:** Aprender a centralizar elementos horizontal e verticalmente.  
**Descrição:** Crie um arquivo `index.html` e um arquivo `styles.css` para centralizar um texto.

**index.html:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Centralização</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <p>Texto centralizado</p>
    </div>
</body>
</html>
```

**styles.css:**
```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
}
```

**Objetivo:** Introduzir o uso de arquivos CSS externos e conceitos básicos de Flexbox.

---

#### **Atividade 2: Criando um Layout com Duas Colunas**
**Contexto:** Dividir o conteúdo da página em duas colunas.  
**Descrição:** Crie um layout básico com colunas lado a lado.

**index.html:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Duas Colunas</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="coluna texto">Texto aqui</div>
        <div class="coluna imagem">Imagem aqui</div>
    </div>
</body>
</html>
```

**styles.css:**
```css
.container {
    display: flex;
    gap: 20px;
}

.coluna {
    flex: 1;
    padding: 20px;
    border: 1px solid #ccc;
}

.texto {
    background-color: #e3f2fd;
}

.imagem {
    background-color: #ffecb3;
}
```

**Objetivo:** Mostrar como criar layouts flexíveis com largura ajustável.

---

#### **Atividade 3: Criando um Menu de Navegação Horizontal**
**Contexto:** Criar um menu de navegação usando Flexbox.  
**Descrição:** Alinhe os links horizontalmente e crie um efeito de destaque ao passar o mouse.

**index.html:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu de Navegação</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="menu">
        <a href="#">Home</a>
        <a href="#">Sobre</a>
        <a href="#">Serviços</a>
        <a href="#">Contato</a>
    </nav>
</body>
</html>
```

**styles.css:**
```css
.menu {
    display: flex;
    justify-content: space-around;
    background-color: #333;
    padding: 10px;
}

.menu a {
    color: white;
    text-decoration: none;
    padding: 5px 10px;
}

.menu a:hover {
    background-color: #555;
}
```

**Objetivo:** Ensinar a organizar links com Flexbox e estilizar menus de navegação.

---

#### **Atividade 4: Criando um Layout Responsivo**
**Contexto:** Criar um layout que se ajuste automaticamente em telas menores.  
**Descrição:** Use `flex-wrap` para permitir a quebra de linha dos elementos.

**index.html:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Responsivo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="box">Caixa 1</div>
        <div class="box">Caixa 2</div>
        <div class="box">Caixa 3</div>
    </div>
</body>
</html>
```

**styles.css:**
```css
.container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.box {
    flex: 1 1 200px;
    padding: 20px;
    text-align: center;
    border: 1px solid #ccc;
    background-color: #e1f5fe;
}
```

**Objetivo:** Demonstrar `flex-wrap` para criar layouts adaptáveis.

---

#### **Atividade 5: Criando um Rodapé Fixo**
**Contexto:** Posicionar um rodapé fixo na parte inferior da página.  
**Descrição:** Use Flexbox para estruturar o conteúdo principal e fixar o rodapé.

**index.html:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rodapé Fixo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="conteudo">
        <p>Conteúdo principal aqui.</p>
    </div>
    <footer class="rodape">
        <p>Rodapé fixo</p>
    </footer>
</body>
</html>
```

**styles.css:**
```css
body {
    display: flex;
    flex-direction: column;
    height: 100vh;
    margin: 0;
}

.conteudo {
    flex: 1;
    padding: 20px;
}

.rodape {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
```

**Objetivo:** Ensinar como estruturar uma página completa com Flexbox.

---

### **Contextualização das Atividades**
- **Cenário Real:** O Flexbox é amplamente utilizado para criar layouts responsivos e organizados em páginas web.
- **Extensão:** Proponha aos alunos usar o Flexbox para construir layouts completos, como landing pages ou portfólios.