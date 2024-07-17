# main
Authenticare2.0 App Approval Testing Support

This document is intented to provide setps to login into the Authenticare2.0 application and troubleshooting steps during login failure.

1) Launch the Authenticare2.0 Application
   - It will land on the SetupcodeScreen
   - Enter Jursidiction Code in the `Setup Code` text box.
   - Press `submit` button.
   - User will be navigated to **Login Screen**

<img width="300" alt="image" src="https://github.com/user-attachments/assets/feff62b3-3d2f-4a6e-addb-964e553f6120">

2) LoginScreen 
   - Enter the workers Username and Password.
   - Press `SIGN IN` button.
  
<img width="300" alt="image" src="https://github.com/user-attachments/assets/bc00cf3d-2fe5-469d-b22c-72bbafd0cdaa">

3) Successful Login
  - With Second Factor Authentication
    -  We have an one-to-one assocation with the **Worker-Device-ID** and **Worker-ID**.
       To bypass this association we need to authenticate the user using the Second-Factor authentication through QR Code.   
    -  Worker will be prompted to Scan the QR code.
    -  Test/Sample QR Code can be downloaded from the URL
       https://github.com/fdsdkteam/Authenticare2.0/blob/b20280ebf1ae0ee974a280061c14752929a0ebf3/73218_NMCCAT_Mobile_QR_Code.pdf
   
  - WithOut Second Factor Authentication
    - User will be landed on the Home screen / Visit List Screen.
