# SELinux-Permissive-Enforcing-Android-Termux
SELinux Permissive/Enforcing mode change Android with Termux Linux command line.

Step1
Root your phone superSU, Magisk etc..

Step2
Download Termux from google play

Step3
Open Termux

Step4
Use root mode

$ su

(Give root access termux)

Step5

Show what mode SELinux use now

$ getenforce

Step6

Set SELinux 
 
 $ setenforce 0

(Permissive)

 $ setenforce 1

(Enforcing)
