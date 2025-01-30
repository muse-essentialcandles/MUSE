# MUSE
Página web de: MUSE - Essential Candles
/* Estilos generales */
body {
    font-family: 'Arial', sans-serif;
    background-color: #F3EDE2;
    color: #6D4C3D;
    margin: 0;
    padding: 0;
    text-align: center;
}

/* Encabezado */
header {
    background-color: #E6D5B8;
    padding: 20px;
}

header h1 {
    font-size: 36px;
    margin: 0;
}

header p {
    font-size: 14px;
    margin: 5px 0;
}

/* Menú de navegación */
nav {
    background-color: #FAF6F0;
    padding: 10px;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #6D4C3D;
    font-weight: bold;
}

/* Imagen destacada */
.hero {
    background-color: #D9C7B0;
    height: 200px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
    font-weight: bold;
}

/* Secciones principales */
.categories {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 20px;
}

.category {
    background-color: #FAF6F0;
    width: 80%;
    margin: 10px;
    padding: 15px;
    border-radius: 5px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.category h2 {
    font-size: 20px;
    margin-bottom: 5px;
}

/* Pie de página */
footer {
    background-color: #E6D5B8;
    padding: 15px;
    margin-top: 20px;
}
