### **Aula: M01U01A04 - Estilização Básica e Seletores CSS**

**Objetivo da Aula:**  
Ensinar a aplicar estilos básicos utilizando CSS, introduzindo seletores como tags, classes, IDs e combinações simples para personalizar elementos HTML.

---

### **Atividades Práticas**

#### **Atividade 1: Alterando as Cores de Títulos e Parágrafos**
**Contexto:** Aplicar cores básicas a elementos utilizando seletores de tags.  
**Descrição:** Crie um arquivo HTML com um título e dois parágrafos. Use CSS para:
- Alterar a cor do título.
- Aplicar uma cor de fundo e alterar a cor da fonte dos parágrafos.

**HTML:**
```html
<h1>Bem-vindo ao meu site</h1>
<p>Este é o primeiro parágrafo do meu site.</p>
<p>Este é o segundo parágrafo, com um fundo diferente.</p>
```

**CSS:**
```html
h1 {
    color: blue;
}

p {
    background-color: lightgray;
    color: black;
    padding: 10px;
}
```

**Objetivo:** Ensinar a usar seletores de tags para estilizar elementos.

---

#### **Atividade 2: Personalizando Elementos com Classes**
**Contexto:** Estilizar múltiplos elementos que compartilham o mesmo estilo.  
**Descrição:** Crie uma lista de itens com duas categorias (ex.: frutas e legumes). Use classes para aplicar estilos diferentes.

**HTML:**
```html
<ul>
    <li class="fruta">Maçã</li>
    <li class="fruta">Banana</li>
    <li class="legume">Cenoura</li>
    <li class="legume">Brócolis</li>
</ul>
```

**CSS:**
```css
.fruta {
    color: red;
}

.legume {
    color: green;
}
```

**Objetivo:** Introduzir classes como uma forma eficiente de estilizar grupos de elementos.

---

#### **Atividade 3: Estilizando um Elemento Específico com IDs**
**Contexto:** Destacar um único elemento com estilo exclusivo.  
**Descrição:** Crie um parágrafo especial e use um ID para aplicar um estilo único.

**HTML:**
```html
<p id="destaque">Este parágrafo é único e possui um estilo exclusivo.</p>
```

**CSS:**
```css
#destaque {
    font-size: 20px;
    font-weight: bold;
    color: purple;
    background-color: yellow;
    padding: 10px;
}
```

**Objetivo:** Mostrar o uso de IDs para estilos exclusivos de elementos específicos.

---

#### **Atividade 4: Trabalhando com Seletores Combinados**
**Contexto:** Criar estilos complexos para elementos que atendem a critérios específicos.  
**Descrição:** Estilize apenas os links que estão dentro de um parágrafo.

**HTML:**
```html
<p>Visite o <a href="https://www.google.com">Google</a> para mais informações.</p>
<p>Este é apenas um texto sem links.</p>
```

**CSS:**
```css
p a {
    color: blue;
    text-decoration: none;
    font-weight: bold;
}

p a:hover {
    text-decoration: underline;
    color: darkblue;
}
```

**Objetivo:** Demonstrar o uso de seletores combinados para aplicar estilos contextuais.

---

#### **Atividade 5: Adicionando Estilos Globais**
**Contexto:** Aplicar estilos padrão para toda a página.  
**Descrição:** Defina um estilo global para a página que:
- Altere a fonte de todos os textos.
- Adicione um fundo cinza claro para o corpo.

**HTML:**
```html
<h1>Meu Site</h1>
<p>Texto com a fonte padrão definida.</p>
```

**CSS:**
```css
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 20px;
}

h1 {
    color: navy;
}
```

**Objetivo:** Introduzir o conceito de estilos globais usando o seletor `body`.

---

### **Solução Final (Combinação de Todas as Atividades)**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estilização com CSS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }

        h1 {
            color: blue;
        }

        p {
            background-color: lightgray;
            color: black;
            padding: 10px;
        }

        .fruta {
            color: red;
        }

        .legume {
            color: green;
        }

        #destaque {
            font-size: 20px;
            font-weight: bold;
            color: purple;
            background-color: yellow;
            padding: 10px;
        }

        p a {
            color: blue;
            text-decoration: none;
            font-weight: bold;
        }

        p a:hover {
            text-decoration: underline;
            color: darkblue;
        }
    </style>
</head>
<body>
    <h1>Bem-vindo ao meu site</h1>

    <p>Este é o primeiro parágrafo do meu site.</p>
    <p>Este é o segundo parágrafo, com um fundo diferente.</p>

    <p id="destaque">Este parágrafo é único e possui um estilo exclusivo.</p>

    <ul>
        <li class="fruta">Maçã</li>
        <li class="fruta">Banana</li>
        <li class="legume">Cenoura</li>
        <li class="legume">Brócolis</li>
    </ul>

    <p>Visite o <a href="https://www.google.com">Google</a> para mais informações.</p>
</body>
</html>
```

---

### **Contextualização da Atividade**
- **Cenário Real:** Personalizar elementos HTML com estilos específicos é essencial para criar interfaces visuais atraentes.
- **Extensão:** Os alunos podem criar páginas temáticas, como um catálogo de produtos ou blog, utilizando os mesmos conceitos.