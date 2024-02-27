# CreateServerStarted-withNodeJS
🎓 THIS SERVER USE NODE JS USING FOR LEARNING AND PORTFOLIO

> server.js file
```
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

![CreateServerwithNodeJS](https://github.com/DevChalaam/mdFile/assets/124075393/90d5123e-42c7-4890-9175-49fc8a3a912a)

```
node server.js
```

![Command Run Server](https://github.com/DevChalaam/mdFile/assets/124075393/abe26ee8-bae9-46da-bc61-016fd94b69a8)

My Server is Running

![Start Server](https://github.com/DevChalaam/mdFile/assets/124075393/c0fb1cb8-d535-4389-a940-bb94ebca486b)

### Enter your Browser

> localhost:3000

![LinkURL](https://github.com/DevChalaam/mdFile/assets/124075393/793f7d32-2482-4f34-b5dd-c3d9837d674c)

### Show on your Browser

![Result on Browser](https://github.com/DevChalaam/mdFile/assets/124075393/b9614ac0-5a2a-44c4-b83f-897f1cab23c8)
