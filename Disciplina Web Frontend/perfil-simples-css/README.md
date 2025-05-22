
# Atividade: Estilizando um Perfil Simples com CSS

## 🎯 Objetivo

Desenvolver um pequeno layout de perfil utilizando **HTML** e aplicar estilos com **CSS**, praticando o uso de **classes**, **IDs**, **seletores compostos** e **propriedades visuais básicas**.

---

## 📁 Parte 1 – Estrutura do Projeto

Crie dois arquivos:

- `perfil.html`
- `estilos.css`

Vincule o CSS ao HTML com a seguinte tag dentro da `<head>`:

```html
<link rel="stylesheet" href="estilos.css">
```

---

## 🧱 Parte 2 – Código HTML sugerido

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Perfil de Usuário</title>
  <link rel="stylesheet" href="estilos.css">
</head>
<body>
  <h1>Perfil</h1>

  <div id="perfil">
    <p class="nome">Nome: Joana Silva</p>
    <p class="descricao">Desenvolvedora front-end apaixonada por design.</p>
    <p class="status online">Status: Online</p>
    <p class="status offline">Status: Offline</p>
    <p class="mensagem erro">Erro ao carregar a foto.</p>
    <p class="mensagem sucesso">Dados salvos com sucesso.</p>
  </div>

  <div class="aviso importante">Atenção: Atualize seu perfil.</div>
</body>
</html>
```

---

## 🎨 Parte 3 – Estilos CSS

Crie o conteúdo do arquivo `estilos.css` com as seguintes instruções:

- Defina **fontes**, **cores**, **tamanhos** e **margens** para os elementos `body`, `h1` e `p`.
- Aplique estilos distintos às classes:
  - `.erro`
  - `.sucesso`
  - `.aviso`
- Estilize os elementos com **classes compostas**:
  - `.status.online`
  - `.status.offline`
  - `.aviso.importante`
- Estilize os **IDs**:
  - `#perfil`

---

## 🧠 Desafio Extra

Crie uma nova classe `.botao-editar`, adicione-a a um botão dentro da `<div id="perfil">` e defina um estilo visual para ele com as propriedades:

- `background-color`
- `border`
- `padding`
- `font-weight`
