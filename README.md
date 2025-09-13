index.html <!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sorveteria Doce Sabor</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fdfdfd;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: #ff6f91;
      padding: 15px;
      position: sticky;
      top: 0;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    h1, h2 {
      text-align: center;
      margin-top: 30px;
    }
    .secao {
      margin: 40px auto;
      max-width: 800px;
      padding: 20px;
    }
    .categoria {
      background: #ffe5ec;
      padding: 15px;
      margin-top: 20px;
      border-radius: 10px;
    }
    .item {
      display: flex;
      justify-content: space-between;
      padding: 8px 0;
      border-bottom: 1px solid #ddd;
    }
    .item:last-child {
      border-bottom: none;
    }
    .preco {
      font-weight: bold;
      color: #e63946;
    }
    footer {
      background: #ff6f91;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <a href="#sabores">Sabores</a>
      <a href="#acai">Açaí & Shakes</a>
      <a href="#bebidas">Bebidas</a>
      <a href="#sobremesas">Sobremesas</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <h1>🍦 Sorveteria Doce Sabor</h1>
  <p style="text-align:center">Refresque seu dia com nossos sabores especiais!</p>

  <!-- Sabores -->
  <div id="sabores" class="secao">
    <h2>🍨 Sabores</h2>
    <div class="categoria">
      <h3>Sorvetes de Massa</h3>
      <div class="item"><span>Chocolate</span><span class="preco">R$ 8,00</span></div>
      <div class="item"><span>Morango</span><span class="preco">R$ 8,00</span></div>
      <div class="item"><span>Baunilha</span><span class="preco">R$ 8,00</span></div>
      <div class="item"><span>Napolitano</span><span class="preco">R$ 8,00</span></div>
    </div>
    <div class="categoria">
      <h3>Paletas Mexicanas</h3>
      <div class="item"><span>Morango com Leite Condensado</span><span class="preco">R$ 10,00</span></div>
      <div class="item"><span>Chocolate Recheado</span><span class="preco">R$ 12,00</span></div>
    </div>
  </div>

  <!-- Açaí & Shakes -->
  <div id="acai" class="secao">
    <h2>🥤 Açaí & Milk-shakes</h2>
    <div class="categoria">
      <h3>Açaí no Copo</h3>
      <div class="item"><span>Açaí com Granola</span><span class="preco">R$ 15,00</span></div>
      <div class="item"><span>Açaí com Banana e Mel</span><span class="preco">R$ 17,00</span></div>
    </div>
    <div class="categoria">
      <h3>Milk-shakes</h3>
      <div class="item"><span>Shake de Ovomaltine</span><span class="preco">R$ 18,00</span></div>
      <div class="item"><span>Shake de Morango</span><span class="preco">R$ 16,00</span></div>
    </div>
  </div>

  <!-- Bebidas -->
  <div id="bebidas" class="secao">
    <h2>🥤 Bebidas</h2>
    <div class="categoria">
      <h3>Refrigerantes</h3>
      <div class="item"><span>Coca-Cola (lata)</span><span class="preco">R$ 6,00</span></div>
      <div class="item"><span>Guaraná (lata)</span><span class="preco">R$ 5,00</span></div>
    </div>
    <div class="categoria">
      <h3>Sucos Naturais</h3>
      <div class="item"><span>Suco de Laranja</span><span class="preco">R$ 8,00</span></div>
      <div class="item"><span>Suco de Abacaxi</span><span class="preco">R$ 8,00</span></div>
    </div>
  </div>

  <!-- Sobremesas -->
  <div id="sobremesas" class="secao">
    <h2>🍧 Sobremesas Especiais</h2>
    <div class="categoria">
      <h3>Clássicos</h3>
      <div class="item"><span>Banana Split</span><span class="preco">R$ 20,00</span></div>
      <div class="item"><span>Petit Gateau com Sorvete</span><span class="preco">R$ 22,00</span></div>
    </div>
  </div>

  <!-- Contato -->
  <div id="contato" class="secao">
    <h2>📞 Contato</h2>
    <p style="text-align:center">
      Telefone: (11) 1234-5678<br>
      Endereço: Rua Gelada, 123 - Sorvetópolis<br>
      Instagram: @sorveteria_docesabor
    </p>
  </div>

  <footer>
    <p>&copy; 2025 Sorveteria Doce Sabor - Todos os direitos reservados</p>
  </footer>
</body>
</html>
