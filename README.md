homestead32
===========

Laravel Homestead Using 32-bit Ubuntu 

##Why 32-bit?
The Basebox being used by the official Homestead is using ubuntu/trusty64. That is fine as long as you have the VT-x installed in your BIOS. Which is unfortunately not true for all users. 
Some motherboards even doesn't support VT-x at all. So the only choice you have is to use the 32-bit version.

This is also the common cause of 

    default: Warning: Connection timeout. Retrying…
    
Which sends a lot of developers into series of headaches.
Please check my blog post for further explanation about this : 
http://www.darwinbiler.com/default-warning-connection-timeout-retrying/
    
    

