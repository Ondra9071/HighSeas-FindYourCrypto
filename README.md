# HighSeas: FindYourCrypto🔍
Web app for searching over 1000 cryptocurrencies available on the market. <br>
Made with React, Typescript and TailwindCSS, fetching [CoinGecko API](https://www.coingecko.com/en/api).

**Demo:** [here](https://ondrejpacovsky.cz/demo/highseas/FindYourCrypto/index.html) <br>
**Note:** App is not done and it can have a lot of bugs, also keep in mind that it fetches only some currencies, not all of them.

# Preview
![Preview](https://ondrejpacovsky.cz/demo/highseas/FindYourCrypto/preview.jpg)

# Requirements
- NodeJS

# Setup 
## 1) Install libraries & init tailwind
```
cd ./HighSeas-FindYourCrypto
npm i
cd ./api
npm i
npm install -D tailwindcss
npx tailwindcss init
```
## 2) Start API
```
node api.js
```
## 3) Start web app
```
cd ..
npm start
```

(Own API is used because of the rate limit of original API made by [CoinGecko](https://www.coingecko.com/en/api).

# License
This project is licensed under the MIT License - see the LICENSE file for details.

<br>
<b>#HighSeas 💖</b>
