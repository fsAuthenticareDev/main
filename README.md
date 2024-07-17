# Authenticare2.0 App Approval Testing Support

This document is intented to provide setps to login into the Authenticare2.0 application and troubleshooting steps during login failure.

1) Launch the Authenticare2.0 Application
   - It will land on the SetupcodeScreen
   - Enter Jursidiction Code in the `Setup Code` text box.
   - Press `submit` button.
   - User will be navigated to **Login Screen**

<img width="250" alt="image" src="https://github.com/user-attachments/assets/feff62b3-3d2f-4a6e-addb-964e553f6120">

2) LoginScreen 
   - Enter the workers Username and Password.
   - Press `SIGN IN` button.
  
<img width="250" alt="image" src="https://github.com/user-attachments/assets/bc00cf3d-2fe5-469d-b22c-72bbafd0cdaa">

3) Successful Login
  - With Second Factor Authentication
    -  We have an one-to-one assocation with the **Worker-Device-ID** and **Worker-ID**.
       To bypass this association we need to authenticate the user using the Second-Factor authentication through QR Code.   
    -  Worker will be prompted to Scan the QR code.
    -  Test/Sample QR Code can be downloaded from the URL
       https://github.com/fdsdkteam/Authenticare2.0/blob/b20280ebf1ae0ee974a280061c14752929a0ebf3/73218_NMCCAT_Mobile_QR_Code.pdf
   
  - WithOut Second Factor Authentication
    - User will be landed on the Home screen / Visit List Screen.
<img width="250" alt="image" src="https://github.com/user-attachments/assets/6a0b7eb8-cac2-4e65-89f9-fd87bce5c490">

4) Visit Creation Screen
   - Click on the `New CHECK-IN` button from the visist list screen.
   - It will look for the accurate GPS location and search users/customers close to the workers current location.
   - If there is no user near to workers current location, it will show the alert and press `ok` on the alert.
   - It will land on the **Client Selection Screen**.
  
5) Client Selection Screen
   - Press `Lookup Client` button and enter the Client-ID/ Client-Name to look up the client.
   - It will display the list of clients matching the search criteria.
   - Select any one client from the client list and proceed with the Visit Creation or **Check-IN**.
<img width="250" alt="image" src="https://github.com/user-attachments/assets/f951b140-b096-405b-ba51-afd4a7daca3f">
