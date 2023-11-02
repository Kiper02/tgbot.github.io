<!DOCTYPE html>
<head>
    <title>Магазин обуви</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>

</head>
<body>
    <h1>Магазин обуви</h1>
    <div id="usercard">

    </div>
    <p>Just text</p>
    <a class="link" href="https://mihailgok.ru">Link</a>
    <p class="hint">Some little hint</p>
    <button id="btn" class="button">Show/Hide Main Button</button>
    <button id="btnED" class="button">Enable/Disable Main Button</button>
    <script>
        let tg = window.Telegram.WebApp;
        tg.expand();

        tg.MainButton.text = "Changed Text";
        tg.MainButton.setText("Changed Text1");
        tg.MainButton.textColor = "#F55353";
        tg.MainButton.color = "#143F6B";
        tg.MainButton.setParams({"color":"#143F6B"})

        


    </script>
</body>
