# proxy ssh use http tunnel

For mac/linux pc
vim ~/.ssh/config and input text below
```ssh
Host 47.254.76.210
  ServerAliveInterval 60
  ProxyCommand /opt/homebrew/bin/corkscrew 127.0.0.1 10887 %h %p
```

