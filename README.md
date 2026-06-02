<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
  </head>
  <body>
   

    <!-- 2. Navbar komponenti -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Mening Saytim</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#">Bosh sahifa</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Xizmatlar</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Aloqa</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- 3. Header (Hero) qismi -->
    <header class="bg-primary text-white text-center py-5">
        <div class="container">
            <h1 class="display-4">Xush kelibsiz!</h1>
            <p class="lead">Bu Bootstrap yordamida yaratilgan Hero qismi.</p>
            <a href="#" class="btn btn-light btn-lg">Batafsil ma'lumot</a>
        </div>
    </header>

    <!-- 4. <main> tegi ichida Card komponentlari -->
    <main class="container my-5">
        <div class="row">
            <!-- Card 1 -->
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTcLX-0abAWnmNtlFUGO3g1iDJNPpshv2LrcQ&s" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Kurs 1</h5>
                        <p class="card-text">Bootstrap asoslarini o'rganish juda oson va qiziqarli.</p>
                        <a href="#" class="btn btn-primary">Ko'rish</a>
                    </div>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTcLX-0abAWnmNtlFUGO3g1iDJNPpshv2LrcQ&s" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Kurs 2</h5>
                        <p class="card-text">Responsive dizayn yaratishni o'rganing.</p>
                        <a href="#" class="btn btn-primary">Ko'rish</a>
                    </div>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTcLX-0abAWnmNtlFUGO3g1iDJNPpshv2LrcQ&s" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Kurs 3</h5>
                        <p class="card-text">Tayyor komponentlardan foydalanib vaqtni tejang.</p>
                        <a href="#" class="btn btn-primary">Ko'rish</a>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- 5. <footer> qismi -->
    <footer class="bg-dark text-white text-center py-4">
        <div class="container">
            <p class="mb-0">&copy; 2024 Barcha huquqlar himoyalangan.</p>
            <small>Bootstrap Junior Amaliy Vazifa</small>
        </div>
    </footer>

    <!-- Bootstrap JS Script (Navbar va boshqa interaktiv elementlar ishlashi uchun) -->
 

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
  </body>
</html>
