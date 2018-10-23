# mininet

# Ubuntu 16.04 4.13.0.36-generic  
 - In the newst versions of OVS, the ovs-controller was renamed to test-controller.

 - First install the openvswitch-testcontroller if you haven't with the following command:

    sudo apt-get install openvswitch-testcontroller

 - Second, create a symbolic link to the test-controller:

    sudo ln /usr/bin/ovs-testcontroller /usr/bin/controller 

That works for me. 
