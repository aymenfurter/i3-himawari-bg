# Live Feed from Himawari-8 Weather Satelite as Background in i3.

1) Put updated _bg.sh_ in /home/_YOUR.USERNAME_/bg.sh
2) Add the following line into crobtab: 
```sh
*/10 * * * * DISPLAY=:0 /bin/sh /home/_YOUR.USERNAME/bg.sh
```

