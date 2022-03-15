1.cd ~/home/scott 
2.LS /home 
3.mv ~/log.tar.gz home scott
4.chown ~/log.tar.gz1.


Solutions:

1.It represents another folder in the same psath as Home. We can change it by 2 Ways- cd~ cd/home/scott 
2.L should be in lower case ls/home
3.mv command takes only 2 arguments.We need to covert that into path. mv ~/log.tar.gz /home/scott 
4.It is missing the Octal Representation. chown 644 ~/log.tar.gz (or other mode).
