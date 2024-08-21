# Cxxd
Fdxs
{
  "name": "موقع-مدام-نزار",
  "version": "1.1.0",
  "description": "Madam Nazar's current location for Red Dead Redemption 2: Online",
  "main": "index.js",
  "scripts": {
    "dev": "pm2 start index.js --watch",
    "start": "pm2 start index.js",
    "restart": "pm2 restart index.js",
    "stop": "pm2 stop index.js"
  },
  "author": "Pavel Kuzyakin <pavel@kuzyak.in> (https://kuzyak.in)",
  "license": "MIT",
  "repository": {
    "type": "git",
    "url": "https://github.com/iposho/where-is-madam-nazar.git"
  },
  "keywords": [
    "rdr2",
    "telegram-bot",
    "telegraf"
  ],
  "dependencies": {
    "axios": "^0.21.4",
    "dotenv": "^10.0.0",
    "moment": "^2.29.1",
    "telegraf": "^4.4.2",
    "pm2": "^5.1.1"
  },
  "devDependencies": {
    "eslint": "^7.32.0",
    "eslint-config-airbnb-base": "^14.2.1",
    "eslint-plugin-import": "^2.24.2"
  }
}
