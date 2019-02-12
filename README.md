# verificador-de-nicks-tibia

An application for checking available nicknames in Tibia (2 or 3 characters big).

<p align="center">
  <img src="https://i.imgur.com/9STQDB5.png">
</p>

### Installation

  - You need [Node.js](https://nodejs.org/) to run this bot
  - You need the [xmlhttprequest](https://www.npmjs.com/package/xmlhttprequest) package to send GET requests
  - This project uses the [TibiaData API](https://tibiadata.com/) to get characters information

Install the dependencies with:

```
npm install xmlhttprequest
```

Inside ```index.js``` call the main functions in the driver program:

```javascript
nomes2();
```

or

```javascript
nomes3();
```

Then simply run it with:

```
node index.js
```
