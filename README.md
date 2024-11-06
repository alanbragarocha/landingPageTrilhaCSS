# landingPageTrilhaCSS

# Trilha de CSS - Página HTML

Este documento descreve a estrutura e os componentes de um exemplo de página HTML para a trilha de CSS.

## Estrutura do Documento

- **Tipo de Documento**: HTML5, especificado por `<!DOCTYPE html>`
- **Linguagem**:português, definida no elemento `<html lang="pt_Br">`

## Cabeçalho `<head>`

1. **Codificação de Caracteres**: `UTF-8` para compatibilidade com uma ampla variedade de caracteres.
2. **Compatibilidade**: Configurado para renderização correta em Internet Explorer.
3. **Viewport**: Definida para responsividade em dispositivos móveis.
4. **Estilos CSS**:
   - `styles.css`: Arquivo principal de estilização.
   - `reset.css`: Normaliza estilos entre navegadores.
5. **Fonte**: `Raleway` importada do Google Fonts.
6. **Título da Página**: "Trilha de CSS" (exibido na aba do navegador).

## Corpo `<body>`

### 1. Cabeçalho `<header>`

- **Classe**: `banner`, para estilização geral do cabeçalho.
- **Conteúdo**:
  - **Logotipo**: Imagem da logo com atributos de `title` e `alt`.
  - **Título**: "Trilha de CSS" como `<h1>`.
  - **Descrição**: Parágrafo com texto descritivo sobre a trilha de CSS.
  - **Botão de Inscrição**: Botão com link para a inscrição.

### 2. Conteúdo Principal `<main>`

#### Seção "O que vou aprender?" (`<section id="course-content">`)

- **Descrição do Curso**:
  - Título da seção com `<h2>`.
  - Parágrafo explicativo sobre os módulos do curso.
- **Lista de Módulos** (`<div class="modules-list">`):
  - Cada módulo é apresentado em um `<div class="module">` com um link:
    - **Módulo 01**: Primeiros passos com CSS.
    - **Módulo 02**: Trabalhando com layouts no CSS.
    - **Módulo 03**: Refinando os estilos CSS das páginas.

#### Seção "Transforme o Mundo" (`<section id="transform-world">`)

- Texto inspirador: "TRANSFORME O MUNDO COM A GENTE" exibido em um parágrafo centralizado com a classe `text-transform-world`.

#### Seção "Desafios Profissionais" (`<section id="professional-challenges">`)

- **Título**: "Evolua e encare novos desafios profissionais".
- **Imagem**: Ilustração de um homem lendo depoimentos em um tablet.
- **Texto Motivacional**:
  - Parágrafo explicativo sobre a missão da plataforma e as oportunidades de carreira, com a classe `text-professional`.

### 3. Rodapé `<footer>`

- **Logo da DIO**: Imagem com `title` e `alt`, exibindo "Logotipo DIO com o texto make the change".
- **Link para Cadastro**: Texto e link para o GitHub da DIO, incentivando o cadastro.

## Recursos Externos

- **Folhas de Estilo**:
  - `styles.css`: Define estilos personalizados.
  - `reset.css`: Aplica uma normalização entre navegadores.
- **Fonte**: `Raleway` do Google Fonts para uma aparência mais profissional.

## Estrutura Completa do Código

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="assets/CSS/styles.css">
  <link rel="stylesheet" href="assets/CSS/reset.css">
  <link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
  <title>Trilha de CSS</title>
</head>
<body>
  <!-- Conteúdo do corpo descrito anteriormente -->
</body>
</html>
