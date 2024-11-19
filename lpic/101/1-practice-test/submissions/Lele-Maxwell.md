**1**: B
**2**:
Here are the difference between BIOS and UEFI
- The BIOS is an older version firmware in computers while the UEFI is a
  morden firmware in computers for booting
- The BIOS support older hardwarecomponents while the UEFI supports new and
  mordern devices
- The BIOS make use of the MBR for loading the OS while the UEFI make use
    of the EFI
-The BIOS being an older firmware for booting is more expese to insecurity
   as compared to thr UEFI which is of advace technology
-The UEFI supports drives of larger size as compared to the BIOS
**3**:
  command to list loaded modules
  *lsmod
  how to load a module
  ..use the command modprobe followed by the module name
  ..syntax: modprobe <module-name>
  ..for a module calles dummy the command id as follow
    modprobe dummy
  **4**:
  * /proc :This is a directory that contains information about system processes
    and hard ware .It holds settings and properties for the kernel
  * /sys: It is directory which contains system infos amd file system which provides
    provides the kernel properties,hardwares devices amd device drivers

    **SECTION 2**
    **5**
    * C:apt install package
    **6**
      Diffences between apt and dpkg
      * apt is an advance package manger while dpkg is an older pakage manager
      * apt is a high level as compared to dpkg which is a low-level package manager
      * apt is an advance tool pakage manager while dpkg isnot
      **7**:
       command: apt purge ~o


      

       **8**:



      **SECTION 3**

      **9**:
      B:tail
      **10**:
      cat /var/log/syslog | grep error | wc -l
      **11**:
      Diferrences between hard and soft link
      - hard links can't point accross different file system while a soft
        link can poing accoss different file system
      - hard links points to thesame inode as the original file while soft link
        points to different inode as the original file
      - hard links consumes less space as compared to soft links because of their
      - inode allocation on the disk storage
      - they are also different in syntax when creating
        ...hard link: ln <source-file> <link>
        ...soft link: ln -s <source-file> <link>
      **12**:
          find /etc/*.conf -mtime 7 -daystart
      **13**:
        **Cron**:
        The cron daemon is abackground job that runs autamatically without
        forcefully the intervention human.it used in scheduling jobs to
        to tun after a particular period of time.This can be set  in the
        /etc/crontab configaration file which after save will persist over
        multiple reboot .
        **example**
         
         *  *  *  *  * user-name command to be executed
         *  12 25 12 * Maxwell date > backup.sh  
      
   * In the /ect/crontab file , the script above is entered
   * The script will siply print the date and time into the backup.sh file
   * **every day 25th , 12th month  at 12am every year**

  **14**:
  B:Disk usage in human-readable format
  **15**
  cat /etc/fstab | grep UUID=
  **16**:
  Comparing ext3 an ext4

       
    
