Router Enable Secret<a name="TOP"></a>
===================

### 1. Connect R1 and R2 by their GigabitEthernet0/0 interfaces ###
![picture alt](../002%20Router%20Enable%20Secret/images/a.png "Title is optional")

### 2. Set the hostnames according to the network diagram (R1 and R2) ###
![picture alt](../001%20Router%20Enable%20Password/images/b.png "Title is optional")

### 3. Set the enable password on each router to 'cisco' ###
![picture alt](../001%20Router%20Enable%20Password/images/c.png "Title is optional")

### 4. Set the enable secret of each router to 'ccna' ###
![picture alt](../002%20Router%20Enable%20Secret/images/b.png "Title is optional")

### 5. Exit back to exec mode and try to enter privileged exec mode.  Which password do you have to use? ###
>ccna

### 6. View the running configuration.  Which of the passwords is encrypted? ###
>the secret ccna password

![picture alt](../002%20Router%20Enable%20Secret/images/c.png "Title is optional")

### 7. Enable password encryption on the router, and view the running configuration.  What has changed? ###
![picture alt](../002%20Router%20Enable%20Secret/images/d.png "Title is optional")

### 8. Save the configuration and reload the router to confirm. ###
![picture alt](../002%20Router%20Enable%20Secret/images/e.png "Title is optional")