# Linux Zen 5.15 for Arch Linux  
This is a working, optimized kernel.  
Use this as an entry point for more drastic optimizations.  
List of changes:  
<ol>
  <li>Selected proper CPU family</li>
  <li>Turn off AMD CPU options</li>
  <li>Turn off open source Nvidia drivers</li>
  <li>Decreased maximum number of CPU's and GPU's</li>
  <li>Disabled options for old computers like MBR Tables</li>
  <li>Used <strong>modprobed-db</strong> to disable unused modules </li>
</ol>

_______________________________________________________________________  

Required rebuilding DKMS to connect to internet (which should be the case for all customs, but it is not)  
Booting into DE is slow - some lag at 75%. It seems to get better though.  
Initially all seems to work, including steam, proton and mangohud.  

The login takes still quite long, even after 5 boots.
