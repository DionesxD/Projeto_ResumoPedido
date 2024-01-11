# Frontend Mentor - Order summary card solution

Esta é uma solução para o [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação através da construção de projetos realistas. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


### The challenge

Os usuários devem ser capazes de:

- Ver os estados de foco para elementos interativos
​

### Screenshot

![image](https://github.com/DionesxD/Projeto_ResumoPedido/assets/110851857/d096f8d0-1b7d-4fd8-9df2-edd64d19b721)





### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles



### What I learned

Pratiquei o uso do HTML acompanhado do CSS

Ex:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->


  <link rel="icon" href="./images/icon.png">
  
  <title> PodConnectar | Resumo do pedido</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500;700;900&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="./style.css"/>
</head>
<body>
  <div class="card">
    <img class="card-image" src="./images/illustration-hero.svg" alt="">
    <div class="card-container">
     <h1>Resumo do Pedido</h1>

    <p class="card-text">Agora você pode ouvir milhões de músicas, audiolivros e podcasts em qualquer
      dispositivo em qualquer lugar que você gosta!</p>
  
    <div class="plan-card">
      <img src="./images/icon-music.svg" alt="">
      <div class="plan-info">
        <h4>Plano anual</h4>
        R$59.99/ano
      </div>

    <a href="#">Alterar</a> 
    </div>
  
    <div class="card-button">
      
      <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank"> <button class="btn-primary">Efetuar a compra</button> </a>
      <a href="https://www.youtube.com/watch?v=ywthKNqI7uI" target="_blank"> <button>Cancelar o pedido</button> </a>
    </div>
    
    
    
    </div>
    
  </div>
  
</body>
</html>
```
```css
* {
    box-sizing: border-box;
}

html, 
body{
    background-color: hsl(225, 100%, 94%);
    font-family: 'Red Hat Display', sans-serif;
    height: 100%;
    padding: 0;
    margin:  0;
}

body{
    display: flex;
    align-items: center;
    justify-content: center;
}

.card{
    background-color: white;
    width: 325px;
    overflow: hidden;
    border-radius: 20px;
    text-align: center;
    font-size: 16px;
    color: hsl(224, 23%, 55%);
    
}
.card-image{
    width: 100%;
}
.card-container{
    padding: 10px 20px;

}
.card-text{
    padding: 0 10px;
}

.plan-card{
    background-color: hsl(225, 100%, 98%);
    padding: 20px 12px;
    border-radius: 10px;
    display: flex;
    align-items: center;
    gap: 20px;
    margin: 30px 0;

}

.plan-info{
    flex: 1;
    text-align: left;
    

}
button{
    width: 100%;
    border: 0;
    border-radius: 10px;
    padding: 15px;
    font-size: 15px;
    font-weight: 900;  
    background-color: transparent;
    color: hsl(224, 23%, 55%);
    cursor: pointer;   
}

button:hover{
    color:hsl(223, 47%, 23%);
}

.card-button{
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.btn-primary{
    background-color:hsl(245, 75%, 52%) ;
    color: white;
    box-shadow: 0 20px 20px hsl(245, 75%, 52%, 0.3);
}
.btn-primary:hover{
    color:white;
    background-color: hsl(223, 47%, 23%);
}
h1{
    color: hsl(223, 47%, 23%);
    font-size: 25px;
    font-weight: 900;
}

h4{
    padding: 0;
    margin: 0;
    color: hsl(223, 47%, 23%);
    font-weight: 900;
}

a{
    font-size: 14px;
    font-weight: 700;
}
a:hover{
    color: hsl(223, 47%, 23%);
}

@media (min-width: 500px) {
    html, body {
        background-image: url('./images/pattern-background-desktop.svg');
        background-repeat: no-repeat;
        background-size: 100% auto;
    }
}
```

## Author

- Website - [DionesxD](https://www.github.com/DionesxD)
- Linkedin - [DionesxD](https://www.linkedin.com/johnnyalejandro)



