# LinuxShell_root

* sudo whoami

      ✗ sudo whoami
      Password:
      root

* whoami

      ✗ whoami
      pintred
      
* chmod < number >

原理詳見 https://blog.csdn.net/u013197629/article/details/73608613 ）(三組數字的意義)

  chmod 666
  
  chmod 777
  
  chmod 755

      ➜  desktop ls -l StaceyKent.png  

      -rw-r--r--@ 1 pintred  staff  173305  4 28 00:32 StaceyKent.png

      ➜  desktop chmod 666 StaceyKent.png

      ➜  desktop ls -l StaceyKent.png

      -rw-rw-rw-@ 1 pintred  staff  173305  4 28 00:32 StaceyKent.png
      
* permission

開放權限攸關 chmod 後面所接的三組數字。

      chmod a+x <file>
      // all user can write file.
      
      chmod u+x <file>
      // only owner can write file.
      
* who got the file


      u: user 擁有者

      g: group 群組

      o: others 其他人

(to be continued...)
