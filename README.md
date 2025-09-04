# A suckless IRC package

![image that literally says IRC on it](https://therealtruex.com/static/irc.webp)
![example of IRC with lchat using the fancy coloured filter](https://therealtruex.com/static/ircchat.webp "coloured
filtering and system message removal")

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
  that match a pattern (eg. join messages) check out that script. Use both for a very clean experience.

Copy irc-connect, lchat-connect, and lc to your path. Modify as needed.

```
# connect to a channel
lc commonlisp
beach: the sicl compiler bootstraps itself
> (you type)
```

## TODO
- SSL using socat or some other external program
- ii on your VPS for bouncing
- other init systems
- Better installation (make)
