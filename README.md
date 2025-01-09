# HighSeas: FindYourCrypto🔍
Web app for searching over 1000 cryptocurrencies available on the market. <br>
Made with React, Typescript, TailwindCSS and ExpressJS, fetching [CoinGecko API](https://www.coingecko.com/en/api).

**Demo:** [here](https://ondrejpacovsky.cz/demo/highseas/FindYourCrypto/index.html) <br>
**Note:** App is not done and it can have a lot of bugs, also keep in mind that it fetches only some currencies, not all of them.

# Preview
![Preview](https://ondrejpacovsky.cz/demo/highseas/FindYourCrypto/preview.jpg)

# Requirements
- NodeJS
- LetsEncrypt cert (if using SSL, check configuration in api.js)

# Setup 
# 1) Clone repo
```
git clone https://github.com/Ondra9071/HighSeas-Stopwatch.git
```
## 2) Install libraries & init tailwind
```
cd ./HighSeas-FindYourCrypto
npm i
cd ./api
npm i
npm install -D tailwindcss
npx tailwindcss init
```
## 3) Configuration
a) /src/App.tsx `(Line 22)`
```
const API_URL = 'https://yourdomain.com:1414/api/getData'; // api url (change by your needs)
```
b) /api/api.js `(Line 9-10)`
```
const USE_SSL = true // set to false if u want to run with http (it may not work in every case)
const SSL_DOMAIN = "yourdomain.com" // domain for api, need for ssl only (you can skip this if running http)
```

## 4) Start API
```
node api.js
```
## 5) Start web app
```
cd ..
npm start
```

(Own API is used because of the rate limit of original API made by [CoinGecko](https://www.coingecko.com/en/api).

# License
This project is licensed under the MIT License - see the LICENSE file for details.

<br>
<b>#HighSeas 💖</b>
