# PruebaRA2

## 1A. ¿Por qué NO se centra el texto del <h1> en este caso? Explícalo con tus palabras. (por qué visual y estructuralmente no aparece centrado entre el borde izquierdo y el menú)
Porque display: flex; lo impide y aparte tenemos que meter el h1 con .site-header h1 en el css. Y añadimos text-align:center;

<img width="428" height="269" alt="image" src="https://github.com/user-attachments/assets/326ac1e4-4b97-401b-b23b-e7ddc715d292" />

## 1B. 
.site-header h1 {
  justify-content: space-between;
  align-items: center;
  text-align: center;
  margin-bottom: 30px;
  background-color: coral;
  padding: 70px;
  line-height: normal;
}

## 1C.
.site-header h1 {
  justify-content: space-between;
  align-items: center;
  text-align: center;
  margin-bottom: 30px;
  background-color: coral;
  padding: 70px;
  line-height: normal;
}

.main-nav p{
  align-items: center;
  text-align: center;
}
-Para que haya un espacio de 30px entre el h1 y la fila del menu he añadido un margin-bottom:30px; 

## 1D. 
.site-header h1 {
  justify-content: space-between;
  align-items: center;
  text-align: center;
  margin-bottom: 30px;
  background-color: coral;
  padding: 70px;
  line-height: normal;
}
Para cambiar el color de la cabecera he añadido background-color: coral;, para que haya una separacion visual y un espacio interior para que este pegado al borde he añadido  padding: 70px;

## 2A. 
El html:
<nav class="main-nav">
            <button class="open-menu" aria-label="Abrir menú lateral">☰</button>
                <nav id="sideMenu" class="side-menu">
                    <ul>
                        <li><a href="#hero">Inicio</a></li>
                    </ul>
                </nav>
</nav>

## 2B.
El css:
.open-menu {
  position: fixed;
  top: 14px;
  left: 14px;
  z-index: 20;
  font-size: 26px;
  background: #5c3007;
  color: white;
  padding: 6px 10px;
  border-radius: 6px;
  cursor: pointer;
  border: none;
  transition: transform 0.3s ease, background-color 0.3s ease;
}

.side-menu ul{
  display: block;
  padding: 12px 20px;
  text-decoration: none;
  color: #e06a8c;
  font-weight: bold;

  ## 3A. 
  El html:
    <section id="galeria">
            <h2>Imagen examen</h2>
                <div class="galeria-grid">
                    <img src="./img/examen.png" alt="Examen" link="https://share.google/images/Xg70PaD2P77HV8HFv">
                </div>
        </section>
El css:
.galeria-grid img {
  transition: transform 0.3s; 
  height: 200px;
  object-position: center;
}
Buscamos y apadimos la imagen con el enlace.

## 3B. 
En el css añadimos el efecto hover
.galeria-grid img:hover {
  transform: scale(1.1);
  border-radius: 2px;
  bottom: auto;
}
