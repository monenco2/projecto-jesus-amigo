# projecto-jesus-amigo/* CONTENEDOR GENERAL */
main {
    max-width: 1200px;
    margin: -60px auto 0;
    padding: 20px;
}

/* BLOQUE UNICO */
.bloque-principal {
    background: #ffffff;
    border-radius: 18px;
    box-shadow: 0 25px 50px rgba(0,0,0,0.25);
    padding: 40px;

    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 40px;
}

/* COLUMNAS */
.col-izquierda img {
    width: 100%;
    border-radius: 12px;
    margin-bottom: 20px;
}

.col-izquierda h2 {
    color: #0A3D62;
}

.col-izquierda h3 {
    color: #1E90FF;
    margin-top: 25px;
}

/* ACCESOS (MISMA SECCIÓN, NO TARJETA) */
.col-derecha h2 {
    text-align: center;
    color: #0A3D62;
    margin-bottom: 20px;
}

.col-derecha a {
    display: block;
    padding: 15px;
    margin-bottom: 15px;
    background: linear-gradient(135deg, #0A3D62, #1E90FF);
    color: white;
    text-decoration: none;
    text-align: center;
    border-radius: 10px;
    font-weight: bold;
    transition: 0.3s;
}

.col-derecha a:hover {
    background: linear-gradient(135deg, #F6C90E, #ffe066);
    color: #000;
    transform: scale(1.05);
}

/* RESPONSIVE */
@media (max-width: 900px) {
    .bloque-principal {
        grid-template-columns: 1fr;
    }
}