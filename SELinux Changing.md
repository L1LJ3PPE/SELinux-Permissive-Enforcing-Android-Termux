# SELinux-Permissive-Enforcing-Android-Termux
SELinux Permissive/Enforcing mode change Android with Termux Linux command line.

1. Root your phone superSU, Magisk etc..

2. Download Termux from google play

3. Open Termux
_____________________________________
4. Use root mode (Give root access termux)
  
   COMMAND: $ su   

5. Show what mode SELinux use now

COMMAND: $ getenforce

6. Set SELinux 
 
 COMMAND: $ setenforce 0

(Permissive)

COMMAND: $ setenforce 1

(Enforcing)
____________________________________
