# basharbar.be
<html lang="nl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Bashar Bar Menu</title>

<style>
    body {
        margin: 0;
        padding: 0;
        background: #000;
        color: #d4af37; /* Gold */
        font-family: Arial, sans-serif;
        line-height: 1.7;
        direction: ltr;
    }

    .container {
        max-width: 900px;
        margin: auto;
        padding: 20px;
    }

    /* HEADER */
    .header {
        text-align: center;
        margin-bottom: 40px;
    }

    .header-text {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 25px;
        font-size: 32px;
        font-weight: bold;
        color: #d4af37;
    }

    .header img {
        width: 75px;
        height: auto;
    }

    h2 {
        border-bottom: 1px solid #d4af37;
        padding-bottom: 5px;
        margin-top: 40px;
        font-size: 26px;
        text-transform: uppercase;
        color: #d4af37;
    }

    .item {
        font-size: 20px;
        padding: 6px 0;
        display: flex;
        justify-content: space-between;
    }

    .price {
        color: #d4af37;
        font-weight: bold;
    }
</style>

</head>
<body>

<div class="container">

    <!-- HEADER -->
    <div class="header">
        <div class="header-text">
            <span>Bashar</span>
            <img src="logo.jpeg" alt="logo">
            <span>Bar</span>
        </div>
    </div>

    <!-- DRINKS -->
    <h2>Frisdranken</h2>
    <div class="item"><span>Coca Cola</span><span class="price">2.5€</span></div>
    <div class="item"><span>Coca Cola Zero</span><span class="price">2.5€</span></div>
    <div class="item"><span>Fanta</span><span class="price">2.5€</span></div>
    <div class="item"><span>Sprite</span><span class="price">2.5€</span></div>
    <div class="item"><span>Ice Tea normaal</span><span class="price">2.5€</span></div>
    <div class="item"><span>Ice Tea peach</span><span class="price">2.5€</span></div>
    <div class="item"><span>Ice Tea green</span><span class="price">2.5€</span></div>
    <div class="item"><span>Plat water</span><span class="price">2€</span></div>
    <div class="item"><span>Bruiswater</span><span class="price">2€</span></div>
    <div class="item"><span>Nordic Mist tonic</span><span class="price">2.5€</span></div>
    <div class="item"><span>Nordic Mist agrums</span><span class="price">2.5€</span></div>
    <div class="item"><span>Gini</span><span class="price">2.5€</span></div>
    <div class="item"><span>Loza (ananas, appel, orange, ace)</span><span class="price">2.5€</span></div>
    <div class="item"><span>Redbull</span><span class="price">4.5€</span></div>

    <!-- HOT DRINKS -->
    <h2>Warme dranken</h2>
    <div class="item"><span>Koffie</span><span class="price">2.5€</span></div>
    <div class="item"><span>Koffie verkeerd</span><span class="price">4.5€</span></div>
    <div class="item"><span>Cappuccino</span><span class="price">4€</span></div>
    <div class="item"><span>Zwarte thee</span><span class="price">3€</span></div>
    <div class="item"><span>Green thee</span><span class="price">3€</span></div>
    <div class="item"><span>Verse munt thee</span><span class="price">3€</span></div>
    <div class="item"><span>Thee krank</span><span class="price">5€</span></div>

    <!-- WINES -->
    <h2>Wijnen & Bubbels</h2>
    <div class="item"><span>Witte wijn</span><span class="price">4€</span></div>
    <div class="item"><span>Rode wijn</span><span class="price">4€</span></div>
    <div class="item"><span>Rosé</span><span class="price">4€</span></div>
    <div class="item"><span>Cava</span><span class="price">4€</span></div>

    <!-- BEER -->
    <h2>Bieren</h2>
    <div class="item"><span>Jupiler</span><span class="price">2.5€</span></div>
    <div class="item"><span>Maes</span><span class="price">2€</span></div>
    <div class="item"><span>Carlsberg</span><span class="price">3€</span></div>
    <div class="item"><span>Kriek</span><span class="price">3€</span></div>
    <div class="item"><span>Hoegaarden</span><span class="price">2.5€</span></div>
    <div class="item"><span>Westmalle Tripel</span><span class="price">4.5€</span></div>
    <div class="item"><span>Duvel</span><span class="price">4.5€</span></div>
    <div class="item"><span>Orval</span><span class="price">5.5€</span></div>
    <div class="item"><span>Leffe blond</span><span class="price">4.5€</span></div>
    <div class="item"><span>Leffe bruin</span><span class="price">4.5€</span></div>
    <div class="item"><span>Corona</span><span class="price">5€</span></div>
    <div class="item"><span>Desperados</span><span class="price">5€</span></div>
    <div class="item"><span>Tripel Karmeliet</span><span class="price">4.5€</span></div>
    <div class="item"><span>Kasteel Rouge</span><span class="price">4.5€</span></div>

    <!-- Aperitif -->
    <h2>Aperitief</h2>
    <div class="item"><span>Martini bianco</span><span class="price">5€</span></div>
    <div class="item"><span>Martini rood</span><span class="price">5€</span></div>
    <div class="item"><span>Martini rosé</span><span class="price">5€</span></div>
    <div class="item"><span>Campari orange</span><span class="price">7€</span></div>
    <div class="item"><span>Apero Spritz</span><span class="price">8€</span></div>

    <!-- Vodka -->
    <h2>Vodka’s</h2>
    <div class="item"><span>Eristoff</span><span class="price">6.5€</span></div>
    <div class="item"><span>Smirnoff</span><span class="price">6.5€</span></div>
    <div class="item"><span>Absolut</span><span class="price">6.5€</span></div>
    <div class="item"><span>+ Soft drink</span><span class="price">2€</span></div>

    <!-- Cocktails -->
    <h2>Cocktails</h2>
    <div class="item"><span>Long Island</span><span class="price">10€</span></div>
    <div class="item"><span>Mojito</span><span class="price">9€</span></div>
    <div class="item"><span>Mojito aardbei</span><span class="price">9.5€</span></div>
    <div class="item"><span>Mojito Royal</span><span class="price">10€</span></div>
    <div class="item"><span>Margarita</span><span class="price">8€</span></div>
    <div class="item"><span>Cuba Libre</span><span class="price">8€</span></div>
    <div class="item"><span>Pina Colada</span><span class="price">8€</span></div>
    <div class="item"><span>Sunrise Crush</span><span class="price">8€</span></div>
    <div class="item"><span>Tequila Sunrise</span><span class="price">8€</span></div>
    <div class="item"><span>Zombie</span><span class="price">8€</span></div>
    <div class="item"><span>Black Angel</span><span class="price">8€</span></div>
    <div class="item"><span>Caipirinha</span><span class="price">8€</span></div>

    <!-- Mocktails -->
    <h2>Mocktails</h2>
    <div class="item"><span>Virgin Mojito</span><span class="price">8€</span></div>
    <div class="item"><span>Virgin Mojito aardbei</span><span class="price">8.5€</span></div>
    <div class="item"><span>Virgin Zombie</span><span class="price">7€</span></div>
    <div class="item"><span>Virgin Pina Colada</span><span class="price">7€</span></div>

    <!-- SHISHA -->
    <h2>Shisha’s</h2>
    <div class="item"><span>Love</span><span class="price">15€</span></div>
    <div class="item"><span>Mi Amor</span><span class="price">15€</span></div>
    <div class="item"><span>Dubbel Appel</span><span class="price">15€</span></div>
    <div class="item"><span>Watermelon</span><span class="price">15€</span></div>
    <div class="item"><span>Lemon & munt</span><span class="price">15€</span></div>
    <div class="item"><span>Munt</span><span class="price">15€</span></div>
    <div class="item"><span>Druif</span><span class="price">15€</span></div>
    <div class="item"><span>Lady killer</span><span class="price">15€</span></div>
    <div class="item"><span>Kauwgom munt</span><span class="price">15€</span></div>

</div>

</body>
</html>
