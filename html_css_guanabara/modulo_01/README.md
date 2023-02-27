# html_css

Comandos em Html: [Clique Aqui](https://github.com/PamelaRondina/step-by-step/tree/main/html)

<hr>

## Aula 001

Introdução ao Html, aprendendo sobre tags (abertura e fechamento)

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>

    <body>
        <h1>Olá, Mundo!</h1>
        <hr>
        <p>Vamos aprender sobre tags em Html!</p>
        <p> &lt;h1&gt;: Título, possui tag de fechamento &lt;/h1&gt;</p>
        <p>&lt;p&gt;: Parágrafo, possui tag de fechamento &lt;/p&gt;</p>
        <p> &lt;h2&gt;: Subtítulo, possui tag de fechamento &lt;/h2&gt;</p>
        <p>&lt;hr&gt;: Linha horizontal</p>
        <p>&lt;br&gt;: Pula linha</p>
       <hr>
        <h1>Título </h1>
        <p>Parágrafo</p>
        <h2>Subtítulo</h2>
        <hr>

    </body>

</html>
```

![image](https://user-images.githubusercontent.com/108991648/184901292-35193ba8-19b1-49bb-bc7e-af421cbff984.png)

<hr>

## Aula 002

Podemos escrever o código em vários formatos: pulando linha, com muitos espaçamentos; a leitura não será feita! O Html é lido por marcações, para que seja feito uma quebra de linha, necessitamos utilizar o < br >

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aula 002 - Html e CSS</title>
</head>
<body>
    <h1> Parágrafo e quebras e linhas</h1>
    <hr>
    <p>Podemos escrever o código em vários formatos:
         pulando linha, 
         com muitos espaçamentos;
          a leitura não será feita! <br><br>
           Aqui, incluímos a marcação &lt;br&gt;.  Html é lido por marcações, 
           para que seja feito uma quebra de linha, necessitamos utilizar o &lt;br&gt;.</p>
    </body>
</html>
```

Resultado:

![image](https://user-images.githubusercontent.com/108991648/184971011-1719f53b-5287-4571-a787-d46ec55c92d4.png)

Para incluirmos emoji: &#x+número do emoji

O número do emoji pode ser encontrado pelo site [emojipedia](https://www.emojipedia.org/openmoji/)

- [x] Entre no site e escolha um emoji;
- [x] Role o mouse até localizar o "Codepoint": U+código
- [x] `&#x1F970;` No HTML insira: &#x + CódigoEmoji + ; 

<hr>

## Aula 003

- [x] Assunto importante, direito das imagens! Sites disponíveis;
- [x] Software Gimp (programa gratuito para edição de imagens)

Nome | Link
:-|:-
Pexels|https://www.pexels.com/pt-br/procurar/cachorro/
Unplash|https://unsplash.com/
Freepik|https://br.freepik.com/
Rawpixel|https://www.rawpixel.com/
Pixabay|https://pixabay.com/pt/
LibreShot|https://libreshot.com/

<hr>

## Aula 004

- [x] Software Gimp (programa gratuito para edição de imagens)

 * Utilizar a ferramenta de corte para identificar o tamanho que deseja da imagem 
* Diminuir a largura do arquivo: imagem > Redimensionar 


Adicionando imagem
    - De um diretório local
    - De uma imagem da internet 

```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Inserir imagem</title>
    </head>

    <body>
        <h2>Imagem de um diretório local</h2>
        <br>
        <img src="logo-html150.png" alt="Html do diretório">

        <h2>Imagem da uma URL</h2>
        <img src="https://cdn.pixabay.com/photo/2016/11/19/23/00/css3-1841590_960_720.png" alt="Imagem de uma URL">
    </body>
    </html>
```

<hr>

## Aula 005

- [x] Inserir Favicon

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="html.ico.ico" type="image/x-icon">
    <title>Adicionar Favicon</title>
</head>
<body>
    
</body>
</html>
```

<hr>

## Aula 006

- [x] Hierarquia de títulos

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hierarquia de título</title>
</head>
<body>
    <h1>Título de nível 1</h1>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
    <br>
    <h2>Título de nível 2</h2>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. 
    <br>
    <h3>Título de nível 3</h3>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. 
    <h4>Título de nível 4</h4>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. 
    <h5>Título de nível 5</h5>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. 
    <h6>Título de nível 6</h6>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. 
    <br>    
</body>
</html>
```
<br>
<hr>

## Aula 007

- [x] 

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formatação de Textos</title>
    <style>
        mark {
            background-color: limegreen;
        }
    </style>
</head>
<body>
    <h1>Principais formatações</h1>
    <h2>Negrito / Destaque</h2>
    <p>Nesta frase temos um <b>termo em negrito</b> usando a tag B (não semântica).</p>
    <p>Nesta frase, tenho um <strong>termo em destaque</strong> usando a tag STRONG (semântica).</p>
    <h2>Itálico / Ênfase</h2>
    <p>Nesta frase, temos um <i>termo em itálico</i> usando a tag I (não semântica).</p>
    <p>Nesta frase, temos um <em>termo em ênfase</em> usando a tag EM (semântica).</p>
    <h2>Texto marcado</h2>
    <p>Podemos criar também <mark>um texto marcado</mark> usando a tag MARK.</p>
    <p>E no outro parágrafo, temos <mark>outro texto marcado</mark> no final.</p>
    <h2>Texto grande e pequeno</h2>
    <p>Estamos criando um <big>texto grande</big> e um <small>texto pequeno</small> nesse parágrafo.</p>
    <h2>Texto deletado</h2>
    <p>Podemos marcar <del>um texto como excluído</del> para indicar que ele deve ser lido, mas não considerado.</p>
    <h2>Texto inserido</h2>
    <p>Podemos marcar <ins>um texto como inserido</ins> para dar uma ênfase e indicar que ele foi adicionado depois.</p>
    <p>Existe também o <u>sublinhado</u> com a tag U (não semântica)</p>
    <h2>Texto sobrescrito</h2>
    <p>Para inserir coisas do tipo x<sup>20</sup>+3</p>
    <h2>Texto subscrito</h2>
    <p>Para inserir coisas do tipo H<sub>2</sub>O</p>
    teste

    teste
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/220713318-dc524e40-2fe1-4168-948b-59204935989a.png)


___________________

## Aula 008

- [x] 

_______________

## Aula 009

- [x] 

_______________

## Aula 010

- [x] 

_______________

## Aula 011

- [x] 

_______________




##
##
##
##
##
##

