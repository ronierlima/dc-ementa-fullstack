### **Aula: M01U01A03 - Formulários e Introdução ao CSS**

**Objetivo da Aula:**  
Ensinar como criar formulários básicos para capturar dados do usuário e introduzir a aplicação de estilos simples utilizando CSS inline e seletivos.

---

### **Atividades Práticas**

#### **Atividade 1: Criando um Formulário Simples**
**Contexto:** Criar um formulário básico que capture informações de nome e e-mail.  
**Descrição:** Crie um formulário HTML com os seguintes elementos:
- Campo de texto para nome.
- Campo de texto para e-mail.
- Botão de envio.

**Exemplo de Código:**
```html
<form>
    <label for="name">Nome:</label>
    <input type="text" id="name" name="name"><br><br>

    <label for="email">E-mail:</label>
    <input type="email" id="email" name="email"><br><br>

    <button type="submit">Enviar</button>
</form>
```

**Objetivo:** Ensinar os alunos a criar formulários básicos com `<form>`, `<label>`, `<input>` e `<button>`.

---

#### **Atividade 2: Personalizando a Organização com Quebras de Linha**
**Contexto:** Melhorar a aparência do formulário usando quebras de linha (`<br>`).  
**Descrição:** Organize os elementos do formulário para que fiquem mais claros e espaçados.

**Exemplo de Código:**
```html
<form>
    <label for="name">Nome:</label><br>
    <input type="text" id="name" name="name"><br><br>

    <label for="email">E-mail:</label><br>
    <input type="email" id="email" name="email"><br><br>

    <button type="submit">Enviar</button>
</form>
```

**Objetivo:** Demonstrar o uso de `<br>` para melhorar a legibilidade.

---

#### **Atividade 3: Aplicando CSS Inline**
**Contexto:** Tornar o formulário mais atraente utilizando estilos simples inline.  
**Descrição:** Adicione estilos diretamente às tags HTML para alterar:
- A largura dos campos de texto.
- A cor do botão.

**Exemplo de Código:**
```html
<form>
    <label for="name">Nome:</label><br>
    <input type="text" id="name" name="name" style="width: 100%;"><br><br>

    <label for="email">E-mail:</label><br>
    <input type="email" id="email" name="email" style="width: 100%;"><br><br>

    <button type="submit" style="background-color: blue; color: white;">Enviar</button>
</form>
```

**Objetivo:** Introduzir CSS inline para personalização básica.

---

#### **Atividade 4: Criando um Formulário com Estrutura Melhorada**
**Contexto:** Reorganizar os elementos do formulário para criar uma estrutura mais visualmente equilibrada.  
**Descrição:** Alinhe os campos usando `div` para organizar o conteúdo.

**Exemplo de Código:**
```html
<form>
    <div style="margin-bottom: 10px;">
        <label for="name">Nome:</label><br>
        <input type="text" id="name" name="name" style="width: 100%;">
    </div>

    <div style="margin-bottom: 10px;">
        <label for="email">E-mail:</label><br>
        <input type="email" id="email" name="email" style="width: 100%;">
    </div>

    <button type="submit" style="background-color: blue; color: white;">Enviar</button>
</form>
```

**Objetivo:** Mostrar como usar `div` para melhorar a organização de elementos.

---

#### **Atividade 5: Adicionando Títulos e Instruções ao Formulário**
**Contexto:** Fornecer contexto ao formulário para orientar o usuário.  
**Descrição:** Adicione um título principal (`<h1>`) e uma descrição (`<p>`) antes do formulário.

**Exemplo de Código:**
```html
<h1>Formulário de Contato</h1>
<p>Preencha as informações abaixo para entrar em contato conosco:</p>

<form>
    <div style="margin-bottom: 10px;">
        <label for="name">Nome:</label><br>
        <input type="text" id="name" name="name" style="width: 100%;">
    </div>

    <div style="margin-bottom: 10px;">
        <label for="email">E-mail:</label><br>
        <input type="email" id="email" name="email" style="width: 100%;">
    </div>

    <button type="submit" style="background-color: blue; color: white;">Enviar</button>
</form>
```

**Objetivo:** Ensinar como melhorar a usabilidade do formulário com títulos e instruções claras.

---

### **Solução Final (Combinação de Todas as Atividades)**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário Básico</title>
</head>
<body>
    <h1>Formulário de Contato</h1>
    <p>Preencha as informações abaixo para entrar em contato conosco:</p>

    <form>
        <div style="margin-bottom: 10px;">
            <label for="name">Nome:</label><br>
            <input type="text" id="name" name="name" style="width: 100%;">
        </div>

        <div style="margin-bottom: 10px;">
            <label for="email">E-mail:</label><br>
            <input type="email" id="email" name="email" style="width: 100%;">
        </div>

        <button type="submit" style="background-color: blue; color: white;">Enviar</button>
    </form>
</body>
</html>
```

---

### **Contextualização da Atividade**
- **Cenário Real:** Os alunos criam um formulário funcional para capturar informações de usuários, como em sites de contato ou cadastros simples.
- **Extensão:** Os alunos podem adicionar campos extras para informações adicionais, como telefone ou comentários.
