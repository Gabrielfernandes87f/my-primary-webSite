# html/index.html

inicio

fiz a primeira tela de login

uma imagem que eu nao consegui outro svg ou link pra usar foi a imagem principal da tela de login. 

```html
...

´´´
# html/login.html

O Html tem algumas implementações que eu ainda nao estou usando.. ex: do src Controller.js.
esse link do shortcut icon linha 31 usei essa imagem apenas como um texte

```html


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Gabriel Fernandes">
    <meta name="description" content="estudos de programação">
    <meta name="keywords" content="programação, Gabriel, fernandes, programção web, sites de programção, menipulando a dom, js, javascript">
    <link rel="stylesheet" href="/css/style-home.css">
    <link rel="shortcut icon" href="/image/lente_50mm.png" type="image/x-icon">   <!-- icone do site -->
    <link rel="stylesheet" href="/css/login.css">
    <title>meu primeiro repositorio</title>
</head>
<body>

    <header>
        <img class="logo1" src="/image/logo84.png" alt="logo">

        <nav class="navbar">
           <a href="#"> Home </a>
           <a href="#"> contact </a>
           <a href="/html/login.html"> Login </a>
        </nav>

    </header>



    <main>
        <div class="boxAll">
            <div class="containermain">
                <img class="admin" src="/image/81836.png" alt="adm" srcset="">
                <div class="subContainer" >
                    <h1 class="signH1" >Sign In</h1>
                    <p class="accounts">don't have account?</p>
                    <a class="sig" href="#">sign up!</a>
                </div>

            </div>
                <div class="for1">
                    <div class="formulario1">
                        <svg version="1.1" id="svgForm" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 width="25.452px" height="25.452px" viewBox="0 0 25.452 25.452" style="enable-background:new 0 0 25.452 25.452;"
	 xml:space="preserve">
                    <g>
                        <path d="M24.301,23.281l-0.721-4.043c-0.192-1.09-1.192-2.121-2.275-2.354l-3.702-0.777l-0.76-1.559
                            c-0.04-0.082-0.109-0.142-0.188-0.188c0.665-0.855,1.197-1.87,1.581-2.89c0.663-0.24,1.33-0.832,1.521-1.6
                            c0.258-1.023-0.013-1.937-0.646-2.33V6.076C19.11,2.555,16.424,0,12.726,0C9.026,0,6.342,2.555,6.342,6.076v1.465
                            C5.708,7.934,5.437,8.848,5.693,9.869c0.193,0.772,0.865,1.367,1.53,1.604c0.378,1.021,0.906,2.033,1.568,2.892
                            c-0.075,0.045-0.142,0.102-0.181,0.182l-0.76,1.557l-3.703,0.779c-1.083,0.23-2.083,1.262-2.276,2.352l-0.72,4.043
                            c-0.102,0.57,0.034,1.113,0.382,1.529c0.348,0.416,0.858,0.646,1.438,0.646h19.506c0.58,0,1.091-0.229,1.438-0.646
                            C24.268,24.395,24.402,23.852,24.301,23.281z M23.229,24.232c-0.174,0.207-0.438,0.322-0.749,0.322h-3.757v-2.17
                            c0-0.248-0.202-0.451-0.45-0.451s-0.449,0.203-0.449,0.451v2.17H7.631v-2.17c0-0.248-0.202-0.451-0.45-0.451
                            s-0.45,0.203-0.45,0.451v2.17H2.975c-0.309,0-0.575-0.115-0.749-0.322s-0.24-0.488-0.186-0.793l0.72-4.043
                            c0.13-0.729,0.852-1.476,1.576-1.629l3.447-0.728c0.019,0.017,0.033,0.035,0.055,0.049l3.737,2.162
                            c0.069,0.041,0.147,0.062,0.226,0.062c0.044,0,0.088-0.006,0.131-0.021c0.119-0.034,0.218-0.121,0.273-0.231l0.522-1.07l0.522,1.07
                            c0.055,0.11,0.153,0.197,0.272,0.231c0.043,0.015,0.087,0.021,0.131,0.021c0.079,0,0.156-0.021,0.227-0.062l3.737-2.162
                            c0.021-0.014,0.035-0.032,0.055-0.049l3.447,0.728c0.726,0.153,1.445,0.897,1.575,1.629l0.721,4.043
                            C23.47,23.744,23.403,24.025,23.229,24.232z M8.97,15.871l0.24-0.49l0.559,0.322l0.583,0.338l0.583,0.336l1.232,0.713l-0.558,1.143
                            L9.08,16.768l-0.428-0.246l0.067-0.137L8.97,15.871z M16.485,15.871l0.25,0.514l0.067,0.137l-0.428,0.246l-2.528,1.465
                            l-0.558-1.143l1.232-0.713l0.583-0.336l0.583-0.338l0.56-0.322L16.485,15.871z M7.916,10.664C7.562,10.74,6.749,10.295,6.586,9.65
                            c-0.165-0.656-0.008-1.271,0.35-1.371C7.042,8.248,7.152,8.271,7.263,8.33V6.08c0-3.182,2.446-5.154,5.464-5.154
                            c3.02,0,5.465,1.973,5.465,5.154v2.252c0.109-0.061,0.221-0.084,0.326-0.053c0.356,0.1,0.516,0.715,0.351,1.371
                            c-0.16,0.641-0.97,1.082-1.32,1.014c-0.553,1.682-1.75,3.912-3.483,4.713c-0.416,0.191-0.861,0.305-1.336,0.305
                            c-0.482,0-0.931-0.111-1.349-0.303C9.646,14.587,8.471,12.386,7.916,10.664z"/>
                    </g>

                        </svg>
                        <input type="nome" placeholder="username">
                    </div>

                    <div class="formulario2">

                        <svg version="1.1" id="svgForm" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                        viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve">
                        <g>
                            <g>
                                <g>
                                    <path d="M201.5,472h-105c-22.056,0-40-17.944-40-40V268c0-22.056,17.944-40,40-40h288c22.056,0,40,17.944,40,40v21
                                        c0,11.046,8.954,20,20,20c11.046,0,20-8.954,20-20v-21c0-44.112-35.888-80-80-80h-24.037v-70.534
                                        C360.463,52.695,306.631,0,240.463,0s-120,52.695-120,117.466V188H96.5c-44.112,0-80,35.888-80,80v164c0,44.112,35.888,80,80,80
                                        h105c11.046,0,20-8.954,20-20C221.5,480.954,212.546,472,201.5,472z M160.463,117.466c0-42.715,35.888-77.466,80-77.466
                                        s80,34.751,80,77.466V188h-160V117.466z"/>
                                    <circle cx="203.5" cy="346" r="20"/>
                                    <path d="M491.864,403.503c-0.703-1.001-3.115-4.415-4.614-6.3c-6.696-8.422-22.376-28.146-44.193-45.558
                                        C415.085,329.319,386.299,318,357.5,318s-57.585,11.319-85.556,33.643c-21.82,17.414-37.499,37.137-44.187,45.551
                                        c-1.503,1.889-3.917,5.305-4.621,6.307c-4.847,6.898-4.848,16.096-0.002,22.994c0.705,1.003,3.119,4.421,4.617,6.302
                                        c6.694,8.422,22.373,28.145,44.192,45.559C299.915,500.681,328.701,512,357.5,512s57.584-11.319,85.557-33.643
                                        c21.817-17.413,37.498-37.136,44.196-45.562c1.498-1.885,3.908-5.296,4.611-6.297
                                        C496.712,419.599,496.712,410.401,491.864,403.503z M357.5,472c-29.705,0-60.841-19.164-92.642-57
                                        c31.799-37.835,62.935-57,92.642-57c29.703,0,60.843,19.169,92.643,57.001C418.342,452.835,387.206,472,357.5,472z"/>
                                    <circle cx="128.5" cy="346" r="20"/>
                                    <circle cx="358.5" cy="415" r="38"/>
                                </g>
                            </g>
                        </g>
                        </svg>
                   
                        <input type="password" placeholder="password">
                    </div>
                    <div class="textos">
                        <input type="checkbox" name="remanber" id="active">
                        <label  class="check" for="checbox">remenber me</label>
                        <a class="forgot1" href="#">forgot password?</a>
                    </div>
        
                <input  class="submits" type="submit" value="login">
               </div>
            </div>

    </main>




    <script src="/script/javascript.js"></script>
    <script src="/node/Controller.js"></script>

</body>
</html>


```

# formulário.html

usei o mesmo cabeçalho

ainda nao fiz o css pra ele. trabalho pra outro dia


```html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Gabriel Fernandes">
    <meta name="description" content="estudos de programação">
    <meta name="keywords" content="programação, Gabriel, fernandes, programção web, sites de programção, menipulando a dom, js, javascript">
    <link rel="stylesheet" href="/css/style-home.css">
    <link rel="shortcut icon" href="/image/lente_50mm.png" type="image/x-icon">   <!-- icone do site -->
    <link rel="stylesheet" href="/css/login.css">
    <link rel="stylesheet" href="/css/formulario.css">
    <title>Formulário</title>
</head>
<body>

    <header>
        <p class="paraLogo">Formulário</p>

        <nav class="navbar">
           <a href="#"> Home </a>
           <a href="#"> Contact</a>
           <a href="/html/login.html"> Login </a>
        </nav>
    </header>

    <main>

    <form class="formularioPrincipal" action="for-login" autocomplete="on" aria-required="true" method="POST">
        <label for="name">Nome:</label>
        <input type="name" id="name" class="name" autofocus
        required 
        placeholder="digite seu nome completo"
        size="30"
        minlength="10"
        maxlength="50"
        pattern="[A-Za-záàâãéèêíïóôõöúçñÁÀÂÃÉÈÍÏÓÔÕÖÚÇÑ ]+$"
        title="digite seu nome completo com minimo 10 letras"
        >
        <label for="contato">Contato:</label>
        <input type="numeric" id="contato" class="contato"
        required 
        placeholder="seu numero com dd"
        size="8"
        minlength="9"
        maxlength="15"
        inputmode="numeric"
        pattern="[0-9]+$"
        title="apenas números"
        >
        <label for="whats">Whatsapp:</label>
        <input type="numeric" id="whats" class="whats"
        required 
        placeholder="seu whats"
        size="8"
        minlength="10"
        maxlength="15"
        inputmode="numeric"
        pattern="[0-9]+$"
        title="apenas números"
        >
        <label for="endereco">Endereço:</label>
        <input type="name"id="endereco" class="endereco"
        required 
        placeholder="digite seu nome completo"
        size="30"
        minlength="10"
        maxlength="50"
        title="Digite seu endereço"
        pattern="[A-Za-záàâãéèêíïóôõöúçñÁÀÂÃÉÈÍÏÓÔÕÖÚÇÑ ]+$"
        >
        <label for="numero">Numero:</label>
        <input type="numeric" id="numero"
        placeholder="123"
        size="6"
        pattern="[0-9]+$"
        >
        
        <label for="estados" class="estados">Uf:</label>
         <input
           class="estados"
           list="datalist1"
           id="estados"
           placeholder="Paraiba..."
           size="16"
         />
         <datalist id="datalist1">
            <option value="Acre">Acre</option>
            <option value="Alagoas">Alagoas</option>
            <option value="Amapá">Amapá</option>
            <option value="Amazonas">Amazonas</option>
            <option value="Bahia">Bahia</option>
            <option value="Ceará">Ceará</option>
            <option value="Distrito Federal">Distrito Federal</option>
            <option value="Espírito Santo">Espírito Santo</option>
            <option value="Goiás">Goiás</option>
            <option value="Maranhão">Maranhão</option>
            <option value="Mato Grosso">Mato Grosso</option>
            <option value="Mato Grosso do Sul">Mato Grosso do Sul</option>
            <option value="Minas Gerais">Minas Gerais</option>
            <option value="Pará">Pará</option>
            <option value="Paraíba">Paraíba</option>
            <option value="Paraná">Paraná</option>
            <option value="Pernambuco">Pernambuco</option>
            <option value="Piauí">Piauí</option>
            <option value="Rio de Janeiro">Rio de Janeiro</option>
            <option value="Rio Grande do Sul">Rio Grande do Sul</option>
            <option value="Rio Grande do Norte">Rio Grande do Norte</option>
            <option value="Rondônia">Rondônia</option>
            <option value="Roraima">Roraima</option>
            <option value="Santa Catarina">Santa Catarina</option>
            <option value="São Paulo">São Paulo</option>
            <option value="Sergipe">Sergipe</option>
            <option value="Tocantins">Tocantins</option>
         </datalist>
         
         <label for="cidade">Cidade:</label>
         <input type="name" id="cidade" class="senha-repeat"
         required 
         placeholder="qual cidade mora"
         size="11"
         minlength="4"
         maxlength="10"
         >
        <label for="email">E-mail:</label>
        <input type="email" id="email" class="email"
        required 
        placeholder="Digite seu melhor e-mail"
        size="30"
        minlength="10"
        maxlength="30"
        >
        <label for="nova-senha">Criar senha:</label>
        <input type="password" id="nova-senha" class="nova-senha"
        required 
        placeholder="Digite sua senha"
        size="10"
        minlength="4"
        maxlength="8"
        >
        <label for="senha-repeat">senha:</label>
        <input type="password" id="senha-repeat" class="senha-repeat"
        required 
        placeholder="Digite novamente"
        size="11"
        minlength="4"
        maxlength="10"
        >
        <button type="submit ">Enviar</button>


    </form>   
    
</main>

    <script src="/script/javascript.js"></script>
    <script src="/node/Controller.js"></script>

</body>
	
</html>


´´´


# css/style-home


```html
    
:root, body, html{
    display: block;
    margin: 0;
    padding: 0;

}
body {
    background-color: blueviolet;
    
}
.logo1{
    width: 8em;
    height: 3em;
}
header {
    display: grid;
    grid-template-columns: 80% 15em;
    justify-content: center; /* aqui alinhou no eixo x */
    align-items: center; /* aqui alinhou no eixo y */
    background-color: rgba(0, 0, 0, 0.433);
    flex-wrap: nowrap;

    
}
a { 
    color: rgba(255, 255, 255, 0.816);
    text-decoration: none;
    margin-left: .3em;
    padding: .2em .3em .2em .3em;
    box-sizing: content-box;
    border-radius: 3em;
}

/*
@media (max-width:768px) {
    header {
        font-size: 50%;
    }
}
*/
.navbar {
    font-size: 1.1em;
    flex-wrap: nowrap;
}
 .navbar a{
     color: rgba(255, 255, 255, 0.94);
     font-weight: bolder;
     font-family:monospace;
     font-size: 1.2em;
 }





```
# css/login.css

esse é meu primeiro site, vou fazer ele responsivo, por enquanto apenas o front-end. a implementação javascript ainda preciso aprender muita coisa.

```html
img {
    width: 2.5em;
    height: 2.5em;
}
.boxAll {
    margin: 0 auto;
    margin-top: 5em;
    margin-top: 15px;
    padding: 0;

}
.containermain  {
    display: flex;
    justify-content: center;
   
    align-items: center;
    
}

.admin {
    margin-bottom: -1.5em;
    width: 5.5em;
    height: 5.5em;
  
    
}
    
.sig {
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 1.3em;
    margin-left: .9em;
    text-align: center;
    color: rgb(119, 119, 248);
   

}
.accounts {
    margin-left: .2em;
    margin-bottom: .6em;

    
}

.signH1 {
    margin-bottom: -.3em;
    text-align: center;
}
.sig:hover {
    background-color: rgb(119, 119, 248);
    color: white;

}

.for1 {
    background-color: #0e76a75d;
    border-radius: 4em 1em 4em 1em;
    width: 23em;
    height: 18em;
    text-align: center;
    margin: 0 auto;
    padding-top: 1em;
    box-shadow: rgba(0, 0, 0, 0.487) 5px 5px 20px -10px ;
    margin-top: 1em;

}
.for1 img{
    margin-bottom: -.5em;   
}

.formulario1{
    margin-top: 3em;
}

.formulario2{
    margin-top: 1.5em;
}

.textos {
    display: flex;
    margin-top: 2em;
    align-items: center;
    justify-content: space-between;
}

.forgot1 {
    margin-right: 1.5em;
}

.submits:hover{
    background-color: rgba(91, 91, 238, 0.72);
    color: white;
}


.forgot1:hover {
    background-color: rgba(113, 139, 245, 0.645);
    color: black;
}

input {
    
    background: none;
    border: none;
    border-bottom: black solid 2px;
    outline: none;
}

#active{
    margin-left: 3em;
    margin-right: -5.5em;
}

.submits {
    margin-top: 2em;
    border-radius: 2em;
    height: 3em;
    width: 10em;
    background-color: rgb(119, 119, 248);
    outline: none;
    border-bottom: none;
    
    
}
::-webkit-input-placeholder {
   color: rgba(0, 0, 0, 0.391);
}

#svgForm {
    width: 2em;
    height: 2em;
    margin-bottom: -0.3em;
}
```
