*Flores Amarillas*


*Código de colores*


- Azul: `#007bff`
- Verde: `#2ecc71`
- Amarillo: `#ffff00`
- Rojo: `#ff0000`


*Código HTML*


```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flores Amarillas</title>
    <link rel="stylesheet" href="Css/style.css">
</head>
<body>
    <div class="Contenedor-Binicio">
        <button class="Button" id="BVer">Clicka aqui</button>
    </div>
    <div class="Con-Emergente">
        <div id="resultado" class="cua">
            <p id="res">Hola, antes de iniciar, solo quiero recordarte que eres muy especial para mí y gracias por todo.</p>
            <button id="BotonCerrar" class="Button">Cerrar</button>
        </div>
    </div>
</body>
</html>
```


*Código CSS*


```
body {
    background-color: #f2f2f2;
    font-family: Arial, sans-serif;
}

.Contenedor-Binicio {
    background-color: #007bff;
    padding: 20px;
    text-align: center;
}

.Button {
    background-color: #2ecc71;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.Con-Emergente {
    background-color: #ffff00;
    padding: 20px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

#resultado {
    background-color: #fff;
    padding: 20px;
    border: 1px solid #ddd;
}

#res {
    font-size: 18px;
    font-weight: bold;
    color: #ff0000;
}