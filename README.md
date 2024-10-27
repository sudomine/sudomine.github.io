<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
<body class="dark-mode">
  <div class="container">
    <div class="login-box">
      <h1>Bem-vindo!</h1>
      <p>Por favor, faça login para continuar.</p>
      <form>
        <label for="username">Usuário</label>
        <input type="text" id="username" placeholder="Digite seu usuário">
        
        <label for="password">Senha</label>
        <input type="password" id="password" placeholder="Digite sua senha">
        
        <button type="submit">Login</button>
      </form>
    </div>
    <div class="image-box">
      <img src="https://via.placeholder.com/300x300?text=Gato" alt="Imagem de um gato preto fofo">
    </div>
    <div class="switch">
      <label class="switch-label">
        <input type="checkbox" id="theme-toggle" checked>
        <span class="slider"></span>
      </label>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
