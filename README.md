<div align="center">
  <h1>HutaoDaily</h1>
  <img src="https://raw.githubusercontent.com/FireStreaker2/hutao-dotfiles/refs/heads/main/Pictures/hutao-pfp.png" height="128" />
  <p>Daily Hu Tao pictures via Discord webhook<p>
</div>

# Installation

```bash
$ git clone https://github.com/FireStreaker2/HutaoDaily.git
$ cd HutaoDaily
$ cp .env.example .env
$ npm i
$ npm start
```

You can also use something like [pm2](https://pm2.keymetrics.io/)!

```bash
$ npm i -g pm2
$ pm2 start index.js
```

# Configuration

```sh
# .env.example
API_KEY="" # Gelbooru API key
USER_ID="" # Gelbooru user ID
WEBHOOK="" # Discord webhook
```

# License

[MIT](https://github.com/FireStreaker2/HutaoDaily/blob/main/LICENSE)
