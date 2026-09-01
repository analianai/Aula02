# Ctrl+Young 2 — Aula 02: Introdução ao HTML

## Objetivos

- Compreender a sintaxe da linguagem HTML.
- Criar códigos-fonte com as estruturas básicas e imagens.

## Material da aula

[📁 Acessar material no Google Drive](https://drive.google.com/drive/folders/1y1p0EcL86cTbfD0w8UvJzTWk6-eN_JCI?usp=sharing)

---

# O que é Sintaxe?

Sintaxe é a parte da gramática que estuda como as palavras se relacionam e se organizam dentro das frases e orações.

### Exemplo

> O cachorro comeu a ração.

Nós entendemos perfeitamente a frase.

Agora observe:

> Ração cachorro a comeu o.

As palavras estão ali, mas foram organizadas de uma forma estranha.

**Sintaxe é justamente a maneira correta de organizar as frases.**

---

# Sintaxe da linguagem HTML

Compreender a sintaxe da linguagem HTML significa entender as regras usadas para escrever e organizar corretamente os elementos de uma página HTML.

No HTML, isso envolve saber:

- como abrir e fechar uma tag;
- como inserir conteúdo dentro dela;
- como usar atributos;
- como organizar elementos dentro de outros elementos;
- como respeitar a estrutura básica de uma página.

---

# Estrutura básica de uma página HTML

```html
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>

</body>

</html>
```

---

# Entendendo cada parte do HTML

## `<!DOCTYPE html>`

Indica ao navegador que o arquivo é uma página HTML moderna.

```html
<!DOCTYPE html>
```

---

## `<html>`

Marca o início da página HTML.

O atributo `lang="pt-br"` informa que o idioma da página é **Português Brasileiro**.

```html
<html lang="pt-br">

</html>
```

---

## `<head>`

É a parte de configuração da página.

Normalmente, o conteúdo colocado dentro do `<head>` não aparece diretamente para o usuário.

```html
<head>

</head>
```

### Conteúdo do `<head>`

#### Codificação de caracteres

```html
<meta charset="UTF-8">
```

Permite usar acentos e caracteres especiais corretamente, como:

`ç`, `ã`, `é`, `í`.

#### Adaptação para diferentes telas

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Ajuda a página a se adaptar melhor ao celular, tablet e computador.

#### Título da página

```html
<title>Document</title>
```

Define o título que aparece na aba do navegador.

---

# `<body>`

O `<body>` é a parte visível da página.

Tudo que o usuário consegue ver e interagir, como textos, títulos, imagens, links e botões, deverá ficar dentro dele.

```html
<body>

</body>
```

## Conteúdos básicos do `<body>`

| Elemento | Função |
|---|---|
| `<h1>` | Cria um título principal |
| `<p>` | Cria um parágrafo |
| `<img>` | Coloca uma imagem na página |
| `<a>` | Cria um link |
| `<button>` | Cria um botão |

---

# Tags e atributos estudados

## Estrutura e aparência

| Tag / atributo | Inglês | Significado |
|---|---|---|
| `<head>` | Head | Cabeça |
| `<body>` | Body | Corpo |
| `<!DOCTYPE html>` | Document Type is HTML | Tipo do documento é HTML |
| `<title>` | Title | Título |
| `<img>` | Image | Imagem |
| `src` | Source | Fonte |
| `id` | Identifier | Identificador |
| `bgcolor` | Background color | Cor de fundo |
| `background` | Background | Fundo da página |
| `text` | Text | Cor do texto |
| `<h1>...<h6>` | Heading Levels | 6 níveis de cabeçalho |

---

## Formatação de texto

| Tag | Inglês | Significado |
|---|---|---|
| `<i>` | Italic | Itálico |
| `<em>` | Emphasis | Visualmente semelhante ao itálico, mas representa ênfase |
| `<strong>` | Strong | Visualmente semelhante ao negrito, mas representa maior importância |
| `<br>` | Break | Quebra de linha |

### Exemplos

```html
<i>Texto em itálico</i>

<em>Texto com ênfase</em>

<strong>Texto importante</strong>

Texto da primeira linha<br>
Texto da segunda linha
```

---

# Atributos apresentados na aula

| Atributo | Inglês | Significado |
|---|---|---|
| `size` | Size | Tamanho do texto |
| `color` | Color | Cor da letra |
| `face` | Face | Estilo da fonte |
| `align` | Align | Alinhar |
| `height` | Height | Altura |
| `width` | Width | Largura |
| `vspace` | Vertical space | Espaço em branco acima e abaixo de uma imagem |
| `hspace` | Horizontal space | Espaço em branco nos lados da imagem |

---

# Exemplos de HTML

## Cabeçalhos

```html
<h1>Cabeçalho grande</h1>
<h3>Cabeçalho médio</h3>
<h6>Cabeçalho pequeno</h6>
```

## Parágrafo

```html
<p>Este é um parágrafo.</p>
```

## Imagem

```html
<img src="imagens/minhaimagem.png">
```

## Imagem com tamanho definido

```html
<img src="imagens/minhaimagem.png" width="50%" height="50%">
```

## Alinhamento

```html
<p align="left">Texto alinhado à esquerda</p>

<p align="center">Texto alinhado ao centro</p>

<p align="right">Texto alinhado à direita</p>
```

## Comentário em HTML

O comentário fica no código, mas não aparece na página.

```html
<!-- Este texto não aparece no navegador -->
```

## Cor de fundo

```html
<body bgcolor="green">

</body>
```

## Imagem de fundo

```html
<body background="imagens/universo.png">

</body>
```

---

# Desafio em sala

## Crie sua página pessoal!

Crie uma página HTML utilizando os conteúdos estudados.

**Regra:** use no mínimo **10 tags e atributos** diferentes.

---

# Atividade para Casa — Minha Primeira Página em HTML

## Tema: **Meu Universo**

Crie uma página HTML que apresente um pouco sobre você.

Você pode falar sobre:

- seus interesses;
- hobbies;
- jogos;
- filmes;
- séries;
- músicas;
- esportes;
- profissão que deseja seguir;
- outros assuntos que representem seus gostos.

A ideia não é apenas copiar os códigos apresentados em sala. Você deverá **combinar os comandos aprendidos para construir sua própria página**.

---

## Requisitos da atividade

### 1. Estrutura básica do HTML

```html
<html>

<head>
    <title>Meu Universo</title>
</head>

<body>

</body>

</html>
```

### 2. Título da página

Utilize a tag:

```html
<title>Meu Universo</title>
```

### 3. Pelo menos três cabeçalhos

Utilize tamanhos diferentes.

```html
<h1>Meu Universo</h1>

<h3>Coisas que eu gosto</h3>

<h6>Página criada por...</h6>
```

### 4. Textos e parágrafos

Inclua textos falando sobre você ou sobre o tema escolhido.

```html
<p>Este é um texto sobre mim.</p>
```

### 5. Quebras de linha

Utilize:

```html
<br>
```

### 6. Formatação de texto

Utilize pelo menos **quatro tipos de formatação** entre:

```html
<b>negrito</b>

<strong>texto com importância</strong>

<i>itálico</i>

<em>texto com ênfase</em>

<u>sublinhado</u>
```

### 7. Imagem

Inclua pelo menos uma imagem relacionada ao tema da página.

```html
<img src="imagens/minhaimagem.png">
```

### 8. Aparência da página

Altere a aparência utilizando algum dos recursos apresentados na aula, como:

- cor de fundo;
- imagem de fundo.

Exemplo:

```html
<body bgcolor="lightblue">
```

### 9. Alinhamento

A página deverá possuir:

- pelo menos um texto centralizado;
- outro texto com um alinhamento diferente.

Exemplo:

```html
<p align="center">Texto centralizado</p>

<p align="left">Texto alinhado à esquerda</p>
```

### 10. Comentário no código

Inclua um comentário que não aparecerá na página.

```html
<!-- Esta parte da página apresenta meus hobbies -->
```

---

# Exemplo de organização do projeto

```text
meu-universo/
│
├── index.html
│
└── imagens/
    └── minhaimagem.png
```

---

# Checklist antes de entregar

- [ ] O arquivo principal se chama `index.html`.
- [ ] A página possui a estrutura básica do HTML.
- [ ] Foi utilizado `<title>`.
- [ ] Existem pelo menos três cabeçalhos.
- [ ] Existem textos e parágrafos.
- [ ] Foi utilizada quebra de linha com `<br>`.
- [ ] Foram utilizadas pelo menos quatro formatações de texto.
- [ ] Existe pelo menos uma imagem.
- [ ] A aparência da página foi modificada.
- [ ] Existem diferentes alinhamentos.
- [ ] Existe pelo menos um comentário no código.
- [ ] O arquivo foi testado no navegador antes da entrega.

---

**Ctrl+Young 2 — Aula 02**
