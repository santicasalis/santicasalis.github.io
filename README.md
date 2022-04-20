<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/toastify-js/src/toastify.min.css">
    <link rel="stylesheet" href="C:\Users\santi\Desktop\Final-casalis\estilos\styles.css">
    <link rel="icon" href="C:\Users\santi\Desktop\PROGRAMACION\Proyecto 2 entrga\Practica\imagenes\favicon-32x32.png">
    <title>Viajes por la patagonia</title>
</head>
<body>
    <header>
        <picture>
            <a href="index.html"> 
             <img src="imagenes/sssss.png" alt="patagonia" >   
            </a>
        </picture>
  
        <nav class=" navbar-expand-lg navbar-light " style="width:min-content">
          <div class="container">
            
            <button class="navbar-toggler " type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
              <ul class="navbar-nav">
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle text-success " href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    Patagonia
                  </a>
                  <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                    <li><a class="dropdown-item text-success" href="C:\Users\santi\Desktop\Final-casalis\links\tierraDelFuego.html">Tierra del fuego</a></li>
                    <li><a class="dropdown-item text-success" href="C:\Users\santi\Desktop\Final-casalis\links\chubut.html">Chubut</a></li>
                    <li><a class="dropdown-item text-success" href="C:\Users\santi\Desktop\Final-casalis\links\santaCruz.html">Santa cruz</a></li>
                    <li><a class="dropdown-item text-success" href="C:\Users\santi\Desktop\Final-casalis\links\rioNegro.html">Rio negro</a></li>
                    <li><a class="dropdown-item text-success" href="C:\Users\santi\Desktop\Final-casalis\links\neuquen.html">Neuquen</a></li>
                  </ul>
                <li class="nav-item">
                  <a class="nav-link text-success" href="C:\Users\santi\Desktop\Final-casalis\links\nosotros.html">Nosotros</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link text-success" href="C:\Users\santi\Desktop\Final-casalis\links\contacto.html">Contacto</a>
                </li>
                
              </ul>
            </div>
          </div>
        
    </nav>
    </header>

     <main>
      
      <article   class="container" >
      <div id= "listaProvincias" class=" grid ">

      </div>

         </article>
     

<section id="carroCompras"class="carritoFinal contenido">
  <div class="container ">
      <h1 class="text-center">CARRITO</h1>
      <hr>
      <table class="table align-middle">
        <thead>
          <tr>
            <th scope="col"></th>
            <th scope="col">Destino</th>
            <th scope="col">Precio</th>
            <th scope="col">Cantidad</th>
            <th scope="col">X</th>
          </tr>
        </thead>
        <tbody id="agregarAlFinal">
         
         
 
        </tbody>
      </table>
      </div>
      
     </section>
 
     
      <div class=" container boton">
       <div class=" col totalCarrito">
         <p  >Total:</p> 
      </div>
        <button id= "botonComprar" class=" col-md-2 btn btn-primary botonFinal data-id=5">Comprar </button>

      </div>

      <footer>
        <hr>
        <div class="redes">
          <a href="https://www.instagram.com/santicasalis/"> <img class="Insta" src="data:image/svg+xml;base64,PHN2ZyBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAgMCAyNCAyNCIgaGVpZ2h0PSI1MTIiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjUxMiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayI+PGxpbmVhckdyYWRpZW50IGlkPSJTVkdJRF8xXyIgZ3JhZGllbnRUcmFuc2Zvcm09Im1hdHJpeCgwIC0xLjk4MiAtMS44NDQgMCAtMTMyLjUyMiAtNTEuMDc3KSIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSItMzcuMTA2IiB4Mj0iLTI2LjU1NSIgeTE9Ii03Mi43MDUiIHkyPSItODQuMDQ3Ij48c3RvcCBvZmZzZXQ9IjAiIHN0b3AtY29sb3I9IiNmZDUiLz48c3RvcCBvZmZzZXQ9Ii41IiBzdG9wLWNvbG9yPSIjZmY1NDNlIi8+PHN0b3Agb2Zmc2V0PSIxIiBzdG9wLWNvbG9yPSIjYzgzN2FiIi8+PC9saW5lYXJHcmFkaWVudD48cGF0aCBkPSJtMS41IDEuNjMzYy0xLjg4NiAxLjk1OS0xLjUgNC4wNC0xLjUgMTAuMzYyIDAgNS4yNS0uOTE2IDEwLjUxMyAzLjg3OCAxMS43NTIgMS40OTcuMzg1IDE0Ljc2MS4zODUgMTYuMjU2LS4wMDIgMS45OTYtLjUxNSAzLjYyLTIuMTM0IDMuODQyLTQuOTU3LjAzMS0uMzk0LjAzMS0xMy4xODUtLjAwMS0xMy41ODctLjIzNi0zLjAwNy0yLjA4Ny00Ljc0LTQuNTI2LTUuMDkxLS41NTktLjA4MS0uNjcxLS4xMDUtMy41MzktLjExLTEwLjE3My4wMDUtMTIuNDAzLS40NDgtMTQuNDEgMS42MzN6IiBmaWxsPSJ1cmwoI1NWR0lEXzFfKSIvPjxwYXRoIGQ9Im0xMS45OTggMy4xMzljLTMuNjMxIDAtNy4wNzktLjMyMy04LjM5NiAzLjA1Ny0uNTQ0IDEuMzk2LS40NjUgMy4yMDktLjQ2NSA1LjgwNSAwIDIuMjc4LS4wNzMgNC40MTkuNDY1IDUuODA0IDEuMzE0IDMuMzgyIDQuNzkgMy4wNTggOC4zOTQgMy4wNTggMy40NzcgMCA3LjA2Mi4zNjIgOC4zOTUtMy4wNTguNTQ1LTEuNDEuNDY1LTMuMTk2LjQ2NS01LjgwNCAwLTMuNDYyLjE5MS01LjY5Ny0xLjQ4OC03LjM3NS0xLjctMS43LTMuOTk5LTEuNDg3LTcuMzc0LTEuNDg3em0tLjc5NCAxLjU5N2M3LjU3NC0uMDEyIDguNTM4LS44NTQgOC4wMDYgMTAuODQzLS4xODkgNC4xMzctMy4zMzkgMy42ODMtNy4yMTEgMy42ODMtNy4wNiAwLTcuMjYzLS4yMDItNy4yNjMtNy4yNjUgMC03LjE0NS41Ni03LjI1NyA2LjQ2OC03LjI2M3ptNS41MjQgMS40NzFjLS41ODcgMC0xLjA2My40NzYtMS4wNjMgMS4wNjNzLjQ3NiAxLjA2MyAxLjA2MyAxLjA2MyAxLjA2My0uNDc2IDEuMDYzLTEuMDYzLS40NzYtMS4wNjMtMS4wNjMtMS4wNjN6bS00LjczIDEuMjQzYy0yLjUxMyAwLTQuNTUgMi4wMzgtNC41NSA0LjU1MXMyLjAzNyA0LjU1IDQuNTUgNC41NSA0LjU0OS0yLjAzNyA0LjU0OS00LjU1LTIuMDM2LTQuNTUxLTQuNTQ5LTQuNTUxem0wIDEuNTk3YzMuOTA1IDAgMy45MSA1LjkwOCAwIDUuOTA4LTMuOTA0IDAtMy45MS01LjkwOCAwLTUuOTA4eiIgZmlsbD0iI2ZmZiIvPjwvc3ZnPg==" />
          </a>
          <a href="https://api.whatsapp.com/send?phone=5491153492473">   <img class="Insta" src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPg0KPHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJDYXBhXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSIwIDAgNTEyIDUxMiIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTEyIDUxMjsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHBhdGggc3R5bGU9ImZpbGw6IzRDQUY1MDsiIGQ9Ik0yNTYuMDY0LDBoLTAuMTI4bDAsMEMxMTQuNzg0LDAsMCwxMTQuODE2LDAsMjU2YzAsNTYsMTguMDQ4LDEwNy45MDQsNDguNzM2LDE1MC4wNDhsLTMxLjkwNCw5NS4xMDQNCglsOTguNC0zMS40NTZDMTU1LjcxMiw0OTYuNTEyLDIwNCw1MTIsMjU2LjA2NCw1MTJDMzk3LjIxNiw1MTIsNTEyLDM5Ny4xNTIsNTEyLDI1NlMzOTcuMjE2LDAsMjU2LjA2NCwweiIvPg0KPHBhdGggc3R5bGU9ImZpbGw6I0ZBRkFGQTsiIGQ9Ik00MDUuMDI0LDM2MS41MDRjLTYuMTc2LDE3LjQ0LTMwLjY4OCwzMS45MDQtNTAuMjQsMzYuMTI4Yy0xMy4zNzYsMi44NDgtMzAuODQ4LDUuMTItODkuNjY0LTE5LjI2NA0KCUMxODkuODg4LDM0Ny4yLDE0MS40NCwyNzAuNzUyLDEzNy42NjQsMjY1Ljc5MmMtMy42MTYtNC45Ni0zMC40LTQwLjQ4LTMwLjQtNzcuMjE2czE4LjY1Ni01NC42MjQsMjYuMTc2LTYyLjMwNA0KCWM2LjE3Ni02LjMwNCwxNi4zODQtOS4xODQsMjYuMTc2LTkuMTg0YzMuMTY4LDAsNi4wMTYsMC4xNiw4LjU3NiwwLjI4OGM3LjUyLDAuMzIsMTEuMjk2LDAuNzY4LDE2LjI1NiwxMi42NA0KCWM2LjE3NiwxNC44OCwyMS4yMTYsNTEuNjE2LDIzLjAwOCw1NS4zOTJjMS44MjQsMy43NzYsMy42NDgsOC44OTYsMS4wODgsMTMuODU2Yy0yLjQsNS4xMi00LjUxMiw3LjM5Mi04LjI4OCwxMS43NDQNCgljLTMuNzc2LDQuMzUyLTcuMzYsNy42OC0xMS4xMzYsMTIuMzUyYy0zLjQ1Niw0LjA2NC03LjM2LDguNDE2LTMuMDA4LDE1LjkzNmM0LjM1Miw3LjM2LDE5LjM5MiwzMS45MDQsNDEuNTM2LDUxLjYxNg0KCWMyOC41NzYsMjUuNDQsNTEuNzQ0LDMzLjU2OCw2MC4wMzIsMzcuMDI0YzYuMTc2LDIuNTYsMTMuNTM2LDEuOTUyLDE4LjA0OC0yLjg0OGM1LjcyOC02LjE3NiwxMi44LTE2LjQxNiwyMC0yNi40OTYNCgljNS4xMi03LjIzMiwxMS41ODQtOC4xMjgsMTguMzY4LTUuNTY4YzYuOTEyLDIuNCw0My40ODgsMjAuNDgsNTEuMDA4LDI0LjIyNGM3LjUyLDMuNzc2LDEyLjQ4LDUuNTY4LDE0LjMwNCw4LjczNg0KCUM0MTEuMiwzMjkuMTUyLDQxMS4yLDM0NC4wMzIsNDA1LjAyNCwzNjEuNTA0eiIvPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPC9zdmc+DQo=" />
          </a>
          <a href="https://www.linkedin.com/in/santiago-casalis-18bba1168/"> <img class="Insta" src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE4LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPg0KPCFET0NUWVBFIHN2ZyBQVUJMSUMgIi0vL1czQy8vRFREIFNWRyAxLjEvL0VOIiAiaHR0cDovL3d3dy53My5vcmcvR3JhcGhpY3MvU1ZHLzEuMS9EVEQvc3ZnMTEuZHRkIj4NCjxzdmcgdmVyc2lvbj0iMS4xIiBpZD0iQ2FwYV8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4PSIwcHgiIHk9IjBweCINCgkgdmlld0JveD0iMCAwIDExMi4xOTYgMTEyLjE5NiIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgMTEyLjE5NiAxMTIuMTk2OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+DQo8Zz4NCgk8Y2lyY2xlIHN0eWxlPSJmaWxsOiMwMDdBQjk7IiBjeD0iNTYuMDk4IiBjeT0iNTYuMDk3IiByPSI1Ni4wOTgiLz4NCgk8Zz4NCgkJPHBhdGggc3R5bGU9ImZpbGw6I0YxRjJGMjsiIGQ9Ik04OS42MTYsNjAuNjExdjIzLjEyOEg3Ni4yMDdWNjIuMTYxYzAtNS40MTgtMS45MzYtOS4xMTgtNi43OTEtOS4xMTgNCgkJCWMtMy43MDUsMC01LjkwNiwyLjQ5MS02Ljg3OCw0LjkwM2MtMC4zNTMsMC44NjItMC40NDQsMi4wNTktMC40NDQsMy4yNjh2MjIuNTI0SDQ4LjY4NGMwLDAsMC4xOC0zNi41NDYsMC00MC4zMjloMTMuNDExdjUuNzE1DQoJCQljLTAuMDI3LDAuMDQ1LTAuMDY1LDAuMDg5LTAuMDg5LDAuMTMyaDAuMDg5di0wLjEzMmMxLjc4Mi0yLjc0Miw0Ljk2LTYuNjYyLDEyLjA4NS02LjY2Mg0KCQkJQzgzLjAwMiw0Mi40NjIsODkuNjE2LDQ4LjIyNiw4OS42MTYsNjAuNjExTDg5LjYxNiw2MC42MTF6IE0zNC42NTYsMjMuOTY5Yy00LjU4NywwLTcuNTg4LDMuMDExLTcuNTg4LDYuOTY3DQoJCQljMCwzLjg3MiwyLjkxNCw2Ljk3LDcuNDEyLDYuOTdoMC4wODdjNC42NzcsMCw3LjU4NS0zLjA5OCw3LjU4NS02Ljk3QzQyLjA2MywyNi45OCwzOS4yNDQsMjMuOTY5LDM0LjY1NiwyMy45NjlMMzQuNjU2LDIzLjk2OXoNCgkJCSBNMjcuODY1LDgzLjczOUg0MS4yN1Y0My40MDlIMjcuODY1VjgzLjczOXoiLz4NCgk8L2c+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8L3N2Zz4NCg==" />
          </a>
          </div>

      </footer>
     
    </main>




    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script> 
    <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/toastify-js"></script>

    <script src="C:\Users\santi\Desktop\Final-casalis\scripts\script.js"> </script>





</body>
</html>


