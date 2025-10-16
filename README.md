<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tableros de Control de Obra • CDMX</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
</head>
<body>

    <header class="header">
        <div class="header-left">
            <div class="logo">
                <img src="logo_cdmx.png" alt="Logo Ciudad de México">
                <div class="logo-text">
                    <p>CIUDAD DE MÉXICO</p>
                    <p>GOBIERNO DE LA CIUDAD DE MÉXICO</p>
                </div>
            </div>
            <div class="sobrse">
                <img src="logo_sobrse.png" alt="Logo SOBRSE">
            </div>
        </div>
        <div class="header-right">
            <h1>Tableros de Control de Obra • CDMX</h1>
            <p>Plataforma de seguimiento operativo • Avances físicos y financieros</p>
        </div>
    </header>

    <main class="main-content">
        <section class="welcome-section">
            <div class="welcome-text">
                <h2>Bienvenido(a) a los tableros de obra</h2>
                <p>Consulta el desempeño por proyecto con visualizaciones optimizadas para iPhone, iPad y escritorio. KPIs con modo promedio simple y ponderado por monto, y gráficos claros con la identidad visual de la Ciudad de México.</p>
                <div class="buttons">
                    <button class="btn btn-primary">Abrir Utopía Oyamel</button>
                    <button class="btn btn-secondary">Ver todos los proyectos</button>
                    <button class="btn btn-tertiary">Abrir SIG-SOBRSE</button>
                </div>
            </div>
            <div class="color-palette">
                <div class="color-row">
                    <div class="color-box green-light"></div>
                    <div class="color-box green-dark"></div>
                    <div class="color-box red-light"></div>
                    <div class="color-box red-dark"></div>
                </div>
                <div class="color-row">
                    <div class="color-box red-dark"></div>
                    <div class="color-box red-light"></div>
                    <div class="color-box green-dark"></div>
                    <div class="color-box green-light"></div>
                </div>
            </div>
        </section>

        <section class="projects-container">
            <div class="project-card">
                <h3><img src="icon.png" alt="Icono de proyecto"> UTOPIA Oyamel</h3>
                <p class="subtitle">Obra pública - CDMX · Tablero interactivo</p>
                <p>Seguimiento de avances físicos y financieros, KPIs y diferencias con frente con esquema verde/guinda.</p>
                <a href="#">Abrir tablero &rarr;</a>
            </div>
            <div class="project-card disabled">
                <h3><img src="icon.png" alt="Icono de proyecto"> Proyecto 2</h3>
                <p class="subtitle">Próximamente · Tablero interactivo</p>
                <p>Espacio reservado para otro frente/obra.</p>
                <span>No disponible</span>
            </div>
            <div class="project-card disabled">
                <h3><img src="icon.png" alt="Icono de proyecto"> Proyecto 3</h3>
                <p class="subtitle">Próximamente · Tablero interactivo</p>
                <p>Espacio reservado para otro frente/obra.</p>
                <span>No disponible</span>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>Gobierno de la Ciudad de México - SOBRSE - Tableros de Control de Obra</p>
    </footer>

</body>
</html>
