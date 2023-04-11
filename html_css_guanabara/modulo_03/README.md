# html_css


- [x] Exercícios ([022 até ***](https://github.com/PamelaRondina/html_css/tree/main/html_css_guanabara/modulo_03#aula-022))<br>
- [x] Desafios ([d011 até d***](https://github.com/PamelaRondina/html_css/tree/main/html_css_guanabara/modulo_03#desafio-d011))
<br>

Comandos em HTML: [clique Aqui](https://github.com/PamelaRondina/step-by-step/tree/main/html)<br>
Comandos em CSS: [clique Aqui](https://github.com/PamelaRondina/step-by-step/tree/main/css)



### [Aula 022](https://github.com/PamelaRondina/html_css/tree/main/html_css_guanabara#aula-022) 


- [x] background-image: url('link');
- [x] background-repeat: url('link');
- [x] background-position: ---;
- [x] background-size;
- [x] background-attachment e shorthand;

**fundo001 -  background-image: url('link');**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teste de Imagem de Fundo - 001</title>

    <style>

        body {
            background-image: url('images/wallpaper001.jpg');
        }
        div.quadrado {
            display: inline-block;
            border: 2px solid black;
            border-radius: 10px;
            width: 300px;
            height: 300px;            
        }
        
        div#q1 {
            background-color: aqua;
        }

        div#q2 {
            background-image: linear-gradient(to right, yellow, lightgreen,  blue);
        }

        div#q3 {
            background-image: url('images/pattern001.png');
        }

    </style>
</head>
<body>
    
    
</body>
<div class="quadrado" id="q1">

</div >

<div class="quadrado" id="q2">

</div>

<div class="quadrado" id="q3">

</div>

</html>
```

![image](https://user-images.githubusercontent.com/108991648/228563543-f57d81f4-2743-4b8a-89f5-b07e24b94860.png)

--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->

**fundo002. background-image: url(link externo)**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teste de Imagem de Fundo - 002</title>

    <style>
        body {
            background-image: url('https://avatars.githubusercontent.com/u/8683378?v=4');
        }


    </style>
</head>
<body>
    
    
</body>
</div>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/228575637-f4f3396c-becd-4693-83ce-3ddd3a202d40.png)

--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->


**background-position: ---;**

```html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Posição dos fundos</title>

    <style>
        div.bloco {
         background-image: url('images/wallpaper003.jpg');
         height: 200px;
         border: 1px solid black;
         border-radius: 20px;
         margin: 10px;        
        }
 
        div#q1 {
         background-position: left top;
         
        }
 
        div#q2 {
         background-position: left center;        
        }
 
        div#q3 {
         background-position: right bottom;        
        }
 
        div#q4 {
         background-position: center center;
        }
 
 
     </style>  
</head>
<body>
    
    
    <div class="bloco" id="q1">
        
    </div>

    <div class="bloco" id="q2">

    </div>

    <div class="bloco" id="q3">

    </div>

    <div class="bloco" id="q4">

    </div>
</body>
</div>
</html>
```

![image](https://user-images.githubusercontent.com/108991648/228623618-39e441bd-277f-417d-8ffb-19672c1de5d2.png)

--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->


**background-position: center center;**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Posição</title>
</head>
<body>
    <style>
        body {
            height: 50vh;
            border: 1px dashed black;
            background-image: url('https://avatars.githubusercontent.com/u/8683378?v=4');
            background-size: 100px;
            background-repeat: no-repeat;
            background-position: center center; 
        }           
    </style>
       
</body>

</html>
```

![image](https://user-images.githubusercontent.com/108991648/229554814-40066070-c010-4de3-a67d-84a2272d82fe.png)

--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->--->



__________________________








## Desafio d010

