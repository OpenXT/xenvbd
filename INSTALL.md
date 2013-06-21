To install the XenServer Virtual Block Device Driver onto a XenServer Windows 
guest VM:

*    Copy xenvbd.sys, xencrsh.sys xenvbd_coinst.dll and xenvbd.inf onto the 
     guest VM 
*    Install xenbus.sys on the guest VM 
*    Copy dpinst.exe from the Windows driver kit into the same folder as
     xenvbd.sys, xencrsh.sys xenvbd_coinst.dll and xenvbd.inf on the guest vm, 
     ensuring the version of dpinst.exe matches the architecture of the 
     verison of Windows installed on your VM
*    As administrator, run dpinst.exe on the guest vm
*    If any warnings arise about unknown certificates, accept them

