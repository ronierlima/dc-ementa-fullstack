### **Aula: M01U01A02 - Tabelas e Listas em HTML**

**Objetivo da Aula:**  
Ensinar a criar tabelas para organizar dados e listas para categorizar informações de forma clara e semântica.

---

### **Atividades Práticas**

#### **Atividade 1: Criando uma Tabela Simples**
**Contexto:** Organizar informações como um cronograma semanal.  
**Descrição:** Crie uma tabela com dias da semana na primeira coluna e três horários de aula nas colunas seguintes.

**Exemplo de Código:**
```html
<table border="1">
    <thead>
        <tr>
            <th>Dia</th>
            <th>Manhã</th>
            <th>Tarde</th>
            <th>Noite</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Segunda-feira</td>
            <td>Matemática</td>
            <td>História</td>
            <td>Física</td>
        </tr>
        <tr>
            <td>Terça-feira</td>
            <td>Português</td>
            <td>Química</td>
            <td>Inglês</td>
        </tr>
    </tbody>
</table>
```

**Objetivo:** Ensinar a criar tabelas com cabeçalho (`<thead>`) e corpo (`<tbody>`), além de trabalhar com bordas básicas.

---

#### **Atividade 2: Adicionando Estilo à Tabela**
**Contexto:** Tornar a tabela visualmente mais atraente.  
**Descrição:** Adicione estilos CSS inline para colorir o cabeçalho e alternar a cor das linhas.

**Exemplo de Código:**
```html
<table border="1">
    <thead style="background-color: #f0f0f0;">
        <tr>
            <th>Dia</th>
            <th>Manhã</th>
            <th>Tarde</th>
            <th>Noite</th>
        </tr>
    </thead>
    <tbody>
        <tr style="background-color: #f9f9f9;">
            <td>Segunda-feira</td>
            <td>Matemática</td>
            <td>História</td>
            <td>Física</td>
        </tr>
        <tr>
            <td>Terça-feira</td>
            <td>Português</td>
            <td>Química</td>
            <td>Inglês</td>
        </tr>
    </tbody>
</table>
```

**Objetivo:** Demonstrar como aplicar estilos simples usando atributos inline.

---

#### **Atividade 3: Criando uma Lista Ordenada**
**Contexto:** Organizar uma sequência de etapas ou tarefas.  
**Descrição:** Crie uma lista ordenada para exibir as etapas de um processo, como uma receita de bolo.

**Exemplo de Código:**
```html
<ol>
    <li>Pré-aqueça o forno a 180°C.</li>
    <li>Separe os ingredientes.</li>
    <li>Misture a massa.</li>
    <li>Asse por 30 minutos.</li>
</ol>
```

**Objetivo:** Introduzir listas ordenadas (`<ol>`) para exibir informações sequenciais.

---

#### **Atividade 4: Criando uma Lista Não Ordenada**
**Contexto:** Categorizar informações sem ordem específica.  
**Descrição:** Crie uma lista de materiais escolares necessários.

**Exemplo de Código:**
```html
<ul>
    <li>Cadernos</li>
    <li>Canetas</li>
    <li>Lápis</li>
    <li>Borracha</li>
</ul>
```

**Objetivo:** Ensinar listas não ordenadas (`<ul>`) e o uso de itens (`<li>`).

---

#### **Atividade 5: Combinação de Tabela e Listas**
**Contexto:** Criar uma estrutura que utilize tabelas e listas.  
**Descrição:** Crie uma tabela que mostre as categorias de um supermercado com listas de itens em cada célula.

**Exemplo de Código:**
```html
<table border="1">
    <thead>
        <tr>
            <th>Categoria</th>
            <th>Itens</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Frutas</td>
            <td>
                <ul>
                    <li>Maçã</li>
                    <li>Banana</li>
                    <li>Uva</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Legumes</td>
            <td>
                <ul>
                    <li>Cenoura</li>
                    <li>Abobrinha</li>
                    <li>Brócolis</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
```

**Objetivo:** Combinar tabelas e listas para criar interfaces ricas e organizadas.

---

### **Solução Final (Combinação de Todas as Atividades)**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabelas e Listas</title>
</head>
<body>
    <h1>Cronograma Semanal</h1>
    <table border="1">
        <thead style="background-color: #f0f0f0;">
            <tr>
                <th>Dia</th>
                <th>Manhã</th>
                <th>Tarde</th>
                <th>Noite</th>
            </tr>
        </thead>
        <tbody>
            <tr style="background-color: #f9f9f9;">
                <td>Segunda-feira</td>
                <td>Matemática</td>
                <td>História</td>
                <td>Física</td>
            </tr>
            <tr>
                <td>Terça-feira</td>
                <td>Português</td>
                <td>Química</td>
                <td>Inglês</td>
            </tr>
        </tbody>
    </table>

    <h2>Receita de Bolo</h2>
    <ol>
        <li>Pré-aqueça o forno a 180°C.</li>
        <li>Separe os ingredientes.</li>
        <li>Prepare a massa.</li>
        <li>Asse por 30 minutos.</li>
    </ol>

    <h2>Materiais Escolares</h2>
    <ul>
        <li>Cadernos</li>
        <li>Canetas</li>
        <li>Lápis</li>
        <li>Borracha</li>
    </ul>
</body>
</html>
```

---

### **Contextualização da Atividade**
- **Cenário Real:** Alunos podem criar cronogramas, listas de tarefas ou inventários para projetos futuros.
- **Extensão:** Incentive a personalização da tabela e das listas com estilos adicionais.