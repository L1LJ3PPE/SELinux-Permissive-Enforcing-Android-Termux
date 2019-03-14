# SELinux-Permissive-Enforcing-Android-Termux
SELinux Permissive/Enforcing mode change Android with Termux Linux command line.

1. Root your phone superSU, Magisk etc..

2. Download Termux from google play

3. Open Termux
_____________________________________
4. Use root mode (Give root access termux)
  
  $ su   

5. Show what mode SELinux use now

  $ getenforce

6. Set SELinux 
 
  $ setenforce 0

(Permissive)

  $ setenforce 1

(Enforcing)
____________________________________
