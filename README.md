# LinuxShell_root

* sudo whoami

      ✗ sudo whoami
      Password:
      root

* whoami

      ✗ whoami
      pintred
      
* chmod < number >

  chmod 666
  
  chmod 777

      ➜  desktop ls -l StaceyKent.png  

      -rw-r--r--@ 1 pintred  staff  173305  4 28 00:32 StaceyKent.png

      ➜  desktop chmod 666 StaceyKent.png

      ➜  desktop ls -l StaceyKent.png

      -rw-rw-rw-@ 1 pintred  staff  173305  4 28 00:32 StaceyKent.png
      
* permission

      chmod a+x <file>
      // all user can write file.
      
      chmod u+x <file>
      // only owner can write file.
      
* who got the file


      u: user 擁有者

      g: group 群組

      o: others 其他人

(to be continued...)
