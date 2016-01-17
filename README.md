
# Chatbox

A simple chatbox app adapted from Socket.io's chat example, it allows file transfer and image/video can be rendered directly. 


## How to use

```
$ cd chatbox
$ npm install
$ node index.js
```

And point your browser to `http://localhost:4321`.

To embed this chatbox into a web page, just copy paste the content in public/index.html to the page you want to have chatbox, then change all `http://localhost` to your domain name (remember to keep the port value). This app works great with light box library, I personally recommend using fancybox. 

## Other features

User can change nickname at any time.
Show recent chat history.
Sound notification when new user join or receive new message.
Support unstable Internet connection.
Admin can run JavaScript on users' browser (use with cautious).

## future plan

Improve chat history feature, currently only storing latest 20 messages
Improve file transfer support, currently file larger than 10MB may fail to transfer due to timeout, and client side may freeze once receive large file.
Add admin authentication.


