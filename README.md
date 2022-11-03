# Telegram Api Reference Links

- [telegram-bot-api](https://www.npmjs.com/package/telegram-bot-api)

- [telegram oficial api documentation](https://core.telegram.org/bots/api)

- Navent telegram bot [@NaventBot](https://web.telegram.org/#/im?p=@NaventBot)

- [Configuring Webhooks](https://core.telegram.org/bots/webhooks)

# How to

- [Como configurar SSL en express](https://blog.usejournal.com/securing-node-js-apps-with-ssl-tls-b3570dbf84a5)

# SSL

ig-middleware-chat.mybluemix.net

https://www.ssllabs.com/ssltest/analyze.html

https://www.ssllabs.com/ssltest/analyze.html?d=**ig-middleware-chat.mybluemix.net/api/telegram**&hideResults=on&latest

sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout ig.key -out ig.crt

curl -F "url=https://ig-middleware-chat.mybluemix.net:8443/api/telegram" -F "certificate=@certificate.pem" https://api.telegram.org/bot832045599:AAHXe1jn1X6a3zlGYaukfrudEI_S7mqH5PQ/setWebhook

curl -F "url=https://middleware-chat.mybluemix.net/api/telegram" https://api.telegram.org/bot832045599:AAHXe1jn1X6a3zlGYaukfrudEI_S7mqH5PQ/setWebhook

curl -F "url=" https://api.telegram.org/bot832045599:AAHXe1jn1X6a3zlGYaukfrudEI_S7mqH5PQ/setWebhook
# middleware-chat
