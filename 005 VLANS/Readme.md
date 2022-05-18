VLANS<a name="TOP"></a>
===================

![picture alt](../005%20VLANS/images/o.png "Title is optional")

### 1. Ping between the computers to test connectivity. ###
![picture alt](../005%20VLANS/images/a.png "Title is optional")

### 2. Assign PC1 and PC3 to VLAN1, and PC2 and PC4 to VLAN2. ###

![picture alt](../005%20VLANS/images/ba.png"Title is optional")


![picture alt](../005%20VLANS/images/bb.png "Title is optional")

### 3. Attempt to ping between PC1 and PC3, and then PC2 and PC4.  Why does the ping between PC1 and PC3 work, but the ping between PC2 and PC4 doesn't? ###

![picture alt](../005%20VLANS/images/ca.png "Title is optional")

![picture alt](../005%20VLANS/images/cb.png"Title is optional")

>The f0/1 interfaces of sw1 and sw2 are assigned to the native vlan which is vlan 1 by default, so only traffic from vlan 1 can pass through them

### 4. Configure the interfaces connecting SW1 and SW2 as trunk interfaces.. ###
![picture alt](../005%20VLANS/images/d.png "Title is optional")



### 5. Ping between the computers again.  Which pings fail, and which pings succeed? ###
>PC1 to PC2 fails <br> PC1 to PC3 succeeds <br> PC1 to PC4 fails

>PC2 to PC1 fails <br> PC2 to PC3 fails <br> PC2 to PC4 succeeds

![picture alt](../005%20VLANS/images/ea.png "Title is optional")

![picture alt](../005%20VLANS/images/eb.png "Title is optional")