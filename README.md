<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Iguanas Electricas - Instituto Tecnológico Superior de Acatlán de Osorio</title>
 <link rel="stylesheet" href="styles.css">
    <!-- Bootstrap para darle un diseño más estilizado -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Barra de Navegación -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Instituto Tecnológico Superior de Acatlán de Osorio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#Instrumentacion">Categorías</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contacto">Contacto</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Sección Principal -->
    <header class="bg-primary text-white text-center py-5">
        <h1>Bienvenido a Iguanas Electricas</h1>
        <p>Tu sitio de confianza para todo lo relacionado con tecnología y electrónica</p>
        <a href="#categorias" class="btn btn-light">Explorar</a>
    </header>

    <!-- Sección de Instrumentación -->
    <section id="categorias" class="container my-5">
        <h2 class="text-center">Categorías</h2>
        <div class="row">
            <div class="col-md-4 text-center">
                <img src="hardware.jpg" alt="Hardware" class="img-fluid">
                <h3>Hardware</h3>
                <p>Todo sobre componentes electrónicos, PC, móviles y más.</p>
            </div>
            <div class="col-md-4 text-center">
                <img src="software.jpg" alt="Software" class="img-fluid">
                <h3>Software</h3>
                <p>Noticias sobre desarrollo de software, apps y sistemas operativos.</p>
            </div>
            <div class="col-md-4 text-center">
                <img src="reviews.jpg" alt="Reviews" class="img-fluid">
                <h3>Reseñas</h3>
                <p>Opiniones y análisis sobre los últimos productos tecnológicos.</p>
            </div>
        </div>
    </section>

    <!-- Sección del Blog -->
    <section id="blog" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center">Últimas Publicaciones</h2>
            <!-- Aquí irían los artículos más recientes -->
            <div class="row">
                <div class="col-md-4">
                    <h3>Guía: Cómo montar tu propio PC</h3>
                    <p>Aprende a armar un PC desde cero con esta guía paso a paso.</p>
                </div>
                <div class="col-md-4">
                    <h3>Review: El mejor smartphone del 2024</h3>
                    <p>Análisis del último modelo con todas sus características.</p>
                </div>
                <div class="col-md-4">
                    <h3>Comparativa: Las mejores laptops para programadores</h3>
                    <p>Comparamos las laptops más populares para desarrolladores.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección de Contacto -->
    <section id="contacto" class="container my-5">
        <h2 class="text-center">Contacto</h2>
        <form>
            <div class="mb-3">
                <label for="nombre" class="form-label">Nombre</label>
                <input type="text" class="form-control" id="nombre">
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Correo Electrónico</label>
                <input type="email" class="form-control" id="email">
            </div>
            <div class="mb-3">
                <label for="mensaje" class="form-label">Mensaje</label>
                <textarea class="form-control" id="mensaje" rows="3"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Enviar</button>
        </form>
    </section>

    <!-- Pie de Página -->
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2024 TecnoWorld. Todos los derechos reservados.</p>
    </footer>

    <!-- Bootstrap JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
4. Estilos CSS (styles.css)
Puedes personalizar los estilos para que la página se vea más moderna y profesional. Aquí tienes un ejemplo básico para agregar al archivo styles.css:

css
Copiar código
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-image: url('header-background.jpg');
    background-size: cover;
    background-position: center;
    color: white;
    padding: 100px 0;
}

h1, h2, h3 {
    font-family: 'Roboto', sans-serif;
}

section {
    padding: 50px 0;
}

footer {
    background-color: #333;
}
