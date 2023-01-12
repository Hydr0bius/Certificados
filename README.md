# Certificados
Contiene pdf de los cursos tomados en Udemy

Sitio de la página [Link](https://hydr0bius.github.io/Certificados/)

Se usaron los siguientes elementos:

Para dar un color difuminado:
```CSS
body{
    background: linear-gradient(to right, #0A2647, #144272, #205295, #2C74B3);
}
```
Pare centrar el elemento:

```CSS
header p{
    display: flex;
    justify-content: center;
}
```
Para el efecto de que solo la imagen seleccionada se haga grande y las otras imagenes queden opacas se hizo uso del **:not(:hover)**

```CSS
div:hover :not(:hover){
    opacity: 0.3;
}
img:hover{
    scale: 1.9;
    border-radius: 10%;
}
```
