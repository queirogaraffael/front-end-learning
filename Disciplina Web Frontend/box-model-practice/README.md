
# Atividade Prática: Explorando o Box Model na Prática

## 🎯 Objetivo

Compreender e experimentar, na prática, os elementos que compõem o Box Model no CSS:  
- Conteúdo  
- Preenchimento (*padding*)  
- Borda (*border*)  
- Margem (*margin*)

---

## 📚 Pré-requisitos

- Conhecimentos básicos de **HTML**
- Noções iniciais de **CSS**

---

## 🧪 Instruções

### 1️⃣ Estrutura base (HTML)

Crie um arquivo HTML com o seguinte conteúdo:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Box Model na Prática</title>
  <style>
    .caixa {
      width: 200px;
      height: 100px;
      background-color: #cce5ff;
      padding: 20px;
      border: 5px solid #004085;
      margin: 30px;
    }
  </style>
</head>
<body>
  <div class="caixa">Olá, Box Model!</div>
</body>
</html>
```

---

### 2️⃣ Exploração orientada

- Altere os valores de `padding`, `border`, `margin`, `width` e `height`.
- Observe as mudanças no navegador.
- Use o **DevTools** (Ferramentas de Desenvolvedor) para visualizar o **Box Model**.

---

### 3️⃣ Desafio prático

Crie **3 caixas lado a lado** com diferentes configurações de `padding` e `margin`:

```html
<style>
  .caixa {
    display: inline-block;
    background-color: #f0f0f0;
    border: 2px solid #333;
  }

  .a { padding: 10px; margin: 5px; }
  .b { padding: 20px; margin: 15px; }
  .c { padding: 30px; margin: 25px; }
</style>

<div class="caixa a">Caixa A</div>
<div class="caixa b">Caixa B</div>
<div class="caixa c">Caixa C</div>
```

Depois, responda:

- **Qual caixa parece maior? Por quê?**
- **Qual valor não afeta o conteúdo interno diretamente?**
- **Qual valor afasta a caixa das outras?**

---

### 4️⃣ Extra (opcional)

Adicione `box-sizing: border-box` à classe `.caixa` e compare os resultados:

```css
.caixa {
  box-sizing: border-box;
}
```
