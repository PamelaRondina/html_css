# html_css


- [x] Exercícios ([016 até ***](https://github.com/PamelaRondina/html_css/tree/main/html_css_guanabara/modulo_02#aula-016))<br>
- [x] Desafios ([d010 até d***](https://github.com/PamelaRondina/html_css/tree/main/html_css_guanabara/modulo_02#desafio-d010))
<br>

Comandos em HTML: [clique Aqui](https://github.com/PamelaRondina/step-by-step/tree/main/html)<br>
Comandos em CSS: [clique Aqui](https://github.com/PamelaRondina/step-by-step/tree/main/css)



### [Aula 016](https://github.com/PamelaRondina/html_css/tree/main/html_css_guanabara#aula-016) 


**Cores**

- [x] Cores In linea
- [x] Cores Estilo Interno
- [x] Cores Gradiente

**Cores Inlinea**

```html
<body>
    <h1>Exemplos de Cores</h1>
    <h2>Cores</h2>
    <p>Representação Hexadecimais - 0 1 2 3 4 5 6 7 8 9 A B C D E F</p>    
    &lt;style="background-color: #0000ff; color: #ffffff;""&gt;
    <p style="background-color: #0000ff; color: #ffffff;">Teste</p>

    <h2>rgb | rgba</h2>

    <h3><strong>rbg (Red, Green, Blue)</strong></h3>    
    &lt;style="background-color: rgb(0, 0, 255); color: rgb(255, 255, 255)"&gt;
    <p style="background-color: rgb(0, 0, 255); color: rgb(255, 255, 255)">Teste</p>
    
    <h3><strong>rbga (Red, Green, Bue, Transparência )</strong></h3>    
    &lt;style="background-color: rgba(27, 78, 33, 0.205);"&gt;
    <p style="background-color: rgba(27, 78, 33, 0.205); color: #047000">Teste</p>

    <h2>hsl</h2>

    <h3><strong>hsl (Hue, Sturation, Luminosity)</strong></h3>    
    &lt;style="background-color: hsl(240, 100%, 50%); color: hsl(0, 0%, 100%)""&gt;
    <p style="background-color: hsl(240, 100%, 50%); color: hsl(0, 0%, 100%)">Teste</p>
    
</body>
```

![image](https://user-images.githubusercontent.com/108991648/224811690-76dcbeb5-77b7-4bc2-9040-5818bda3116f.png)

__________

**Cores em CSS - Estilo interno**

```html
    <title>Cores em CSS - Estilo Interno</title>
    <style>
        body {
            background-image: linear-gradient(to right, #5cc8ff, #125e8a, #dbabbe, #a8ba9a, #246a73);
        }
    </style>

</head>
```

![image](https://user-images.githubusercontent.com/108991648/224811975-563f1cc0-e3ad-4117-b570-d0abd9caadf0.png)

**Cores em CSS - Estilo externo**

- link CSS no HTML
- Style.CSS

```css
@charset "UTF-8";

* {
    font-family: Arial, Helvetica, sans-serif;
}

body  {
    margin: auto;
    background-image: linear-gradient(to right,  #FFD8B1, #FDB1A7, #e5c3a1,#67BAB7);
}

main {
    background-color: white;
    border-radius: 10px;
    box-shadow: 5px 5px 15px rgb(135, 96, 80);
    width: 600px;
    padding: 10px;
    margin: auto;
}

h1 {
    color: #67BaB7;
    text-align: center;
    text-shadow: 1px 1px 2px rgba(92, 65, 54, 0.705);
}

h2 {
    color: #876050;
   
}
p {
    text-align: justify;
}
```

![image](https://user-images.githubusercontent.com/108991648/224812318-536e85a5-c8b6-4062-9cd9-86e803fc74e0.png)

![image](https://user-images.githubusercontent.com/108991648/224800188-d9c28389-0ab9-46e9-89b2-682c1d140acf.png)

<hr>

## Aula 17

- [x] Font CSS - Estilo Interno
- [x] Alinhamentos

**Font CSS - Estilo Interno**
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fontes em CSS</title>

    <style>
        body {
            font-family:Arial, Helvetica, sans-serif;
        }
    </style>
</head>
<body>
    <h1>Trabalhando com fontes</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
    <h2>Subtítulo do exercício</h2>
</body>
</html>
```

<hr>

# História das Fontes

![image](https://user-images.githubusercontent.com/108991648/224875711-0aaf7fe8-4591-4bd4-b7a7-ed71c5fc40cf.png)

![image](https://user-images.githubusercontent.com/108991648/224873716-50519e14-999c-49ca-9179-908bfa6ecacb.png)

![image](https://user-images.githubusercontent.com/108991648/224873921-63625dc0-7251-4c40-81b5-b33aeb2f1168.png)

![image](https://user-images.githubusercontent.com/108991648/224874771-32b4670b-689f-482d-90a6-db08ad6a6512.png)

![image](https://user-images.githubusercontent.com/108991648/224875059-243da244-17f3-446c-be62-d9fb4fa1a688.png)


## Aula 18

- [x] Google Fontes ([Step by Step](https://github.com/PamelaRondina/menu_digital#editando-as-fontes))
- [x] Fontes Externas ([Step by Step](LINK*********)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Fontes</title>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Satisfy&display=swap');
        
        h1 {
            font-family: 'Satisfy', cursive;
        }
    
</style>
    
</head>
<body>
    <h1>Testando Fontes Google</h1>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium tempora harum cupiditate, natus, magni numquam provident deleniti error corporis aliquam fugiat iure maxime id, eos itaque labore laborum exercitationem nemo.</p>

</body>
</html>
```
![image](https://user-images.githubusercontent.com/108991648/225021664-ef59fc08-073b-4b29-890f-9f3e2eed53c4.png)

--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->

### Fonte Externa

- [x] Escolher uma fonte e baixar do site [DaFont](https://www.dafont.com/pt/bachelorette.font)

Tipos | Formatos 
-|-
opentype | otf
truetype | otf
embedded-opentype | 
trutype-aat | Apple Advanced Typography
 .| svf

 Em CSS adicionar:

```css
@font-face {
    font-family: 'CrieUmNome';
    src: url('fonts/Bachelorette_PERSONAL_USE_ONLY.otf') format('opentype');
    font-weight: normal;
    font-style: normal;
}


body {
    font-family: 'CrieUmNome', Times, serif;
    font-size: 3em;
    font-weight: normal;
}
```

**Código HTML**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fontes Externas</title>
    <style>
        @font-face {
    font-family: 'CrieUmNome';
    src: url('fonts/Bachelorette_PERSONAL_USE_ONLY.otf') format('opentype');
    font-weight: normal;
    font-style: normal;
}

body {
    font-family: 'CrieUmNome', Times, serif;
    font-size: 3em;
    font-weight: normal;
}

    </style>
</head>
<body>
    <h1>Teste Fonte</h1>
    
</body>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/225100490-320be852-4b61-48c3-96d9-e64760b13b3f.png)

## Aula 18 - B

- Alinhamentos
```css
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alinhamentos</title>
    <style>
        h1 {
            text-align: center;
        }
     
        h2 {
            text-align: right;
        }

        p {
            text-align: justify;
            text-indent: 30px;
        }

    </style>
</head>
<body>
    <h1>Tipos de Alinhamento</h1>
    <h2>Subtítulo</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. A quisquam cupiditate quod tempore sed nostrum, laboriosam voluptate. Modi, in. Nesciunt animi labore modi perferendis? Consectetur odit quisquam est magni nulla?</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum, sequi aperiam. Asperiores cum impedit earum. Doloribus ad tenetur sed ratione nihil sequi perferendis hic voluptatem fugiat, debitis officia labore cum.</p>   
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium nobis iure doloribus, similique obcaecati libero alias vel veniam ducimus est veritatis eos reiciendis non vero? Dolore, harum aspernatur. Ducimus, perferendis.</p>
    
</body>
</html>
```
![image](https://user-images.githubusercontent.com/108991648/225108914-e6acd04b-2398-4548-b0c3-96324b4e78ff.png)


<hr>

## Aula 19

- [x] id e class

**HTML**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="style.css">
    <title>Seletores</title>
</head>
<body>
    <h1 id="principal">Criando Sites com HTML e CSS</h1>
    <h1>Aprendendo HTML</h1>
    <h2>HTML básico</h2>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nemo vel officia repellendus asperiores officiis sit ducimus veniam? Amet, repudiandae quae sapiente cum quisquam voluptatibus excepturi temporibus voluptatem dolores ut natus?</p>
    <h2>HTML Intermediário</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque nostrum dolorem dolor facilis earum dolores voluptate modi totam odit delectus fugiat sit veritatis ullam, quidem libero atque excepturi harum at.</p>
    
</body>
</html>
```

**CSS**
```css
@charset "UTF-8";

body {
  background-color: rgb(175, 228, 170);  
}

h1#principal {
text-align: center;
background-color: rgb(7, 105, 23);
color: rgb(172, 180, 180);

}

h1 {
    color: rgb(22, 85, 20);
}

h2 {
    color:rgb(18, 131, 37)
}

p {
    text-indent: 30px;
}
```

![image](https://user-images.githubusercontent.com/108991648/225137646-561300f9-24e7-469b-b351-6943f0e1dd74.png)

_______________

## Desafio d010

