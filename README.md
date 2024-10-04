<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida - Isma Cosmo</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f8f9fa;
        }
        .navbar {
            background-color: #3b5998; /* Azul oscuro */
        }
        .navbar-brand, .nav-link {
            color: white
        }
        .jumbotron {
            background-color: green
            color: white;
            padding: 2rem;
            text-align: center;
        }
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid grey
            margin: 0 auto;
        }
        .card {
            background-color: greenyellow
            color: white;
            margin-bottom: 20px;
        }
        .card-body {
            text-align: center;
        }
        .btn-custom {
            background-color: blue
            color: white;
            border: none;
        }
        .btn-custom:hover {
            background-color: blanchedalmond
        }
    </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg">
    <a class="navbar-brand" href="#">Isma Cosmo</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item">
                <a class="nav-link" href="#">Perfil</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Experiencia</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Proyectos</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Contacto</a>
            </li>
        </ul>
    </div>
</nav>

<!-- Jumbotron -->
<div class="jumbotron">
    <img src="https://www.okchicas.com/wp-content/uploads/2018/01/Poses-para-una-buena-foto-de-perfil-15-1-701x700.jpg" alt="https://www.okchicas.com/wp-content/uploads/2018/01/Poses-para-una-buena-foto-de-perfil-15-1-701x700.jpg" class="profile-pic">
    <h1 class="mt-3">Isma Cosmo</h1>
    <p>Comunicadora Publicitaria | Visual Merchandiser | Asesora Comercial</p>
    <a href="#" class="btn btn-custom">Descargar CV</a>
</div>

<!-- Cards Section -->
<div class="container">
    <div class="row">
        <!-- Card 1 -->
        <div class="col-12">
            <div class="card">
                <div class="card-body">
                    <h5 class="card-title">Perfil</h5>
                    <p class="card-text">Soy una apasionada del diseño de espacios, la creatividad y la comunicación visual. Me encanta el trabajo en equipo y la solución de problemas.</p>
                    <a href="#" class="btn btn-custom">Ver más</a>
                </div>
            </div>
        </div>

        <!-- Card 2 -->
        <div class="col-12">
            <div class="card">
                <div class="card-body">
                    <h5 class="card-title">Experiencia</h5>
                    <p class="card-text">Experiencia en asesoría de moda, exhibiciones visuales y desarrollo de estrategias de comunicación para marcas de ropa.</p>
                    <a href="#" class="btn btn-custom">Ver más</a>
                </div>
            </div>
        </div>

        <!-- Card 3 -->
        <div class="col-12">
            <div class="card">
                <div class="card-body">
                    <h5 class="card-title">Proyectos</h5>
                    <p class="card-text">Trabajo en proyectos relacionados con sustentabilidad, desarrollo de modelos de negocio y diseño consciente para el medio ambiente.</p>
                    <a href="#" class="btn btn-custom">Ver más</a>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Scripts -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>