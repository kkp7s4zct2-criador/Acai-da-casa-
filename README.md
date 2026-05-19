<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Açaí da Casa - Catálogo</title>
    <style>
        /* Estilos Gerais */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f7f5f8;
            color: #333;
            padding-bottom: 40px;
        }

        /* Cabeçalho */
        header {
            background-color: #4a154b; /* Roxo açaí */
            color: white;
            text-align: center;
            padding: 30px 20px;
            border-bottom-left-radius: 30px;
            border-bottom-right-radius: 30px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .logo {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #fff;
            object-fit: cover;
            margin-bottom: 15px;
            background-color: #fff;
        }

        header h1 {
            font-size: 24px;
            margin-bottom: 5px;
        }

        header p {
            font-size: 14px;
            opacity: 0.9;
        }

        /* Container de Produtos */
        .container {
            max-width: 600px;
            margin: 20px auto;
            padding: 0 15px;
        }

        .section-title {
            color: #4a154b;
            margin: 20px 0 10px 0;
            font-size: 18px;
            border-left: 4px solid #e67e22; /* Detalhe laranja */
            padding-left: 8px;
        }

        /* Card de Produto */
        .card {
            background: white;
            border-radius: 15px;
            padding: 15px;
            margin-bottom: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .product-info {
            flex: 1;
            padding-right: 10px;
        }

        .product-title {
            font-size: 16px;
            font-weight: bold;
            color: #4a154b;
            margin-bottom: 5px;
        }

        .product-desc {
            font-size: 13px;
            color: #666;
            margin-bottom: 8px;
        }

        .product-price {
            font-size: 16px;
            font-weight: bold;
            color: #27ae60;
        }

        /* Botão do WhatsApp */
        .btn-order {
            background-color: #25d366; /* Verde WhatsApp */
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            border-radius: 25px;
            font-size: 13px;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 5px;
            transition: background 0.3s;
            white-space: nowrap;
        }

        .btn-order:hover {
            background-color: #128c7e;
        }
    </style>
</head>
<body>

    <!-- Cabeçalho com a Foto da Empresa -->
    <header>
        <!-- Substitua 'logo.png' pelo caminho ou link da imagem do seu açaí -->
        <img src="logo.png" alt="Açaí da Casa" class="logo">
        <h1>Açaí da Casa</h1>
        <p>✨ Delícia em Casa • Feito com Amor em Casa ✨</p>
    </header>

    <div class="container">
        
        <!-- Categoria 1 -->
        <div class="section-title">Copos Tradicionais</div>

        <!-- Produto 1 -->
        <div class="card">
            <div class="product-info">
                <div class="product-title">Copo Tradicional 300ml</div>
                <div class="product-desc">Açaí batido puro, acompanha 3 adicionais gratuitos (Banana, Granola e Leite em Pó).</div>
                <div class="product-price">R$ 15,00</div>
            </div>
            <!-- VEJA COMO CONFIGURAR O LINK: Substitua o número 55031920095218 pelo seu WhatsApp com DDD --> 031920095219
            <a href="https://wa.me." target="_blank" class="btn-order">
                Pedir no Zap
            </a>
        </div>

        <!-- Produto 2 -->
        <div class="card">
            <div class="product-info">
                <div class="product-title">Copo Tradicional 500ml</div>
                <div class="product-desc">Açaí batido puro, acompanha 3 adicionais gratuitos (Banana, Granola e Leite em Pó).</div>
                <div class="product-price">R$ 20,00</div>
            </div>
            <a href="https://wa.me." target="_blank" class="btn-order">
                Pedir no Zap
            </a>
        </div>

        <!-- Categoria 2 -->
        <div class="section-title">Na Tigela</div>

        <!-- Produto 3 -->
        <div class="card">
            <div class="product-info">
                <div class="product-title">Tigela da Casa 700ml</div>
                <div class="product-desc">Nossa tigela especial com morango, banana, granola e calda de chocolate.</div>
                <div class="product-price">R$ 28,00</div>
            </div>
            <a href="https://wa.me." target="_blank" class="btn-order">
                Pedir no Zap
            </a>
        </div>

    </div>

</body>
</html>
