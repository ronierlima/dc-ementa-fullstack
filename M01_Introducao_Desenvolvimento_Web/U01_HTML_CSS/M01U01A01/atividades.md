### **Aula: M01U01A01 - Introdução ao HTML e Estruturas Básicas**

**Objetivo da Aula:**  
Introduzir a estrutura básica de um documento HTML e ensinar como criar e organizar elementos fundamentais como títulos, parágrafos, links e imagens.

---

### **Atividades Práticas**

#### **Atividade 1: Criando a Estrutura Básica**
**Contexto:** O aluno aprenderá a criar a base de um documento HTML.  
**Descrição:** Crie um arquivo `index.html` que contenha a estrutura básica de uma página HTML. Inclua:
- A tag `<!DOCTYPE>`.
- As tags `html`, `head` e `body`.
- Um título no navegador.

**Exemplo de Código:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Primeira Página</title>
</head>
<body>
    <h1>Bem-vindo ao meu site</h1>
</body>
</html>
```

**Objetivo:** Ensinar a estrutura básica e o uso correto das tags principais.

---

#### **Atividade 2: Adicionando um Parágrafo e um Link**
**Contexto:** O aluno criará conteúdo textual com parágrafos e adicionará links.  
**Descrição:** No mesmo arquivo, adicione um parágrafo com uma breve descrição e um link para um site externo (ex.: Google).

**Exemplo de Código:**
```html
<p>Este é um site de exemplo criado na minha primeira aula de HTML.</p>
<p>Visite o <a href="https://www.google.com" target="_blank">Google</a> para saber mais.</p>
```

**Objetivo:** Introduzir as tags de texto e links (`<p>` e `<a>`).

---

#### **Atividade 3: Inserindo Imagens**
**Contexto:** Adicionar elementos visuais à página.  
**Descrição:** Insira uma imagem abaixo do parágrafo. Use uma imagem pública ou uma URL da internet.

**Exemplo de Código:**
```html
<img src="https://via.placeholder.com/150" alt="Imagem de exemplo">
```

**Objetivo:** Trabalhar com a tag `<img>` e aprender a adicionar descrições para acessibilidade.

---

#### **Atividade 4: Criando uma Lista**
**Contexto:** Organizar informações usando listas.  
**Descrição:** Crie uma lista não ordenada com os tópicos aprendidos na aula.

**Exemplo de Código:**
```html
<ul>
    <li>Estrutura básica do HTML</li>
    <li>Tags para texto</li>
    <li>Links e imagens</li>
</ul>
```

**Objetivo:** Ensinar a organização de conteúdo com listas (`<ul>` e `<li>`).

---

#### **Atividade 5: Personalizando o Título da Página**
**Contexto:** Ajustar o título exibido na aba do navegador.  
**Descrição:** Atualize o `<title>` no `<head>` para refletir o tema da página.

**Exemplo:**
```html
<title>Minha Página de Aprendizado</title>
```

**Objetivo:** Mostrar como o título afeta a experiência do usuário e SEO.

---

### **Solução Final (Combinação de Todas as Atividades)**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página de Aprendizado</title>
</head>
<body>
    <h1>Bem-vindo ao meu site</h1>
    <p>Este é um site de exemplo criado na minha primeira aula de HTML.</p>
    <p>Visite o <a href="https://www.google.com" target="_blank">Google</a> para saber mais.</p>
    <img src="https://via.placeholder.com/150" alt="Imagem de exemplo">
    <ul>
        <li>Estrutura básica do HTML</li>
        <li>Tags para texto</li>
        <li>Links e imagens</li>
    </ul>
</body>
</html>
```

---

### **Contextualização da Atividade**
- **Cenário Real:** Os alunos estão criando sua primeira página web, que servirá como base para projetos futuros.
- **Extensão:** Incentive os alunos a personalizarem a página adicionando informações sobre seus hobbies ou interesses.