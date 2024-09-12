# Documentation  ![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)


 En esta seccion se encontraran los fundamentos teoricos del proyecto
## Estructura de Archivos

>IntegradoraI-NombreProyecto<br>
>| - Backend <br>
>| . Database<br>
>**| - Documentation**<br>
>&nbsp;&nbsp;|- FRs<br>
>&nbsp;&nbsp;|- NFRs<br>
>| - FrontEnd


## Equipo de Desarrollo

|Integrante|Contacto|Rol|Observaciones|
|------------|--------|---|---|
|Obed Guzman Flores|[@ObedGuzmanGuz](https://github.com/ObedGuzmanGuz)|Lider Documentador|✅ Revisado y aprobado.|
|Yazmin Gutierrez Hernandez|[@YazUtxj](https://github.com/YazUtxj)| Desarrollador de Backend|😔 No ha revisado|
|Citlalli Perez Dionicio|[@KouDionicio](https://github.com/KouDionicio)|Desarrollador de Frontend|😔 No ha revisado|




html {
    box-sizing: border-box;
    font-size: 62.5%;
}
/*Define tamaño de fuente de toda la página y agrega márgenes de tipo caja*/
body {
    fontsize: 1.6rem;
    font-family: 'Lato', sans-serif;
    background-color: gray;
}

*, *:before, *:after {
    box-sizing: inherit;
}

/*Margin, Border y Padding*/
header {
    padding: 3rem 0;
}

header h1 {
    text-align: center;
    color: wheat;
    font-size: 6rem;
}

header p {
    color:thistle;
    text-align: center;
    font-size: 3.2rem;
}

header p a {
    text-decoration: none;
    color:tomato;
}

.DOM {
    max-width: 120rem;
    margin: 0 auto;
}

.DOM h2 {
    color: #fff;
    text-align: center;
}

.DOM nav a {
    color: #fff;
    font-size: 20px;
    text-decoration: none;
    margin-right: 10px;
}

.DOM p {
    color: #2563EB;
    font-size: 20px;
}

.DOM #formulario {
    max-width: 500px;
    margin: 0 auto;
}

.DOM #formulario input {
    display: block;
    width: 100%;
    border: none;
    margin-bottom: 2rem;
    padding: 2rem;
    border-radius: 1rem;
}

.alerta {
    padding: 1rem;
    text-align: center; 
    color: #fff;
    text-transform: uppercase;
    font-size: 20px;
}

.alerta.error {
    background-color: rgb(162,0,0);
}

.alerta.exito {
    background-color: rgb(7,145,7);
}





