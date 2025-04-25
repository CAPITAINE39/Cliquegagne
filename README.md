<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clique & Gagne</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(145deg, #ffcb05, #ffa500);
      color: #333;
      text-align: center;
      padding: 50px;
      animation: gradientAnimation 10s ease infinite;
    }

    @keyframes gradientAnimation {
      0% { background: linear-gradient(145deg, #ffcb05, #ffa500); }
      50% { background: linear-gradient(145deg, #ffa500, #ff5722); }
      100% { background: linear-gradient(145deg, #ffcb05, #ffa500); }
    }

    h1 {
      font-size: 3em;
      color: white;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.4);
    }

    p {
      font-size: 1.2em;
      color: white;
      margin: 20px;
    }

    .btn {
      margin-top: 30px;
      padding: 15px 25px;
      background-color: #ff5722;
      color: white;
      font-size: 1.2em;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .btn:hover {
      background-color: #e64a19;
    }

    .gift {
      margin-top: 50px;
      padding: 20px;
      background-color: #4caf50;
      color: white;
      font-size: 1.5em;
      border-radius: 10px;
      animation: bounce 1s infinite;
    }

    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
      }
      40% {
        transform: translateY(-10px);
      }
      60% {
        transform: translateY(-5px);
      }
    }
  </style>
</head>
<body>
  <h1>Clique & Gagne</h1>
  <p>Partage à 15 amis et 5 groupes pour débloquer tes mégas !</p>
  <p>À chaque ami, tu gagnes 100 Mo. Plus tu partages, plus tu gagnes !</p>
  
  <!-- Redirection vers la page de partage -->
  <a href="partager.html">
    <button class="btn">Commencer maintenant</button>
  </a>

  <div class="gift">
    🎁 Cadeau spécial : Si tu partages avec 20 amis, tu débloques 500 Mo de plus !
  </div>
</body>
</html>
