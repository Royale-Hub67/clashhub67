<?php
session_start();
require_once("conexion.php");

// ======================================
// OBTENER LOS MAZOS MÁS POPULARES
// ======================================

$sql = "SELECT *
        FROM mazos
        ORDER BY votos_positivos DESC
        LIMIT 6";

$resultado = mysqli_query($conexion, $sql);

$mazos = [];

if ($resultado) {
    while ($fila = mysqli_fetch_assoc($resultado)) {
        $mazos[] = $fila;
    }
}

// ======================================
// FUNCIÓN PARA LIMPIAR TEXTO
// ======================================

function limpiar($dato) {
    return htmlspecialchars((string)$dato, ENT_QUOTES, 'UTF-8');
}

// ======================================
// TRADUCCIÓN DE CARTAS
// ESPAÑOL -> INGLÉS
// ======================================

$imagenesCartas = [

    "Barril de Duendes" => "Goblin Barrel",
    "Princesa" => "Princess",
    "Pandilla de Duendes" => "Goblin Gang",
    "Torre Infernal" => "Inferno Tower",
    "Caballero" => "Knight",
    "Espíritu de Hielo" => "Ice Spirit",
    "Cohete" => "Rocket",
    "El Tronco" => "The Log",
    "Tronco" => "The Log",
    "Montapuercos" => "Hog Rider",
    "Esqueletos" => "Skeletons",
    "Golem de Hielo" => "Ice Golem",
    "Mosquetera" => "Musketeer",
    "Cañón" => "Cannon",
    "Bola de Fuego" => "Fireball",
    "Pekka" => "Pekka",
    "Mago Eléctrico" => "Electro Wizard",
    "Bandida" => "Bandit",
    "Fantasma Real" => "Royal Ghost",
    "Ariete de Batalla" => "Battle Ram",
    "Veneno" => "Poison",
    "Descarga" => "Zap",
    "Zap" => "Zap",
    "Esbirros" => "Minion",
    "Mago" => "Wizard",
    "Valquiria" => "Valkyrie",
    "Dragón Infernal" => "Inferno Dragon",
    "Bebé Dragón" => "Baby Dragon",
    "Gigante" => "Giant",
    "Globo Bombástico" => "Balloon",
    "Leñador" => "Lumberjack",
    "Minero" => "Miner",
    "Arquera" => "Archers",
    "Arqueras" => "Archers",
    "Reina Arquera" => "Archer Queen",
    "Rey Esqueleto" => "Skeleton King",
    "Caballero Dorado" => "Golden Knight",
    "Minero Poderoso" => "Mighty Miner",
    "Fénix" => "Phoenix",
    "Monje" => "Monk",
    "Esqueleto Gigante" => "Giant Skeleton",
    "Megaesbirro" => "Mega Minion",
    "Dragón Eléctrico" => "Electro Dragon",
    "Lanzafuegos" => "Firecracker",
    "Murciélagos" => "Bats",
    "Tornado" => "Tornado",
    "Ejército de Esqueletos" => "Skeleton Army",
    "Duendes" => "Goblins",
    "Cementerio" => "Graveyard",
    "Cazador" => "Hunter",
    "Pescador" => "Fisherman",
    "Gigante Noble" => "Royal Giant",
    "Mega Caballero" => "Mega Knight",
    "Bruja" => "Witch",
    "Bruja Madre" => "Mother Witch",
    "Dragones Esqueleto" => "Skeleton Dragons",
    "Jaula del Forzudo" => "Goblin Cage",
    "Mortero" => "Mortar",
    "Ballesta" => "X-Bow",
    "Lanzarrocas" => "Bowler",
    "Duende Lanzadardos" => "Dart Goblin",
    "Barril de Bárbaro" => "Barbarian Barrel",
    "Flechas" => "Arrows",
    "Horno" => "Furnace",
    "Recolector de Elixir" => "Elixir Collector",
    "Torre Bombardera" => "Bomb Tower",
    "Cazador" => "Hunter",
    "Guardias" => "Guards",
    "Bruja Nocturna" => "Night Witch",
    "Duende Gigante" => "Goblin Giant",
    "Furia" => "Rage",
    "Rayo" => "Lightning",
    "Congelación" => "Freeze",
    "Espejo" => "Mirror",
    "Clon" => "Clone",
    "Terremoto" => "Earthquake",
    "Reclutas Reales" => "Royal Recruits",
    "Puercos Reales" => "Royal Hogs",
    "Máquina Voladora" => "Flying Machine",
    "Cerdos Reales" => "Royal Hogs",
    "Espíritu Eléctrico" => "Electro Spirit",
    "Espíritu Sanador" => "Heal Spirit",
    "Espíritu de Fuego" => "Fire Spirit",
    "Bárbaros" => "Barbarians",
    "Bárbaros de Élite" => "Elite Barbarians",
    "Dragón Infernal" => "Inferno Dragon",
    "Príncipe" => "Prince",
    "Príncipe Oscuro" => "Dark Prince",
    "Cementerio" => "Graveyard"
];

?>

<!DOCTYPE html>
<html lang="es">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Clashito | Mazos y Cartas</title>

    <link rel="stylesheet" href="estil.css">

</head>

<body>

<!-- ==================================
     NAVEGACIÓN
================================== -->

<header class="navbar">

    <a href="inicio.php" class="logo">
        <span class="logo-icon">⚔</span>
        CLASHITO
    </a>

    <nav class="nav-links">

        <a href="inicio.php" class="active">Inicio</a>
        <a href="busqueda.php">Mazos</a>
        <a href="servicios.php">Servicios</a>
        <a href="contacto.php">Contacto</a>

    </nav>

    <a href="IniciarSesion.php" class="login-btn">
        Iniciar sesión
    </a>

</header>


<main>

<!-- ==================================
     HERO
================================== -->

<section class="hero">

    <div class="hero-content">

        <span class="hero-tag">
            ⚡ TU COMUNIDAD DE CLASH ROYALE
        </span>

        <h1>
            Encuentra tu próximo
            <span>mazo ganador.</span>
        </h1>

        <p>
            Descubre estrategias, explora combinaciones de cartas
            y encuentra el mazo perfecto para conquistar la arena.
        </p>

        <div class="hero-buttons">

            <a href="busqueda.php" class="primary-btn">
                Explorar mazos →
            </a>

            <a href="#populares" class="secondary-btn">
                Ver populares
            </a>

        </div>

    </div>

    <div class="hero-decoration">

        <div class="shield">♛</div>

        <span>CONSTRUYE · EXPLORA · GANA</span>

    </div>

</section>


<!-- ==================================
     ESTADÍSTICAS
================================== -->

<section class="stats">

    <div class="stat-item">

        <span class="stat-icon">🃏</span>

        <div>
            <strong>8 cartas</strong>
            <small>Por cada mazo</small>
        </div>

    </div>

    <div class="stat-item">

        <span class="stat-icon">⚡</span>

        <div>
            <strong>Estrategias</strong>
            <small>Para cada estilo</small>
        </div>

    </div>

    <div class="stat-item">

        <span class="stat-icon">🏆</span>

        <div>
            <strong>Comunidad</strong>
            <small>Comparte tus mazos</small>
        </div>

    </div>

</section>


<!-- ==================================
     MAZOS POPULARES
================================== -->

<section class="popular-section" id="populares">

    <div class="section-heading">

        <div>

            <span class="section-tag">LOS FAVORITOS</span>

            <h2>Mazos populares</h2>

            <p>
                Los mazos con más votos de nuestra comunidad.
            </p>

        </div>

        <a href="busqueda.php" class="view-all">
            Ver todos →
        </a>

    </div>


    <div class="deck-grid">

        <?php if (count($mazos) > 0): ?>

            <?php foreach ($mazos as $mazo): ?>

                <article class="deck-card">

                    <!-- INFORMACIÓN DEL MAZO -->

                    <div class="deck-header">

                        <div>

                            <span class="deck-type">
                                <?php echo limpiar($mazo['tipo_mazo']); ?>
                            </span>

                            <h3>
                                <?php echo limpiar($mazo['nombre_mazo']); ?>
                            </h3>

                        </div>

                        <div class="elixir">

                            ⚡
                            <?php echo limpiar($mazo['coste_elixir_promedio']); ?>

                        </div>

                    </div>


                    <!-- CARTAS DEL MAZO -->

                    <div class="cards-grid">

                        <?php for ($i = 1; $i <= 8; $i++): ?>

                            <?php

                            // Obtener nombre de carta
                            $nombreCarta = trim(
                                (string)($mazo['carta_' . $i] ?? '')
                            );

                            // Traducir al inglés
                            // Limpiar el nombre de la carta
$nombreCarta = trim($nombreCarta);

// Buscar traducción al inglés
$nombreArchivo = $imagenesCartas[$nombreCarta] ?? $nombreCarta;

// Normalizar espacios
$nombreArchivo = preg_replace('/\s+/', ' ', $nombreArchivo);

// Separar las palabras y poner iniciales en mayúscula
$nombreArchivo = ucwords(strtolower($nombreArchivo));

// Sustituir espacios y puntos por guiones bajos
$nombreArchivo = str_replace([' ', '.'], '_', $nombreArchivo);

// Crear nombre de archivo
$rutaImagen = "img/Card_" . $nombreArchivo . ".png";

// Comprobar existencia
$archivoExiste = file_exists(__DIR__ . "/" . $rutaImagen);

                            // Crear ruta de imagen
                            $rutaImagen = "img/Card_" . $nombreArchivo . ".png";

                            // Comprobar existencia
                            $archivoExiste = (
                                $nombreCarta !== '' &&
                                file_exists(__DIR__ . "/" . $rutaImagen)
                            );

                            ?>

                            <div class="game-card">

                                <?php if ($archivoExiste): ?>

                                    <img
                                        src="<?php echo limpiar($rutaImagen); ?>"
                                        alt="<?php echo limpiar($nombreCarta); ?>"
                                        class="card-image"
                                        loading="lazy"
                                    >

                                <?php else: ?>

                                    <div class="card-placeholder">
                                        🃏
                                    </div>

                                <?php endif; ?>

                                <span>
                                    <?php echo limpiar($nombreCarta); ?>
                                </span>

                            </div>

                        <?php endfor; ?>

                    </div>


                    <!-- DESCRIPCIÓN -->

                    <div class="deck-description">

                        <?php

                        $descripcion = $mazo['descripcion_estrategia'] ?? '';

                        echo limpiar(
                            mb_strimwidth(
                                (string)$descripcion,
                                0,
                                105,
                                "..."
                            )
                        );

                        ?>

                    </div>


                    <!-- PIE DE TARJETA -->

                    <div class="deck-footer">

                        <span class="votes">

                            👍
                            <?php echo (int)$mazo['votos_positivos']; ?>
                            votos

                        </span>

                        <a href="busqueda.php?id=<?php echo (int)$mazo['id_mazo']; ?>">
                            Explorar mazo →
                        </a>

                    </div>

                </article>

            <?php endforeach; ?>

        <?php else: ?>

            <div class="empty-message">

                <span>🃏</span>

                <h3>Aún no hay mazos disponibles</h3>

                <p>
                    Cuando se publiquen mazos, aparecerán aquí.
                </p>

            </div>

        <?php endif; ?>

    </div>

</section>


<!-- ==================================
     CATEGORÍAS
================================== -->

<section class="categories-section">

    <div class="section-heading">

        <div>

            <span class="section-tag">ENCUENTRA TU ESTILO</span>

            <h2>Explora por estrategia</h2>

            <p>
                Descubre diferentes formas de jugar.
            </p>

        </div>

    </div>


    <div class="category-grid">

        <a href="busqueda.php?tipo=Cycle" class="category-card">

            <span>🔄</span>

            <h3>Cycle</h3>

            <p>Rota tus cartas rápidamente.</p>

        </a>


        <a href="busqueda.php?tipo=Control" class="category-card">

            <span>🛡️</span>

            <h3>Control</h3>

            <p>Defiende y domina la partida.</p>

        </a>


        <a href="busqueda.php?tipo=Beatdown" class="category-card">

            <span>⚔️</span>

            <h3>Beatdown</h3>

            <p>Construye ataques poderosos.</p>

        </a>


        <a href="busqueda.php?tipo=Spell%20Bait" class="category-card">

            <span>🎯</span>

            <h3>Spell Bait</h3>

            <p>Obliga al rival a gastar sus hechizos.</p>

        </a>

    </div>

</section>


<!-- ==================================
     COMUNIDAD
================================== -->

<section class="community">

    <div>

        <span class="section-tag">
            FORMA PARTE DE LA COMUNIDAD
        </span>

        <h2>¿Tienes un mazo ganador?</h2>

        <p>
            Comparte tus estrategias y permite que otros jugadores
            descubran tus mejores combinaciones.
        </p>

    </div>

    <a href="IniciarSesion.php" class="primary-btn">
        Únete ahora →
    </a>

</section>

</main>


<!-- ==================================
     FOOTER
================================== -->

<footer>

    <a href="inicio.php" class="logo">
        ⚔ CLASHITO
    </a>

    <p>
        Tu espacio para descubrir y compartir mazos de Clash Royale.
    </p>

    <small>
        © <?php echo date("Y"); ?> Clashito.
        Todos los derechos reservados.
    </small>

</footer>

</body>
</html>