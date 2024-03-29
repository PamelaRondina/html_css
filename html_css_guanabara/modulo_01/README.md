# html_css


- [x] Exercícios ([001 até 011](https://github.com/PamelaRondina/html_css/tree/main/html_css_guanabara/modulo_01#aula-001))<br>
- [x] Desafios ([d001 até d009](https://github.com/PamelaRondina/html_css/tree/main/html_css_guanabara/modulo_01#desafio-d001))
<br>

- [x] [Comandos em Html](https://github.com/PamelaRondina/step-by-step/tree/main/html)

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

- [x] Formatações:
  - Negrito
  - Itálico
  - Marca texto
  - Texto grande e pequeno
  - Texto sublinhado
  - Texto sobrescrito e subscrito

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

- [x] Texto como código - monoespaçado
- [x] Citação Simples
- [x] Citações Completas
- [x] Abreviações
- [x] Texto invertido

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Outras formatações</title>
</head>
<body>
    <h1>Formatação por código</h1>
    <pre><code>
num = int(input('Digite um número'))
    </code></pre>

<h2>Citações simples</h2>
<p>Como diria o pai de um amigo: <q>o computador é um burro muito rápido</q></p>
    
<h2>Citações completas</h2>
<p>Segundo Jeff Noble, no seu livro HTML para Leigos:</p>
<blockquote cite="site">
    A diferença entre elementos inline e um bloco de texto é importante. Os elementos HTML neste capítulo descrevem os blocos de texto
</blockquote>
<h2>Abreviações</h2>
<p>Estou estudando <abbr title="HyperText Markup Language">HTML</abbr> e <abbr title="Cascate Style Sheets ">CSS</abbr>.</p>
<h2>Texto invertido</h2>
<p><bdo dir="rtl">Texto invertido</bdo></p>
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/221666334-6fc07573-c019-43cf-83be-5b6412197a58.png)
_______________

## Aula 009

- [x] Listas Ordenadas 
- [x] Listas não ordenadas 
- [x] Listas de definição

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listas</title>
</head>

<body>
    <h1>Trabalhando com Listas</h1>

    <h2>Listas ordenadas</h2>

    <ol type="a" start="4"> 
        <li>Acordar
        <li>Levantar
        <li>Escovar os dentes
        <li><code>1 A a I i </code>    
    </ol>

    <h2>Lista não ordenada</h2>
    <code>circle  |  disc  | square </code>  

    <ol>
        <li type="1">Círculo aberto
        <ul type="circle">
            <li>Pão
            <li>Leite
            <li>Café    
        </ul>
        <br>

        <li>Círculo fechado
        <ul type="disc">
            <li> Manteiga
            <li> Azeite
            <li> Queijo
        </ul>
        <br>

        <li> Quadrado
        <ul type="square">
            <li> Água
            <li> Bolo
            <li> Sucrilhos
        </ul>
    </ol>

    <h2>Lista de Definições </h2>
    <dl>
        <dt>HTML</dt>
        <dd>LInguagem de marcação para a criação do conteúdo de um site</dd>
        <dt>CSS</dt>
        <dd>LInguagem de marcação para a criação do desing de um site</dd>
        <dt>JavaScript</dt>
        <dd>Linguagem de programação para a criação de interatividade de um site</dd>
    </dl>
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/221883786-52c7052d-68fc-46bc-b462-57ffe38f7be3.png)
_______________

## Aula 010

- [x] Links externo
- [x] Links internos´
- [x] Links downloads

**Página principal**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trabalhando com Links</title>
</head>

<body>
    <h1>Usando Links</h1>
    <ol>
    <li><h2>Links Externos</h2>
    <p>Você pode acessar o meu <a href="https://github.com/PamelaRondina"></a> repositório público no Github por um link externo</p> 
    
    <li><h2>Links Internos - criar outras páginas</h2>    
    <p>Acesse a <a href="pag002.html" rel="next" target="_self">página 002.</a></p>

    <p>Acesse a <a href="noticias/pag003.html" rel="next" target="_self">página 003 (pasta criada)</a></p>

    <li><h2>Link para Download</h2>
    <p>Baixe o arquivo em <a href="localarquivo" download="nomedoarquivo" type="aplicattion/pdf" >PDF</a></p>
    <p>Baixe o arquivo em <a href="localarquivo" download="nomedoarquivo" type="application/zip">ZIP</a></p>
    
</ol>
</body>
</html>
```

**Página 002**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página 002</title>
</head>
<body>
    <h1>Segunda página do meu site</h1>
    <p>Testando a segunda página</p>
    <p><a href="index.html" rel="prev">Voltar</a></p>
</body>
</html>
```

**Página 003**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Terceira Página</title>
</head>
<body>
    <h1>Terceira página</h1>
    <p>Testando página 003</p>
    <p><a href="../index.html" rel="prev">Voltar</a></p>
    
</body>
</html>
```

**Página principal**

![image](https://user-images.githubusercontent.com/108991648/222224564-3a41a9fc-65d9-4f94-a983-8d3a6eac9893.png)

**Página 002**

![image](https://user-images.githubusercontent.com/108991648/222224842-abe6c31b-5d8f-464d-856a-58c0271410ae.png)

**Página 003**

![image](https://user-images.githubusercontent.com/108991648/222224989-4ddc9f25-8927-4006-a3b6-c48ca0ed089b.png)

_______________

## Aula 011

- [x] Imagens Dinâmicas
- [x] Elemento Picture
- [x] Elemento Audio

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mídias em HTML5</title>
</head>
<body>
    <h1>Imagem dinâmica</h1>
    <p>Tente abrir esse site em vários dispositivos diferentes ou simplesmente aumente e diminua o tamanho do seu navegador</p>

    <picture>
        <source media="(max-width: 750px)" srcset="imagens/foto-p.png" type="image/png">
        <source media="(max-width: 1050px)" srcset="imagens/foto-m.png" type="image/png">
        <img src="imagens/foto-g.png" alt="Imagem G">
    </picture>

    <h1>Reproduzir áudio HTML5</h1>

    <audio src="midia/Bluesy Vibes (Sting) - Doug Maxwell_Media Right Productions.mp3" controls autoplay loop></audio>
    </audio>    
    
</body>
</html>
```
___________

## Aula 012

- [x] Elemento Vídeo

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vídeo HTML5</title>
</head>
<body>
    <h1>Inserindo vídeos hospedados localmente</h1>
    <p>Este vídeo está hospedado em meu computador</p>

    <video class autoplay loop width="500" poster="images/foto-m.png" controls >
        <source  src="midia/video-mario.mp4" type="video/mp4">
    </video>

    <h1>Inserindo vídeos do Youtube</h1>
    <p>Buscar o iframe do Youtube</p>
    <iframe id="video" width="560" height="560" src="https://www.youtube.com/embed/Cb4WV4aXBpk" title="Trailer oficial" frameborder="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</body>
</html>
```
_______________

## Aula 013, 014 e 015

- [x] CSS in linea
- [x] CSS no HTML - Estilo Interno
- [x] Style.css - Estilo Externo

**In Linea**

```html
...
<body style="background-color: aqua;" >
    <h1 style="color:blue">Capítulo 1</h1>
    <h2 style="font-family: 'Courier New', Courier, monospace;">Capítulo 1.1</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab totam accusantium libero est dolorum porro velit ipsa modi, eveniet ea aspernatur, accusamus nihil dicta nobis. Similique perferendis unde tempora porro!</p>
    </body>
...
```

![image](https://user-images.githubusercontent.com/108991648/224589588-130c68f0-8478-430e-9d9c-19eafcc6f7aa.png)

**CSS no HTML - Estilo Interno**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Estilos Locais / Internos</title>

<style>
    body {
        background-color: aquamarine;
        font-family: 'Courier New', Courier, monospace;
        text-align: justify;        
    }

    h1 {
        color: blueviolet
    }

    h2 {
        color: brown
    }

    
</style>
</head>
<body>
    <h1>Capítulo 1</h1>
    <h2>Capítulo 1.1</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab totam accusantium libero est dolorum porro velit ipsa modi, eveniet ea aspernatur, accusamus nihil dicta nobis. Similique perferendis unde tempora porro!</p>
</body>
</head>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/224590424-a77e59a5-9747-4e8a-a24a-68caa92ba769.png)

**Style.css - Estilo Externo**

 - HTML

```html
<title>Estilos  / Externos</title>
    <link rel="stylesheet" href="style.css">
    
```
- CSS

```css
@charset "UTF-8";

body {
    background-color: aquamarine;
    font-family: 'Courier New', Courier, monospace;
}v

h1 {
    color: blueviolet
}

h2 {
    color: brown
}
```

_______________

## Desafio d001

Desafio das Mensagens

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">     

    <title>Desafio 001</title>
</head>
<body>
    <h1>Desafio das Mensagens</h1>
    <p>*Um</p>
    <p>**Dois</p>
    <p>***Três</p>
    <p>****Quatro</p>
    <br>
    <p>****Quatro</p>
    <p>***Três</p>
    <p>**Dois</p>
    <p>*Um</p>
    
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/222445916-cb7743bb-2244-49f4-a256-ba8bdc888861.png)
________________

## Desafio d002

Desafio das Imagens


```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">

    <title>Desafio 002</title>

    <h1>Desafio das Imagens</h1>
    <p>Inserir imagens em HTML é muito simples, tanto no conteúdo quanto lá em cima, como ícone de favoritos!</p>

    <img src="imagens/github-m.png" alt="Imagem Guanabara GitHub">
    
</head>
<body>
    
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/222448946-8236ceb4-3313-41ac-9c74-2ed082f3f2b1.png)

________________

## Desafio d003

Desafio do Mapa

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desafio 003</title>
</head>
<body>
    <h1>Desafio do Mapa</h1>
    <p>Agora chegou a hora de treinar um pouco o uso de imagens, parágrafos <br>e quebras de linhas.</p>
    <img src="imagens/01.png" alt="imagem 01">
    <img src="imagens/02.png" alt="imagem 02">
    <img src="imagens/03.png" alt="imagem 03">
    <br>
    <img src="imagens/04.png" alt="imagem 04">
    <img src="imagens/05.png" alt="imagem 05">
    <img src="imagens/06.png" alt="imagem 06">
    <br>
    <img src="imagens/07.png" alt="imagem 07">
    <img src="imagens/08.png" alt="imagem 08">
    <img src="imagens/09.png" alt="imagem 09">

    
</body>
</html>
```
![image](https://user-images.githubusercontent.com/108991648/222509322-adc917f4-2023-4eef-aeee-69f0c35b2415.png)


________________
## Desafio d004

Meus emojis favoritos

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desafio 004</title>
</head>
<body>
    <h1>Meus emojis favoritos</h1>

    <ol type="A">
        <li><h2>Carinhas</h2>
            <ul type="square">
                <li>&#x1F601 U+1F601                
            </ul>
                        
        <li><h2>Animais</h2>
            <ul type="circle">
                <li>&#x1F436 U+1F436
            </ul>

        <li><h2>Especiais</h2>
            <ul type="disc">
                <li>&#x1F680 U+1F680
            </ul>
    </ol>
    
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/222515170-84831d3e-fb36-46d9-b18c-c66383f5f958.png)


________________
## Desafio d005

Minhas redes sociais

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Desafio 005</title>
</head>
<body>
    <h1>Minhas redes sociais</h1>
    <h2>Quem somos?</h2>
    <img src="Imagens/logo.jpg" alt="logo">
    <p>Somos a "Arca de Nóis É!", um canal criado por um casal na área de TI descobrindo e aprendendo novos hobbies. 
        <ol>Por aqui, vocês vão encontrar:
            <li> Fase 1: Brinquedos de Madeira, teclado e violino.</p>
    </ol>
    <h2>Nos acompanhem por...</h2>
    <ul type="square">      
        <li><img src="Imagens/youtube-logo-24.png" alt="icon-youtube"> <a href="https://www.youtube.com/@aarcadenoise" target="_blank" rel="external" >/aarcadenoise</a> - Se inscreve lá no canal no Youtube
        <li><img src="Imagens/instagram-alt-logo-24.png" alt="icon-instagram"> <a href="https://www.instagram.com/aarcadenoise/" target="_blank" rel="external">/aarcadenoise</a> - Segue lá no Instagram
        <li><img src="Imagens/tiktok-logo-24.png" alt="icon-tiktok"> <a href="https://www.tiktok.com/@aarcadenoise" target="_blank" rel="external">/aarcadenoise</a> - Segue lá no TikTok     
    </ul>
      
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/222741619-5930270d-9ccc-4606-9bea-6f6b7031a62e.png)

________________
## Desafio d006

- [x] Tags em HTML

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desafio 006</title>
</head>
<body>
    <h1>Tags em HTML</h1>
    <p>Em HTML5, podemos inserir os elementos da lista a seguir. Passe o mouse<br>
    sobre os termos para descobrir qual tag deverá utilizar em cada caso.</p>
    <ul type="square">
        <li><abbr title="<p>">Parágrafo</abbr>
        <li><abbr title="<h1> <h2> <h3> <h4> <h5> <h6>">Títulos</abbr>
        <li><abbr title="<img>">Imagens</abbr>
        <li><abbr title="<abbr>">Abreviações</abbr>
        <li><abbr title="<hr>">Linha horizontal</abbr>
        <li><abbr title="<br>">Pular linha</abbr>
        <li><abbr title="<ol>">Listas numeradas</abbr>
        <li><abbr title="<ul>">Listas com demarcadores</abbr>
    </ul>
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/222769370-e4d756bb-0641-41f8-9db7-a189ad8c32f2.png)
________________

## Desafio d007

- [x] Imagens Flexível

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desafio 007</title>
</head>
<body>
    <h1>Imagem Flexível</h1>
    <p>Você está vendo a imagem completa? Experimente ampliar o tamanho da sua janela para poder aproveitar a melhor experiência</p>

    <picture>
        <source media="(max-width: 750px)" srcset="images/foto-p.png" type="image/png">
        <source media="(max-width: 1050px)" srcset="images/foto-m.png" type="image/png">
        
        <img src="images/foto-g.png" alt="Imagem G">
    </picture>

</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/224324602-6ce99261-ce1c-4b27-a7a7-ded7ad294280.png)

________________

## Desafio d008

- [x] Criando uma Navegação

**Página Principal - Cinza**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="shortcut icon" href="images/Google-Noto-Emoji-Travel-Places-42598-rocket.32.png" type="image/x-icon">

    <style>
        body {
            background-color: rgb(175, 179, 175);
        }
    </style>
    
    <title>Navegação - Cinza</title>
</head>
<body>
    <h1>Desafio da Navegação</h1>
    <p>Esta é a página principal, o ínidice do seu site.<br><br> É a página cinza!<br><br>A partir dela você pode acessar as outras áreas principais através dos links a seguir</p>

    <ul>
    <li>
    <a href="pagina_verde.html" rel="next" target="_self"> Acessar a área verde</a>
    <li>
    <a href="pagina_amarela.html" rel="next" target="_self">Acessar a área amarela</a>
    </li>

</ul>

</body>
</html>
```

**Página 2 - Verde**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="shortcut icon" href="images/Google-Noto-Emoji-Travel-Places-42598-rocket.32.png" type="image/x-icon">

    <style>
        body {
            background-color: rgba(175, 219, 131, 0.925);
            color:rgba(58, 78, 38, 0.925);
        }

       
    </style>

    <title>Navegação - Verde</title>
</head>
<body>
   

    <h1>Página Verde</h1>
    <p>Você agora está na área verde<br>
    Você acessou clicando no primeiro link da página principal</p>

    <ul>
        <li><a href="pagina_cinza.html" rel="prev">Voltar para a página cinza</a></li>
    </ul>
</body>
</html>
```

**Página 3 - Amarela**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="shortcut icon" href="images/Google-Noto-Emoji-Travel-Places-42598-rocket.32.png" type="image/x-icon">

    <style>
        body {
            background-color: rgb(238, 224, 102);
            color: darkgoldenrod;
        }
    </style>

    <title>Navegação - Amarela</title>
</head>
<body>
    <h1>Página Amarela</h1>

    <p>Você agora está na área amarela.<br>
    Você acessou clicando no segundo link da página principal</p>

    <ul>
        <li><a href="pagina_cinza.html" rel="prev">Voltar a página cinza</a></li>
    </ul>
    
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/224400393-46516e73-b327-46de-9907-16771004758a.png)

________________

## Desafio d009

- [x] Página principal - 4 thumbs
- [x] 4 páginas com link para acesso ao vídeo e retorno a página principal

**Página Principal**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="shortcut icon" href="images/favicon_youtube.png" type="image/x-icon">

    <style>
        body{
            background-color: rgb(65, 63, 63);
            color: white;
            text-align: center;            
        }
    </style>
    <title>Meus Vídeos</title>  
</head>

<body>
    <h1>Vídeos legais para assistir</h1>  
    <picture>
        <a href="video_arca.html" rel="next" target="_blank"><img src="images/Thumb - Vídeo Arca.PNG" alt="imagem 'A Arca de Nóis É'" width="250"></a>

        <a href="video_python.html" rel="next" target="_blank"><img src="images/Thumb - Vídeo Python.webp" alt="imagem 'Python'" width="250"></a>

        <br>
        
        <a href="video_chaves.html" rel="next" target="_blank"><img src="images/Thumb - Vídeo Chaves.jpg" alt="imagem 'Chaves'" width="250"></a>

        <a href="video_musica.html" rel="next" target="_blank"><img src="images/Thumb - Vídeo Shakira.webp" alt="imagem 'Shakira'" width="250"></a>
</body>
</html>
```

**Vídeo, acesso ao canal e retorno a  página principal**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  

    <link rel="shortcut icon" href="images/favicon_youtube.png" type="image/x-icon">

    <style>
        body {
            background-color: rgb(65, 63, 63);
            color: white;
            font: bold;
            text-align: center;
        }     
    </style>

    <title>A Arca de Nóis É!</title>
  
</head>

<body>
    <h1>A Arca de Nóis É!</h1>   

    <iframe width="560" height="315" src="https://www.youtube.com/embed/c8fI_UGFuWA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    
    <p>Veja o canal no <a href="https://www.youtube.com/@aarcadenoise" rel="external" target="_blank" style="color:white">Youtube!</a></p>

    <a href="pagina_principal.html" rel="prev"><img src="images/seta branca.png" alt="seta-retornando" width="60"></a>   
    
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/224494811-09319c5c-ec29-4261-9336-b8834a634ed5.png)

________________

