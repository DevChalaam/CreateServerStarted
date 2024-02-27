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

```
node server.js
```

