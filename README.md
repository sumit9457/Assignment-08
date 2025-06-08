<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bootstrap Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .header-section {
      background: linear-gradient(to right, rgba(131,58,180,0.8), rgba(253,29,29,0.7));
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    .header-section h1 {
      font-size: 3rem;
      font-weight: bold;
    }
    .content-section {
      padding: 60px 20px;
    }
    .bold-text {
      font-weight: bold;
    }
    .calendar-box {
      background-color: #222;
      color: white;
      font-size: 1.5rem;
      padding: 20px;
      text-align: center;
      border-radius: 10px;
    }
    .calendar-box div {
      margin: 10px 0;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">HEADER THEME</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" href="#">WATCH VIDEO</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown">MENUS</a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Menu 1</a></li>
              <li><a class="dropdown-item" href="#">Menu 2</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown">BLOCKS</a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Block A</a></li>
              <li><a class="dropdown-item" href="#">Block B</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="btn btn-light text-primary ms-2" href="#">BUY NOW</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Header -->
  <div class="header-section">
    <h1>Headers</h1>
  </div>

  <!-- Content -->
  <div class="container content-section">
    <div class="row align-items-center">
      <div class="col-md-6 mb-4 mb-md-0">
        <h2>Economic <span class="bold-text">Analysis</span></h2>
        <p>
          Click any text to edit or style it. Click blue "Gear" icon in the top right corner to hide/show buttons, text, title and change the block background.
          Click red "+" in the bottom right corner to add a new block. Use the top left menu to create new pages, sites and add extensions.
        </p>
      </div>
      <div class="col-md-6">
        <div class="calendar-box">
          <div>1 &nbsp;&nbsp; 6 &nbsp;&nbsp; 11 &nbsp;&nbsp; 16 &nbsp;&nbsp; 21  &nbsp;&nbsp; 26 </div>
          <div>2 &nbsp;&nbsp; 7 &nbsp;&nbsp; 12 &nbsp;&nbsp; 17 &nbsp;&nbsp; 22  &nbsp;&nbsp; 27 </div>
          <div>3 &nbsp;&nbsp; 8 &nbsp;&nbsp; 13 &nbsp;&nbsp; 18 &nbsp;&nbsp; 23 &nbsp;&nbsp; 28 </div>
          <div>4 &nbsp;&nbsp; 9 &nbsp;&nbsp; 14 &nbsp;&nbsp; 19 &nbsp;&nbsp; 24  &nbsp;&nbsp; 29 </div>
         <div>5 &nbsp;&nbsp; 10 &nbsp;&nbsp; 15 &nbsp;&nbsp; 20 &nbsp;&nbsp; 25 &nbsp;&nbsp; 30</div>
        </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Scripts -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
