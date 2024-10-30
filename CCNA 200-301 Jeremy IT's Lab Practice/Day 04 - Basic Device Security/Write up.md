Lab overview:
Implement basic device security on networking devices such as router and switch by adding password to the device's configuration

Task 1:
Change the hostnames of the router and switch to the appropriate names (R1, SW1) 
##Use the 'hostname' command in global configuration mode##

This can be done by using the device's CLI and enter into privileged mode and enter the configuration terminal and change the hostname by "hostname <device-name>" command.
Router: ![Screenshot 2024-10-29 003229](https://github.com/user-attachments/assets/3c90e21c-213b-4132-bdea-1d846d8d6e3b) Switch: ![Screenshot 2024-10-29 003257](https://github.com/user-attachments/assets/24495303-0588-4b6b-a956-afdba0e7789c)

Task 2:
Configure an unencrypted enable password of 'CCNA' on both devices.

This can be done by using command "enable password CCNA". Router:![Screenshot 2024-10-29 003417](https://github.com/user-attachments/assets/c305d815-2818-45ec-bd34-dea38483f98e) Switch:![Screenshot 2024-10-29 003447](https://github.com/user-attachments/assets/80438938-b876-4dc5-a154-36c49078266d)

Task 3: 
Exit back to user EXEC mode and test the password
Router:![Screenshot 2024-10-30 145928](https://github.com/user-attachments/assets/f9616bf9-96fe-4fec-9fd5-faf3fa4d6d2c) Switch: ![Screenshot 2024-10-30 150002](https://github.com/user-attachments/assets/d611d465-472e-4919-b639-39a6ff277e8d)

Task 4:
View the password in the running configuration

To show the running config, i used the show running-config/sh run/do sh run. Router:![Screenshot 2024-10-30 150036](https://github.com/user-attachments/assets/7da4aeac-ddec-4ccd-a624-88fb48e13142) Switch:![Screenshot 2024-10-30 150048](https://github.com/user-attachments/assets/baf8562c-2baa-4160-b7a0-19ce112b5837)

Task 5:
Ensure that the current password, and all future passwords, are encrypted

To encrypt current password, i used the command "service password-encryption" on both devices.

Task 6:
View the password in the running configuration. Router: ![Screenshot 2024-10-30 150232](https://github.com/user-attachments/assets/d351d1aa-18e3-4e87-b801-8818e55fe529) Switch:![Screenshot 2024-10-30 150247](https://github.com/user-attachments/assets/7e18de37-3e3d-452a-8c59-1b7432e0f213)

Task 7:
Configure a more secure, encrypted enable password of 'Cisco' on both devices

To configure a more secure password, i used "enable secret <password>" on both devices which automatically encrypt the password using more secure encryption. 

Task 8:
Exit back to user EXEC mode and then return to privileged EXEC mode. Which password do you have to use?

Of course i need to use the newer and more secure password, which is 'Cisco'

Task 9:
View the passwords in the running configuration. What encryption type number is used for the encrypted 'enable password'? What encryption type number is used for the encrypted 'enable secret'?
enable password use type 7 and enable secret use type 5
Router: ![Screenshot 2024-10-30 150433](https://github.com/user-attachments/assets/364e59a9-7428-4e94-88a3-9227e1e8f2dc) Switch:![Screenshot 2024-10-30 150443](https://github.com/user-attachments/assets/47744a2d-800c-4200-83be-7086ca2d8363)

Task 10:
Save the running configuration to the startup configuration.

Router: ![Screenshot 2024-10-30 150548](https://github.com/user-attachments/assets/b0b36d40-01ec-496e-8c06-fdc440132151) Switch: ![Screenshot 2024-10-30 150611](https://github.com/user-attachments/assets/0045bd8a-5d31-47d5-a334-9ba2818588eb)






