<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profilo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    .profile-container {
      width: 80%;
      max-width: 800px;
      margin: 50px auto;
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      padding: 20px;
      border-radius: 8px;
    }
    .profile-header {
      text-align: center;
    }
    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #333;
    }
    .profile-info {
      margin-top: 20px;
      text-align: center;
    }
    .profile-info h2 {
      margin: 10px 0 5px;
    }
    .profile-info p {
      margin: 0;
      color: #777;
    }
    .profile-bio {
      margin-top: 20px;
      font-size: 16px;
      line-height: 1.5;
      color: #555;
      text-align: justify;
    }
  </style>
</head>
<body>
  <div class="profile-container">
    <div class="profile-header">
      <img src="profile.jpg" alt="Immagine del Profilo" class="profile-pic">
      <h2>Nome Cognome</h2>
      <p>Ruolo o Professione</p>
    </div>
    <div class="profile-info">
      <h3>Biografia</h3>
      <p class="profile-bio">
        Qui puoi scrivere una breve descrizione su di te. Spiega chi sei, cosa fai e quali sono i tuoi interessi.
      </p>
    </div>
  </div>
</body>
</html>
