# A suckless IRC package

Get ii/lchat running on your machine. From [therealtruex.com](https://therealtruex.com/posts/iilchat-setup-too-easy)

# INSTALL

- Go install ii with the SSL patch added. This will run as a local server that makes files named in and out for lchat to
use.
- Go install lchat. It uses the suckless library grapheme that you will need to install and link up.
- Go to services and edit/install the file. You will need to register
with nickserv on liberachat. Install it on your machine. If you are
using a service that isn't in there, or you find it doesn't work,
please contribute.
- copy filter/indent to the folder you will have the irc at as .filter if you want that one. To just remove messages
  that match a pattern (eg. join messages) check out that script.

Copy irc-connect and lchat-connect to your path. Modify as needed.

Make aliases for lchat-connect.

```
# example
alias lispirc='/home/jose/src/sh/lchat-connect "$HOME/irc" "irc.libera.chat" "#lisp"'
```

## TODO
- SSL using socat or some other external program
- ii on your VPS for bouncing
- other init systems
- Better installation (make)
