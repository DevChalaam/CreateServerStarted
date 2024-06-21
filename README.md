# CreateServerStarted-withNodeJS
🎓 THIS SERVER USE NODE JS USING FOR LEARNING AND PORTFOLIO

> server.js file

```js
// LOAD MODULES USE WITH SERVER
const http = require('http');

// SETTING PORT SERVER
const port = 3000;

// CERATE MY SERVER WITH NODE.JS
const app = http.createServer(function(request, response) {
    response.writeHead(200, {"Content-Type" : "text/html"});
    response.end("HELLO CHALAAM SERVER IS RUNNING!");
    return
});

// LISTEN PORT SERVER
app.listen(port, function() {
    console.log("SERVER IS RUNNING ON PORT : 3000");
});
```

![CreateServerwithNodeJS](https://github.com/DevChalaam/CreateServerStarted/assets/124075393/dda45cf9-faa4-4543-9899-0207329235f7)

### Command Run Server

```
node server.js
```

![Command Run Server](https://github.com/DevChalaam/CreateServerStarted/assets/124075393/c7ae1eda-b022-4057-a365-e08afaa82c4d)

### Server is Running

![Start Server](https://github.com/DevChalaam/CreateServerStarted/assets/124075393/3edfd589-8087-46c1-bd68-191dfc883b8c)

### Enter your Browser

> localhost:3000

![LinkURL](https://github.com/DevChalaam/CreateServerStarted/assets/124075393/625b78b7-169e-48b2-b849-b497236ea644)

### Show on your Browser

![Result on Browser](https://github.com/DevChalaam/CreateServerStarted/assets/124075393/af968340-6d72-4259-bace-8957bfff6f11)
