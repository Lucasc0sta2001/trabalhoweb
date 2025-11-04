<!DOCTYPE html>
<html lang="en">
<head>
   <style>
    * {
    margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    .carousel {
        margin: 100px auto;
        width: 90%;
        border: 5px solid rgb(255, 255, 255);
        display: flex;
        overflow-x: auto;   /*barra de rolagem*/
        padding: 20px;
    }

    .group{
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 1em;
        padding-right: 1em;
        
    }


    .card{
        flex: 0 0 150px;
        height: 5em;
        padding: 0%;
        background: rgb(247, 0, 0); /* fundo das imagens*/
        font-size: 3rem;
        border-radius: .2em;
        text-align: center;
        align-content: center;
        border-radius: .3em;

    }
    .rodape{
        align-items: center;
    }
   </style>
</head>
<body>
    <div class="carousel">
        <div class="group">                                 
            <div class="card"><img src="https://images.unsplash.com/photo-1514525253161-7a46d19cd819?auto=format&fit=crop&w=400&h=240" alt=""></div>        
            <div class="card"><img src="https://images.unsplash.com/photo-1514525253161-7a46d19cd819?auto=format&fit=crop&w=400&h=240" alt=""></div>        
            <div class="card"><img src="https://images.unsplash.com/photo-1514525253161-7a46d19cd819?auto=format&fit=crop&w=400&h=240" alt=""></div>
            <div class="card"><img src="https://images.unsplash.com/photo-1514525253161-7a46d19cd819?auto=format&fit=crop&w=400&h=240" alt=""></div>
            <div class="card"><img src="https://images.unsplash.com/photo-1514525253161-7a46d19cd819?auto=format&fit=crop&w=400&h=240" alt=""></div>
            <div class="card"><img src="https://images.unsplash.com/photo-1514525253161-7a46d19cd819?auto=format&fit=crop&w=400&h=240" alt=""></div>
        </div>
    </div>
    <div class="rodape">
         <h1>Tire suas dúvidas aqui</h1>

         <h2> Como eu cancelo ou peço reembolso de ingressos?</h2>


         <h3>Como localizar meus ingressos?</h3>

        <h4>Como trocar a titularidade do ingresso?</h4>
        </div>
    </div>
    <script>


    </script>
</body>
</html>
