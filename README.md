ColorOS Patchrom
==================

Source initializing:
------------------
http://source.android.com/source/initializing.html

Repo synchronization
----------
1.ColorOS patchrom repo sync

     mkdir patchrom
     cd patchrom
     repo init -u git://github.com/OneLabsOrganization/patchrom.git -b 4.2
     repo sync

Build：
-------
1.Extract your stock rom from device. And rename to update.zip

2.Type the codes below one by one 

     . build/envsetup.sh
     cd device
     make firstpatch (May gives you reject[s])
     make fullota (Give you color-update.zip）