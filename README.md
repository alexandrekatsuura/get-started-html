# Get started HTML

![GitHub repo size](https://img.shields.io/github/repo-size/alexandrekatsuura/get-started-html?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/alexandrekatsuura/get-started-html?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/alexandrekatsuura/get-started-html?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/alexandrekatsuura/get-started-html?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/alexandrekatsuura/get-started-html?style=for-the-badge)


## Descrição
> HTML é uma linguagem de marcação utilizada para estruturar o conteúdo de páginas da web.

## Conceitos importantes
### Tags
>  São usadas para marcar e definir diferentes partes do conteúdo. As tags são escritas entre "<" e ">".

### Elementos
>  Os elementos são construídos utilizando tags de abertura e fechamento.

### Atributos
> Atributos fornecem informações adicionais às tags. Eles são inseridos dentro da tag de abertura e podem conter valores específicos. 

### Estrutura
> Uma página HTML básica tem uma estrutura geral que inclui uma tag "html" (elemento raiz), que contém as tags "head" (cabeçalho) e "body" (corpo). O cabeçalho é usado para fornecer informações sobre o documento, enquanto o corpo contém o conteúdo visível da página.

## Exemplos de Tags
* h1 a h6
```
<h1>Título 1</h1>

<h2>Título 2</h2>

<h3>Título 3</h3>

<h4>Título 4</h4>

<h5>Título 5</h5>

<h6>Título 6</h6>
```

* p
```
<p>Parágrafo</p>
```

* a
```
<a href="https://www.exemplo.com">link</a>
```

* img
```
<img src="caminho_da_imagem.jpg" alt="Descrição da imagem">
```

* ul e li (lista não ordenada)
```
<ul>
    <li>Lista item 1</li>
    <li>Lista item 2</li>
    <li>Lista item 3</li>
</ul>
```

* ol e li (lista ordenada)
```
<ol>
    <li>Primeiro item</li>
    <li>Segundo item</li>
    <li>Terceiro item</li>
</ol>
```

* div
```
<div>
    <h3>Título da Divisão</h3>
    <p>Conteúdo da divisão.</p>
</div>
```

* section
```
<section>
    <p>Parágrafo</p>
</section>
```
        
## Exemplos de Estrutura
```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <title>Título da Página</title>
    <meta charset="UTF-8">
</head>

<body>
    <header>
        <p>Header</p>
    </header>

    <main>
        <p>Main</p>
    </main>
    
    <footer>
        <p>Footer</p>
    </footer>
</body>
</html>
```

* `<!DOCTYPE html>` - declara o tipo de documento como HTML5.
* `<html>` - elemento raiz que envolve todo o conteúdo da página.
* `<head>` - contém metadados, como o título da página, a codificação de caracteres, descrição e palavras-chave.
* `<body>` - é o corpo principal da página, onde o conteúdo visível é colocado.
* `<header>` - cabeçalho da página e contém o logotipo ou título do site, juntamente com uma barra de navegação.
* `<main>` - é a seção principal do conteúdo da página.
* `<footer>` - é a área de rodapé da página e geralmente contém informações de direitos autorais.