* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: arial, sans-serif;
}

/* Creación de color de fondo de pantalla */
body {
    background-color: #f7f8f9;
    height: 100vh;
}

/* Estilos para el header */
header {
    display: flex;
    justify-content: flex-end;  /* 'end' no es válido, debe ser 'flex-end' */
    height: 60px;
    padding: 0 12px;
}

/* Estilos para las opciones dentro del header */
header .options {
    display: flex;
    align-items: center;
    gap: 12px;
}

/* Estilos para los enlaces dentro de las opciones */
header .options a {
    font-family: Arial, sans-serif;  /* Capitalización correcta para 'Arial' */
    text-decoration: none;
    color: black;
}

header .options a svg {
    height: 24px;
    width: 24px;

}

header .options a img {
    border-radius: 50%;
    height: 24px;
    width: 24px;
    
}

main {
    height: calc(100% - 60px);
    display: flex;
    justify-content: center; 
    align-items: center; 
}

main .container {
    display: flex;
    flex-direction: column;
    align-items: center; 
    gap: 32px;
}

main .container figure {
    max-height: 92px;
}

main .container figure img {
    height: 100%;
}
