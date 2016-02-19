# Using Router for structure
When using Express you can use express.Router to give your project structure.

In `app.js` you can do

```
var express = require('express')
var app = express()
var message = require('./routes/message')

app.use('/message', message)
```

And inside `/routes/message.js` you can do

```
var express = require('express')
var router = express.Router()

// Routes for /message
router.route('/')
.get(function(req, res, next){
  res.send("Hello World")
})
```

This way you can structure your application very easily!
