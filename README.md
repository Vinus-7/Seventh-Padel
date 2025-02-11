<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Club de Pádel</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Designer&family=Poppins:wght@300;400;700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <h1><i class="fas fa-table-tennis"></i> Bienvenidos al Club de Pádel</h1>
        <nav>
            <ul>
                <li><a href="#inicio"><i class="fas fa-home"></i> Inicio</a></li>
                <li><a href="#reservas"><i class="fas fa-calendar-check"></i> Reservas</a></li>
                <li><a href="#galeria"><i class="fas fa-images"></i> Galería</a></li>
                <li><a href="#eventos"><i class="fas fa-trophy"></i> Eventos</a></li>
                <li><a href="#contacto"><i class="fas fa-envelope"></i> Contacto</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="inicio">
        <h2><i class="fas fa-info-circle"></i> Sobre Nosotros</h2>
        <p>Disfruta del mejor pádel con nuestras canchas de primer nivel, torneos exclusivos y entrenamientos personalizados.</p>
        <img src="img/padel-bn.jpg" alt="Imagen de pádel en blanco y negro">
    </section>
    
    <section id="reservas">
        <h2><i class="fas fa-calendar-alt"></i> Reserva tu Cancha</h2>
        <button id="reservar-btn"><i class="fas fa-check"></i> Reservar Ahora</button>
        <p id="mensaje"></p>
    </section>
    
    <section id="galeria">
        <h2><i class="fas fa-images"></i> Galería</h2>
        <div class="gallery">
            <img src="img/padel1.jpg" alt="Partido en acción">
            <img src="img/padel2.jpg" alt="Cancha iluminada">
            <img src="img/padel3.jpg" alt="Equipo ganador">
        </div>
    </section>
    
    <section id="eventos">
        <h2><i class="fas fa-trophy"></i> Eventos y Torneos</h2>
        <p>Mantente informado sobre los próximos torneos y competiciones en nuestro club.</p>
        <button id="eventos-btn">Ver Próximos Eventos</button>
    </section>
    
    <section id="contacto">
        <h2><i class="fas fa-phone"></i> Contacto</h2>
        <p><i class="fas fa-envelope"></i> Email: contacto@clubpadel.com</p>
        <p><i class="fas fa-phone"></i> Teléfono: +56 9 1234 5678</p>
    </section>
    
    <footer>
        <p>&copy; 2025 Club de Pádel. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
