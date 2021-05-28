Make sure that you are have configured yum & dnf. Then we can do this full screen resolution process
1. yum install perl -y
2. yum install kernel-devel -y
3. yum install elfutils-libelf-devel -y
4. Now unmount your RHEL8 ISO FILE from Devices-> Optical Drives 
5. Now again go to Devices-> Select insert guest additions CD image option 
and select Run
wait for the installation of the guest cd. do not minimize or use your VM during installation as it may raise some errors.
6.  After installation just press any key and finished.
7. Now Reboot by using init 6
8. Now press ctrl+f and VM will scaled to full Resolution and your mouse movements will be smoother. now you can also switch your mouse from VM to your Windows or Mac withour pressing right ctrl key.
if ctrl+f dont work then go to settings and Choose your preferred resolution their.
9. When ecerything is done, 
Just unmount yout Guest CD from VM 
10. Mount RHEL8 iso and you are done
