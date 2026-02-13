# html-metadados-scripts# Elemento Raiz, Metadados e Scripting no HTML

## 🌱 Elemento Raiz (Root Element)
O **elemento raiz** é o que contém todo o documento HTML. Em HTML, esse elemento é a tag `<html>`.

### **Exemplo:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Meu site</title>
</head>
<body>
    <h1>Olá, mundo!</h1>
</body>
</html>
```

### **Principais características:**
- O elemento `<html>` envolve todo o código da página.
- O atributo `lang="pt-BR"` define o idioma da página para navegadores e motores de busca.

---

## 📄 Metadados
Metadados são informações sobre o documento que não aparecem diretamente na página, mas são usadas por navegadores e motores de busca. Eles são definidos dentro da **tag `<head>`**.

### **Exemplo de metadados:**
```html
<head>
    <meta charset="UTF-8"> <!-- Define a codificação de caracteres -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Responsividade -->
    <meta name="description" content="Site sobre tecnologia e programação"> <!-- Descrição do site -->
    <meta name="author" content="Seu Nome"> <!-- Autor do site -->
    <title>Meu Site</title>
</head>
```

### **Explicação dos principais metadados:**
- **`<meta charset="UTF-8">`**: Define o conjunto de caracteres, permitindo o uso de acentos corretamente.
- **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Torna a página responsiva em dispositivos móveis.
- **`<meta name="description" content="...">`**: Fornece uma descrição da página para motores de busca (SEO).
- **`<title>`**: Define o título da aba do navegador.

---

## 🖥️ Elementos de Scripting
Os **elementos de scripting** permitem adicionar e executar scripts, geralmente em **JavaScript**, para tornar a página dinâmica. O principal elemento usado é a **tag `<script>`**.

### **Exemplo de script embutido (inline)**
```html
<script>
    alert("Olá, bem-vindo ao site!");
</script>
```

### **Exemplo de script externo**
```html
<script src="script.js"></script>
```

### **Boas práticas:**
- O atributo `src` carrega um arquivo JavaScript externo.
- O `<script>` deve ser colocado **antes do fechamento da tag `<body>`**, para evitar que o JavaScript bloqueie a renderização da página.

---

## 📌 Resumo
| Conceito | Descrição | Exemplo |
|----------|-----------|---------|
| **Elemento raiz** | O elemento principal que contém toda a estrutura do HTML. | `<html>` |
| **Metadados** | Informações sobre o documento (charset, SEO, responsividade). | `<meta charset="UTF-8">` |
| **Elementos de scripting** | Permitem a execução de código JavaScript na página. | `<script>alert('Olá!');</script>` |

---

Feito com ❤️ por [Alessandro](https://github.com/asovitorio) 😊

